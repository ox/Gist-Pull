# Gist_Pull #

gist_pull is a tool that helps pull gists in from github. That's all it does.

## Installing ##

`gem install gist_pull` 
that's all you need

## Nifty Usage ##

`gist_pull <gist id>` this gets all the relevant information about the gist

If there is just one file in this gist then it gets downloaded.
If there are many files, you are prompted to select the ones you want to download. You provide a list of files on a single, space-delimited line and we get them for you.

If you ever forget how to work this incredibly complicated tool, just run it without arguments: `gist_pull`