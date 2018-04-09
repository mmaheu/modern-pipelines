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

- jx create cluster gke
- jx get environment or environments
- jx get apps
- jx create environment
- jx rsh



### Pipeline Interaction
- jx create issue -t 'comments'
- jx create spring or jx create spring -d web -d actuator
- jx get build log
- jx start pipeline codemartians/demo

## Additional commands with Hub
- https://hub.github.com/
