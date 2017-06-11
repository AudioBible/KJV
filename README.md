King James Version Audio Bible
==============================

King James Version Audio Bible for Mac, Windows and Unix/Linux

**Note:** Tested and created on a Mac, should work on Windows and Unix/Linux and other OSes.

**Note:** This project is not associated with AudioBible.com, please purchase a KJV Bible from [audiobible.com](http://audiobible.com/kjv-audio-bible-king-james/) if you like this.

- [King James Audio Bible Download for MP3 and iPod devices](http://www.audiobible.com/king-james-bible-download-for-mp3-and-ipod/)
- [Russian Audio Bible Download for MP3 or iPod devices](http://www.audiobible.com/download-russian-audio-bible-mp3-and-ipod/)
- [Mandarin Chinese Audio Bible Download for MP3, iPhone or iPod](http://www.audiobible.com/mandarin-chinese-audio-bible-download-mp3-ipod-devices/)

## Install On Mac

    brew install python libxml2                                 # install dependencies
    pip install scrapy audiobible                               # install AudioBible with python pip


## Install On Ubuntu Linux

    sudo apt-get install python-pip libxml2 python-lxml         # install dependencies
    sudo pip install scrapy audiobible                          # install AudioBible with python pip


## How to use

    pip install --upgrade audiobible                            # update AudioBible to the latest version
    
    audiobible -h | --help                                      # show help
    audiobible help                                             # show help
    
    audiobible version                                          # show version number and exit
    
    audiobible init                                             # download data about all books and chapters in the KJV
    audiobible load                                             # download all books' and chapters' text and audio mp3 files
    
    audiobible list                                             # to list all books and the number of chapters each book has
    
    audiobible hear                                             # to hear the book of "Genesis" chapter 1
    audiobible hear mark                                        # to hear the book of "Mark" chapter 1
    audiobible hear -b mark                                     # to hear the book of "Mark" chapter 1
    audiobible hear mark 4                                      # to hear the book of "Mark" chapter 4
    audiobible hear -b mark -c 4                                # to hear the book of "Mark" chapter 4
    audiobible hear 1_john 3                                    # to hear the book of "1 John" chapter 3
    audiobible hear -b 1_john -c 3                              # to hear the book of "1 John" chapter 3
    
    audiobible read mark 4                                      # to read Mark 4, (use params like with hear operation)
    
    audiobible find                                             # to output the whole Bible
    audiobible find -b 2_john                                   # to output the whole book of "2 John"
    audiobible find -b james -c 5                               # to output chapter 5 for the book of "James"
    audiobible find water of life                               # to find water of life, say words to search for as params
    audiobible find water                                       # to find water, say the word to search the whole bible
    audiobible find 'it is done'                                # to find it is done, say the words to search as a string
    audiobible find circle of the earth                         # to find circle of the earth
    
    audiobible find jesus -b luke -c 3 -C 2                     # to find jesus in the book of "Luke" chapter 3, showing 2 verses before and after the matched verse context
    audiobible find circle -A 5 -B 2                            # to show 2 verse before and 5 verses after the matched verse context


# KJV Bible - List of Books and Chapters Count

**Note:** This list can be shown by typing `audiobible list`

    Old Testament                 |   ###   | New Testament                 |   ##
    ------------------------------|---------|-------------------------------|--------
    
    GENESIS                       |   50    | MATTHEW                       |   28
    EXODUS                        |   40    | MARK                          |   16
    LEVITICUS                     |   27    | LUKE                          |   24
    NUMBERS                       |   36    | JOHN                          |   21
    DEUTERONOMY                   |   34    | ACTS                          |   28
    JOSHUA                        |   24    | ROMANS                        |   16
    JUDGES                        |   21    | 1_CORINTHIANS                 |   16
    RUTH                          |   4     | 2_CORINTHIANS                 |   13
    1_SAMUEL                      |   31    | GALATIANS                     |   6
    2_SAMUEL                      |   24    | EPHESIANS                     |   6
    1_KINGS                       |   22    | PHILIPPIANS                   |   4
    2_KINGS                       |   25    | COLOSSIANS                    |   4
    1_CHRONICLES                  |   29    | 1_THESSALONIANS               |   5
    2_CHRONICLES                  |   36    | 2_THESSALONIANS               |   3
    EZRA                          |   10    | 1_TIMOTHY                     |   6
    NEHEMIAH                      |   13    | 2_TIMOTHY                     |   4
    ESTHER                        |   10    | TITUS                         |   3
    JOB                           |   42    | PHILEMON                      |   1
    PSALMS                        |   150   | HEBREWS                       |   13
    PROVERBS                      |   31    | JAMES                         |   5
    ECCLESIASTES                  |   12    | 1_PETER                       |   5
    SONG_OF_SOLOMON               |   8     | 2_PETER                       |   3
    ISAIAH                        |   66    | 1_JOHN                        |   5
    JEREMIAH                      |   52    | 2_JOHN                        |   1
    LAMENTATIONS                  |   5     | 3_JOHN                        |   1
    EZEKIEL                       |   48    | JUDE                          |   1
    DANIEL                        |   12    | REVELATION                    |   22
    HOSEA                         |   14    |
    JOEL                          |   3     |
    AMOS                          |   9     |
    OBADIAH                       |   1     |
    JONAH                         |   4     |
    MICAH                         |   7     |
    NAHUM                         |   3     |
    HABAKKUK                      |   3     |
    ZEPHANIAH                     |   3     |
    HAGGAI                        |   2     |
    ZECHARIAH                     |   14    |
    MALACHI                       |   4     |

# THERE IS NO GRAVITY! WAKE UP NEO!

![ImpulsiveNeo](ImpulsiveNeo.jpg)

# THE EARTH IS FLAT! [RESEARCH IT ON YOUTUBE](https://www.youtube.com/results?search_query=flat+earth&page=&utm_source=opensearch)!


- [Under The Dome - Full Documentary](https://www.youtube.com/watch?v=fk4YqPtvJao)
- [A History Of Flat Earth - Eric Dubay](https://www.youtube.com/watch?v=pGl8I3l-5ac)
- [A Flat Earth Awakening Story - Eric Dubay](https://www.youtube.com/watch?v=ER9Ul_ostZ8)
- [OUR FLAT DOMED CLOSED SYSTEM EXPLAINED - DMurphy25](https://www.youtube.com/watch?v=-RIBO7VB0VE)
- [Firmament Rising - The Globular Deception](https://www.youtube.com/watch?v=rez2CmyyfN4)
- [The Best Flat Earth Documentary](https://www.youtube.com/watch?v=GhRiLP32qfs)
- [IMPOSSIBALL Flat Earth Documentary (2017)](https://www.youtube.com/watch?v=UbYtkrTquXE)
- [THE BEST Flat Earth VIDEO | 1000% Proof The Earth Is Flat | Lets See You Debunk This!!!!](https://www.youtube.com/watch?v=p7lDq4dOlIk)


![flat-earth-isaiah40-22](flat-earth-isaiah40-22.jpg)

# WHAT DOES THE REAL WORLD LOOK LIKE?

![Flat Earth; Exposing the Jesuit Agenda! 4](Flat-Earth-Exposing-the-Jesuit-Agenda-4.png)

# PRAISE GOD FOR THE FLAT EARTH TRUTH! JESUS LIVES!

![Gleasons-New-Standard-Map](Gleasons-New-Standard-Map.jpg)

o       o   O  o  o o--o     o   o o--o      o   o o--o  o-o  
|       |  / \ | /  |        |   | |   |     |\  | |    o   o 
o   o   o o---oOO   O-o      |   | O--o      | \ | O-o  |   | 
 \ / \ /  |   || \  |        |   | |         |  \| |    o   o 
  o   o   o   oo  o o--o      o-o  o         o   o o--o  o-o  

![flat-earth-model](flat-earth-model.gif)

# BE KIND TO EACH OTHER

![56f6b029eb00d9b24cc7470fd0a68468](56f6b029eb00d9b24cc7470fd0a68468.jpg)

