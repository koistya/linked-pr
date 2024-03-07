# Linked PR

Finds a pull request (PR) associated with the current commit.

## Usage

```yaml
steps:
  - uses: actions/checkout@v4
  - uses: koistya/linked-pr@v1
    id: pr
  - run: echo "PR #{{ steps.pr.outputs.number }} by {{ steps.pr.outputs.author }}"
```

## License

The scripts and documentation in this project are released under the [MIT License](./LICENSE.txt).
