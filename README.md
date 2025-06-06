githooks
====

Specific centralized [githook-companion](https://github.com/ylallemant/githook-companion) configuration for [Golang](https://go.dev/) projects.

- execute tests on commit

## Prerequisite

Install [githook-companion](https://github.com/ylallemant/githook-companion?tab=readme-ov-file#installation) in order to reference this configuration in your projects

## Reference This Configuration

In your project root directory, simply run following command :

```bash
githook-companion init -m --parent-path ../githooks-golang --parent-repository https://github.com/ylallemant/githooks-golang
```

> [!NOTE]
> The `parent-path` should be relative to your current project, because there is no mean to know how users structure their files.
> Using this property also sets a standard on how a set of projects get structured on the filesystem : at least between the depths from the current project to the shared configuration.
> Communicate it within the team !
