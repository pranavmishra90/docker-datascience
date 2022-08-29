# v0.0.6
## YODA
Following the [Datalad YODA principles](https://f1000research.com/posters/7-1965):

- Created seperate git repository specifically for this docker container, rather than tracking it inside of a larger git repository

## Gitea
- Added Gitea as a docker image repository for testing purposes

## #Dockerfile

### Added packages
- [Zsh](https://www.zsh.org/)
- [yadm](https://github.com/TheLocehiliosan/yadm) - yet another dotfile manager
- [Exa](https://the.exa.website/) - a newer form of ls

### Labels
Used the Docker / OCI label standards to save labels in the docker image