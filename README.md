# AudioBible

King James Version Audio Bible for Mac, Windows and Unix/Linux

# [The Visual Bible - The Gospel Of Matthew](https://www.youtube.com/watch?v=woAhReBytBk) [MOVIE]

**Note:** Tested and created on a Mac, should work on Windows and Unix/Linux and other OSes.

**Note:** This project is not associated with AudioBible.com, please purchase a KJV Bible from [audiobible.com](http://audiobible.com/kjv-audio-bible-king-james/) if you like this.

- [King James Audio Bible Download for MP3 and iPod devices](http://www.audiobible.com/king-james-bible-download-for-mp3-and-ipod/)
- [Russian Audio Bible Download for MP3 or iPod devices](http://www.audiobible.com/download-russian-audio-bible-mp3-and-ipod/)
- [Mandarin Chinese Audio Bible Download for MP3, iPhone or iPod](http://www.audiobible.com/mandarin-chinese-audio-bible-download-mp3-ipod-devices/)

**ISAIAH 40:22:** It is he that sitteth upon the circle of the earth, and the inhabitants thereof are as grasshoppers; that stretcheth out the heavens as a curtain, and spreadeth them out as a tent to dwell in:

**ISAIAH 40:23:** That bringeth the princes to nothing; he maketh the judges of the earth as vanity.

**ISAIAH 40:24:** Yea, they shall not be planted; yea, they shall not be sown: yea, their stock shall not take root in the earth: and he shall also blow upon them, and they shall wither, and the whirlwind shall take them away as stubble.

# I pray God helps you to see, hear, read and understand and most importantly do something right about it! God bless you on your journey! Thank you for reading.

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
    audiobible hear psalms 71                                   # to hear a Prayer for God's Protection, praying is left up to the hearer
    
    audiobible read mark 4                                      # to read Mark 4, (use params like with hear operation), please disable your hearing protection
    audiobible read psalms 71                                   # to read a Prayer for God's Protection, praying is left up to the reader
    
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

# THIS IS POSITIVE INFO! IT'S A MATTER OF PERSPECTIVE!

# THE WAR ON TERROR IS A WAR ON YOU!

## RETARDS - Round Earth Taught Analed Retention Disorder Syndrome


- 1:  [Under The Dome - Full Documentary](https://www.youtube.com/watch?v=fk4YqPtvJao)
- 2:  [A History Of Flat Earth - Eric Dubay](https://www.youtube.com/watch?v=pGl8I3l-5ac)
- 3:  [A Flat Earth Awakening Story - Eric Dubay](https://www.youtube.com/watch?v=ER9Ul_ostZ8)
- 4:  [Flat Earth, Fake Aliens and Real Giants](https://www.youtube.com/watch?v=oqPLShx0Jfc)
- 5:  [Giant Human Beings Existed](https://www.youtube.com/watch?v=mRqjY5kyu34)
- 6:  [OUR FLAT DOMED CLOSED SYSTEM EXPLAINED - DMurphy25](https://www.youtube.com/watch?v=-RIBO7VB0VE)
- 7:  [Firmament Rising - The Globular Deception](https://www.youtube.com/watch?v=rez2CmyyfN4)
- 8:  [The Best Flat Earth Documentary](https://www.youtube.com/watch?v=GhRiLP32qfs)
- 9:  [IMPOSSIBALL Flat Earth Documentary (2017)](https://www.youtube.com/watch?v=UbYtkrTquXE)
- 10: [THE BEST Flat Earth VIDEO | 1000% Proof The Earth Is Flat | Lets See You Debunk This!!!!](https://www.youtube.com/watch?v=p7lDq4dOlIk)
- 11: [THE BEST Flat Earth VIDEO FOR All PEOPLE | 100% PROOF THE EARTH IS FLAT](https://www.youtube.com/watch?v=ynnFwTiQlxM)
- 12: [FLAT EARTH - 'Absolute Proof' | Rocket Hitting The Dome](https://www.youtube.com/watch?v=echpThvHli8)
- 13: [200 Proofs Earth is Not a Spinning Ball Videobook](https://www.youtube.com/watch?v=h5i_iDyUTCg)
- 14: [The Zionists, Freemasons, and NASA's Biggest Secret](https://www.youtube.com/watch?v=dTqmcvdm4hM)
- 15: [There are no forests on Flat Earth Wake Up](https://www.youtube.com/watch?v=UHkiZNT3cyE)
- 16: [There are no forests on earth! (ENGLISH VOICEOVER)](https://www.youtube.com/watch?v=ObJL6aA2czo)
- 17: [The World's Biggest Secret](https://www.youtube.com/watch?v=TFsuOFoolW8)
- 18: [Big Bang Evolution is a Masonic Lie Hiding Intelligent Design](https://www.youtube.com/watch?v=JkEL4yBJxm8)
- 19: [Under The Dome - Documentary (Edge of the firmament)](https://www.youtube.com/watch?v=4BxHP9T6480)
- 20: [The Flat Earth History and WHY it's hidden from us. By Eric Dubay. As Talked About with Eddie Bravo!](https://www.youtube.com/watch?v=9UbV3kTY8jw)
- 21: [NASA ISS HOAX! INTERNATIONAL SPACE STATION DOES NOT EXIST!](https://www.youtube.com/watch?v=TSQjerWbRfo)
- 22: [Flat Earth PROOF of God [6/9/2017]](https://www.youtube.com/watch?v=YI3BrH5t7oQ)
- 23: [Flat Earth Dome Explained 100% & the Entrance to Agartha](https://www.youtube.com/watch?v=fDBRhxryfZM)
- 24: [No One Has Been To Space~Watch This!](https://www.youtube.com/watch?v=WHMzgKB_uhY)
- 25: [Flat Earth Evidence and Proof June 2017](https://www.youtube.com/watch?v=-utWNUnrT9g)
- 26: [BEST FLAT EARTH PROOF 2017 - YOU CANT DENY THIS EVIDENCE](https://www.youtube.com/watch?v=awl8Eel7fgg)
- 27: [How to Quit Your Slave Job (and Live Your Dream Life!)](https://www.youtube.com/watch?v=HLwNG5l0Yoo)
- 28: [The Most Important Thing in Your Life](https://www.youtube.com/watch?v=sKH-NmLFDH4)
- 29: [Satan's Computer; What you Where Not Taught In School, This Will Blow Your Mind - Flat Earth Stream](https://www.youtube.com/watch?v=jwK6aUfTrvQ)
- 30: [ANONYMOUS. URGENT MESSAGE: SOCIAL MEDIA AND THE MARK OF THE BEAST. NWO AGENDA ARRIVES](https://www.youtube.com/watch?v=X6plO9aABeQ)
- 31: [The MARK of The BEAST Identified](https://www.youtube.com/watch?v=13RzjyhKz3M)
- 32: [Trump Declares "One World Currency" Sooner than most think (bloomberg)](https://www.youtube.com/watch?v=PuH_wCwxBhw)
- 33: [Devils tower and Pagan rituals](https://www.youtube.com/watch?v=y2dBpiS_Aik)
- 34: [Donald Trump's Saudi Arabia Visit "Orb Ritual" - Melania & Ivanka Are Men!](https://www.youtube.com/watch?v=ktFzCnMn6_Y)
- 35: [Trump will usher in the 7 Noahide Laws ONE WORLD RELIGION](https://www.youtube.com/watch?v=sPEQO-3UqkM)
- 36: [ARCODEAUS - The Noahide Laws - May 20, 2017](https://www.youtube.com/watch?v=oETRa_ExfXA)
- 37: [CHRISTIANS MUST WATCH we are being LIED TO ISRAELITES](https://www.youtube.com/watch?v=xNTdajfE14Y)
- 38: [The TRUE Hebrew Israelites defined by Scripture and history. WARNING you will be shocked!!!](https://www.youtube.com/watch?v=bEDfrBBPZzg)
- 39: [A History of the True Hebrews (Documentary)](https://www.youtube.com/watch?v=biPDp8pGqGg)
- 40: [WHO ARE THE REAL BIBLICAL ISRAELITES?](https://www.youtube.com/watch?v=HuUAnpIPK5E)
- 41: [EUROPEAN CONFESSIONS-AFRICAN AMERICANS ARE THE TRUE ISRAELITES AND THE CHOSEN PEOPLE OF GOD](https://www.youtube.com/watch?v=ja93FjyCSfo)
- 42: [Demonic Sigils and Eyes in the Skies](https://www.youtube.com/watch?v=N-kdx5IhIoc)
- 43: [TELEVISION Will Kill you. PATENT to PROVE it..](https://www.youtube.com/watch?v=15GtRc7ViBk)
- 44: [You Won't Believe What They Admitted on the News in 1971...](https://www.youtube.com/watch?v=yfaAtdTgBGk)
- 45: [Mass Hypnosis and Trigger Words](https://www.youtube.com/watch?v=fznpRaM1wIg)
- 46: [Society Is Being Programmed By A Black Box](https://www.youtube.com/watch?v=rQmIPK7DQh8)
- 47: [The Privacyless, Freedomless Smart City of 2030 the Elite Are Engineering](https://www.youtube.com/watch?v=GRybM76qx6I)
- 48: [Obsolete — Full Documentary Official (2016)](https://www.youtube.com/watch?v=jPmUGq25KBk)
- 49: [Rosa Koire : Smart Cities are Future Agenda 21 Hi-Tech Monitored Concentration](https://www.youtube.com/watch?v=p3XuSo03N7s)
- 50: [Why Are We Literally Eating Demon-Shaped Dead Food in This Society?](https://www.youtube.com/watch?v=EeK_iampjjg)
- 51: [We Are Being Groomed for the Next Big War](https://www.youtube.com/watch?v=poQPBppFyWM)
- 52: [Elon Musk: 'We Must Hack Our Brains or Be Destroyed by AI'](https://www.youtube.com/watch?v=MOs-ib5STPE)
- 53: [NASA's Future of War 2025 Is Already Here! (HD)](https://www.youtube.com/watch?v=aDpGB9J27_g)
- 54: [What Bilderberg Really Wants In 2017](https://www.youtube.com/watch?v=EbFMnrPbAmU)
- 55: [AGENDA 21 THE MOVIE: THE MEGACITIES ARE COMING.](https://www.youtube.com/watch?v=mZhI9vvZ2Wo)
- 56: [This Creepy Patent Proves They Can Remotely Hijack Your Nervous System](https://www.youtube.com/watch?v=yf_EdKxfDiY)
- 57: [Trump's New World Order](https://www.youtube.com/watch?v=eLS5h1ZDKvE)
- 58: [Agenda 21 Smart Cities: Orwell's Dystopic Nightmare Comes True](https://www.youtube.com/watch?v=T9DK0JThOio)
- 59: [Bill Gates Just Warned a New Bioweapon Will Wipe Out 30 Million](https://www.youtube.com/watch?v=sErgwyD2KR0)
- 60: [WOLVES IN SHEEP'S CLOTHING: How the public was duped into socialism, but got totalitarianism](https://www.youtube.com/watch?v=cYgyDjl2nCU)
- 61: [Psywar - Full Documentary](https://www.youtube.com/watch?v=2eB046f998U)
- 62: [We Are Becoming the Internet, the Internet Is Becoming Us](https://www.youtube.com/watch?v=GnLyjsO7mZc)
- 63: [The Real Secrets Hidden in Antarctica... Revealed](https://www.youtube.com/watch?v=237F1_aLXZ8)
- 64: [6 Secret Cities That Prove We Don't Know What's Really Going On](https://www.youtube.com/watch?v=wYyBcOLq8bs)
- 65: [Two Top Secret Missions Disguised As Historic Moments You Thought Were Real](https://www.youtube.com/watch?v=1ZiQUngMhr4)
- 66: [AGENDA 21 THE MOVIE: THE MEGACITIES ARE COMING.](https://www.youtube.com/watch?v=mZhI9vvZ2Wo)
- 67: [POWERUL TESTIMONY!! THIS MAN SAW HITLER AND OTHER EVIL PEOPLE IN HELL DURING A NEAR DEATH EXPERIENCE](https://www.youtube.com/watch?v=xt9xodhZ5KI)
- 68: [Aaliyah, Lefteye,Biggie,Eazy E,Whitney Houston, Amy Winehouse Are All N Hell](https://www.youtube.com/watch?v=wwUffrMRDqE)
- 69: [CELEBRITIES SEEN IN HELL (TUPAC, ROBIN WILLIAMS, ELVIS, HEATH LEDGER, AND MORE)](https://www.youtube.com/watch?v=_gNw4SGGwDU)
- 70: [INDIA IMPLEMENTING THE BEAST SYSTEM. CAN'T BUY OR SELL UNLESS YOU TAKE A 12 DIGIT NUMBER](https://www.youtube.com/watch?v=ppEDMsnMfJw)


## God is so kind that it is impossible to imagine His unbounded kindness

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

![SunAnimation](SunAnimation.gif)

# BE KIND TO EACH OTHER

![56f6b029eb00d9b24cc7470fd0a68468](56f6b029eb00d9b24cc7470fd0a68468.jpg)

![Globe](globe_1.jpg)

# AUDIOBIBLE HEAR PSALMS 71

## WARNING! DEMONIC SIGILS OF SUMMONING! FOR EDUCATIONAL PURPOSES!

![Demons](demons.png)

## OPEN YOUR MIND! BREAK FREE FROM THE LIES AND SATANIC PROGRAMMING!

![youtube-search-flat-earth-letter](youtube-search-flat-earth-letter.jpg)

