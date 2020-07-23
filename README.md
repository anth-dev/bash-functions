# bash-functions
These are useful bash functions that I have written. You can add them to your ` .bashrc` file to use them.

## Hey you files, go on git! (read in Jimmy Fallon voice)
This function simplifies the process of commiting and pushing to git reducing it to a single command.

Use as follows `goongit (. or a filename) "your commit message"`
Here is an example `goongit . "added the Go On Git! function"`

```
goongit ()
{
  git add $1 && git commit -m "$2" && git push origin HEAD
}
```


