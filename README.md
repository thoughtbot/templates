# Templates

Use the files in this repo as templates for your projects. Be sure to read
through them, understand their implications, and fill in the placeholders.

## Usage

```sh
cp templates/README.md.template my-awesome-project/README.md
$VISUAL my-awesome-project/README.md
```

### Dynamic content for the footer

The [README.md.template](/README.md.template) includes a dynamic README
content snippet. That means the footer will be rendered and updated automatically
for you with the contents from the [templates footer](/templates/footer.md) file.

To make it work, copy this [github workflow example](/.github/workflows/dynamic-readme-example.yaml)
and rename it to `dynamic-readme`.

## Contributing

See the [CONTRIBUTING] document.
Thank you, [contributors]!

[CONTRIBUTING]: CONTRIBUTING.md
[contributors]: https://github.com/thoughtbot/templates/graphs/contributors

## License

Open source templates are Copyright (c) thoughtbot, inc.
It contains free software that may be redistributed
under the terms specified in the [LICENSE] file.

[LICENSE]: /LICENSE

<!-- START /templates/footer.md -->
<!-- END /templates/footer.md -->
