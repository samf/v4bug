# v4bug: showing a possible bug in the v4 CLI

## setup

run "npm i"

## building

run "./build" in the top level directory, and look at the public directory.

## to reproduce the bug...

Clone this (or move this) repo underneath a directory with a .gitignore
file consisting entirely of * (just an asterisk).

Note that git won't pay attention to this, because this repo is a git repo,
and directories above won't matter. But the tailwindcss command seems to
act on this directive and ignore everything.
