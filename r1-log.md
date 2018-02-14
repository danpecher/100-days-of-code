# #100DaysOfCode Log - Round 1 - Daniel Pecher

The log of my #100DaysOfCode challenge. Started on [January 15, Monday, 2018].

## Log

### R1D0
Wrote my first blog post ever (https://medium.com/@dan.pecher/a-new-start-advancing-in-programming-by-building-projects-ad1908070009) to set myself clear on my goals and tell others what I plan on doing.

### R1D1
Started work on first app, and trying to keep it simple from the beginning - it's a note-taking app: https://github.com/danpecher/notes-app. Setup a rails project and create empty components.

### R1D2
Setup css modules and created basic layout with switchable notes (only dummy data for now). I haven't added redux to the project, but probably will. I feel like redux (or some other state management) is useful even in tiniest apps. Today's commits: https://github.com/danpecher/notes-app/search?q=committer-date%3A2018-01-18&type=Commits&utf8=%E2%9C%93

### R1D3
Replaced dummy notes with actual data from db and added some buttons (add, save, delete). Adding works, next step is to make saving and deleting work.
Today's commits: https://github.com/danpecher/notes-app/search?q=committer-date%3A2018-01-19&type=Commits&utf8=%E2%9C%93

### R1D4
Today I added a TODO list to the [README](https://github.com/danpecher/notes-app/blob/master/README.md). Saving and deleting works and I also added ability to edit the note title. To make the code more consistent, I started using [prettier](https://github.com/prettier/prettier). I'm looking forward to playing with css so the app looks better.

### R1D5
Added a simple frontend search and started to work on text formatting (just simple B, U, I for now) so I'm reading about Selection API https://developer.mozilla.org/cs/docs/Web/API/Selection.
Today's commit (1 🤷‍♂️): https://github.com/danpecher/notes-app/commit/b3fcc3bead43b56d863c005f7753b553f9260299

### R1D6
No commits today. I wanted to make simple text formatting, but after realising how much work that is, I decided to incorporate an existing text editor. Not that I were so lazy, but I think text formatting in JS is a challenge of itself and will make for a project of its own. In the future I will try to make my own simple text editor from scratch.

### R1D7
Finished quilljs integration, added devise gem and made the app little bit prettier.
I found out that the link to today's commits on github doesn't respect my timezone so sometimes it might return empty results even though I made commits that day. 

### R1D8
I updated the app to keep note content after switching between them and added autosave + logout link.

### R1D9
Finished notes app by styling login form and deploying to heroku. There is so much I could improve about this app but since it's just an exercise, I will leave it like that. Also I worked on [Brewtime app](https://brewtimeapp.com/) update.

### R1D10
I made some final fixes to @AppBrewtime before an update to app store and started working on a new app that could potentially be useful to people doing #100DaysOfCode. I setup rails project with react_on_rails and had some trouble enabling css modules. (fixed with https://github.com/rails/webpacker/blob/master/docs/webpack.md#overriding-loader-options-in-webpack-3-for-css-modules-etc)

### R1D11
R1D11 first missed day (not because I was lazy but because I simply didn't find the time). But today I finally started coding my #100DaysOfCode app, after some initial fight with webpacker and hot reloading. Right now I'm coding the timeline and thinking about its design & UX.

### R1D12
Pushed myself to code even though I returned home from camping tired at 8PM. Coded first simple version of the design of #100daysofcode app.

### R1D13
Today I took a detour and dived into Redux documentation. I tried some basic examples and tomorrow I will start using Redux in my #100DaysOfCode app.

### R1D14
I started implementing TodoMVC using React&Redux to really grasp the concepts, hopefully tomorrow I will finish it so I can continue working on the #100DaysOfCode app – I'm getting tired of manually posting to Twitter + Github

### R1D15
I still haven't finished the todomvc app..Even the (seemingly) simple things in programming can take exponentially longer than originally estimated😋 But fortunately purpose of this exercise is to learn, not to rush. And I'm learning a lot about react & redux

### R1D16
React/redux todomvc app is finished! I'm really starting to like Redux and the flux pattern. Looking forward to solving more complex problems with it! Tomorrow I will finally continue with the #100DaysOfCode app.

### R1D17
No commits today but I started using Redux in my #100DaysOfCode app. Hopefully after this weekend I'll be able to use this app to post my daily log 🤞today at my job coding I used Vuex in one project and it was interesting to see how it compares to Redux.

### R1D18
#100DaysOfCode app: I implemented basic posting using Redux (https://github.com/danpecher/daysofcode/commit/cec6a4aa52a36a71e77dedf3d2a581eefaae8f9a) and started working on authentication. I'm using https://github.com/omniauth/omniauth to connect with Github and Twitter. There will be an on-boarding process to guide the user through authentication. 

### R1D19
#100DaysOfCode app: Today was less about coding and more about designing and thinking how the onboarding process should look. I designed it in sketch and started implementing frontend code for it.

### R1D20
#100DaysOfCode app: I decided to ditch the onboarding process and just display an overlay when the user is not logged in, so that's what I'm working now. Don't overcomplicate things :) Yesterday was a miss as I didn't find the time and/or energy. 

### R1D21
#100DaysOfCode app: I'm already able to query twitter and github on the authenticated user's behalf and now I'm working on the interface where user chooses which file of which github repo is his 100DaysOfCode log (so it can later be updated automatically).


### R1D22
Today I'm already posting from the 100DaysOfCode app! It's still rough around the edges and needs more work, but at least for now the core functionality works. Remaining: support for projects, better design, public timeline, missed days, timezone setting.

### R1D23
I'm currently implementing missed days – there will be a rails job running every hour (bcs of timezones), adding missed days for users who didn't post on a given day.  It will be a challenge to properly handle timezones! (two missed days so i can test it 😜)
