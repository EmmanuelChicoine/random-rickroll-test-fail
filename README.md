# Random Rick-Roll

This action comments a gif of Rick Astley when someone opens a new issue.

## Inputs

### `GITHUB_TOKEN`

**Optional** Github token of the repository. (Defaults to `${{ github.token }}`)


## Example usage


```
jobs:
  comment:
    runs-on: ubuntu-latest
    steps:
      - name: Rick Roll on test failure
        uses: EmmanuelChicoine/random-rickroll-test-fail@v1.0
```
