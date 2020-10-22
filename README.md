# Alfred Workflows

A collection of the simple Alfred workflows. 

Alfred is a spotlight replacement for macOS that also does a bunch of other stuff, you should check it out.

[The Alfred Website](https://www.alfredapp.com)

## HTTP Lookup

<img src="https://github.com/AlexJHayward/alfred-workflows/blob/master/img/httpLookup.png" width="256" title="Http Lookup Workflow">

Looks up the given HTTP status code on [httpstatuses.com](https://httpstatuses.com). Just opens a window in the default browser.

So `http 405` would go to [this page](https://httpstatuses.com/405)

## Jira Ticket

<img src="https://github.com/AlexJHayward/alfred-workflows/blob/master/img/jira.png" width="256" title="jira workflow">

Lets you type in either `jira TCK-1234` to jump to the ticket TCK-1234 or there is a separate keyword trigger in there that lets you skip the jira bit if you want to go to a specific project often. For example, to set it up to trigger on `tck` you can then type in `tck 1243` to perform the same action.

There's a environment variable to specify the jira instance URL.

## Random UUID

<img src="https://github.com/AlexJHayward/alfred-workflows/blob/master/img/uuid.png" width="256" title="UUID Workflow">

Triggered by either `randomuuid` or `uuid`, it simply uses the `uuidgen` bash command (which is packaged by default on MacOS and probably other distros too) to generate a random uuid, converts it lowercase, then drops it in the clipboard.

## Workflows not made by me

The alfred-repos workflow by Dean Jackson is amazing and makes Alfred worth the money all on its own if you're a developer.

[check it out](https://github.com/deanishe/alfred-repos)
