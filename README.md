# SpamFilter-Indian-IT-Recruiters
List of email blocking rules to cut down on spam from Indian "IT Recruiters."

## Development

Enable the repository's native Git hooks after cloning:

```bash
git config core.hooksPath .githooks
```

The pre-commit hook applies a locale-independent unique sort to every changed
`filterlist.*.txt` file in the staged snapshot. If a file has additional
unstaged edits, the hook leaves those edits alone while sorting the version
that is committed.
