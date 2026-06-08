# cicd

## Exercises

[Q1] Print the following dynamically in the action:
```
Hello Swapnil
You pushed to main
from repository cicd
at 2026-06-08 10:30 IST
```

[Q2] Format the above data like this:
```
=================================
        DEPLOYMENT RECEIPT
=================================

Repository : cicd
Branch     : main
Triggered By : swapnil
Event Type : push

Timestamp : Mon Jun 8 14:12:08 UTC 2026

=================================
```

[Q3] Print the following data dynamically:
```
📊 SERVER HEALTH REPORT

Disk Usage:
42%

Memory Available:
13 GB

CPU Cores:
4

Node Version:
v22.15.0

Python Version:
3.12.1

Health Status:
✅ HEALTHY
```

[Q4] Run the tests in the GitHub action (reference: src/02-run-tests.yml) by putting the calculator and calculator test files. 9 of 10 tests will pass and 1 will fail. Fix the subtract function and push a new commit. Now all tests should pass.

[Q5] Right now, Handle Issues (reference: src/04-issue-events.yml) runs when an issue is opened or edited. Modify this to run when it is closed as well.

[Q6] Can you figure out how to trigger CI/CD workflows on pull requests as well?

[Q7] Sometimes, you might want to publish a change quickly without running the checks in the pipeline. There’s a neat way to do that while committing to skip checks for that particular commit. Find that out!
