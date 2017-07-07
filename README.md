# YouTube Search "[Flat Earth](https://www.youtube.com/results?search_query=flat+earth)" - [KJV](https://github.com/AudioBible/KJV) [AudioBible](https://github.com/AudioBible/AudioBible)

## King James Version Audio Bible for Mac, Windows and Unix/Linux

###### What I know is that I don't know anything, so I keep looking for the truth/answers and realize how little I actually know, but the more I keep looking for the truth the more I know that I have a chance to be saved!

###### One thing if for sure, this has taught me how to put my ego to the side

#### [Biblical Flat Earth 24/7 LIVE! ✞ Discussing Creation From The Word of God - Christian Flat Earth](https://www.youtube.com/CelebrateTruth/live)

## [OLD BOOKS](BOOKS.md)

## [MORE INFO](INFO.md)

## [LINKS ONLINE](LINKS.md)

## [VIDEOS ON YOUTUBE](VIDEOS.md)

## [HELP WITH THE PROJECT](HELP.md)

# Install On Mac

    brew install python libxml2                                 # install dependencies
    pip install scrapy                                          # install this to be able to download the Books
    pip install fuzzywuzzy                                      # install this to have search algorithms                              
    pip install python-Levenshtein                              # install this to have search algorithms
    
    pip install audiobible                                      # install AudioBible with python pip


# Install On Ubuntu Linux

    sudo apt-get install python-pip libxml2 python-lxml         # install dependencies
    pip install scrapy                                          # install this to be able to download the Books
    pip install fuzzywuzzy                                      # install this to have search algorithms                              
    pip install python-Levenshtein                              # install this to have search algorithms
    
    sudo pip install audiobible                                 # install AudioBible with python pip


# How to use

    pip install --upgrade audiobible                            # update AudioBible to the latest version

    audiobible update                                           # update AudioBible using pip command internally
    
    audiobible -h | --help                                      # show help
    audiobible help                                             # show help
    
    audiobible version                                          # show version number and exit
    
    audiobible init                                             # download data about all books and chapters in the KJV
    audiobible init speaker                                     # download all the names of speakers from sermonaudio.com
    audiobible init topics                                      # download all the topics from sermonaudio.com
    audiobible init words                                       # download all the words from biblestudytools.com
    
    audiobible load                                             # download all books' and chapters' text and audio mp3 files
    
    audiobible list                                             # to list all books and the number of chapters each book has
    audiobible list speakers                                    # to list all speakers found on sermonaudio.com
    audiobible list speakers this                               # to list all speakers which have this in there name
    audiobible list topics                                      # to list all topics found on sermonaudio.com
    audiobible list words                                       # to list all words found on biblestudytools.com
    
    audiobible praise                                           # open a browser to a youtube playlist with hymns for praising God
    
    audiobible path daniel                                      # show the path on the hard drive to the book of "Daniel"
    
    audiobible quote                                            # to output a quote
    
    audiobible hear mark                                        # to hear the book of "Mark" chapter 1
    audiobible hear mark all                                    # to hear all chapters from the book of "Mark"
    audiobible hear -b mark                                     # to hear the book of "Mark" chapter 1
    audiobible hear mark 4                                      # to hear the book of "Mark" chapter 4
    audiobible hear -b mark -c 4                                # to hear the book of "Mark" chapter 4
    audiobible hear 1_john 3                                    # to hear the book of "1 John" chapter 3
    audiobible hear -b 1_john -c 3                              # to hear the book of "1 John" chapter 3
    audiobible hear -b mark -c all                              # same as hear mark all, there is a bug i can't fix where it starts to play from the last file,
                                                                #   just double click on the first one and it will start from the beginning playing the rest
    
    audiobible read mark 4                                      # to read Mark 4, (use params like with hear operation)
    
    audiobible show mark 4                                      # to show the book of "Mark" chapter 4 text in the terminal, specify params like with hear operation
    
    audiobible find                                             # to output the whole Bible
    audiobible find -b 2_john                                   # to output the whole book of "2 John"
    audiobible find -b james -c 5                               # to output chapter 5 for the book of "James"
    audiobible find water of life                               # to find water of life, say words to search for as params
    audiobible find water                                       # to find water, say the word to search the whole bible
    audiobible find 'it is done'                                # to find it is done, say the words to search as a string
    audiobible find circle of the earth -a partial              # to find query using fuzzy partial algorithm, also try: 'ratio', 'set', 'sort'; default is 'regex'
                                                                # algorithms are only for the find operation
    
    audiobible find jesus -b luke -c 3 -C 2                     # to find jesus in the book of "Luke" chapter 3, showing 2 verses before and after the matched verse context
    audiobible find circle -A 5 -B 2                            # to show 2 verse before and 5 verses after the matched verse context
    
    audiobible quote                                            # usage is same as with find operation
    
    audiobible sermons                                          # opens the default browser to http://sermonaudio.com
                                                                #  usage is same as with hear operation
    audiobible sermons -b mark -s "Charles Lawson"              # open browser to sermon "Charles Lawson" preaching the book of "Mark"
    
    # THE EARTH IS FLAT! [RESEARCH IT ON YOUTUBE](https://www.youtube.com/results?search_query=flat+earth&page=&utm_source=opensearch)!
    
    # THIS IS POSITIVE INFO! IT'S A MATTER OF PERSPECTIVE!
    
    # THE WAR ON TERROR IS A WAR ON YOU!
    
    ## God is so kind that it is impossible to imagine His unbounded kindness


