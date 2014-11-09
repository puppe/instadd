instadd is a simple shell script that lets you add articles to
[Instapaper](https://www.instapaper.com) from the command line.

## Installation

Simply copy `instadd` to a location that is on your `PATH`.

Alternatively, if you are on OS X and are using Homebrew, you can just
type the following into your terminal:

```
brew tap puppe/instadd
brew install instadd
```

## Usage

You need to create a file `$HOME/.instadd` that contains your
credentials:

```
cd $HOME
touch .instadd
chmod 600 .instadd
```

The content of the file should look like this:

```
username=johndoe@example.org
password=supersecretpassword
```

Afterwards, adding an article is as simple as typing:

```
instadd http://www.example.org/article
```

## License

Copyright © 2014 Martin Puppe

Distributed under the MIT License.
