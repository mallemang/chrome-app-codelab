# Set up development environment

## Dependencies and prerequisites

* [Chrome Canary on Mac and Windows](https://tools.google.com/dlpage/chromesxs) and [Chromium Dev on Linux](http://www.chromium.org/getting-involved/dev-channel#TOC-Linux)

* Your preferred text editor, we have an under development [Chrome apps plugin](http://chrome-api.storage.googleapis.com/index.html) for [Sublime](http://www.sublimetext.com)

## This lesson teaches you to

* Set up Chrome

* Set up workspace

* Test a simple app

## Set up Chrome

1. Make sure you are using Chrome Canary. Access 

![Checking Chrome version](imgs/screenshot1.png)

1. Enable flags in `chrome://flags`

    * Experimental Extension APIs

    * Enable debugging for packed apps

1. Enable Developer mode in `chrome://extensions

![Enabling developer mode](imgs/screenshot2.png)

## Set up workspace

If you don't have it yet, [install git](https://help.github.com/articles/set-up-git) and run 

<pre>
    git clone https://github.com/GoogleChrome/chrome-apps-appcelerated-tutorial
</pre>

Note: for the rest of this tutorial, we will refer to the directory you've cloned the git repository above as <tutorial>
