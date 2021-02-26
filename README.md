# shell - script that prints hello (gh repo)

## Intro
This manual is dedicated to execute script that prints hello on Mac OS X

## Requirements
- git installed
[Git installation manual](https://git-scm.com/download/mac)

## Preparation 
- Clone git repository. 

```bash
git clone https://github.com/antonakv/shell-hello-ob
```

Expected command output looks like this:
```bash
➜  git clone https://github.com/antonakv/shell-hello-ob          
Cloning into 'shell-hello-ob'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
```
- Change folder to folder of the cloned repository

```
cd shell-hello-ob 
```
Expected result:
```
$ cd shell-hello-ob
$
```

## Run script

- In the same folder you were before run 
```bash
bash helloscript.sh
```
Expected result
```bash
$ bash helloscript.sh
hello
$
```