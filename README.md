# CSV on the Web metadata Mustache template

This repository contains a [Mustache][mustache] template for rendering CSV metadata defined in JSON-LD according to the [CSV on the Web][csvw] model and vocabulary.

## Requirements

- [pystache][pm]

## Usage

<kbd>pystache csvw-metadata.mustache data.csv-metadata.json > data-metadata.html</kbd>

## Notes

[Ruby Mustache][rm] does not accept colons in tags, which are hard to avoid in JSON-LD metadata.
[Python Mustache][pm] does accept colons.

## License

TBD

[mustache]: https://mustache.github.io
[csvw]: https://www.w3.org/TR/tabular-data-primer/
[rm]: https://github.com/mustache/mustache
[pm]: https://github.com/defunkt/pystache
