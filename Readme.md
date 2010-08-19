# Tasks Bundle #

Tasks bundle for Textmate. Based on Tasks bundle from [Henrik Nyh](http://henrik.nyh.se/2007/08/tasks-bundle) but improved in some aspects.

## Features ##

This bundle let's you manage tasks lists with Textmate. Tasks can be grouped in sections. Each task has two available states: pending, and done.

For example:

    Project 1:
    ✓ task 1
    ✓ task 2
    - task 3

All this features came with the original version from Henrik.

I have added a second level for sections, and also a footer for each sections. That's because I get use to create a task list per day, and inside each day, a list per project. Also, I like to annotate some conclusions at the end of each day in each project.

This would be a sample task list for me:

    Monday:

    @ Project 1

    ✓ task 1
    ✓ task 2
    ✓ task 3

    > spent 3h

    @ Project 2

    - update the library version and deploy

    Tuesday:

    @ Project 1

    - task 1
    - task 2

    @ Project 2

    - check for bugs
 

## Installation ##

To install via Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/ferblape/Tasks.tmbundle.git
    osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [http://github.com/ferblape/Tasks.tmbundle.git](http://github.com/ferblape/Tasks.tmbundle.git)

## License ##

(The MIT License)

Copyright (c) 2010 Fernando Blat, http://fernando.blat.es. 

Based in the code from [Henrik Nyh](http://henrik.nyh.se/2007/08/tasks-bundle)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.