![Logo](logo.png)
# Feed-Nim
A feed parsing module for [Nim](https://nim-lang.org), which parses RSS, Atom, and JSONfeed syndication formats. This has been substantially re-written and expanded from [Nim-RSS](https://github.com/achesak/nim-rss).

It has not been tested, has no tests, and is mostly written by an inexperienced dope who barely understands Nim. It probably doesn't work. Use at your own risk.

## Usage

<code>loadAtom(filename: string): Atom</code> Loads the Atom from the given _filename_<br>
<code>getAtom(url: string): Atom</code> Gets the Atom from the specified _url_<br>

<code>loadRSS(filename: string): RSS</code> Loads the RSS from the given _filename_<br>
<code>getRSS(url: string): RSS</code> Gets the RSS from the specified _url_<br>

<code>loadJsonFeed(filename: string): JSONfeed</code> Loads the JSONFeed from the given _filename_<br>
<code>getJsonFeed(url: string): JSONfeed</code> Gets the JSONfeed from the specified _url_<br>