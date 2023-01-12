# Class 19 Automation

## Reading

### Python Regular Expressions Tutorial
[Source Credit](https://www.datacamp.com/tutorial/python-regular-expression-tutorial)
- re module for regex `import re`
- `r`before makes a raw sting literal - will be stored as it appears
- search() returns the first location that matches
- wild card characters:
  - period . special wild card character to match any character except newline 
  - caret ^ matches the start of a string
  - dollar sign $ matches the end of a string
  - `[abc]` - Matches a or b or c.
  - `[a-zA-Z0-9]` - Matches any letter from (a to z) or (A to Z) or (0 to 9).
  - \w - Lowercase 'w'. Matches any single letter, digit, or underscore.
  - \W - Uppercase 'W'. Matches any character not part of \w (lowercase w).
  - \s - Lowercase 's'. Matches a single whitespace character like: space, newline, tab, return.
  - \S - Uppercase 'S'. Matches any character not part of \s (lowercase s).
  - \d - Lowercase d. Matches decimal digit 0-9.
  - \D - Uppercase d. Matches any character that is not a decimal digit.
  - \t - Lowercase t. Matches tab.
  - \n - Lowercase n. Matches newline.
  - \r - Lowercase r. Matches return.
- repetitions
  - {x} - Repeat exactly x number of times.
  - {x,} - Repeat at least x times or more.
  - {x, y} - Repeat at least x times but no more than y times.
  - ex. `re.search(r'\d{9,10}') would find digits 0-9 that repeat 9 or 10 times
- `(?P<name>...)` lets you create a names group (such as for a username)
- 

### shutil
[Source Credit](https://pymotw.com/3/shutil/)
- a module that includes high-level operations such as copying and archiving
- shutil.copyfile() creates an exact copy of the contents of a file into another file
-  shutil.copymode() copies the permissions from one file to another
- 

## Videos

### Automation Ideas
[Source Credit](https://www.youtube.com/watch?v=qbW6FRbaSl0&t=69s)
- 4 python automation ideas
    - automatically moving files
    - automatically move and rename files
    - open Youtube when my favorite YouTuber uploads a new video
    - calculate compounding interest

[optional: Automating Your Browser and Desktop Apps](https://www.youtube.com/watch?v=dZLyfbSQPXI)

## Bookmark and review

[Watchdog](https://pythonhosted.org/watchdog/)

## Things I want to know more about
- I didn't really understand what the shutil module would be used for? Why would we need to copy files and permissions from withing python? For writing scripts?