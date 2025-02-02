# .github-workflows-test1.yml
23f1002634@ds.study.iitm.ac.in
name: Test Action

on: [push]

jobs:
  test:
    runs-on: ubuntu-latest

    steps:
      - name: Step with Email Reference
        run: echo "This step is linked to 23f1002634@ds.study.iitm.ac.in"
