# git-todo
Write commit messages for your future commits

```sh
> git todo add "Strip out all the console.log()s"

# ... 2 days later ...

> git todo show
[O] Strip out all the console.log()s
[_] Add in api calls

> git todo done
[O] Strip out all the console.log()s
[_] Add in api calls

[main b249cb4] Strip out all the console.log()s
 12 file changed, 12 insertions(+), 12 deletions(-)
> git todo show
[-] Add in api calls
[X] Strip out all the console.log()s
```
