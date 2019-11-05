_(This is a fork of [Mapbox's spritezero-cli](https://github.com/mapbox/spritezero). The original repo is no longer maintained and fails to install, but as of 2019-11-05 this copy works.)_

# spritezero-cli

A command-line interface to [spritezero](https://github.com/mapbox/spritezero).

## Installation

    npm install git+https://git@github.com/JaGallup/spritezero-cli.git

## Usage

    spritezero [output filename] [input directory]

      --retina      shorthand for --ratio=2
      --ratio=[n]   pixel ratio
      --unique      map identical images to multiple names

Spritezero reads an input directory containing SVG files and generates a JSON
layout file and PNG spritesheet.
