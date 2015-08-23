---
layout: post
title: how to sync a github fork
image: https://octodex.github.com/images/andycat.jpg
imglink: https://octodex.github.com/andycat/
tags:
 - github
 - 
---

When i [fork](https://en.wikipedia.org/wiki/Fork_(software_development)) a repo my worst problem is how to sync my repo with the principal master.

So... this is the action's list for resolve this problem.

1. go to the [official doc by github about fork a repo](https://help.github.com/articles/fork-a-repo/)
2. open the terminal into the folder
3. `git remote -v`
	`# origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)`
	`# origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)`
4. type `git remote add upstream` with url from ![image url](https://help.github.com/assets/images/help/repository/clone-repo-clone-url-button.png) 
5. [how to syncing a fork](https://help.github.com/articles/syncing-a-fork/)



