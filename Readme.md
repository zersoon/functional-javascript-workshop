# Functional Javascript Workshop
<img alt="Functional Javascript Workshop" src="https://f.cloud.github.com/assets/43438/1368315/63919ad8-3997-11e3-909e-8193f5a94b59.png" align="right">



### Teaching fundamental functional programming features of Javascript.

#### No libraries required (i.e. no underscore), just ES5.

<a href="https://nodei.co/npm/functional-javascript-workshop/" ><img src="https://nodei.co/npm/functional-javascript-workshop.png?downloads=true&stars=true"></a>

**Work in Progress.** New lessons and/or revisions will be added weekly and tested upon participants of the [SingaporeJS meetup group](http://www.meetup.com/Singapore-JS/).

## Mission

Many functional programming learning resources will teach you to write functional code, but it's often highly indirect,
deeply abstracted, requires understanding complex relationships between custom library calls, and doesn't represent
the reality of how people actually write JavaScript.

The goal of this workshop is to create realistic problems that can be solved using terse, vanilla, idomatic JavaScript.


## Installation & Update

```
$ npm install -g functional-javascript-workshop@latest
```

**Note**: the workshop is being updated weekly. 
Please regularly rerun the above command to get the latest set of exercises.

## Usage

#### Displaying the Problems Menu

Once the workshop is installed, run `functional-javascript-workshop` to print a menu
where you can select a problem to work on.

```
$ functional-javascript-workshop
```

Problems are listed in rough order of difficulty. You are advised to complete them in order, as later problems
will build on skills developed by solving previous problems.

#### Writing a solution.

Once you have selected a problem, the workshop will remember which problem you are working on. 
Using your preferred editor, create a file to write your solution in.

#### Testing your solution

Use the workshop's `run` command to point the workshop at your solution file. Your solution will loaded 
and passed the problem input. This usually won't perform any validation, it will only show the program output.

```
$ functional-javascript-workshop run mysolution.js
```
 
#### Verifying your solution

Verify your solution against the output of the 'official' solution. If all of the output matches, then you have successfully
solved the problem!

```
$ functional-javascript-workshop verify mysolution.js
```

## Stuck?

Feedback and critisism is welcome, please log your troubles in [issues](https://github.com/timoxley/functional-javascript-workshop/issues). 

Full curriculum reviews [like this one](https://github.com/timoxley/functional-javascript-workshop/issues/7) are incredibly helpful. More feedback like this please!

We're looking for more practical problems, so if you come across a problem in your day-to-day work which was solved simply and elegantly with some functional JavaScript techniques, please help us create an exercise out of it.


## Screenshots

![screen shot 2013-09-27 at 5 18 45 pm](https://f.cloud.github.com/assets/43438/1225514/08c87a70-276a-11e3-8db7-485e3c760373.png)
![screen shot 2013-09-23 at 9 13 02 pm](https://f.cloud.github.com/assets/43438/1191466/f289f38a-2451-11e3-9ba5-a3c224b5ca97.png)

## Resources

[A growing collection of quality functional javascript resources can be found in the wiki](https://github.com/timoxley/functional-javascript-workshop/wiki). 


## Thanks rvagg

This tutorial was built using rvagg's [workshopper](https://github.com/rvagg/workshopper) framework.

## Licence

MIT
