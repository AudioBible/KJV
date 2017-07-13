## Welcome to [http://audiobible.life](http://audiobible.life) - [KJV](https://github.com/AudioBible/KJV) - [AudioBible](https://github.com/AudioBible/AudioBible)

[![thomas-jefferson-educate-and-inform-the-masses-quote](images/thomas-jefferson-educate-and-inform-the-masses-quote.png)](https://www.youtube.com/watch?v=72Lrz0khXP0)

0.0.1
=====

- Initial version


0.0.2
=====

- Added find functionality
    
0.0.3
=====

- Added find to help, as it was missing from 0.0.2 
- Added upload.sh script to upload to pypi the package easier

0.0.4
=====

- Nothing changed just trying to please pypi with a version bump

0.0.5
=====

- Updated README
- Added params for book, chapter(-b, -c)
- Updated find operation functionality

0.0.6
=====

- Fixed list functionality to show all the books from old testament

0.0.7
=====

- Fixed spider/crawler

0.0.8
=====

- Update README
- Clean up output

0.0.9
=====

- Update README
- Added VERSION and version operation to show version 

0.0.10
======

- Fixed version operation

0.0.11
======

- Added version operation to help and updated the README
- IT IS DONE

0.0.12
======

- Extended help

0.0.13
======

- Made operation to be acceptable as single letter f r h

0.0.14
======

- Fix the feature added in 0.0.13, duh I'm not perfect, Jesus is though!

0.0.15
======

- Added path operation to result with a path the the book

0.0.16
======

- Print filename on read and hear

0.0.17
======

- Removed single letter operations
- Added show operation
- Added praise operation
- Added update operation
- Removed default book of GENESIS, must pass book param now when a book is required, a list will be shown if one is

0.0.18
======

- Removed ASCII header

0.0.19
======

- Updated README.md
- Make Python3 ready

0.1.0
=====

- bumped version number, same thing as 0.0.19

0.1.1
=====

- Updated CHANGES

0.1.2
=====

- Finish quote functionality to result in random quote with options like with find operation

0.1.3
=====

- change praise operation url to a search result for "praise worship hymns" instead of a single video playlist
- fixed some bugs with quote operation
- fixed a bug in spider pipelines with urllib2 not being defined, last working is 0.0.18 before i broke it in 0.0.19

0.1.4
=====

- fixed something i broke in 0.1.3 to do with operation, I'm glad I'm not the one that has to be creator of everything

0.1.5
=====

- update setup.py to use find_packages instead like it was before

0.1.6
=====

- do what i was trying to do in 0.1.5, because i fogot to commit the file changes duh

0.2.0
=====

- added chapter all, to open all chapter in a book to hear or show  or read the text

0.2.1
=====

- Updated readme

0.3.0
=====

- Added heal operation which opens a browser to 528Hz tones on youtube

0.3.1
=====

- version bump, same as 0.3.0

0.4.0
=====

- added algorithms to be able to fuzzy match search text with levenshtein
- fix show operation lines output to be separated

0.4.1
=====

- change url for heal operation to point to a solfeggio tones generator

0.4.2
=====

- change print to sys.stdout.write
- handle keyboard interrupt and system exit exceptions
- make it so dont have to type the whole book name to select a book

0.4.3
=====

- fix bug in 2_ki as param should return 2_kings

0.5.0
=====

- remove heal operation, its the frequency of saturn/satan, i was deceived into adding that operation, now its gone
- added sermons operation

0.5.1
=====

- update readme

0.7.0
=====

- added speakers and topics and sermons

0.7.1
=====

- finish list topics

0.7.2
=====

- fix sermons operation 

0.7.3
=====

- added words and dict operations
- fixed find operation it wasn't finding all verses, _files function replace 1_, 2_, 3_

0.7.4
=====

- fixed dict operation

0.7.5
=====

- fix valid_book function and added chapters count to output
- refactor dictionary spider
- fix find operation to take book and chapter:verse

0.7.6
=====

- fix book_name refactor added in 0.7.5

0.7.7
=====

- fix dictionary spider
- added exit operation
- enabled httpcache in spider settings to cache data for one week, 604800 seconds
- added force param to init operation to remove existing data before crawling
- added init git operation to clone all data from git repo instead of using spiders to download it
- change CONCURRENT_REQUESTS to 32, default 16
- words operation display words
- fixed "list words" operations, display strong's number and translated word
- remove load operation since "init bible" operation, or "init" twice does the same thing
- fix list topics operation filter topics

0.7.8
=====

- added hub operation to open browser to biblehub.com interlinear tool

![stats](https://c.statcounter.com/11394989/0/e56d199b/0/)
