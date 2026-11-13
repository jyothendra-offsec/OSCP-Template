# OSCP+ Notes Template

**PEN-200 · 2026 edition · Markdown**

Track six hosts from first observation to final report. Each objective has three independent checkpoints: screenshot captured, proof submitted, and reproduction documented.

| Open | Use it for |
| --- | --- |
| [Exam dashboard](template.md) | Target objectives, evidence status, deadlines, next actions |
| [Standalone host worksheet](templates/standalone.md) | Service triage, foothold, privilege escalation |
| [Active Directory worksheet](templates/active-directory.md) | Assumed breach, three-host chain, credentials, routes |
| [Report worksheet](templates/report.md) | Reproduction steps, exploit references, proof placement, submission |
| [Worked example](examples/standalone.md) | See how one fictional observation becomes a report step |

## Start a session

1. Copy this folder into a private local workspace. Keep filled notes, screenshots and exam data there.
2. Open `template.md`. Fill in your exam and report deadlines and copy each objective from the control panel.
3. Duplicate the standalone worksheet for each independent target. Use one AD worksheet for the entire set.
4. Assign evidence IDs as you work. Record the exact command and meaningful output while the session is open.
5. Before exam access ends, reconcile your dashboard against the control panel. Build the PDF using the report worksheet.

## 2026 scoring

| Exam start | Result |
| --- | --- |
| Before 1 December 2026 at 08:00 GMT | Fixed threshold of 70 raw points |
| At or after that time | Passing scaled score of 400 on a 100–500 scale. The raw points needed depend on the exam set. |

The published exam structure is three standalone targets worth 20 raw points each and one three-machine AD set worth 40. Use your control panel for the specific objectives and point allocation. Keep recording objectives and evidence throughout the exam.

Use the static Markdown locally. OffSec prohibits LLM and chatbot assistance during the exam, including report preparation. Check current tool restrictions before your session.

- [OffSec OSCP+ Exam Guide](https://help.offsec.com/hc/en-us/articles/360040165632-OSCP-Exam-Guide)
- [OffSec scaled scoring FAQ](https://help.offsec.com/hc/en-us/articles/54589877508884-OSCP-Equated-Scaled-Scoring-FAQ)
- [OffSec reporting requirements](https://help.offsec.com/hc/en-us/articles/360046787731-OSCP-Reporting-Requirements)

Independent study resource. [MIT license](LICENSE).
