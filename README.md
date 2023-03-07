
# Stream Deck Plugin Template


## PLEASE NOTE: 
THIS PLUGIN TEMPLATE IS OUTDATED!!

PLEASE USE THE CURRENT ONE HERE:

https://github.com/elgatosf/streamdeck-plugin-template





---- 


The `Stream Deck Plugin Template` is a boilerplate template to let you get started quickly when writing a Javascript plugin for [Stream Deck](https://developer.elgato.com/documentation/stream-deck/).

`Stream Deck Plugin Template` requires Stream Deck 4.1 or later.

# Description

`Stream Deck Plugin Template` is a complete plugin that shows you how to

- Load and save settings using Stream Deck's persistent store
- Setup and communicate with the Property Inspector
- Passing messages directly from Property Inspector to the plugin (and vice versa)
- Localize your Property Inspector's UI to another language
  
If you think about creating a Stream Deck plugin, it's a good idea to start with this template, because it already implements all code required to communicate from your plugin to the `Property Inspector` and to your `Stream Deck`.

There are also a bunch of utility helpers included, which makes it easy to process messages sent and received via Websockets.

Together with the [`PISamples` library](https://github.com/elgatosf/streamdeck-pisamples/) it helps you create your full-fledged Stream Deck plugin fast.

## Features

Features:

- Written in Javascript
- Cross-platform (macOS, Windows)
- Localization support
- Styled [Property Inspector](https://developer.elgato.com/documentation/stream-deck/sdk/property-inspector/) included
- Property Inspector contains all required boilerplate code to let you instantly work on your plugin's code.

----

# Quickstart

A short guide to help you getting started quickly.

## Pre-requisites

- Download or fork this plugin template.

## Search/replace

Use your utility of choice (or your terminal) to do a full string replace using:

Replace all occurrences of:

`com.elgato.template` with `your.desired-identifier.plugin`

And:

`Stream Deck Template` to `Your Plugin Name`

Notice: the plugin folder **must end** with `.sdPlugin`

Fire up your preferred code-editor and open `app.js`.

Remove what you don't need and start coding (e.g. in the `onKeyDown` method)

## Coding

Happy coding...

## Debug on Stream Deck

Follow [this step](https://developer.elgato.com/documentation/stream-deck/sdk/create-your-own-plugin/)

## Build

Download [Distribution Tool on this page](https://developer.elgato.com/documentation/stream-deck/sdk/packaging/) and follow the step
