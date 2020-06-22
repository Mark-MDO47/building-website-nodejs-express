# This is my forked copy of Daniel Kahn's brilliant course materials

I forked from https://github.com/danielkhan/building-website-nodejs-express.git

I will be doing some updates based on later versions of NPM modules being available, but I doubt anything I do will be of interest to him.

He actually did not put any license file in his repository, but I took the course and assume I can use the files.

The rest of the README is from Daniel Kahn.

# Building a website with Node.js and Express

This repository contains the code for my course 'Building a Website with Node.js Node.js' on [LinkedIn Learning](https://www.linkedin.com/learning/building-a-website-with-node-js-and-express-js-3).

The master branch contains the initial version to get started with, while the branches contain the state of the code at the beginning (e.g. 02_02**b**) and end (e.g. 02_02**e**) of a video.

## Setting up the project

* In your terminal, create directory `building-website-nodejs-express` and **change into it**.
* Run 
  ```bash
  git clone --bare git@github.com:danielkhan/building-website-nodejs-express.git .git
  git config --bool core.bare false
  git reset --hard
  git branch
  ```
  
Everything else will be discussed in my course.
