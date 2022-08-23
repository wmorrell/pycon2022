# (Professionally) Coding with Others

Here's a bunch of resources referenced in my PyCon US 2022 talk!

## Documentation

+ [WriteTheDocs](https://www.writethedocs.org)
+ [Choose a License](https://choosealicense.com)
+ *Building Docs Like Code*, by Mason Egger, PyCon US 2020 ([youtube](https://www.youtube.com/watch?v=4SwdVMKhbn4))
+ *Static Sites with Sphinx and Markdown*, by Paul Everitt, PyCon US 2021 ([youtube](https://www.youtube.com/watch?v=YclYtM56qjo))
+ [Sphinx](https://www.sphinx-doc.org/en/master/)
+ [MkDocs](https://www.mkdocs.org)
+ *Write Docs Devs Love*, by Mason Egger, PyCon US 2022 ([youtube](https://www.youtube.com/watch?v=9WobKoE9OPI))

## Version Control

+ [Atlassian Git Tutorial](https://www.atlassian.com/git)
+ [Oh Shit, Git?!?](https://ohshitgit.com)
+ [Dangit, Git?!?](https://dangitgit.com/en)
+ Graphical Clients: a non-exhaustive list, only things I have tried:
  + [Sourcetree](https://www.sourcetreeapp.com)
  + [Tower](https://www.git-tower.com)
  + [GitKraken](https://www.gitkraken.com/)
  + [Sublime Merge](https://www.sublimemerge.com/)
+ [XKCD 1296](https://xkcd.com/1296), "Git Commit"
+ The Git manual's [Discussion section](https://git-scm.com/docs/git-commit#_discussion) on `git-commit`, re: messages
+ My quick command guide:
  + DON'T USE `git commit -am 'terrible message'`!
  + `git reset HEAD~` = commit undo
  + `git add -p` or `git add --patch` = stage partial lines/chunks for file(s)
  + `git checkout --ours` and `git checkout --theirs` = very simple resolutions for merge conflicts
  + `git cherry-pick [HASH]` = adds arbitrary commit changes to tip of current branch
  + `git rebase -i [REF]` = oh man, uhhh [Read The Manual](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)

## Code Quality Tools

+ The OG, [`lint`](https://en.wikipedia.org/wiki/Lint_\(software\))
+ [`pylint`](https://pylint.pycqa.org/en/latest/)
+ [`flake8`](https://flake8.pycqa.org/en/latest/)
  + [`flake8-bandit`](https://github.com/tylerwince/flake8-bandit)
  + [`flake8-bugbear`](https://github.com/PyCQA/flake8-bugbear)
+ [`isort`](https://pycqa.github.io/isort/)
+ [`2to3`](https://docs.python.org/3/library/2to3.html) in the standard library
+ [`pyupgrade`](https://github.com/asottile/pyupgrade)
+ [`black`](https://github.com/psf/black)
+ [`yapf`](https://github.com/google/yapf)
+ [`pre-commit`](https://pre-commit.com)

Also, a special highlight for tools for code quality highlighted by Amethyst Reese in her PyCon 2022 talk, *Open Source on Easy Mode* ([youtube](https://www.youtube.com/watch?v=lSqyKoPYtr0)):
+ [`usort`](https://usort.readthedocs.io/en/stable/index.html)
+ [`ufmt`](https://ufmt.omnilib.dev/en/latest/)
+ [`thx`](https://thx.omnilib.dev)

## Pull Requests

Lots of resources are available from each provider of common `git` platforms with pull request tools. For a more general or philosophical take, I really like the writing of [Chelsea Troy](https://chelseatroy.com/tag/temporally-distributed/) on this topic.

## Dependency Management

+ [XKCD 1987](https://xkcd.com/1987), "Python Environment"
+ [Poetry](https://python-poetry.org)
+ [Python Speed](https://pythonspeed.com/docker/)

Also, for even more detail, see *Bootstrapping Your Local Python Environment*, by Calvin Hendryx-Parker, PyCon US 2022 ([youtube](https://www.youtube.com/watch?v=-YEUFGFHWgQ))
