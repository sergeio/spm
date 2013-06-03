spm
===

My personal package manager.

Installs things from this github account into `~/code`, and
runs the project's `install` script, if it exists.


Installation
------------
```bash
~/code$ git clone https://github.com/sergeio/spm.git
~/code$ cd spm
~/code/spm$ ./install
```

`install` will symlink `spm` to `~/bin/spm`.  So make sure `~/bin`
exists, and is on your `$PATH`.


Usage
-----

Installing
```bash
~$ spm install watchfiles
Cloning into '/home/bat/code/watchfiles'...
remote: Counting objects: 43, done.
remote: Compressing objects: 100% (23/23), done.
remote: Total 43 (delta 18), reused 43 (delta 18)
Unpacking objects: 100% (43/43), done.
```

Uninstalling
```bash
~$ spm uninstall watchfiles
rm: remove all arguments recursively? y
```

Updating
```bash
~$ spm update watchfiles
From github.com:sergeio/watchfiles
 * branch            master     -> FETCH_HEAD
Already up-to-date.
```
