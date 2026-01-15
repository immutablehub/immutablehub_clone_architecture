# 📥 ImmutableHub Clone Architecture

---


# [After Login and Project setup is already done shown here https://github.com/immutablehub/immutablehub_commits_architecture/blob/main/workflow.md?plain=1]

## Clone Mechanism

> All clones on immutablehub are natively Git-powered. The system retrieves data from the network via Git bundles and integrates them using a clone strategy. This ensures that the transition from the decentralized network to your local machine is seamless and preserves the original state.

## Bash

Clone repo 
```bash
ihub op clone <reponame>
```
Clone mcprepo 
```bash
ihub op clone <mcpreponame> --mcp true
```

Clone prompt data
```bash
ihub op clone <projectname> --prompt true
```
