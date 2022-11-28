# shell_command
various shell command to make my life easier and healthier.

To copy mp3 from one source to another source in an easy way to maintain the structure
```
rsync -a --prune-empty-dirs --include '*/' --include '*.mp3' --exclude '*' /source/ /target/
```

copy files with progress
```
rsync -ah --progress --inplace /source/ /target/
```

copy files with progress and ignored already copied files
```
rsync -ah --progress --ignore-existing /source/ /target/
```
