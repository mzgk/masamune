# Masamune（正宗）

## Overview

Masamune is a 2 column simple blog theme for Hugo.

- Simple and clean design
- Pagination
- Category
- Tag
- Disqus
- Source code highlighting
- Google Analytics

## Screenshot


## Installation
Clone this repository to your hugo theme directory.

```@bash
$ cd themes
$ git clone https://github.com/mzgk/masamune
$ hugo server -t masamune -D -w
```


## Configuration
To take full advantage of the features in this theme, you can add variables to your site config file.

The following is the example configuration.

```@toml
baseurl = "http://mzgkworks.com"
languageCode = "ja-JP"
title = "mzgkworks.com"

canonifyurls = true
isCKJLanguage = true
disqusShortname = "mzgkworks-com"

[Params]
subtitle = "Stack the little bets."
facebook = ""
twitter = "https://twitter.com/mzgkworks"
github = "https://github.com/mzgk"
showsRSS = true
profile = "/images/profile.png"
copyrightyear = "2016"
copyright = "mzgk"
analytics = ""
```

Details of each parameter are as follows.

| Parameter | Required | Comment |
| :--- | :--- | :--- |
| baseurl | yes | Enter the title of your site. |
| languageCode | yes | Enter the language code of HTML. Example: en-US, ja-JP. |
| title | yes | Enter the title of your site. |
| canonifyurls | yes | true |
| isCKJLanguage | no | true |
| disqusShortname | no | Enter the short name of the disqus. If you do not enter, disqus section is hidden. |
| subtitle | no | Enter the subtitle of your site. If you do not enter, subtitle is hidden. |
| facebook | no | Enter the URL of Facebook. If you do not enter, the link is hidden. |
| twitter | no | Enter the URL of Twitter. If you do not enter, the link is hidden. |
| github | no | Enter the URL of Github. If you do not enter, the link is hidden. |
| showsRSS | no | Enter true to show the URL of RSS. If you enter false or nothing, the link is hidden. |
| profile | no | Enter the path to the profile image. If you do not enter, profile section will be hidden. |
| copyrightyear | no | Enter the copyright year. If you do not enter, copyright display is hidden. |
| copyright | no | Enter the copyright notice. If you do not enter, copyright display is hidden. |
| analytics | no | Enter the tracking ID of Google analytics. If you do not enter, the analysis will be skipped. |


## License

Open sourced under the [MIT license](https://github.com/mzgk/masamune/blob/master/LICENSE.md).


## Author

Takeshi Mizugaki


## Contact

Please contact me via [email](https://github.com/mzgk) / [Twitter](https://twitter.com/mzgkworks) :smile:
