# Grund – a foundation to build upon

"Grund" is "foundation" in Swedish. This is my own SCSS foundation I start out new projects from. It's built with [Compass](http://compass-style.org) in mind, but that dependency can be easily pulled out.

# Why create Grund?

Since I'm tired of setting up the same file structure for every new project. I find myself copying over the same files and snippets all over again. Having these resources in a repository is great for collaboration, learning and developing good practices.

Building modular reusable CSS is hard. Thanks to [SCSS](http://sass-lang.org) we are able to do some more fancy work, but when developing a semi-large project it's important to have structure and a way of thinking. 

I've written a post on the subject some time ago which you should read: ["Bringing order to CSS"](http://johanbrook.com/design/css/bringing-order-to-css/). 

# Installation

There are a couple of ways:

## 1. Use the gem

I've created a [RubyGem](http://rubygems.org) for easy installations of Grund. You didn't think I'd create a reusable CSS foundation without a quick way of putting it into a new project, did you?

	gem install grund
	grund install

It'll pull down the files in this repo and put it in the current directory. Run `grund help` for brief info. The repository for the CLI client is located here: [github.com/johanbrook/grund](https://github.com/johanbrook/grund).

## 2. Download the ZIP package

Download the **[ZIP file](https://github.com/johanbrook/grund.css/zipball/master)** with the files.

## 3. Clone the git repo

	git clone git://github.com/johanbrook/grund.css.git

For development, forking, etc.

# Contribute

Contributions, tips and suggestions are welcomed! CSS is a living thing – new best practices develops, and while I'd like to keep the bloat down, it would be great to learn how others are doing it.

# License (MIT)

Copyright © 2012 Johan Brook, http://johanbrook.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.