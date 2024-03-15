# Templates

Use the files in this repo as templates for your projects. Be sure to read
through them, understand their implications, and fill in the placeholders.

## Usage

```sh
cp templates/README.md.template my-awesome-project/README.md
$VISUAL my-awesome-project/README.md
```

### Dynamic content rendering for the footer

The [README.md.template](/README.md.template) includes a dynamic README
content snippet. That means the footer will be rendered and updated automatically
for you with the contents from the [footer](/templates/footer.md) template.

To make it work when using the [README.md.template](/README.md.template):
- copy the [github workflow example](/.github/workflows/dynamic-readme-example.yaml)
and rename it to `dynamic-readme`.
- add the repo path to the repository matrix in the [workflow dispatch](/.github/workflows/trigger-dynamic-readme-update.yaml).

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
## About thoughtbot

![thoughtbot](https://thoughtbot.com/thoughtbot-logo-for-readmes.svg)

This repo is maintained and funded by thoughtbot, inc.
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

We love open source software!
See [our other projects][community].
We are [available for hire][hire].

[community]: https://thoughtbot.com/community?utm_source=github
[hire]: https://thoughtbot.com/hire-us?utm_source=github

<!-- END /templates/footer.md -->
