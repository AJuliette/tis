# GitHub Protips: Tips, tricks, hacks, and secrets

[Source: The GitHub Blog](https://github.blog/2020-04-09-github-protips-tips-tricks-hacks-and-secrets-from-lee-reilly/)

A colleague showed me one day <kbd>command</kbd> <kbd>p</kbd> in VSCode to browse files by name (I think it now saves me 15 minutes every day). Turns out there is the same thing on an online repository, try type: <kbd>t</kbd> and be mind-blown like I was.

A friend of mine told me about [Octotree](https://github.com/ovity/octotree), which is also presented in this blog post, maybe I should give it a try ?

If you're like me a little bit nosy and tend to type `git blame` on repos you'll love these tools:  [GitHub High Scores](https://leereilly.net/github-high-scores/) (for public repos), [git-stats](https://github.com/IonicaBizau/git-stats) or just type `git shortlog -sn` in your command-line to "generate an ordered list of authors by commit count from the command line".

I liked this one too to make it clear in a code review what should be changed by what:

```diff
10 PRINT “BASIC IS COOL”
- 20 GOTO 11
+ 20 GOTO 10
```
