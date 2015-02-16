# Learning GitHub

## What is GitHub (and what is git)?

If you're already reading this, you probably have a rudimentary idea
of the purpose of [GitHub](https://github.com/). But just in case
you're viewing this somewhere other than GitHub, here's a very brief
introduction.

In a nutshell, GitHub is a service that provides disk space for
projects, allowing people to collaborate using a standard,
well-regulated mechanism for downloading, modifying, uploading,
merging, and tracking changes to a set of files.

Such systems are known collectively as
[distributed revision control systems](https://en.wikipedia.org/wiki/Distributed_revision_control).
GitHub specifically uses
[git](https://en.wikipedia.org/wiki/Git_%28software%29).  In addition
to the files you create and modify, git provides a hidden directory of
files containing meta-data that keeps track of changes. Your files,
plus hidden files are collectively referred to as a _repository_.

Git provides a set of commands and protocols storing, merging and
transferring files as well as querying the state of the project.  Git
also checks the integety of repository, and forces collaborators to
play nicely together by requiring specific steps be taken when working
with a repository. For example, before a repository is considered to
be in a stable state, users must _commit_ their changes, adding a
comment to explain the change.

Git is a command-line tool, and as such, isn't very pretty.  GitHub
provides a web interface to the repositories, adding in nice graphics
that chart the progress of a project, as well as offering e-mail
updates, a mechanism for tracking issues such as bug reporting and
feature requests, and other useful features.

## README.md

One of those features that GitHub adds to git is a means of documenting
work.

GitHub looks for a file named `README.md` in each directory of a
repository.

If it finds a `README.md` file, the contents of the file are displayed
beneath a list of the contents of the directory, when viewed in a
browser.  This provides a very useful feature of allowing coders to
add documentation explaining the purpose and use of the directory.

Note the `.md` file extension. This indicates that the file is
formatted using [Markdown](https://en.wikipedia.org/wiki/Markdown)
syntax. Markdown is a minimal markup language that is relatively easy
to read in a text editor and most commonly displayed &mdash; as GitHub
does &mdash; as HTML.

The Markdown syntax is explained at
http://daringfireball.net/projects/markdown/syntax &mdash; a site
maintained by the primary author of the Markdown language.

## Using Git and GitHub

The [Learn GitHub for OS X](learn-github-osx.md) found here is most
excellent, and, aside from the section on installing `git`, applies to
Linux systems as well. Most Linux users should already know how to
install software for their distribution, and git, having been written
by Linus Torvalds himself, is likely to be very available in any Linux
distribution.
