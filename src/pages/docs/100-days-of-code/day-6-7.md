---
title: Day 6-7
weight: 7
template: docs
---

I didn't touch a code editor yesterday (day 6) but I did some work engaging with my community on Twitter.

I'm letting it be known that I want to work as a developer in a community or advocate role. Engaging with the community and writing documentation are skills I am working on demonstrating and creating a body of work around.

Worked on a few exercises for my iOS class.

![swift code](/images/swift.png)

Digging into daily.co api

![Get / in Insomnia app](/images/get-insomnia.png)

I was able to create my own new room from the API 🙌🏾

## Getting my environment cleaned up 🧹

I was using an old version of node and I kept getting this "Possible EventEmitter memory leak" error. This has been going on for months and I decided to fix it today. 

I didn't know that [the problem was that I was on an old version of node](https://github.com/nodejs/node/issues/29239) and once I identified that I tried upgrading with homebrew.

`brew upgrade node`

That wasn't the solution to my problem because I am using nvm to manage node versions.

Here's what did it

>To download, compile, and install the latest release of node, do this:

    nvm install node # "node" is an alias for the latest version

## A first with docker 🎉

I started a [Wordpress API and React tutorial today by Traversy Media](https://www.youtube.com/watch?v=fFNXWinbgro) on YouTube. I've worked with local Wordpress before but I've never used a docker compose file to set one up. 

Wordpress Docker Compose File: https://gist.github.com/bradtraversy/faa8de544c62eef3f31de406982f1d42

Very cool and easy compared to proprietary tools and other solutions like MAMP.

*****

Links to work:
- https://github.com/prophen/daily-js
- https://[mysubdomain].daily.co/from-insomnia
- https://github.com/prophen/frontend

Resources I used today:

- https://github.com/facebook/create-react-app
- https://www.youtube.com/watch?v=fFNXWinbgro

Node
- https://github.com/nvm-sh/nvm

Swift
- https://developer.apple.com/documentation/swift/range#see-also
- https://developer.apple.com/documentation/swift/closedrange

Daily.co API
- https://docs.daily.co/reference#introduction

Social posts:
- https://twitter.com/dev_nikema/status/1231322299669762049?s=20
- https://twitter.com/dev_nikema/status/1231422919697321984?s=20

****

<p align="center"> <a href="https://www.buymeacoffee.com/nikema" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" width="150px"></a></center></p>