**Note:** Tested and created on a Mac, should work on Windows and Unix/Linux and other OSes.

# KJV Bible - List of Books and Chapters Count

**Note:** This list can be shown by typing `audiobible list`

    Old Testament                 |   ###   | New Testament                 |   ##
    ------------------------------|---------|-------------------------------|--------
    (GE)    GENESIS               |   50    | (MAT)    MATTHEW              |   28
    (EX)    EXODUS                |   40    | (MAR)    MARK                 |   16
    (LE)    LEVITICUS             |   27    | (LU)     LUKE                 |   24
    (NU)    NUMBERS               |   36    | (JOH)    JOHN                 |   21
    (DE)    DEUTERONOMY           |   34    | (AC)     ACTS                 |   28
    (JOS)   JOSHUA                |   24    | (RO)     ROMANS               |   16
    (JUDG)  JUDGES                |   21    | (1_CO)   1_CORINTHIANS        |   16
    (RU)    RUTH                  |   4     | (2_CO)   2_CORINTHIANS        |   13
    (1_S)   1_SAMUEL              |   31    | (GA)     GALATIANS            |   6
    (2_S)   2_SAMUEL              |   24    | (EP)     EPHESIANS            |   6
    (1_K)   1_KINGS               |   22    | (PHILI)  PHILIPPIANS          |   4
    (2_K)   2_KINGS               |   25    | (CO)     COLOSSIANS           |   4
    (1_CH)  1_CHRONICLES          |   29    | (1_TH)   1_THESSALONIANS      |   5
    (2_CH)  2_CHRONICLES          |   36    | (2_TH)   2_THESSALONIANS      |   3
    (EZR)   EZRA                  |   10    | (1_TI)   1_TIMOTHY            |   6
    (NEH)   NEHEMIAH              |   13    | (2_TI)   2_TIMOTHY            |   4
    (EST)   ESTHER                |   10    | (TI)     TITUS                |   3
    (JOB)   JOB                   |   42    | (PHILE)  PHILEMON             |   1
    (PS)    PSALMS                |   150   | (HEB)    HEBREWS              |   13
    (PR)    PROVERBS              |   31    | (JA)     JAMES                |   5
    (EC)    ECCLESIASTES          |   12    | (1_P)    1_PETER              |   5
    (SO)    SONG_OF_SOLOMON       |   8     | (2_P)    2_PETER              |   3
    (IS)    ISAIAH                |   66    | (1_J)    1_JOHN               |   5
    (JE)    JEREMIAH              |   52    | (2_J)    2_JOHN               |   1
    (LA)    LAMENTATIONS          |   5     | (3_J)    3_JOHN               |   1
    (EZ)    EZEKIEL               |   48    | (JUDE)   JUDE                 |   1
    (DA)    DANIEL                |   12    | (REV)    REVELATION           |   22
    (HO)    HOSEA                 |   14    |
    (JOE)   JOEL                  |   3     |
    (AM)    AMOS                  |   9     |
    (OB)    OBADIAH               |   1     |
    (JON)   JONAH                 |   4     |
    (MI)    MICAH                 |   7     |
    (NA)    NAHUM                 |   3     |
    (HAB)   HABAKKUK              |   3     |
    (ZEP)   ZEPHANIAH             |   3     |
    (HAG)   HAGGAI                |   2     |
    (ZEC)   ZECHARIAH             |   14    |
    (MAL)   MALACHI               |   4     |


