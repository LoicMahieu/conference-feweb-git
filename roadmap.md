1. Git is awesome
  - version control
  - deployment
  - git as database
  - ...

2. Git hosting
  a. Github
    a. Summary
    b. Github secrets
      - Concept Fork + pull request

      - Raw github!

      - Github pages!

      - canonical URLs (press Y)
        This page won't change even if the branch does

      - Access to user's public keys
        https://github.com/loicmahieu.keys

      - Github URL shortener (git.io)
        CLI: gitio <url> <name>

      - Email replies

      - Github language detection
        github.com/github/linguist

      - github:gist: ain't just for snippets
        - prototyping tool
        - comments
        - screenshots
        - code
        - ...
        Git are full repos!!

      - Github with command line
        `hub` (https://github.com/github/hub)

      - Advanced compare
        ( https://github.com/paulmillr/ostio/compare/master%40%7B300day%7D...master )
        ( https://github.com/thedersen/backbone.validation/compare/v0.8.2...v0.9.0 )
    c. You can do a lot without leaving the browser
      - Create branch/new file/...
      - file template
    d. Tasks list/wiki/pull requests
      - Wiki as git repot

  c. bitbucket ?

  d. Gitlab

4. Git GUI ? Smartgit, Tower, Sourcetree, ...
5. Git Extras
3. Git tips
  a. merge strategy ?
  b. submodule
  c. git stripspace
  d. git status --ignored
  e. git checkout - (go back)
  f. git branch --merged
     git branch --no-merged
     git branch --contains <commit>
     git checkout <branch>> -- <path/to/file> (copies file at branch without switching branches)
     git log branchA ^branchB (commits in A that aren't in B)
     git fsck --lost-found (find lost commits!)
     git diff HEAD^ --stat
     git blame
     git blame -W
     git blame -M
     git blame -C
     git blame -CC
     git blame -CCC
     git status -sb
     git diff HEAD^
     git diff HEAD^ --word-diff
     git commit --amend -C HEAD
     git reset --soft HEAD^
     git shortlog -sn
     git bisect
     git lol -10
     git filter-branch

  g. Multi-remote fetches
     git config remotes.mygroup 'remote1 remote 2'
     git fetch mygroup
