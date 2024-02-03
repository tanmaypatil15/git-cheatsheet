# SETUP GIT USER-NAME & USER-EMAIL:

##### Show current configuration:
```
$ git config --list
```
##### Show local repository configuration:
```
$ git config --local --list
```

##### Show global configuration:
```
$ git config --global --list
```

##### Show system configuration:
```
$ git config --system --list
```

##### Set a name that is identifiable for credit when review version history:
```
$ git config --global user.name "[firstname lastname]"
```

##### Set an email address that will be associated with each history marker:
```
$ git config --global user.email "[valid-email]"
```

##### Set automatic command line coloring for Git for easy reviewing:
```
$ git config --global color.ui auto
```

##### Set global editor for commit
```
$ git config --global core.editor vi
```

##### Set default code editor as VsCode
```
$ git config --global core.editor "code --wait"
```

##### Change git user-name and git user-email directly in the config file using vim
````
$ git config --global --edit
````

##### To store git user-name and git user-email in disk
``````
$ git config credential.helper store
``````

##### To exit vim
``````
$ escape + :wq
``````



