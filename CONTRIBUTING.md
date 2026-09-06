\# Contributing



\## Branch Naming



Use:



\- `feature/<name>`

\- `bugfix/<name>`

\- `hotfix/<name>`



Example:



`feature/add-bitlocker-policy`



\## Pull Requests



Every production change must use a Pull Request.



The Pull Request should include:



\- What changed

\- Why it changed

\- Testing performed

\- Deployment impact

\- Rollback plan



\## Testing



Before creating a Pull Request:



1\. Run PowerShell syntax validation.

2\. Run PSScriptAnalyzer.

3\. Run Pester tests.

4\. Validate Graph payloads.

5\. Test in the development tenant.



\## Production



Never directly push to `main`.



Production deployment requires Pull Request approval.

