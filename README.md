# bashlivescore

## About

bashlivescore is a BASH utility that provides US sports game times for the current day
version: v0.1a



## Dependencies
jq



## How it works
1) Calls the ESPN API
2) Decode json data
3) Format and colorize output



## Disclaimer
This script is only tested on my own computer and terminal. It may not work on yours



## Usage

Usage: livescore [COMMAND] [ARGUMENT]

This script checks for today's US sports games using the ESPN API.

Commands:
        planning                Shows games played today
        live (not yet implemented)

Arguments:
        planning: [nba,nhl,mlb,all]
        live: (not yet implemented)



## Examples

livescore planning all

![](D:\BASH\bashlivescore\livescorebash.gif)



## To-Do



Add support for week input

Add support for multiple date input

Add support for future date input

Add support for past date input with score

Add support for live game with score 