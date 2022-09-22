# deta-change-visor-action
Simple GitHub Action to change visor set

```shell
- name: Change visor set on Deta
  uses: jhihyulin/deta-change-visor-action@v1.0.0
  with:
    deta-access-token: '' #Deta access token https://docs.deta.sh/docs/cli/auth
    deta-name: '' #Deta Micro name https://docs.deta.sh/docs/cli/commands/#deta-clone
    deta-project: '' #Optional: Deta project name https://docs.deta.sh/docs/cli/commands/#deta-clone
    deta-project-dir: ''#Optional: directory to be deployed on Deta. Default is the root "."
    visor-mode: '' #open, enable or disable https://docs.deta.sh/docs/cli/commands/#deta-visor
```
