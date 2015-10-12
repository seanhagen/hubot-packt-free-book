# hubot-packt-free-book

A Hubot script to get the Packt Publishing free book of the day

See [`src/packt-free-book.coffee`](src/packt-free-book.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-packt-free-book --save`

Then add **hubot-packt-free-book** to your `external-scripts.json`:

```json
[
  "hubot-packt-free-book"
]
```

## Sample Interaction

```
user1>> todays free book
hubot>> Packt free book of the day: Some Awesome Programming Book
hubot>> There is 4 hours and 34 minutes left to claim this book!
```
