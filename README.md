# Nitroradical

Scrape the [BBC iPlayer](http://www.bbc.co.uk/iplayer/) TV listings
by category. It displays the programme info for that category as JSON
and outputs an RSS feed.

## Why?

Because the BBC recently stopped their RSS feeds for iPlayer. They have
a replacement API (Nitro), but that's only open to BBC employees right
now :(

## Install

Install dependencies using `pip install -r requirements.txt`.

## Usage

`nitroradical.py <category name>`

e.g. `nitroradical.py films`

## Not implemented yet

* Getting [BBC Programme Identifiers](https://en.wikipedia.org/wiki/BBC_Programme_Identifier)
for shows with multiple episodes.
* Extracting information from flags (e.g. HD, audio described).
* Radio information.
* Tests!
