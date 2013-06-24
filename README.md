# chatty

A very (very) simple chat server with web client interface.

## RECENT EDIT for OpenShift Blog Readers

I haven't (completely) abandoned this code, but you'd think I have with my lack of updates. If you are here due to the OpenShift blog article I did some time ago, thanks to a couple of readers I've fixed things up so this code works with the current iteration of OpenShift. The problems were minor and had to do with OpenShift supporting websockets natively (which is awesome) and some incompatibilities with node 0.10.

## Requirements

* node.js (assumes 0.6.0 or greater)
* npm (assumes 1.0.0 or greater)  

## Basic usage

    # all from the command prompt within this directory
    npm install
    # start the server piece
    node server.js
    # from here, load up a web browser and point it to
    #     http://localhost:8080/
    # and if you are secure in your sanity, open more than one
    # web browser and chat with yourself.
