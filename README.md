# Mozilia MVP LAB

## Summary
> One line summary of the MVP.* 

A web UI framework in pure wasm

## Desc
> Description of the product: What will the MVP be in 8 weeks? *

This UI framework can write web pages in both rust and javascript, we currently support the basic web components listed in MDN, in the 8 weeks, we plan to implement:

+ A port of basic Material Design
+ rust(wasm) component package manager
+ An official website developed by our lib

## Awesome
> Why does your idea matter: How will it help deliver on the full promise of the internet, or make the internet more awesome? *

Our web UI framework is implemented in wasm, it's faster than vue for 2~3 times and react for 6~8 times for now.

+ People can choose to write web pages in wasm with both rust and javascript
+ If you want to use our library with javascript,  it's like dart, no HTML nor CSS nor JSX.

## Users
> Who are your users or potential users? *

We focus to solve the web development experience for backend developers and newbies.
+ People who doesn't have html and css knowledge want to write web pages
  + backend developers
   + green-hand developers who can not set up web servers themselves
+ Web developers need better performance in their web APPs
  + They can use some sepcified component from our libraray

## Personal connection
> What is your personal connection to the service & the user group you are planning to reach with your product? *

We currently have little idea about this.

+ Develop websites with our library for public service for free.
+ We are members of a large rust community in China, lots of rust developers in that community seems like to try our library.
+ We'd like to hold a contest for developing web pages with our library.

## Idea
> Why did you pick this idea? Do you have domain expertise? How do you know people need what you’re building? *

Our team is composed of a full-stack developer and a backend developer, we'd like to write web pages but it is hard for us to use javascript which has flexible syntax and verbose package managing system.

We have rich experience in rust and Golang and we utilize static programming language to empower js web development experience.

After talking with developers around us, many backend developers also have the same puzzles, and the frontend developers like the wasm idea, so we decide to make it happen.

## Work Plan

Competitors

Yew and Seed are our competitors, 

For Yew, we support writing web pages in pure rust or dart-style(no html, no css, no jsx) javascript, the develop efficiency and experience will be better than nesting html/css in our code.

For Seed, we port our lib to javascript developers who are the mainly developers of web pages.

Milestons

First 2 week development milestone:

+ Write toolkits for rust developers.
+ Clean the code for production.

Second 2 week milestone:

+ Ask 100 developers to try our library
+ Start Migrating Material Design to our library

We currently have milestone after 4 week, it depends on the result of the first 4 week.



## Teammates
> Are you looking for any teammates? If so, please indicate what skills or roles you seek.

We need teammates who:

+ Have the knowledge of both frontend and wasm(Developer)
+ Have good English reading and writing skills including video editing(Marketing Specialist)

## Work Plan
> Describe your work plan. *

## Chanllenges
> What challenges do you anticipate with this idea? *

The wasm-bindgen repo which we currently depend on is not stable for now, API maybe changing all the time, we have to update our design frequently, but at the same time, we will contribute to wasm-bindgen to make the ecosystem of wasm bigger and stronger.

## Details
> Team Details *
Here are two teammates in our team, all of us are blockchain developers.

clearloop, has experience with react and flutter, currently focus on rust, the original author of elvijs and leetcode-cli(rust), and the core developer of darwinia-network.

bear, who loves rust and Golang to hack backend tools in daily life, work in a blockchain minor kernel cita in recent years，which helps enterprise setup private chains from scratch and build the business.

## 8 weeks
> Will all team members be committing their full-time energy to this project during the 8 weeks of the program? Not all successful MVP applicants will, but we do expect a major commitment to the MVP Lab. Please explain if you’re not able to commit fulltime to this & how we can be sure this will be a very serious commitment by you and your team *
We have a plan to contribute to open source projects for full-time energy, but we both have jobs for now.

The project prototype has already developed, all we need to do is upgrading the project to the new design and write more components based on the current framework.

## Hear
> How did you hear about the MVP Lab? *
We have a rust community in China, people recommend us to join MVP Lab.

## Should know
> Anything else we should know? *
If MVP LAB will supports us, we hope the LAB can give us some guidance on how to let more developers come in and contribute to our project.

