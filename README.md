# Calendar Page

A simple webpage calendar for your events. Designed to be entirely staticly hosted in a git like environment, no database, no backend.

## Setup

Assuming you are using github for this but there isn't anything stopping you hosting this anywhere you like and using what ever update process you like.

* Fork this repo
* Edit the `config.json` file
  * Fill in the calendar name
  * Fill in the description
  * Fill in the repo name using your fork.
  * Decide if you want a link to the repo to be displayed so people know where to come to add entries to it
* Enter your entries in the `entries.csv` file.
  *
* Enable github pages on the main branch and wait for the action to run.

## Design Principles

* No external dependencies.
* Static files only. No backend processing required
* Understandable code. Readable over clever
* Use the platform. Prefer HTML and CSS to Javascript

## TODO

* Multi day events
