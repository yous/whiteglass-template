# whiteglass-template

![Jekyll Deploy](https://github.com/yous/whiteglass-template/workflows/Jekyll%20Deploy/badge.svg)

Template site for [whiteglass](https://github.com/yous/whiteglass) theme.

## Configuration

You need to add a secret named `JEKYLL_PAT` to make GitHub Actions work.
Generate a personal access token on <https://github.com/settings/tokens>, select
`public_repo` or `repo` depending on your repository.

Then in the settings page of your repository, go to Secrets tab
(`https://github.com/<user>/<repo>/settings/secrets`) and add that token with
its name `JEKYLL_PAT`.

## License

whiteglass-template is free and unencumbered software released into the public
domain. For more information, please refer to <http://unlicense.org/>.
