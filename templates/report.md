# OSCP+ report worksheet

**Candidate / OSID:**  
**Exam date:**  
**Report date:**  

## 1. Scope and results

| Target / IP | Objective | Access demonstrated | Report subsection | Proof figure |
| --- | --- | --- | --- | --- |
| | | | | |

## 2. Technical walkthrough

Create a section for each standalone target and one for the AD set. Present targets and objectives in the order you intend them to be reviewed. Preserve dependencies in the AD chain.

### Target or AD step

1. **Starting context.** State the target, source host, identity and prerequisites.
2. **Discovery.** Show the observation and the output that justified the next action.
3. **Reproduction.** Give exact commands or requests in execution order, where they run, and meaningful console output.
4. **Result.** Identify the resulting shell and privilege, what it proves, and any dependency it creates.
5. **Proof.** Place the screenshot immediately after the step and label the target, objective and evidence ID.

For an unchanged public exploit, give its source URL. For a modified exploit, include the source URL, modified code, highlighted changes and why they were needed. Include the shellcode generation command when applicable. Put necessary scripts and PoCs in the PDF as readable text.

## 3. Proof review

- [ ] Each required proof was read from its original location with `cat` or `type` in an interactive shell on the target.
- [ ] The corresponding screenshot shows both the proof contents and target IP from `ip addr`, `ifconfig` or `ipconfig`.
- [ ] Privileged access is documented where claimed, including root on Linux or the applicable administrator-level context on Windows.
- [ ] Each required value was entered in the control panel before access ended.
- [ ] Captions identify the right target and objective. Screenshots are readable in the exported PDF.

## 4. Package and submit

- [ ] Export as `OSCP-OS-XXXXX-Exam-Report.pdf`, replacing `OS-XXXXX` with your OSID.
- [ ] Put only the PDF in `OSCP-OS-XXXXX-Exam-Report.7z`, without a password, and keep the archive within the 200 MB limit.
- [ ] Inspect the PDF and archive. Check line wrapping, page breaks and every proof screenshot.
- [ ] Upload at [upload.offsec.com](https://upload.offsec.com/) within the report window. Compare the portal’s MD5 with the local archive, then complete **Submit File** and confirm receipt.

Run from a clean staging directory with your final PDF. Replace the sample OSID in each command.

~~~bash
7z a OSCP-OS-XXXXX-Exam-Report.7z OSCP-OS-XXXXX-Exam-Report.pdf
7z l OSCP-OS-XXXXX-Exam-Report.7z
7z t OSCP-OS-XXXXX-Exam-Report.7z
md5sum OSCP-OS-XXXXX-Exam-Report.7z
~~~

[OffSec submission and proof rules](https://help.offsec.com/hc/en-us/articles/360040165632-OSCP-Exam-Guide)
