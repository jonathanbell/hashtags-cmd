# Hashtags cmd

Uses text files organized by category (filename) to randomize and display useful hashtags on the command line. The 30 or less hashtags can then be copied and pasted into Instagram.

## Usage

```bash
php hashtags hockey soccer etc
```

Each parameter should be a requested category. Store your hashtags (one per line) inside text files inside the `data` directory. The filename of each file is a category. So, store related hashtags in each of their own files.

## Installation

1. `git clone this repo`
1. `cd hashtags-cmd`
1. `composer install`
1. Run an example: `php hashtags test` Neato!
1. Place all of your text (`.txt`) hashtag files inside the `data` directory.
