## Personal Project "Post-Mortems"

I’ve been enjoying seeing Twitter abuzz with side projects and people discussing why they do or don’t get to them so I thought I’d make a laundry list of projects I started, why they failed, and what I learned from them. 

If you have any projects that you’d like to share, write it up and open a PR on my [Side Project Post Mortem Github repo](https://github.com/AntJanus/side-project-post-mortems).

The purpose of this exercise is to get a feel why things don’t get finished, why they fail, and also to share in the struggle many developers experience.

I’ll be listing these from based on how they show up in my repos tab on Github and Bitbucket. Hopefully, I’ll add to the list over time!

## The Projects

### [Programmer’s Proverbs](https://github.com/AntJanus/programmers-proverbs)

My most popular repo with over 500 stars. The project was supposed to be a fun collection of programming wisdoms written like proverbs. And on the flip side, existing proverbs rewritten as fun programming wisdoms. With my most famous one being:

- **Even a greybeard will drop production DB.**

The project stalled quickly as people submitted general wisdoms that weren’t in that fun format, or just proverbs that didn’t make sense. A few times, the proverbs were plagiarized or submitted by someone other than the author.

I _did_ write an API to access these. 

**Tl;dr** The project didn’t really“fail”, more of fell into unpopularity and never got updated by anyone. With a fresh coat of paint, I could probably restart it!

### [OMEN](https://github.com/AntJanus/omen)

Not really a post-mortem since I’m still working on it! But OMEN is a markdown editor that I want to build to be a Scrivener killer. If you do any amount of writing or self-publishing, you’ll recognize Scrivener. So far, I’ve been able to write a 30K novel in it without issues. Check my Dev Updates entries for more info.

**Tl;dr** Not dead, still being developed! Albeit, slowly.

### [AngularJS To Angular Book](https://github.com/AntJanus/AngularJS-To-Angular-Book)

A mini-ebook that walks a user through converting and integrating AngularJS 1.X with Angular 2+. The project never really started because I still haven’t been able to do it in a production setting. I’ll most likely not come back to it due to time constraints. I have a lot of these empty repos that are ideas that never really even started.

**tl;dr** An idea for a project quickly abandoned because of technical difficulties and time constraints.

### [RollD20](https://github.com/AntJanus/rollD20)

A CLI utility that allows you to roll a D20(or other dice) for a game of DnD. It was supposed to be a simple and cool CLI with some nice output options. A part of it was supposed to also read the current folder for a config file so that you could do rolld20 attack and it would figure out the equation from it.

Alas, just like the previous project, it died before it began. Time constraints, existing alternatives, and other issues left me with an empty repo.

**tl;dr** Lost interest in the project, essentially

### [JSON Structure Validator](https://github.com/AntJanus/JSON-structure-validator)

What should be called a Javascript Object Structure Validator became my favorite project yet. It’s a library that helps test the structure of objects that came back from an API to ensure the structure satisfies minimal requirements.

I built this and used this heavily on two production apps in the testing suite. The project still gets a handful of [downloads from NPM](https://www.npmjs.com/package/json-structure-validator). It was an utter success though. It meant that you could check the integrity of an API response without needing to know the exact values to expect. It worked well for generated data, fast-changing seeds, and so on. In fact, you could simply loop through collections of responses and any new seeds would be automatically tested.

The project evolved into a more robust reincarnation called [Skorice](https://github.com/asteridux/skorice) which added features such as:

1. check exact(to see if the structures are exactly matching, not just“like” each other)
2. type checking(checks the type of the value, still in development)
3. templating(so that you could build an assertion structure and not have to recreate it each time)

**tl;dr** The project was a success and due to the fact that it satisfied 99% of my personal use cases, it was left mostly untouched for a couple of years. It also inspired a successor project!
