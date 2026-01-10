# Marketplace for Cosmos

This repo is a marketplace for Cosmos ServApps.
It will be for testing or maybe also my own ServApps.

## How to use

Go to Market in Cosmos UI, and then click 'Sources'.
Add the url `https://julowe.github.io/cosmos-marketplace`
to the sources list, give it a name, and save it.

## Stable Apps

Unless otherwise listed below, assume the other apps in this marketplace are
either some random configuration I wanted, or are not stable enough for general
use.

- [Obsidian LiveSync Server](./servapps/obsidian-livesync-server/cosmos-compose.json)
- [twitter-futzing](./servapps/twitter-futzing/cosmos-compose.json) - a very
  hacky web UI to some python code I made/had an LLM make for a friend to parse
  their twitter archive/export and do some random NLP stuff on it.
- [Vikunja](./servapps/vikunja/cosmos-compose.json)

## Works In Progress / Unstable Apps

- [linkwarden](./servapps/linkwarden/cosmos-compose.json) - Tried to get
  [meilisearch](https://www.meilisearch.com/docs/guides/docker)
  working, no luck yet.
- Actual-server - I left this as a template to remind myself how to make
  ServApps. And also to have a known good ServApp to test installing through
  the Cosmos UI Marketplace.
