Just flux repo template and nothing else.
```bash
export GITHUB_TOKEN=ghp_qzuafgfgfgfgfgfKclQSug4JPmRk
export GITHiUB_USER=ipeacocks
export GITHUB_REPO_NAME=flux-template
```
```bash
flux bootstrap github \
--owner=$GITHUB_USER \
--repository=$GITHUB_REPO_NAME \
--branch=main \
--path=./clusters/main-cluster/bootstrap \
--personal
```
