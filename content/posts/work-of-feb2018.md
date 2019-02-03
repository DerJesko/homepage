---
title: "Work of Febuary 2018"
date: 2019-02-02T23:24:38+01:00
---
## Projects
Currently I have a few for fun projects:

 - implementing a cryptography library
 - finishing up and testing my reversi/othello libary
 - fixing packaging for sosml interpreter
 - starting this website
 - working on container based server for the computer science students council at Saarland University

I'm also working in vipfy and on my bachelor thesis.

My latest book purchase is "The Outsider" by Colin Wilson, which I heard Duncan "Thorin" Shields mention in one of his videos.
Reading used to be one of my passion and I want to revive that. My goal is to be done with the book on the 15th of march.

## reversi
On a Global Day of Code event we had a challenge of implementing a board game called [reversi/othello](https://en.wikipedia.org/wiki/Reversi) in just a few minutes with different limitations.
My groups were never able to finish the assignment in time like many others.
(Luckily) It is also a part of an event like this to delete ones code directly after the challenge so none of code is available anymore.
However this sparked the idea of doing it for real.
That is what I did (with my own modifications).
I thought it was boring that only it is only a two player game so I "improved" it by making it for arbitrary amounts of people.
The board only has a dimension of 2 which means it is way to easy to imagine and play and therefore I had to fix this major flaw by making it a arbitrary dimesion board.
The problem with this change is that I have lost the ability to imagine a useable UI my solution so far has been to declare it a library.
This month I want to change that eventhough I doubt my version of the game will be much fun to play.
I used Rust to implement this (actually this project is just an excuse to learn Rust).
I doubt this will be much of a longterm project.

## Crypto library
Since I have lots of fun in a course I'm taking called "Advanced Public Key Cryptography" which is concered with Public Key Cryptography (who imagined that) I thought it would be a good idea to implement some of the learned cryptosystems.
For [this projects](https://github.com/DerJesko/bad_crypto") I have chosen Rust as a language because I like it and it's harder to write wrong code than in other languages.
I might write a post about my favourite programming languages at some point.
This library is not supposed to be useful, it's more a toy project.
Further information about that in future posts.

## SOSML
Quite some time ago I had a software engineering project in university which was to write a SML interpreter.
Saarland University (where I study) uses [SML](https://en.wikipedia.org/wiki/Standard_ML) to teach first semester students basic programming in a lecture called "Programmierung 1" (programming 1).
When I started the course, which should be 2015 we used a interpreter called MosML aka. MoscowML.
MosML doesn't have all the features our professors wanted and it was kind of a struggle to install.
So in 2017 a few friends of mine and I decided to write our own interpreter and a webinterface for it.
Big parts of our inspiration came from using [pseuco.com](https://pseuco.com) in our "Nebenlaeufige Programmierung" (concurrent programming) lecture.
This tool was/is developed by the chair of Prof. Hermanns and was very convenient for the students.
After some research we decided on using Node, TypeScript and React eventhough most of us had almost no experience in any of these things.
This caused us to have a horrible packaging and deployment scheme.
Since I have learned alot about these technologies while working for [Vipfy](https://vipfy.store) I will now try to improve these problems.
Except for this I'm not much involved in the maintainace of [SOSML](https://github.com/SOSML/SOSML) anymore.

## This Website
For a while I had urge to host my own website and a few other things. Luke Smith inspired me to finally go through with it.
I went and registerd a free domain name "dujmovic.ml" on [freenom](https://myfreenom.com) and rented a VPS from [netcup.de](https://netcup.de).
So far this has been alot of fun.
I'm also thinking about hosting other things on here but thats not concrete yet.
The Website is generated with Hugo which also is a interesting technology.

## Students council server
In the students council i was appointed SysAdmin without having much experience.
Now I have to migrate all our old systems to a newer container based architecture which I want to have done by the end of this month.
