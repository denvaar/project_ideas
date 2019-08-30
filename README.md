# Project Ideas

This is a list of ideas and inspiration for programming projects. Check out the [contributing docs](./contributing.md) if you want to add some ideas of your own.

### Location Tracker

Mobile app that allows you to see where others are in real time on a map

### Battle Royale Game

Web-based multiplayer game where you try to be the last one left.
Basically a very simplistic version of PUBG. Players could even just be dots - nothing fancy required.

### GraphQL Schema Service

A Service that lets users dynamically configure a GraphQL schema for their client side app to consume.
Allow users to quickly and simply create and edit a GraphQL schema.
Allow users to add and edit data for their schema

### Realtime Code Editor

Allow one or more users to create and edit code together.
As a bonus, allow code to be executable for certain languages, similar to JSFiddle, CodeSandbox, etc.

### Personal Budgeting App

Web application that is able to scrape Mint or other data sources to collect financial data.
Allow user to categorize income and expenses.
Display pretty graphs and visualizations of the data.

### Snake Game

Create a version of the classic Snake game.

### Tetris Game

Create a version of te classic Tetris game.

### Tanks Game

Create a multiplayer game that allows players to take turns trying to destroy each other.

### Open World Game

Create a game that allows users to wonder arround and perform at least 3 actions (besides move around.)

### Spelling Checker

A program that takes one or more words as input and outputs the suggested spelling.

### Programming App for Kids

A web application that allows users to build programs. Similar to the Scratch programming language from MIT.

### Maze Generator/Solver

A program that can generate mazes of various sizes, as well as find a path through them.

### 13kb Javascript Game

Create any sort of game, but only with 13kb of Javascript.

### Random Internet Database API

Create an API/service that allows users to store data _somewhere_ on the internet.
That somewhere could be a combination of Pastebin, JSFiddle, whatever.
Encrypt the data at rest so it can be stored at public URLs.

### Base64 Encode/Decode Service

Write a Service, API, or program that can encode and decode using Base64.
Write it from scratch, of course. Try to do the encoding/decoding in parallel.

### Word Game

Create a game that mimics the popular word game, Bananagrams.
Instead of having players battle each other, have the user play against a clock to see how many words they can spell within the time limit.

### Predict Next Word

Create a program that is able to predict the next word of a sentance.
The input is a sentance, up until the missing word. The output is the missing word.

### Text Compressor

Create a program that uses the Huffman Coding algorithm to compress text.

### Sorting Algorithm Visualizer

Create a tool that helps visualize, step-by-step, how different sorting algorithms work.
The visualization should be based off of the input to the tool.

### Data Structure Algorithm Visualizer

Create a tool taht helps visualize, step-by-step, operations on various data structures.
The visualization should be based off of the input to the tool.

### Network Traffic Monitor

Create a program that can monitor network traffic, similar to Wireshark. Much much simpler, of course.

### Concurrent Key-Value Store

Create a key-value store that allows for concurrent and consistent read-write access.

### Video Chat Application

Create a web application that allows two people to chat over live video.

### Walkie-Talky Mobile App

Create a mobile application that allows two people to chat with each other, like a walkie talkie.

### Slideshow Presentation App

Create something similar to Google Slides.
Allow users to create slides.

### URL Shortening Service

Create a service similar to bit.ly.
Possible challenges to solve include:

- Allow users to pick the url
- The service should be highly available (distributed.)
- Shortened links should not be predictable

### Red Light Avoider Program

Create a program that is able to tell users a route to their destination that avoids red lights at all cost.
The program can use fake/simulation data for streets and intersections
The input to the program would be:

1. Start location
2. End location
3. Start time

The output would be a route (list of directions, etc.) Example:

"Forward 3 blocks; Left turn; Forward 1 block; ..."

### Pastebin Clone

Users can store plain text.
Users of the service will enter a piece of text and get a randomly generated URL to access it.

### Command-line Content Publisher

Create a command line application that can be used to manage CRUD operations for a blog site.

### CPU Monitor

Write a program that monitors and displays information about the state of the CPU.

### SP Network

Create a simplified SP Network.

### Keyboard Piano

Create a program that turns the keyboard into a piano
Bonus: Add graphics or visual effects when keys are pressed.

### Dance-Dance Revolution: Keyboard Edition

Create an application that is like DDR, except using the keyboard.

### Sheet music generator

Create a program that can listen to notes on the piano and produce sheet music.

### Simple HTTP Server

Create a simple HTTP web server

### PoliteQL

This is a silly project.
Inspiration comes from GraphQL.
For example, a GraphQL query might look like:

```
query Example {
  people {
    name
    id
  }
}
```

And it would come back with:

```
{
  "data": {
    "people": [
      { "name": "Jack", "id": 1 },
      { "name": "Jill", "id": 2 },
    ]
  }
}
```

Make your own query language that looks like:

```
  Excuse me, may I please know the name and id of the people?
# ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^++++^^^^^++^^^^^^^^++++++^
```

And it would come back with:

```
{
  "yes, you may": {
    "people": [
      { "name": "Jack", "id": 1 },
      { "name": "Jill", "id": 2 },
    ]
  }
}
```

### Base10 to Roman Numeral Converter

Write a program that takes a base10 number as input, and returns a the Roman Numeral as a string.

### RGB to Hex Converter

Write a program that converts RGB colors to Hexidecimal. The program should take three integers as input, and output a string.
Do this as a command-line application, or web application, or whatever you please.

### IBM Watson II

Create a program that can reliably answer "yes" or "no" to any given question. The program should take a query, like, "Is the sky blue?" and come back with "Yes". The main goal is accuracy.

### Tic-Tac-Toe

Create a Tic-Tac-Toe game that allows two players to play against each other.

### Is Computer Turned On?

Make a program that tells the user if their computer is powered on or not.

### Survey App

Make an application which allows users to define questions, share with others, and collect responses.

### Word Counter

Make a program that can process text files and tell the user a bunch of details about the text:

- Total words
- Number of identical words
- 10 Most common words
- Longest word
- Total setences
- Average number of words in a sentence

The goals of this program are accuracy and speed - it should finish execution as fast as possible. The program should be able to gather all of these details in a single go.

### Web Crawler

Write a program that will follow links on the web until it finds a dead end.
The input should be a start URL. The output should be a list of URLs that were visited until the dead end.
For simplicity, the crawler should only crawl the first link it finds on a page, and disregard any others.

### Testing Framework

Write a library that can be used to make assertions about any given function.

### Foreground Text Color Optimizer

Given a background color, determine if the foreground color should be white or black.
For example, if the background color was bright yellow, the foreground should probably be black, or else text would be hard for people to read.

### Music Visualizer

Write a program that can visualize audio in some way.
