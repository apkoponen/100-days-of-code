# 100 Days Of Code - Log

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