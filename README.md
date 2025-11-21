Introduction
============

It's a GitHub Page for Scratch 3 GUI

Scratch 3 GUI for Sipp Rabboni --> [LINK](https://nctutwtlab.github.io/scratch-gui/rabboni/)


Development
=====

Follow this [Wiki - Getting Started](https://github.com/scratchfoundation/scratch-gui/wiki/Getting-Started#example-scratch-gui-vm-and-blocks-linked)

### Setup project links

* `scratch-vm` Side

``` bash
npm install
npm link
```

* `scratch-gui` Side

``` bash
npm install
npm link scratch-vm
```

### Start developing

* `scratch-gui` Side

``` bash
npm run start
```

Deployment
==========

Reference: [LLK/scratch-gui Wiki - Publishing to GitHub Pages](https://github.com/LLK/scratch-gui/wiki/Publishing-to-GitHub-Pages)

```
npm run build
npm run deploy -- -e rabboni
```