###### I pray God helps you to see, hear, read and understand and most importantly do something right about it! God bless you on your journey! Thank you for reading.

## THE EARTH IS FLAT, IN CASE YOU DIDN'T KNOW, NASA LIES!

**ISAIAH 40:22:** It is he that sitteth upon the circle of the earth, and the inhabitants thereof are as grasshoppers; that stretcheth out the heavens as a curtain, and spreadeth them out as a tent to dwell in:

**ISAIAH 40:23:** That bringeth the princes to nothing; he maketh the judges of the earth as vanity.

**ISAIAH 40:24:** Yea, they shall not be planted; yea, they shall not be sown: yea, their stock shall not take root in the earth: and he shall also blow upon them, and they shall wither, and the whirlwind shall take them away as stubble.


#### God is so kind that it is impossible to imagine His unbounded kindness

![flat-earth-isaiah40-22](images/flat-earth-isaiah40-22.jpg)

![the-firmament](images/the-firmament.jpeg)

![firmament](images/firmament.jpg)

![flat-earth-maps](images/flat-earth-maps.jpg)

![AncientFirmament](images/AncientFirmament.jpg)

![flat-earth-firmament-2c](images/flat-earth-firmament-2c.png)

![e83e3141866d8a5c082b646ed52bcf53](images/e83e3141866d8a5c082b646ed52bcf53.jpg)

![FlatEarthModel1](images/FlatEarthModel1.jpg)

![MJ_2014_Firmament_Realm_of_God](images/MJ_2014_Firmament_Realm_of_God.jpg)

![mqdefault](images/mqdefault.jpg)

![jtot_genesis_cosmology](images/jtot_genesis_cosmology.jpg)

![NASA_Serpent](images/NASA_Serpent.jpg)

![HkAHHM3c](images/HkAHHM3c.png)

![atheism](images/atheism.png)

![closed-minded-open-minded](images/closed-minded-open-minded.png)


#### Flat Earth Matters If Truth Matters, Up is Up and Down is Down, no matter where in the world you are!


    JN 14:6 Jesus saith unto him, I am the way, the truth, and the life: no man cometh unto the Father, but by me.


## Praised be Jesus Christ name! Praise Jesus for the Flat Earth Truth! Amen.

# LOVE YOU, BREAK FREE

**Note:** This project is not associated with AudioBible.com, please purchase a KJV Bible from [audiobible.com](http://audiobible.com/kjv-audio-bible-king-james/) if you like this.

- [King James Audio Bible Download for MP3 and iPod devices](http://www.audiobible.com/king-james-bible-download-for-mp3-and-ipod/)
- [Russian Audio Bible Download for MP3 or iPod devices](http://www.audiobible.com/download-russian-audio-bible-mp3-and-ipod/)
- [Mandarin Chinese Audio Bible Download for MP3, iPhone or iPod](http://www.audiobible.com/mandarin-chinese-audio-bible-download-mp3-ipod-devices/)
