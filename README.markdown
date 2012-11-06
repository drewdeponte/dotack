# My .ackrc setup

This is my personal `.ack` directory setup which contains my `.ackrc` and any dependency scripts/files that my `.ackrc` uses.

## Installation

    cd ~/
    git clone git@github.com:cyphactor/dotack.git ~/.ack
    ln -s ~/.ack/ackrc .ackrc

## What it Provides

My configuration adds `sass`, `less`, and `scss` extensions to the `css` type.
It also adds Ruby on Rails specific directories to the ignores and explicitly
defines types for Ruby on Rails. This include Cucumber feature files, etc.
