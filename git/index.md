# Git Guide
Here you will learn the essentials of git versioning and repo structuring in 2025

The People now understand that git is a content based versioning system so it works only with readable content.
There are abstractions to pull in binarys and manage them in conjunction with git

The most People that got a lot of dependencies did understand that they need to get control over the readable code and review the changes
there is no no cost dependencie so they started to create repos that at last hold the full content of all content based depenencies. 

## 3 Types of dependencies
If you integrate directly build artifacts in a binary form you trust the author 100% and delegate all tasks to them. Including all risks at last your Integration tests should cover every dependencie.
else you even deligate api stability to them.

If your not planning to contribute back you can use "gitsubmodule" it allows version pinning and incremental upgrades you only need to do that
when you run additional checks and audits on that code and you should do that or maybe consider a binary form.

If your plan is to contribute back you can use "git subrepo" it allows easy forking while it gives you the ability to contribute back if needed!

## Releasing
You should only handle Version able Content Based Code in git that includes any build release instructions. you will publish only the useable result.
That is called Release or Build Artifact you also should consider to take as much of your dependencies as build artifacts if possible in case of NPM nodejs packages you 
get the most time a lot of useless stuff also with many other package managers. In That case it can be clever to create code to audit the source so you will use git submodule/subrepo + your build code 
and release a stripped maintained artifact of that dependencie it is part of your build process.





