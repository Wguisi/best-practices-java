# best-practices-java
Design to aggregate various design patterns and best practices

## Markdown Readme.md
You can use this to help write the Readme
[CommonMark](https://commonmark.org/help/)

## How to GitFlow
That's a good tool for it: [GitFlowCheatSheet](http://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html)

1. First, you must configurate your repository for *develop* and *master* branches.
2. Define the *develop* as default. When someone clone, will clone that one.
3. There're restrictions to commit directly on those branches. You must do a Pull Request (PR)
4. In that case, when in your environment, after cloning, you must create a new *feature* branch.
5. If you're using the git-flow tool, just init your project with *git flow init*.
6. After that, create a feature: *git flow feature start MYFEATURE*
7. When you finish coding, just commit and push. On Github, ask for a Pull Request.
8. Same works for *release* branch: *git flow release start RELEASE*
9. Important detail: do not *finish* or *publish* using this tool. Won't works. Always Pull Request.
