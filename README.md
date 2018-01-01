# rock-paper-scissors

Simple "rock paper scissors" implementation playble from the console. Built for [The Odin Project - Web Development 101](https://www.theodinproject.com/courses/web-development-101/lessons/rock-paper-scissors?ref=lnav)

I learned here how to use `Math.random` to get a random value from an array.

```
let selection = ["rock", "paper", "scissors"];

let computerSelection = selection[Math.floor(Math.random()*selection.length)];
```