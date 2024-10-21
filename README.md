# cicd_ex

CICD for Elixir Projects

Add to an Elixir project as a Git Submodule 

```
> cd <myproject>
> git submodule add git@github.com:andyl/cicd_ex.git .github`
```

| Command                                    | Note                                     |
|--------------------------------------------|------------------------------------------|
| git submodule add <url> <target_dir>       | Add submodule to repo                    |
| git clone <myrepo> --recurse-submodules    | Clone repo, also auto-recurse submodules |
| git pull --recurse-submodules              | Pull main repo and git submodules        |
| git config submodule.recurse true          | Configure 'recurse=true' for your repo   |
| git config --global submodule.recurse true | Configure globally                       |

