medium-cli
==========

Medium for Hackers - A CLI for Medium Stories. 
Now read awesome medium articles right in your terminal.

## Installation

`$ npm install -g djadmin/medium-cli`
or
`$ npm install -g medium-cli`

`$ npm link`

## Usage
There are three commands available: medium top, medium read, medium open

###top
`$ medium top`
    List Medium Top Stories
`$ medium top -n 5`
    List only top 5 Medium Stories
##read
`$medium read <url>`
Read the story right in your terminal

##open
`medium open <url>`
Opens it in your browser
`medium open -a firefox <url>`
Opens it in the given application, like it opens the url using firefox in above example.

## DOCS
 Usage: medium [options] [command]

  Commands:

    top [options]         List Medium Top Stories
    read <url>            Read the story right in your terminal
    open [options] <url>  Opens it in your browser

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
    top [options]
    n, --number <int>", "specify number of stories
    open [options] <url>
    -a, --app <application>  specify app to open the url. Eg: firefox

## Contributions
medium-cli is developed in Node.js and would love to accept any pull request for issues or any feature request.

## License
Copyright (c) 2016 Dheeraj Joshi
Licensed under the [MIT license](http://opensource.org/licenses/MIT).