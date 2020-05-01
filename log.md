# 100 Days Of Code - Log

### Day 18: May 1, 2020

**Today's Progress:**
- Tried to deploy the proxy to Netlify, with no success.

**Thoughts:**
- Serverless is hard.

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco-proxy)

### Day 17: April 30, 2020

**Today's Progress:**
- I set up a proxy for Git requests using https://github.com/isomorphic-git/cors-proxy
- I worked on the git notes integration

**Thoughts:**
- The proxy really needs to support HTTP/2. I could not deploy it to Vercel successfully, I'll have to look into Netlify.


### Day 16: April 29, 2020

**Today's Progress:**
- I got GIT notes fetching working for multiple reviewers!
- I cleaned up the GIT implementation

**Thoughts:**
- The performance is not as good as I'd like it to be, but it can be improved in the future.

### Day 15: April 28, 2020

**Today's Progress:**
- Continued with isomorphic-git. I was able to fetch a single notes branch, but not with a wildcard `refs/notes/morco/*`.

**Thoughts:**
- Git is hard! :)

### Day 14: April 27, 2020

**Today's Progress:**
- Tried to setup isomorphic-git, but got only got so far as to getting the typings working. :/

**Thoughts:**
- TypeScript typings are sometimes hard to get right.

### Day 13: April 26, 2020

**Today's Progress:**
- I read about Git notes as the review information is going to be stored in there (http://alblue.bandlem.com/2011/11/git-tip-of-week-git-notes.html).
- Studied isomorphic-git https://isomorphic-git.org/ and comlink https://github.com/GoogleChromeLabs/comlink so that adding notes from the browser will be possible.

**Thoughts:**
- Git notes are awesome!

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 12: April 25, 2020

**Today's Progress:**
- Added a simple navbar for the diff view

**Thoughts:**
- Building custom components for Tailwind is quite time consuming vs. e.g. using Reactstrap.
- Tailwind has not yet grown into me, but hopefully it will!

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 11: April 24, 2020

**Today's Progress:**
- Added shortcuts for moving between files in the diff view

**Thoughts:**
- Hooks are quite handy for this kind of stuff. I like them more than HOCs.

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 10: April 23, 2020

**Today's Progress:**
- Added styles for diffs and moved to showing only one diff at a time

**Thoughts:**
- Today was a lazy day, but I stille made progress!

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 9: April 22, 2020

**Today's Progress:**
- Added a simple diff view to the diff page

**Thoughts:**
- It's always a PITA when libraries don't have TS typings.
- The "react-diff-view" library seems to just the thing I was after. Let's see if the performance is good enough.

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 8: April 21, 2020

**Today's Progress:**
- Moved to using SWR instead of MobX

**Thoughts:**
- This refactor was not a "must", but handling caching was going to be a PITA, but necessary. SWR handles many situations "out of the box".

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 7: April 20, 2020

**Today's Progress:**
- Created a task for interviewing commit-by-commit reviewers.
- Did a very simple diff page

**Thoughts:**
- There is constantly new information regarding code reviews that can be distilled in to an awesome UI. It just takes time.

**Link to work:**
- [Interviewing commit-by-commit reviewers](https://trello.com/c/RN9qSxcc/15-interview-commit-by-commit-reviewers)
- [Github Repo](https://github.com/apkoponen/morco)

### Day 6: April 19, 2020

**Today's Progress:**
- Bought, studied, and configured Tailwind UI.
- Studied Github and Gitlab GraphQL APIs. Decided to stick with REST APIs, because I could not find a way to fetch commits through the Gitlab GraphQL API.
- Added a commit list to the Change Page.

**Thoughts:**
- The change page is likely going to be the hardest part of this app in terms of design and functionality.

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 5: April 18, 2020

**Today's Progress:**
- Benchmarked through the PR/MR/Change pages for Github/Gitlab/Gerrit and tried out Reviewable.io.
- Added a page for displaying an individual change (merge request).

**Thoughts:**
- The design for the change page is going to be a big challenge.

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 4: April 17, 2020

**Today's Progress:**
- Added a page for displaying merge requests in a repository.

**Thoughts:**
- Progress is slow, but I'm slowly gettin there!
- Setting up async loading helpers in React is somewhat laborious.

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 3: April 16, 2020

**Today's Progress:**
- Moved state to MobX

**Thoughts:**
- Ended up still pondering, if I should use MobX or maybe Overmind. Didn't have to courage to go with Overmind.
- Setting up decorators with TypeScript was surprisingly straight-forward, thanks to good documentation on the MobX site! 

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 2: April 15, 2020

**Today's Progress:**
- Did some domain modeling with paper and pen.
- Added a simple app layout.
- Refactored the login flow to it's own page.

**Thoughts:**
- Redirects in the login flow caused some headaches.

**Link to work:**
- [Github Repo](https://github.com/apkoponen/morco)

### Day 1: April 14, 2020

**Today's Progress:**
- Set up a Backlog for the project using Trello.
- Studied Gitlab and Github APIs in order to make sure it is possible to comment on commits.
- I skimmed https://kentcdodds.com/blog/stop-using-client-side-route-redirects and https://kentcdodds.com/blog/authentication-in-react-applications. Both great articles.
- Got Gitlab OAuth flow working!

**Thoughts:**
- I tried using "react-openidconnect" in the beginning, but Github does not support OpenID connect so I had to ditch it in favor of a custom OAuth implementation
- Setting up the Gitlab authentication flow was maybe a tad harder than I had thought.
- I probably need to use a day for setting up state management at this point.

**Link to work:**
- [Backlog](https://trello.com/b/VpDLd95f/morco-backlog/)

### Day 0: April 13, 2020

**Today's Progress:**
- Set up a Landing Page with ConvertKit
- Started the project with Create React App with Tailwind CSS
- Read Refactoring UI and studied Gerrit UI for design

**Thoughts:**
- Using ConvertKit was easier than expected. Especially setting up custom domain was surprisingly painless.
- Setting up React development environment with TypeScript was a breeze!
- This tutorial for using Tailwind CSS was super valuable https://blog.logrocket.com/create-react-app-and-tailwindcss/.
- Designing the UI is likely going to be a PITA for me, but that only means that I'll learn a ton of new stuff! :P

**Link to work:**
- [Landing Page](http://morco.app/)
- [Github Repo](https://github.com/apkoponen/morco)