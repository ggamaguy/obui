# Px-Context-Browser [![Build Status](https://travis-ci.org/PredixDev/px-context-browser.svg?branch=master)](https://travis-ci.org/PredixDev/px-context-browser)

[![px-context-browser demo](px-context-browser.png?raw=true)](https://PredixDev.github.io/px-context-browser/)

## Overview

px-context-browser is a hierarchical tree navigation component that uses horizontally cascading lists in columns to allow multiple levels of the hierarchy to be open at once, and provide a visual representation of the current location. Menu items that are `openable` are given an Open button that upon selection chooses the item and closes the navigation, returning it to it's initial state: A drop-down and breadcrumb that display the menu's last-selected state.

## Usage

### Prerequisites
1. node.js
2. npm
3. bower
4. [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs)

Node, npm and bower are necessary to install the component and dependencies. webcomponents.js adds support for web components and custom elements to your application.

### Getting Started

First, install the component via bower on the command line.

```
bower install px-context-browser --save
```

Second, import the component to your application with the following tag in your head.

```
<link rel="import" href="/bower_components/px-context-browser/px-context-browser.html"/>
```

Finally, use the component in your application:

```
<iron-ajax url="<URL.json>" last-response="{{browserContext}}" auto></iron-ajax>
<px-context-browser browserContext={{browserContext}}></px-context-browser>
```

<br />
<hr />

## documentation

Read the full API and view the demo [here](https://predixdev.github.io/px-context-browser).

## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory, to start a local server run:

```
$ gulp serve
```

Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.

### GE Coding Style Guide
[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

<br />
<hr />

## Known Issues

Please use [Github Issues](https://github.com/PredixDev/px-context-browser/issues) to submit any bugs you might find.
