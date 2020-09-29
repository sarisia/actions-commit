# Actions Commit

GitHub Actions Action to commit and push changes to git,
using [Composite action!](https://github.blog/changelog/2020-08-07-github-actions-composite-run-steps/)

## Inputs

- `name`: git `user.name`. _Default: `${{ github.actor }}`_
- `email`: git `user.email`. _Default: `${{ github.actor }}@users.noreply.github.com`_
- `message`: commit message. _Default: `update`_

## Outputs

- `changed`: repository has changes or not. `1` if changed, `0` else.
