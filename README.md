# git-auth
This github action allows you to authenticate git host with use of personal access token. 

# Motivation
This action was created in order to authenticate Swift Package Manager for private repositories with inconsistent urls (https and ssh) and with use of Personal Access Token.

# Parameters

| Argument | Description | Format |
| -------- | ----------- | ------ |
| `token` | Personal access token used for authorization (`Required`) | string |
| `fail_if_empty_token` | If true is provided then fails job whenever token is empty (`Optional` default: `true`) | string |
| `host` | git host to authenticate (`Optional` default: `github.com`) | string |

# License
Code and documentation in this project is released under the [Apache 2.0 License](LICENSE)