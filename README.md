# Hashtags cmd

Uses text files organized by category (filename) to randomize and display useful hashtags and Instagram influencer accounts on the command line. The 30 or less hashtags along with the influencer accounts can then be copied and pasted into Instagram as a single string.

## Usage

```bash
php hashtags hockey soccer etc
```

Each parameter should be a requested category (in the case of the example, the categories are: `hockey`, `soccer`, and `etc`). Store your hashtags (one per line) inside text files inside the `data/hashtags` directory. The filename of each file is a category. So, store related hashtags in each of their own files. Store influencer account names in separate files inside `data/users` (each file being its own category).

## Installation

1. `git clone this repo`
1. `cd hashtags-cmd`
1. `composer install`
1. Run an example: `php hashtags test` Neato!
1. Place all of your text (`.txt`) hashtag files inside the `data` directory.
