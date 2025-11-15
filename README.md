| <img width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/solidity/solidity-original.svg" /> | ETH DAPP TEMPLATE |
| ----------------------------------------------------------------------------------------------------------------- | ----------------- |

![main GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/sripwoud/solidity-template/main.yml?branch=master&label=master)
[![Coverage Status](https://coveralls.io/repos/github/sripwoud/solidity-template/badge.svg?branch=main)](https://coveralls.io/github/sripwoud/solidity-template?branch=master)

| Feature                                                                                                               | With                                                                                         | Configuration File                                     |
| --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| Continuous Integration                                                                                                | [github workflow](https://docs.github.com/en/actions/using-workflows)                        | [.github/workflows](./.github/workflows)               |
| Conventional Commits (`main` branch only)                                                                             | [convco](https://github.com/convco/convco)                                                   | [.convco](./.convco)                                   |
| Conventional PR Titles (because I only squash merge and base changelogs/semantic versioning on `main` commit history) | [amann/action-semantic-pull-request](https://github.com/amannn/action-semantic-pull-request) | [semantic-pr.yml](./.github/workflows/semantic-pr.yml) |
| Git Hooks                                                                                                             | [hk](https://hk.jdx.dev/)                                                                    | [hk.pkl](./hk.pkl)                                     |
| Formatting                                                                                                            | [dprint](https://dprint.dev/)                                                                | [.dprint.jsonc](./.biome.json)                         |
| Smart Contract Development Tools                                                                                      | [foundry](https://book.getfoundry.sh/)                                                       | [foundry.toml](./foundry.toml)                         |
| Tasks Runner, Environment & Runtime Management                                                                        | [mise](https://mise.dev/)                                                                    | [mise.toml](./mise.toml)                               |

## Develop

I use [`mise`](https://mise.jdx.dev) to manage runtimes, manage environment variables, and run tasks.\
To install it and setup the repository:

```commandline
./setup
```

To run tasks interactively:

```commandline
mise run
```
