# Github cleanup

GitHub Action used to cleaup files from previous workers on the runner.

## Usage

To use the action you can add the following to your GitHub Action workflow
file:

```yaml
jobs:
  build:
    name: build
    runs-on: ubuntu-latest

    steps:
      - name: Cleanup
        uses: sortlist/cleanup-action@main
```

## Inputs

None

## Outputs

None
