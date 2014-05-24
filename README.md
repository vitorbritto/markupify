![Markupify Logo](src/markupify.jpg "Markupify")


## Welcome

Markupify is a simple method to extract some parts of HTML files.


## Installation

```bash

# 1. Clone this repository
$ git clone git://github.com/vitorbritto/markupify.git

# 2. Place the `markupify.sh` script wherever you want

# 3. Make the script executable
$ chmod u+x path/to/markupify.sh

```


## Usage

    ./markupify.sh [ options ] <LOCAL_FILE, FILE_URL>


### Options:
      -c, --class        output classes
      -i, -id            output ids
      -u, --url          output urls from href


## Bonus

If you prefer, put the following **alias** inside your `~./.bashrc` file:

    alias mify="bash ~/path/to/script/markupify.sh"

Now, you can simply run:

    mify [ options ] <LOCAL_FILE, FILE_URL>


## License

[MIT License](http://vitorbritto.mit-license.org/) © Vitor Britto
