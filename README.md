# tumblr-lks-downldr-cli
[![npm version](https://badge.fury.io/js/tumblr-lks-downldr-cli.svg)](https://www.npmjs.com/package/tumblr-lks-downldr-cli)
[![downloads total](https://img.shields.io/npm/dt/tumblr-lks-downldr-cli.svg)](https://www.npmjs.com/package/tumblr-lks-downldr-cli)

CLI tool for downloading your precious [Tumblr](https://tumblr.com) likes.

You have probably liked posts with text, photos, quotes, links, chats, audio, videos or/and answers BUT this is just for IMAGES.

![tumblr-lks-downldr-cli](tumblr-lks-downldr-cli.jpg)

## How to use

Install [Node.js](https://nodejs.org) in order to run ```tumblr-lks-downldr-cli```.

Install the module **globally** and then you'll have access to the ```tumblr-lks-downldr-cli``` command anywhere on your system (use the same command to update it):
```sh
npm install -g tumblr-lks-downldr-cli
```

Then just run ```tumblr-lks-downldr-cli``` defining you Tumblr url and the number of likes that you want to download (if you don't set any number the default is the whole list of liked posts that can actually be really big):
```sh
tumblr-lks-downldr-cli -u 'andrscrrn.tumblr.com' -l 1000
```

And of course a custom path if you want:
```sh
tumblr-lks-downldr-cli -u 'andrscrrn.tumblr.com' -l 1000 -p 'my-stupid-folder'
```

If you want to save the image captions, add the -a flag:
```sh
tumblr-lks-downldr-cli -u 'andrscrrn.tumblr.com' -l 1000 -p 'my-stupid-folder' -a
```

## Issues

I'm definitely trying to maintain the utility updated so if anyone find an issue, don't hesitate to report it [here](https://github.com/andrscrrn/tumblr-lks-downldr-cli/issues).
