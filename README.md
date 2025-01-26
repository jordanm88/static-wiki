# jdSite

A lightweight, markdown-powered CMS that turns your plain text files into a dynamic website. Perfect for personal sites and digital gardens, it seamlessly integrates with webDAV storage and supports wiki-style linking. Write in markdown, publish instantly - no build step required.

## Features

- All content (including components - menu, header, footer) is rendered from Markdown files
- There is no need to generate static HTML pages
- Sites can be previewed locally using the file:// protocol - no need to spin up to a server
- Responsive design with auto light/dark modes
- Supports Obsidian-style [[Wikilinks]]
- HTML + CSS + Javascript - can be hosted on Github Pages or other static hosts

## How to use

- Clone repo
- Update 3x config field values in index.html
- Create *.md files in the content sub-directory - these will be your pages
- Edit the navmenu.md, header.md and footer.md files in the _components subdirectory
- Open index.html in your browser to confirm everything works
- Publish to Github Pages or the host of your choice

## Demo

https://jondoran.github.io/jdsite/
