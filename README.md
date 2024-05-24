# go-rock-paper-scissors

A simple implementation of the classic game Rock, Paper, Scissors in Go, with a basic web interface.

## Overview

This repository contains a Go package `rps` which implements the logic of the game Rock, Paper, Scissors, and a web server that allows users to play the game via a web interface.

## How to Play

1. Clone this repository to your local machine.
2. Build and run the web server using the `go run` command.
3. Visit `http://localhost:8080` in your web browser.
4. Click on one of the buttons to choose rock, paper, or scissors.
5. See the result of the round displayed on the page.

## Files

- `rps.go`: Defines the game logic and the `PlayRound` function to play a round of Rock, Paper, Scissors.
- `main.go`: Implements the web server and routes for handling HTTP requests.
- `index.html`: Provides the HTML template for the web interface.
- `go.mod`: Specifies the Go modules used in the project.

## Usage

To use the `rps` package in your own Go program, import it and call the `PlayRound` function with the player's choice as an argument. The function returns a `Round` struct indicating the winner and other details of the round.

To run the web server, build the project and execute the generated binary. The server listens on port 8080 by default.

## Dependencies

- This project uses the Bootstrap CSS framework for styling the web interface. The necessary stylesheet is included via CDN.

## Contributors

- [Huntabyte](https://github.com/huntabyte) - Contributor


