# Security Archive

This directory stores archived, potentially dangerous files for *security review only*.

Files:
- `original-OTP-Bot.csproj` — The original project file that included an obfuscated PreBuild
  Exec target which wrote and executed VBScript and PowerShell payloads.

Important handling instructions:
- **Do not** open or run these files on an internet-connected machine or a workstation with
  sensitive credentials.
- Review in an isolated, offline environment (air-gapped VM) by authorized security staff.
- After review, either sanitize and replace live files (with documented, non-obfuscated steps)
  or remove the archived file from the repo.

If you are a maintainer and need help performing the review or safely sanitizing the repo,
open a PR that references this archive and request a security review from the team.
