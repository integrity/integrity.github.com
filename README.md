# Integrity Website

To regenerate website content:

1. Clone [integrity](https://github.com/integrity/integrity) repository.
2. In integrity repository, run `rake html`.
3. Copy `doc/build` from integrity repository to this repository:
`rsync -a /path/to/integrity/doc/build/ --exclude .git /path/to/integrity.github.com`
4. Commit and push
