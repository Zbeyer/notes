

Source Code Management
====

Git 

+ Repository URL: 

```
https://github.com/Zbeyer/notes
```



Build Triggers
--------

Poll SCM

+ Schedule

```bash
# POLL Every Fifteen Minutes
H/15 * * * * * 
```



Build Environment
-----------------

+ [x] Delete workspace before build starts



Build
-----

Execute Shell

+ Command

```bash
mkdocs build --clean
```



Source files
------------

```bash
site/**/*
```



