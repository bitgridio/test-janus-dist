# Example for generator-janus-dist

> This is an example of how to use the [generator-janus-dist](https://github.com/sirkitree/generator-janus-dist) generator for distributing assets in [Janus VR](http://janusvr.com).

## Getting Started

### Understand Yeoman and this generator

A good place to start is the link above to the generator itself. It explains everything, including how to install it.

### Using this repository

This repository is intended to illustrate how to use this generator with a directory of images in order to generate the HTML and FireBox code necessary for placing them into a Janus VR room.

You can visit this example within Janus itself at http://jeradbitner.com/test-janus-dist/public/index.html.

Any questions, comments or improvements about the generator should be directed to the generator's issue queue at https://github.com/sirkitree/generator-janus-dist/issues.

### How this was created

I started with this simple list if images which you can find in the `images` directory.

The following is a list of command from start to finish to generate the `/public/index.html` file found in this repository.

1. `npm install -g generator-janus-dist`
2. `yo janus-dist`

I then chose the default option when prompted. That's it!
