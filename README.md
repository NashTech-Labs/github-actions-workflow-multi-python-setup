## GitHub Actions Workflow For Python Projects

You can add support for more operating systems and Python versions by changing the below config:

```
    strategy:
      matrix:
        os:
          - ubuntu-latest
          - macos-latest
          - windows-latest
        python:
          - "3.6"
          - "3.7"
          - "3.8"
          - "3.9"
          - "3.10"
```