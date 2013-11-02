Git Mergetool Vimdiff Wrapper
=====

What's this?
-----
Modify git mergetool vimdiff's BAD UI(UI changes when git's BASE dosen't exist).

**Always MERGED pain is bottom!**

Setup
-----
```
$ git clone https://github.com/haya14busa/git-mergetool-vimdiff-wrapper.git
$ git cd git-mergetool-vimdiff-wrapper
$ cp myvimdiff /usr/local/bin/
$ git config --global mergetool.myvimdiff.cmd 'myvimdiff "$MERGED" "$LOCAL" "$BASE" "$REMOTE"'
$ git config --global merge.tool myvimdiff
```
