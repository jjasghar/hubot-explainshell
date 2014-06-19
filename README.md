
# I have updated this to https://github.com/hubot-scripts/hubot-explainshell

# Hubot: hubot-explainshell

A explainshell wrapper for Hubots.

See [`src/explainshell.coffee`](src/explainshell.coffee) for full documentation.

## Installation

Add **hubot-explainshell** to your `package.json` file:

```json
"dependencies": {
  "hubot": ">= 2.5.1",
  "hubot-scripts": ">= 2.4.2",
  "hubot-explainshell": ">= 0.0.0"
}
```

Add **hubot-explainshell** to your `external-scripts.json`:

```json
["hubot-explainshell"]
```

Run `npm install hubot-explainshell`

## Sample Interaction

```
user1> hubot explainshell tar xvzf ball.tar.gz
Hubot> http://explainshell.com/explain?cmd=tar+xvzf+ball.tar.gz
```
