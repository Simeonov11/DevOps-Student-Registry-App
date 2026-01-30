Practising DevOps CI and CD using GitHub Actions as creating a workflow with yaml file to build, test and deploy Node App to Render.com.
3 Jobs has been added:
  - JOB 1: build_and_test
  - JOB 2: run_npm_security_scan
  - JOB 3: deploy
The jobs are depending on the previous one. Job 3 depends on Job2, and Job2 depends on Job1.
Deploy runs on PUSH to main branch, but does not run on PULL requests.
