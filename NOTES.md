

# Will need cargo generate
```
cargo install cargo-generate
```

# Generate template and dir
```
cargo generate ratatui/templates
```


# Create git repo
```
% git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .github/
        .gitignore
        Cargo.lock
        Cargo.toml
        LICENSE
        README.md
        src/

nothing added to commit but untracked files present (use "git add" to track)
% git add .
% git ci -m init
[main (root-commit) d773ed2] init
 8 files changed, 1046 insertions(+)
 create mode 100644 .github/dependabot.yml
 create mode 100644 .github/workflows/ci.yml
 create mode 100644 .gitignore
 create mode 100644 Cargo.lock
 create mode 100644 Cargo.toml
 create mode 100644 LICENSE
 create mode 100644 README.md
 create mode 100644 src/main.rs
% 
```

# Create repo
```
git remote add origin git@github.com:jonknoxdotcom/ratatop.git
git branch -M main
git push -u origin main
```
etc


# Sysinfo
```
% cargo add sysinfo

    Updating crates.io index
      Adding sysinfo v0.37.2 to dependencies
             Features:
             + component
             + disk
             + network
             + objc2-io-kit
             + system
             + user
             - apple-app-store
             - apple-sandbox
             - c-interface
             - debug
             - linux-netdevs
             - linux-tmpfs
             - multithread
             - objc2-core-foundation
             - serde
             - unknown-ci
             - windows
    Updating crates.io index
    ...
```


