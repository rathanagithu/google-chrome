Run actions/checkout@v4
  with:
    repository: rathanagithu/google-chrome
    token: ***
    ssh-strict: true
    persist-credentials: true
    clean: true
    sparse-checkout-cone-mode: true
    fetch-depth: 1
    fetch-tags: false
    show-progress: true
    lfs: false
    submodules: false
    set-safe-directory: true
Syncing repository: rathanagithu/google-chrome
Getting Git version info
  Working directory is '/home/runner/work/google-chrome/google-chrome'
  /usr/bin/git version
  git version 2.43.0
Temporarily overriding HOME='/home/runner/work/_temp/451d25fa-490b-4f62-ad20-8680f39783a8' before making global git config changes
Adding repository directory to the temporary git global config as a safe directory
/usr/bin/git config --global --add safe.directory /home/runner/work/google-chrome/google-chrome
Deleting the contents of '/home/runner/work/google-chrome/google-chrome'
Initializing the repository
  /usr/bin/git init /home/runner/work/google-chrome/google-chrome
  hint: Using 'master' as the name for the initial branch. This default branch name
  hint: is subject to change. To configure the initial branch name to use in all
  hint: of your new repositories, which will suppress this warning, call:
  hint: 
  hint: 	git config --global init.defaultBranch <name>
  hint: 
  hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
  hint: 'development'. The just-created branch can be renamed via this command:
  hint: 
  hint: 	git branch -m <name>
  Initialized empty Git repository in /home/runner/work/google-chrome/google-chrome/.git/
  /usr/bin/git remote add origin https://github.com/rathanagithu/google-chrome
Disabling automatic garbage collection
  /usr/bin/git config --local gc.auto 0
Setting up auth
  /usr/bin/git config --local --name-only --get-regexp core\.sshCommand
  /usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
  /usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
  /usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
  /usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
Fetching the repository
  /usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +ddb19f96d2484efbd7849534b686d0a7aafbfbe7:refs/remotes/origin/main
  From https://github.com/rathanagithu/google-chrome
   * [new ref]      -> origin/main
Determining the checkout info
Checking out the ref
  /usr/bin/git checkout --progress --force -B main refs/remotes/origin/main
  Switched to a new branch 'main'
  branch 'main' set up to track 'origin/main'.
/usr/bin/git log -1 --format='%H'
