# Let's Play with Git

```text
git config --global user.name "Patrice Krakow"
git config --global user.email "patrice.krakow@gmail.com"
```

```text
git config --show-scope --list
```

```text
mkdir my-project
cd my-project/
git init
```

```text
Initialized empty Git repository in C:/Users/user/work/my-project/.git/
```

```text
ls -al
```

```text
touch hello.txt
git status -u
```

```text
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello.txt

nothing added to commit but untracked files present (use "git add" to track)
```

```text
git add .
git status -u
```

```text
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hello.txt
```

```text
git commit -m "Add an empty 'hello.text' file"
```

```text
[main (root-commit) ad97b8d] Add an empty 'hello.text' file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 hello.txt
```

```text
code hello.txt
```

```text
Hello World!

```

```text
git status -u
```

```text
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   hello.txt

no changes added to commit (use "git add" and/or "git commit -a")
```

```text
git commit -a -m "Add some content to the 'hello.txt' file"
```

```text
[main 0be7945] Add some content to the 'hello.txt' file
 1 file changed, 1 insertion(+)
```

```text
git log --oneline --no-decorate
```

```text
0be7945 Add some content to the 'hello.txt' file
ad97b8d Add an empty 'hello.text' file
```
