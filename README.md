# Calendar Page

A simple webpage calendar for your events. Designed to be entirely staticly hosted in a git like environment, no database, no backend.

## Setup

Assuming you are using github for this but there isn't anything stopping you hosting this anywhere you like and using what ever update process you like.

* Fork this repo
* Edit the `config.json` file
  * Fill in the calendar name
  * Fill in the description
  * Fill in the repo name using your fork.
  * Decide if you want a link to the repo to be displayed so people know where to come to add events to it
* Rename the `events_example.csv` to `events.csv`. This will make it easier to update later.
  * The header line must be left in there.
  * For the sake of everyone's sanity all events are assumed to be in the same timezone.
  * If you provide a latitude and longitude location it will link to open street map to show people where the event is.
* Enable github pages on the main branch and wait for the action to run.

## Design Principles

* No external dependencies.
* Static files only. No backend processing required
* Understandable code. Readable over clever
* Use the platform. Prefer HTML and CSS to Javascript

## TODO

* ICS Download
