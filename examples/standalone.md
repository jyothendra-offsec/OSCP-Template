# Worked example · Standalone service triage

This exercise uses a documentation-only IP and fictional lab output.

| Target | Port | Verified observation | Next action |
| --- | --- | --- | --- |
| S1 · 192.0.2.20 | 8080/tcp | HTTP server answers with a redirect to `portal.lab.example` | Replay against that vhost and capture the response |

## S1-STEP01 · Confirm the vhost

**Runs on:** Lab workstation  
**Evidence:** S1-E01 · HTTP headers  
**Command:**

~~~bash
curl -si --resolve portal.lab.example:8080:192.0.2.20 http://portal.lab.example:8080/
~~~

**Illustrative output:**

~~~http
HTTP/1.1 200 OK
Content-Type: text/html
~~~

**Report sentence:** The default HTTP response redirected to `portal.lab.example`. I sent a request for that hostname to `192.0.2.20:8080` and received HTTP 200, confirming the application could be reached using the advertised vhost.

**Ledger update:** Access remains at discovery. Proof evidence, panel submission and report completion are still open.
