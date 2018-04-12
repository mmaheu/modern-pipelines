# General Setup and commands

## Installation
1. MacOS
```bash
brew tap jenkins-x/jx
brew install jx
```
2. linux
```bash
curl -L https://github.com/jenkins-x/jx/releases/download/v1.1.10/jx-linux-amd64.tar.gz | tar xzv
sudo mv jx /usr/local/bin
```
3. Windows: Download the binary and add it to your path

### JX commands
```bash
jx create cluster gke
jx get environment or environments
jx get apps
jx create environment
jx open --env staging
jx promote --version v0.0.x --env production --timeout 1h
jx rsh
```


### Pipeline Interaction
```bash
jx create issue -t 'comments'
jx create spring or jx create spring -d web -d actuator
jx import --url git@your_repo.git
jx get build log
jx start pipeline codemartians/demo
```
## Additional commands with Hub
- https://hub.github.com/
