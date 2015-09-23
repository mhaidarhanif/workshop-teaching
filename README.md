# Teaching @ Le Wagon

Here is a list of recipes you can apply during a workshop or a lecture.

## Setup

The closer your own setup is to the [standard student's one](https://github.com/lewagon/setup),
the better. That way you can share with them keyboard shortcuts. We use [Sublime Text 2](https://github.com/lewagon/setup).

When you are video-projecting your screen, please follow these guidelines:

- The only app running on your computer should be Finder, Sublime Text, Terminal and Browser
- Have your text editor and terminal with a **light background**. You can install the [Solarized](http://ethanschoonover.com/solarized) theme, with the [Sublime Text package](https://github.com/braver/Solarized) and the [OSX terminal theme](https://github.com/tomislav/osx-terminal.app-colors-solarized)
- Zoom a lot your font size (`⌘=`) in Sublime Text and your terminal.
- If you don't have a lot of files, hide the folder drawer on the left with `⌘K, ⌘B`.
- Switch from one file to the other with the `⌘P` (Command Palette)
- You should use two windows layouts:
  - Sublime Text in full screen
  - Vertical split (50/50) with Sublime Text on the right, Terminal on the left

![Split Layout](img/split_layout.png)

## Tools

### Gist

After a long session of live-coding, usually students ask for the code. They like to keep it on their computer, for future's reference. A quick way to share some code files is to use [Github's gist service](http://gist.github.com/). A quicker way than copy/pasting manually every file is to install the [gist](https://github.com/defunkt/gist) gem on your computer:

```bash
$ brew install gist  # On ubuntu, you can `gem install gist`
```

Then, in an exercise folder, you can run:

```bash
$ gist -p *.rb
```

This will automatically create a private gist with **all the ruby files** in the current folder. The program will give you the gist private URL that you can then share on Slack.







