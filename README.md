# Full-stack from scratch boilerplate

This is a simple boilerplate for building a full-stack application from scratch using React, Express and Webpack. Babel is also pre-configured inside of the webpack.config.js file.

I created this boilerplate for a few different reasons:

- As a sandbox to practice webpack for any future personal projects.
- To avoid becoming to dependent on Create-React-App (CRA) and risking not grasping CRA's configurations underneath the hood.
- To share with others and learn from those smarter than me.

Feel free to chime in with any comments or suggestions. And I'd love to see other boilerplates as well!

If nothing else, I hope this is useful to you!

Cheers!

## Install

Clone this repo and rename directory

```bash
git clone https://github.com/matthewoctober/full-stack-from-scratch-boilerplate.git
mv full-stack-from-scratch-boilerplate/ enter-project-name
```

Install dependecies

```bash
cd enter-project-name
npm i
cd client
npm i
```

Launch webpack dev server

```bash
npm run dev
```

Open a new terminal window and launch express server

```bash
cd ..
npm run dev
```

Now fire up <a href="http://localhost:8080" target="_blank">http://localhost:8080</a> in your browswer and you're off to the races!

Oh, and don't forget to edit your package.json files' info to your project details (name, description, keywords, author, etc.).

Enjoy!
