# notif-be

Notification backend: a Go monorepo with one Go module per service.

## Layout

Each service is a separate Go module in its own directory, with the module path `github.com/takumu-dev/notif-be/<dir>`. Releases are tagged per module as `<dir>/vX.Y.Z`, the format the Go toolchain resolves.

## Contributing

- Branching follows Gitflow. `feature/*` and `bugfix/*` branch from `develop` and are squash-merged back into it. `release/*` and `hotfix/*` merge into `main`, where releases are tagged.
- Commit messages follow [Conventional Commits](https://www.conventionalcommits.org/).
