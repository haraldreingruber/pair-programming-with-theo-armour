[to do]( #todo.md )


# pair-programming-with-theo-armour

This repo will be used for discussing and prioritizing collaboration topics.

## 2020-04-08

Harald's Blog Post about Week 1 of Pair-Programming Tour: https://dev.to/harald3dcv/remote-mob-programming-hunter-industries-18ac

Updates since Monday:

### [Cookbook]( https://ladybug-tools.github.io/spider-covid-19-viz-3d/cookbook )

* Demos of the various modules used to build the viewer

### [Archive Gallery 2]( https://ladybug-tools.github.io/spider-covid-19-viz-3d/dev/covid-19-viz-3d-archive )

* Files for every daily project update since 200-03-19. Some files are better than others.

### [Archive Gallery 1]( https://ladybug-tools.github.io/spider-covid-19-viz-3d/dev/covid-19-statistics-on-globe )

* Files from the first day of the project

No work on ESLint yet



## 2020-04-06

* Move this repo to an organization?
- Adrian Bolboaca - Remote Pair-Programming: https://www.youtube.com/channel/UC7H7P2tu2i3Wnz-ZBdnO13Q

- Mr.Doob Approves Rules: https://github.com/zz85/mrdoobapproves/blob/gh-pages/mdcs_eslint.js


## 2020-04-02

> If it hurts, do it more often.
>
> *-- Jez Humble* from https://continuousdelivery.com/

- https://jsonbox.io/
- force ESLint formatter: https://github.com/microsoft/vscode-eslint/issues/417#issuecomment-566209216

## 2020-03-31

Links to Harald's "Google Summer of Code" proposals:
- Blender: https://docs.google.com/document/d/1jhj93fujGBkRm0z1FdE2_MOWuOOgKerYJdjSEYEooRA/edit?usp=sharing
- Inkskape: https://docs.google.com/document/d/1Jf-NruuNOqh-_lIeqLbIvhRfjJs3BmuFamjDeGeu-rA/edit?usp=sharing

Interesting (Synced) Mob-Programming timer (could be also used for Pair-Programming):
- https://github.com/mrozbarry/mobtime

## 2020-03-30 - Evening Session

### DateVer/CalVer (instead of SemVer)

- https://calver.org/



## 2020-03-30 - Morning Session

### Mostly Harald

Let's get started with pair-programming.

For the beginning we decided to loosely start pair-programming with the traditional Driver/Navigator roles, and switch roles after several minutes using a timer.


Here are some pair-programming resources:

- https://www.thekguy.com/2-tips-to-make-pair-programming-less-scary.html
- https://medium.com/@volkanbier_42259/how-to-put-pair-programming-into-action-ce9ebb9d711
- https://en.wikipedia.org/wiki/Pair_programming
- https://www.agilealliance.org/glossary/pairing/
- https://martinfowler.com/articles/on-pair-programming.html
- https://stackify.com/pair-programming-advantages/
- https://hackernoon.com/the-ultimate-guide-to-pair-programming-b606625bc784
- https://wiki.c2.com/?PairProgramming


Here are timers we can use for starting pairing:

- https://double-trouble.wielo.co/
- https://theo-armour.github.io/qdata/apps/dashboard3/teodori-2020-02-08.html


Initial configuration of eslint we created during our first session:

- https://github.com/haraldreingruber/spider-covid-19-viz-3d/tree/feature/linting

### Mostly Theo


#### Node

I had uninstalled node, so I have to reinstall

* http://nodejs.org

Install suggested version: node-v12.16.1-x64.msi

Node installed in C:\Program Files\nodejs\

Chocolatey installs Python 2.7!!!!

#### NPM

* https://docs.npmjs.com/downloading-and-installing-node-js-and-npm

In Git Bash

$ npm install npm -g

later

$ npm -v
6.14.4

#### ESLint

* https://eslint.org/docs/user-guide/getting-started

In Git Bash

$ npm install eslint --save-dev

	npm WARN deprecated mkdirp@0.5.4: Legacy versions of mkdirp are no longer supported. Please update to mkdirp 1.x. (Note that the API surface has changed to use Promises in 1.x.)
	npm WARN saveError ENOENT: no such file or directory, open 'C:\Users\tarmo\package.json'
	npm notice created a lockfile as package-lock.json. You should commit this file.
	npm WARN enoent ENOENT: no such file or directory, open 'C:\Users\tarmo\package.json'
	npm WARN tarmo No description
	npm WARN tarmo No repository field.
	npm WARN tarmo No README data
	npm WARN tarmo No license field.

	+ eslint@6.8.0
	added 134 packages from 84 contributors and audited 179 packages in 8.033s

	7 packages are looking for funding
	run `npm fund` for details

	found 0 vulnerabilities

$ npx eslint --init

Remember

- Very tricky. Install process is dumber than you think.
- You actually have to edit the lines to move the ">" symbol
- Once you have edited the line, go to to the end of line before pressing enter

$ npx eslint main.js

Takes over 7 seconds to run

Could install globally, but:

> It is also possible to install ESLint globally rather than locally (using npm install eslint --global). However,
> this is not recommended, and any plugins or shareable configs that you use must be installed locally in either case.

$ npx eslint main.js --fix

Does not seem to save changes

#### ESLint in VS Code

22:39  ~ Installed, but not working




