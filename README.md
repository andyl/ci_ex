# ci_ex

CI for Elixir Projects

These github workflows verify that: 
- all tests pass 
- all code is formatted 
- commit messages are 'Conventional Commit' compliant 

Add to an Elixir project as a Git Submodule 

```
> cd <myproject>
> git submodule add git@github.com:andyl/ci_ex.git .github`
```

| Command                                    | Note                                     |
|--------------------------------------------|------------------------------------------|
| git submodule add <url> <target_dir>       | Add submodule to repo                    |
| git clone <myrepo> --recurse-submodules    | Clone repo, also auto-recurse submodules |
| git pull --recurse-submodules              | Pull main repo and git submodules        |
| git config submodule.recurse true          | Configure 'recurse=true' for your repo   |
| git config --global submodule.recurse true | Configure globally                       |

Use `https://github.com/zachdaniel/git_ops` at release time to auto-update
CHANGELOG, README, mix.exs and to tag a new version number.
