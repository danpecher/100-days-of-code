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
