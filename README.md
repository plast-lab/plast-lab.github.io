## FAQ

### What to do for the first time?

Read the [github-pages help page](https://help.github.com/articles/using-jekyll-with-pages/)
quickly.

### How to edit structure?

Just to be sure that your changes are OK on a local copy, clone the project:
```shell
> git clone git@github.com:plast-lab/plast-lab.github.io.git
```

Install dependencies
```shell
> bundle update
```

edit structure in ```_layout``` while having the server up and and
running with the following command:
```shell
> bundle exec jekyll serve --watch
```
Press F5 on your browser.

### How to edit content?

Do the same as for structure or just make the changes directly at the
corresponding files
([_include](https://github.com/plast-lab/plast-lab.github.io/tree/master/_includes)).
