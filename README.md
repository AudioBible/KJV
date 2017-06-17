# AudioBible

## King James Version Audio Bible for Mac, Windows and Unix/Linux

- [Are You Serious? Flat Earth?](https://www.youtube.com/watch?v=VkGm0rcxCBU)
- [Illumination of the Third Eye - Pastor Charles Lawson](https://www.youtube.com/watch?v=8B-KT94bWHg)
- [The Fruits Of The Holy Spirit](https://www.youtube.com/watch?v=AFNAriKobp8)
- [Beware the Emerging Church Movement (Pastor Charles Lawson)](https://www.youtube.com/watch?v=3QJ226sGfNI)
- [Great Deception Is Settling In (Pastor Charles Lawson)](https://www.youtube.com/watch?v=WZMf5l9SG9I)
- [What Must I Do To Be Saved? (Pastor Charles Lawson)](https://www.youtube.com/watch?v=EDOeS0fNIJc)
- [http://pastorcharleslawson.org/](http://pastorcharleslawson.org/)

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
    
    audiobible load                                             # download all books' and chapters' text and audio mp3 files
    
    audiobible list                                             # to list all books and the number of chapters each book has
    
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


**Note:** Tested and created on a Mac, should work on Windows and Unix/Linux and other OSes.

**Note:** This project is not associated with AudioBible.com, please purchase a KJV Bible from [audiobible.com](http://audiobible.com/kjv-audio-bible-king-james/) if you like this.

- [King James Audio Bible Download for MP3 and iPod devices](http://www.audiobible.com/king-james-bible-download-for-mp3-and-ipod/)
- [Russian Audio Bible Download for MP3 or iPod devices](http://www.audiobible.com/download-russian-audio-bible-mp3-and-ipod/)
- [Mandarin Chinese Audio Bible Download for MP3, iPhone or iPod](http://www.audiobible.com/mandarin-chinese-audio-bible-download-mp3-ipod-devices/)


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


## I pray God helps you to see, hear, read and understand and most importantly do something right about it! God bless you on your journey! Thank you for reading.


### [The Visual Bible - The Gospel Of Matthew](https://www.youtube.com/watch?v=woAhReBytBk) [MOVIE]
### [The Gospel of Luke](https://www.youtube.com/watch?v=auL-ebjH-xo) [MOVIE]
### [The Gospel of Luke - Film - Visual Bible in HD Very Rare Version](https://www.youtube.com/watch?v=2PHPLApTt7Y) [MOVIE]
### [The Acts of the Apostles - Film - High Quality! HD](https://www.youtube.com/watch?v=tRXNp6K5-JI) [MOVIE]
### [Paul the Apostle Full Movie](https://www.youtube.com/watch?v=t5FhLQhDsk0) [MOVIE]
### [The Book Of Revelation (Full Movie)](https://www.youtube.com/watch?v=NAb2hdQneBY) [MOVIE]
### [The Ruth Story](https://www.youtube.com/watch?v=slEmSyJi81g) [MOVIE]
### [Esther and the King](https://www.youtube.com/watch?v=SQ6qYypfmIo) [MOVIE]
### [Samson and Delilah - full movie - full movie](https://www.youtube.com/watch?v=a9968bcrywY) [MOVIE]
### [David and Goliath...Orson Welles as King Saul](https://www.youtube.com/watch?v=GpVf6JII-VM) [MOVIE]
### [Sodom & Gomorrah FULL VIDEO](https://www.youtube.com/watch?v=WWpknxvxLpk) [MOVIE]
### [The Story of Joseph and His Brethren (1962)](https://www.youtube.com/watch?v=u2dM_kW-SOI) [MOVIE]
### [Abraham, Sarah, Isaac, Jacob ( Full Movie )](https://www.youtube.com/watch?v=V5WNbtj3gZs) [MOVIE]
### [The Ten Commandments.Full Movie HD.](https://www.youtube.com/watch?v=4s320VeVUQA) [MOVIE]
### [Jesus Of Nazareth (Original Bible Movie) 1977](https://www.youtube.com/watch?v=pG6Y88iQhCE) [MOVIE]
### [Jesus is Coming Full Movie](https://www.youtube.com/watch?v=Gi0eW2BEOXM) [MOVIE]


**Note:** These are old movies, you can trust these more than the new ones having new actors and brainwashing tactics.


### [Paganism Surviving In Christianity](https://www.forgottenbooks.com/en/readbook/PaganismSurvivinginChristianity_10066362) [BOOK]
### [How We Got Our Bible](https://www.forgottenbooks.com/en/readbook/HowWeGotOurBible_10038867) [BOOK]
### [The Negro In Our History](https://www.forgottenbooks.com/en/readbook/TheNegroinOurHistory_10101622) [BOOK]


## THE EARTH IS FLAT, IN CASE YOU DIDN'T KNOW, NASA LIES!

**ISAIAH 40:22:** It is he that sitteth upon the circle of the earth, and the inhabitants thereof are as grasshoppers; that stretcheth out the heavens as a curtain, and spreadeth them out as a tent to dwell in:

**ISAIAH 40:23:** That bringeth the princes to nothing; he maketh the judges of the earth as vanity.

**ISAIAH 40:24:** Yea, they shall not be planted; yea, they shall not be sown: yea, their stock shall not take root in the earth: and he shall also blow upon them, and they shall wither, and the whirlwind shall take them away as stubble.


# THERE IS NO GRAVITY! WAKE UP NEO!

![ImpulsiveNeo](ImpulsiveNeo.jpg)

# THE EARTH IS FLAT! [RESEARCH IT ON YOUTUBE](https://www.youtube.com/results?search_query=flat+earth&page=&utm_source=opensearch)!

# THIS IS POSITIVE INFO! IT'S A MATTER OF PERSPECTIVE!

# THE WAR ON TERROR IS A WAR ON YOU!

## RETARDS - Round Earth Taught Analed Retention Disorder Syndrome

## [StopLookThink.com](http://stoplookthink.com)

- 0: [The Greatest Truth Never Told](https://www.youtube.com/watch?v=ekkXHnSrlwY&list=PLD31E34390C5017E8)

- 1: [Admiral Richard E. Byrd - South Pole Video Interview](https://www.youtube.com/watch?v=czW0iRJuH1A)
- 2: [Under The Dome - Full Documentary](https://www.youtube.com/watch?v=fk4YqPtvJao)
- 3: [A History Of Flat Earth - Eric Dubay](https://www.youtube.com/watch?v=pGl8I3l-5ac)
- 4: [A Flat Earth Awakening Story - Eric Dubay](https://www.youtube.com/watch?v=ER9Ul_ostZ8)
- 5: [Flat Earth, Fake Aliens and Real Giants](https://www.youtube.com/watch?v=oqPLShx0Jfc)
- 6: [Giant Human Beings Existed](https://www.youtube.com/watch?v=mRqjY5kyu34)
- 7: [OUR FLAT DOMED CLOSED SYSTEM EXPLAINED - DMurphy25](https://www.youtube.com/watch?v=-RIBO7VB0VE)
- 8: [Firmament Rising - The Globular Deception](https://www.youtube.com/watch?v=rez2CmyyfN4)
- 9: [The Best Flat Earth Documentary](https://www.youtube.com/watch?v=GhRiLP32qfs)
- 10: [IMPOSSIBALL Flat Earth Documentary (2017)](https://www.youtube.com/watch?v=UbYtkrTquXE)
- 11: [THE BEST Flat Earth VIDEO | 1000% Proof The Earth Is Flat | Lets See You Debunk This!!!!](https://www.youtube.com/watch?v=p7lDq4dOlIk)
- 12: [THE BEST Flat Earth VIDEO FOR All PEOPLE | 100% PROOF THE EARTH IS FLAT](https://www.youtube.com/watch?v=ynnFwTiQlxM)
- 13: [FLAT EARTH - 'Absolute Proof' | Rocket Hitting The Dome](https://www.youtube.com/watch?v=echpThvHli8)
- 14: [200 Proofs Earth is Not a Spinning Ball Videobook](https://www.youtube.com/watch?v=h5i_iDyUTCg)
- 15: [The Zionists, Freemasons, and NASA's Biggest Secret](https://www.youtube.com/watch?v=dTqmcvdm4hM)
- 16: [There are no forests on Flat Earth Wake Up](https://www.youtube.com/watch?v=UHkiZNT3cyE)
- 17: [There are no forests on earth! (ENGLISH VOICEOVER)](https://www.youtube.com/watch?v=ObJL6aA2czo)
- 18: [The World's Biggest Secret](https://www.youtube.com/watch?v=TFsuOFoolW8)
- 19: [Big Bang Evolution is a Masonic Lie Hiding Intelligent Design](https://www.youtube.com/watch?v=JkEL4yBJxm8)
- 20: [Under The Dome - Documentary (Edge of the firmament)](https://www.youtube.com/watch?v=4BxHP9T6480)
- 21: [The Flat Earth History and WHY it's hidden from us. By Eric Dubay. As Talked About with Eddie Bravo!](https://www.youtube.com/watch?v=9UbV3kTY8jw)
- 22: [NASA ISS HOAX! INTERNATIONAL SPACE STATION DOES NOT EXIST!](https://www.youtube.com/watch?v=TSQjerWbRfo)
- 23: [Flat Earth PROOF of God [6/9/2017]](https://www.youtube.com/watch?v=YI3BrH5t7oQ)
- 24: [Flat Earth Dome Explained 100% & the Entrance to Agartha](https://www.youtube.com/watch?v=fDBRhxryfZM)
- 25: [No One Has Been To Space~Watch This!](https://www.youtube.com/watch?v=WHMzgKB_uhY)
- 26: [Flat Earth Evidence and Proof June 2017](https://www.youtube.com/watch?v=-utWNUnrT9g)
- 27: [BEST FLAT EARTH PROOF 2017 - YOU CANT DENY THIS EVIDENCE](https://www.youtube.com/watch?v=awl8Eel7fgg)
- 28: [How to Quit Your Slave Job (and Live Your Dream Life!)](https://www.youtube.com/watch?v=HLwNG5l0Yoo)
- 29: [The Most Important Thing in Your Life](https://www.youtube.com/watch?v=sKH-NmLFDH4)
- 30: [Satan's Computer; What you Where Not Taught In School, This Will Blow Your Mind - Flat Earth Stream](https://www.youtube.com/watch?v=jwK6aUfTrvQ)
- 31: [ANONYMOUS. URGENT MESSAGE: SOCIAL MEDIA AND THE MARK OF THE BEAST. NWO AGENDA ARRIVES](https://www.youtube.com/watch?v=X6plO9aABeQ)
- 32: [The MARK of The BEAST Identified](https://www.youtube.com/watch?v=13RzjyhKz3M)
- 33: [Trump Declares "One World Currency" Sooner than most think (bloomberg)](https://www.youtube.com/watch?v=PuH_wCwxBhw)
- 34: [Devils tower and Pagan rituals](https://www.youtube.com/watch?v=y2dBpiS_Aik)
- 35: [Donald Trump's Saudi Arabia Visit "Orb Ritual" - Melania & Ivanka Are Men!](https://www.youtube.com/watch?v=ktFzCnMn6_Y)
- 36: [Trump will usher in the 7 Noahide Laws ONE WORLD RELIGION](https://www.youtube.com/watch?v=sPEQO-3UqkM)
- 37: [ARCODEAUS - The Noahide Laws - May 20, 2017](https://www.youtube.com/watch?v=oETRa_ExfXA)
- 38: [CHRISTIANS MUST WATCH we are being LIED TO ISRAELITES](https://www.youtube.com/watch?v=xNTdajfE14Y)
- 39: [The TRUE Hebrew Israelites defined by Scripture and history. WARNING you will be shocked!!!](https://www.youtube.com/watch?v=bEDfrBBPZzg)
- 40: [A History of the True Hebrews (Documentary)](https://www.youtube.com/watch?v=biPDp8pGqGg)
- 41: [WHO ARE THE REAL BIBLICAL ISRAELITES?](https://www.youtube.com/watch?v=HuUAnpIPK5E)
- 42: [EUROPEAN CONFESSIONS-AFRICAN AMERICANS ARE THE TRUE ISRAELITES AND THE CHOSEN PEOPLE OF GOD](https://www.youtube.com/watch?v=ja93FjyCSfo)
- 43: [Demonic Sigils and Eyes in the Skies](https://www.youtube.com/watch?v=N-kdx5IhIoc)
- 44: [TELEVISION Will Kill you. PATENT to PROVE it..](https://www.youtube.com/watch?v=15GtRc7ViBk)
- 45: [You Won't Believe What They Admitted on the News in 1971...](https://www.youtube.com/watch?v=yfaAtdTgBGk)
- 46: [Mass Hypnosis and Trigger Words](https://www.youtube.com/watch?v=fznpRaM1wIg)
- 47: [Society Is Being Programmed By A Black Box](https://www.youtube.com/watch?v=rQmIPK7DQh8)
- 48: [The Privacyless, Freedomless Smart City of 2030 the Elite Are Engineering](https://www.youtube.com/watch?v=GRybM76qx6I)
- 49: [Obsolete — Full Documentary Official (2016)](https://www.youtube.com/watch?v=jPmUGq25KBk)
- 50: [Rosa Koire : Smart Cities are Future Agenda 21 Hi-Tech Monitored Concentration](https://www.youtube.com/watch?v=p3XuSo03N7s)
- 51: [Why Are We Literally Eating Demon-Shaped Dead Food in This Society?](https://www.youtube.com/watch?v=EeK_iampjjg)
- 52: [We Are Being Groomed for the Next Big War](https://www.youtube.com/watch?v=poQPBppFyWM)
- 53: [Elon Musk: 'We Must Hack Our Brains or Be Destroyed by AI'](https://www.youtube.com/watch?v=MOs-ib5STPE)
- 54: [NASA's Future of War 2025 Is Already Here! (HD)](https://www.youtube.com/watch?v=aDpGB9J27_g)
- 55: [What Bilderberg Really Wants In 2017](https://www.youtube.com/watch?v=EbFMnrPbAmU)
- 56: [AGENDA 21 THE MOVIE: THE MEGACITIES ARE COMING.](https://www.youtube.com/watch?v=mZhI9vvZ2Wo)
- 57: [This Creepy Patent Proves They Can Remotely Hijack Your Nervous System](https://www.youtube.com/watch?v=yf_EdKxfDiY)
- 58: [Trump's New World Order](https://www.youtube.com/watch?v=eLS5h1ZDKvE)
- 59: [Agenda 21 Smart Cities: Orwell's Dystopic Nightmare Comes True](https://www.youtube.com/watch?v=T9DK0JThOio)
- 60: [Bill Gates Just Warned a New Bioweapon Will Wipe Out 30 Million](https://www.youtube.com/watch?v=sErgwyD2KR0)
- 61: [WOLVES IN SHEEP'S CLOTHING: How the public was duped into socialism, but got totalitarianism](https://www.youtube.com/watch?v=cYgyDjl2nCU)
- 62: [Psywar - Full Documentary](https://www.youtube.com/watch?v=2eB046f998U)
- 63: [We Are Becoming the Internet, the Internet Is Becoming Us](https://www.youtube.com/watch?v=GnLyjsO7mZc)
- 64: [The Real Secrets Hidden in Antarctica... Revealed](https://www.youtube.com/watch?v=237F1_aLXZ8)
- 65: [6 Secret Cities That Prove We Don't Know What's Really Going On](https://www.youtube.com/watch?v=wYyBcOLq8bs)
- 66: [Two Top Secret Missions Disguised As Historic Moments You Thought Were Real](https://www.youtube.com/watch?v=1ZiQUngMhr4)
- 67: [AGENDA 21 THE MOVIE: THE MEGACITIES ARE COMING.](https://www.youtube.com/watch?v=mZhI9vvZ2Wo)
- 68: [POWERUL TESTIMONY!! THIS MAN SAW HITLER AND OTHER EVIL PEOPLE IN HELL DURING A NEAR DEATH EXPERIENCE](https://www.youtube.com/watch?v=xt9xodhZ5KI)
- 69: [Aaliyah, Lefteye,Biggie,Eazy E,Whitney Houston, Amy Winehouse Are All N Hell](https://www.youtube.com/watch?v=wwUffrMRDqE)
- 70: [CELEBRITIES SEEN IN HELL (TUPAC, ROBIN WILLIAMS, ELVIS, HEATH LEDGER, AND MORE)](https://www.youtube.com/watch?v=_gNw4SGGwDU)
- 71: [INDIA IMPLEMENTING THE BEAST SYSTEM. CAN'T BUY OR SELL UNLESS YOU TAKE A 12 DIGIT NUMBER](https://www.youtube.com/watch?v=ppEDMsnMfJw)
- 72: [HITLER: Negroes are The True Jews](https://www.youtube.com/watch?v=NE-X985_prM)
- 73: [Blacks are in fact the true jews of the bible](https://www.youtube.com/watch?v=FaqCyBlwCxQ&list=PLA3OCbJL135SGuahCKhuQ20eKMiSdXm2t)
- 74: [THE TRUTH ON THE REAL HEBREW ISRAELITES IS OUT AND THE NATIONS ARE TERRIFIED !!!!!!](https://www.youtube.com/watch?v=mP2ivfkfHVM)
- 75: [Video 10- Testimonies of Edomites/Gentiles Telling Blacks They Are the True Hebrew Israelites](https://www.youtube.com/watch?v=qhjajMbTX1Y)
- 76: [Pt 1 Even the Syrian Refugees Know the Real Hebrew Israelites are Black](https://www.youtube.com/watch?v=YWjd36NOGBg)
- 77: [The Real Hebrews](https://www.youtube.com/watch?v=WvqvteApUGQ)
- 78: [The Real Hebrews 2](https://www.youtube.com/watch?v=IgGXD5nqWXQ&spfreload=1)
- 79: [Adolf Hitler The greatest story Never told Full 6 hours Documentary](https://www.youtube.com/watch?v=7XExjrZxTdk)
- 80: [World Defeated The Wrong Enemy](https://www.youtube.com/watch?v=bm34sj65MkA)
- 81: [Become a Holocaust Denier in 14 Minutes](https://www.youtube.com/watch?v=XEZkvsK7nfo)
- 82: [David Irving Exposes The Holocaust Legend](https://www.youtube.com/watch?v=mYCwaIt-GUM)
- 83: [Celebrities speaking about Zionist Jews](https://www.youtube.com/watch?v=_xchaB_JcAY)
- 84: [EVERYONE NEEDS TO WATCH THIS!! The Protocols of Zion Full Movie](https://www.youtube.com/watch?v=sWjWGVYCMvg)
- 85: [David Irving - Jailed and Beaten For Telling Truth of 2nd World War](https://www.youtube.com/watch?v=8cAFpi4tHMM)
- 86: [The Deleted Interview that George Soros Tried to Ban!](https://www.youtube.com/watch?v=SUdosc33eSE)
- 87: [The Illustrated Protocols of Zion by David Duke](https://www.youtube.com/watch?v=d-xjLa9xrOo)
- 88: [Protocols of Zion The Roadway to destroy America (RichieFromBoston)](https://www.youtube.com/watch?v=848o93RAJtA)
- 89: [Why the Jewish Elite Hates Donald Trump](https://www.youtube.com/watch?v=HV2GhOkQ1yY)
- 90: [Do Zionists Control Wall Street? The Shocking Facts!](https://www.youtube.com/watch?v=pUY7o7pX6vk)
- 91: [Ahmadinejad: They're finished, the Zionist regime is finished.](https://www.youtube.com/watch?v=oLkiM4CHAJo)
- 92: [Israelis Are Not Jews and American Leaders Are Not Christian](https://www.youtube.com/watch?v=PrWguVsEih0)
- 93: [Ahmadinejad on Jews - Larry King](https://www.youtube.com/watch?v=_vYXcna8Pxw)
- 94: [Charlie Rose - Dr. Mahmoud Ahmadinejad, President of Islamic Republic of Iran | Sept. 20, 2010](https://www.youtube.com/watch?v=Im_bRb8CKDk)
- 95: [Mein Kampf - Audio Book](https://www.youtube.com/watch?v=xDOPHZC936c)
- 96: [08/08/2006 President Ahmadinejad Interview](https://www.youtube.com/watch?v=bFCUX5JSA14)
- 97: [Assad say’s “Trumps a Puppet” to Indian media مقابلة الرئيس الأسد مع قناة ويون الهندية](https://www.youtube.com/watch?v=SxpvoVGXURM)
- 98: [Assad smashes journalist with facts in Interview, Oct 6 (مقابلة الرئيس الأسد مع قناة TV2 الدانماركية](https://www.youtube.com/watch?v=7ItP5bLZ8H8)
- 99: [Manchester Bombing False Flag, Pushing the War on Terror (CorbettReport Mirror)](https://www.youtube.com/watch?v=zObCqOaWjh4)
- 100: [False Flag Operations - 9/11, Sandy Hook, Boston Bombing and more - 2016](https://www.youtube.com/watch?v=CQN6wXfQvok)
- 101: [False Flag Alien Event - Don't Fall For It When It Happens!](https://www.youtube.com/watch?v=HF2cBYDvVS8)
- 102: [CAUGHT!!!- State Trucks Poisoning Neighborhoods](https://www.youtube.com/watch?v=bz0-w6zDIT0)
- 103: [City spraying more due to surge in mosquitoes](https://www.youtube.com/watch?v=cOuOqZioiHk)
- 104: [Syria’s Assad BRILLIANTLY Explained How America REALLY Works](https://www.youtube.com/watch?v=zrXvhy8Y57M)
- 105: [Benghazi Whistleblowers – The story behind the cover-up - CTM #670](https://www.youtube.com/watch?v=_vUJSvynuxw)
- 106: [March 22, 2017 U.K. Parliament "terrorism" attack is false flag propaganda / hoax](https://www.youtube.com/watch?v=v3tL_wF-COg)
- 107: [Paris Attack False Flag: Conspiracy Hoax Exposed](https://www.youtube.com/watch?v=OXavIbOQnZw)
- 108: [HOAX GERMAN FALSE FLAG ATTACK.."Return of the Crisis actor III" Lites film action!](https://www.youtube.com/watch?v=-0AeRIjfO0M)
- 109: [Berlin Christmas Market Truck Massacre Hoax](https://www.youtube.com/watch?v=A3aoIenOgdM)
- 110: [Nice France Terror Attack Staged 100% FAKE](https://www.youtube.com/watch?v=SrbNtFfMQ4A)
- 111: [7 CONFIRMED False Flag Attacks](https://www.youtube.com/watch?v=Gst2pwtzz1w)
- 112: [Steve Hughes on war on terror, global warming and X-factor.](https://www.youtube.com/watch?v=Nea-MpVgRL0&list=RDhMcS82DpjSU)
- 113: [Jim Jeffries on America's "freedom"](https://www.youtube.com/watch?v=bjeq3NYUw2M)
- 114: [Donald Trump False Flag Assassination](https://www.youtube.com/watch?v=f9zUeCztKCA)
- 115: [The Untold Story of Adolf Hitler - RFG Chosen 1 & Bro. Sanchez](https://www.youtube.com/watch?v=Q7HhLS7584g)
- 116: [Hillary Clinton & Donald Trump are Cousins EXPOSED!](https://www.youtube.com/watch?v=LuEaf_6P7QY)
- 117: [Biggest False Flag Operation Since 9 11 Happening Right Now!](https://www.youtube.com/watch?v=r_aozYvb_Rs)
- 118: [THIS IS HAPPENING RIGHT BEFORE OUR EYES AND NO ONE SEE'S THE BIGGER ](https://www.youtube.com/watch?v=KjkDqzhCq0c)
- 119: [WHAT DO BANKS, RAILROADS, RETAIL STORES, STANDARD OIL, LUMBER & THE FOOD ](https://www.youtube.com/watch?v=ZI1YUe2oYEQ)
- 120: [A PICTURE IS WORTH A THOUSAND WORDS!](https://www.youtube.com/watch?v=HFTcjSHzyxM)
- 121: [Playing the Trump Card: Obama’s 3rd Term and WW3 (Trump's false flag assassination](https://www.youtube.com/watch?v=HuF14oF2D2Q)
- 122: [IS A 3RD TERM FOR BARACK OBAMA STILL POSSIBLE??? (RIGGED ELECTIONS 2016)](https://www.youtube.com/watch?v=Ol44a2xChqM)
- 123: [This is why Scalia was Murdered](https://www.youtube.com/watch?v=wyPFbDP8W6I)
- 124: [SGTreport: The Paris False Flag of "TRUTH" -- Dr. Paul Craig Roberts](https://www.youtube.com/watch?v=6kSugZtgXsc)
- 125: [Donald Trump - Illuminati Puppet Exposed - Part 1](https://www.youtube.com/watch?v=SL_uAY63IWo)
- 126: [Donald Trump - Illuminati Puppet Exposed - Part 2](https://www.youtube.com/watch?v=7vRHwTZCt7Q&list=RD7vRHwTZCt7Q#t=29)
- 127: [Donald Trump - Controlled by the Illuminati? New World Order MUST WATCH](https://www.youtube.com/watch?v=TXpOiB2kdIM)
- 128: [GISELE TOM BRADY ILLUMINATI TRANNY COUPLE EXPOSED!](https://www.youtube.com/watch?v=FMG4GUgnlMo)
- 129: [MEGYN KELLY ILLUMINATI TRANNY EXPOSED!](https://www.youtube.com/watch?v=t5j1CPUf9RI)
- 130: [2 Different Melania Trump Actresses IMO. Side By Side Split Screen.](https://www.youtube.com/watch?v=zsD7e8NUZO8)
- 131: [Melanie Trump Is A Man. Last Days Satanism.](https://www.youtube.com/watch?v=HwqCscLnCW8)
- 132: [Alex Jones Friend Reveals What Happened To Bill Hicks At A Private Party](https://www.youtube.com/watch?v=_rM2re61BH4)
- 133: [Alex Jones is a Woman. Bill Hicks 2! Part 1](https://www.youtube.com/watch?v=GqpzxccLW_0)
- 134: [Ex government agent admits to the Hollow Earth cover up and that Black Americans are targeted](https://www.youtube.com/watch?v=xk75QtxSYwY)
- 135: [Interview with Reptilian female Lacerta (With Clear Audio and Subtitles)](https://www.youtube.com/watch?v=wjaIq3fuJg8)
- 136: [Hollow Earth True HISTORY , HITLER & NWO ( GOTTA SEE THIS !!! ) Documentary](https://www.youtube.com/watch?v=NiIWMmRkOok)
- 137: [Former CIA Agent Makes a Shocking Statement that Will ROCK the Whole World...](https://www.youtube.com/watch?v=yaTGkSoI8Ic)
- 138: [Amazing Conversation with the Reptilian Hybrid Housewife !!! (MUST WATCH)](https://www.youtube.com/watch?v=7RoLUnN9eWo)
- 139: [A Brief History of the Saurians/Reptilians Documentary !!! (MUST WATCH)](https://www.youtube.com/watch?v=c_NZoSazYJU)
- 140: [CIA Agent Says War Is Eugenics & Drug War Is Fake](https://www.youtube.com/watch?v=0LqDjk8vhyc)
- 141: [CIA is the largest drug cartel in the world](https://www.youtube.com/watch?v=MFzGu5bxnOc)
- 142: [Bill Gates Surprised by Eugenics Question](https://www.youtube.com/watch?v=coHf5UEFUl8)
- 143: [Donald Trump: Eugenics?](https://www.youtube.com/watch?v=3Yh0jAxOxGE)
- 144: [How Mainstream Media Fakes The News - Behind The Scenes](https://www.youtube.com/watch?v=yIUU_VIZn6o)
- 145: [MAAFA 21 THE BLACK HOLOCAUST](https://www.youtube.com/watch?v=UsxwRJZfmMM)
- 146: [EXTINCTION OF THE WHITE RACE APPROACHING.](https://www.youtube.com/watch?v=KYj675gaVQE)
- 147: [The Endgame - Full White Genocide Documentary](https://www.youtube.com/watch?v=uMfk5UeGw4E)
- 148: [Agenda 21 - Replacement Migration - United Nations](https://www.youtube.com/watch?v=9UvURb98aqU)
- 149: [Dear President Trump: The Truth About the 6,000,000](https://www.youtube.com/watch?v=9I-h8Vz6CX0)
- 150: [Queen Admits She Is “Not Human” Published On Royal Website - Screen Capture Before Taken Down](https://www.youtube.com/watch?v=0Kkltxlkxl8)
- 151: [REPTILIAN MAYOR SADIQ KAHN SHAPESHIFTING!](https://www.youtube.com/watch?v=JMkupAEwY70)
- 152: [NOT Advertiser Friendly- "Glitches or Reptilians Caught On Tape - Shape Shifter Species"](https://www.youtube.com/watch?v=XTx9LmR2RjU)
- 153: [The 'Forbidden Fruit 'Was NOT An Apple'](https://www.youtube.com/watch?v=-tSCe2RQPmM)
- 154: [Illuminati, Reptilians & The Manipulation of Reality - David Icke](https://www.youtube.com/watch?v=G2Ta5uAlqgM)
- 155: [David Icke, Revelations of a Mother Goddess - Full Video](https://www.youtube.com/watch?v=ASJou7DvtQE&list=PL4iMnclOjmBfGgkIraEgBZaN32fX5BYNi)
- 156: [Rabbi Weiss Rips the Ideology of Zionism, Controlling ZIONIST are REPTILE ILLUMINATI BANKERS](https://www.youtube.com/watch?v=xt6i6drvGTo)
- 157: [Jews Against Zionism And Rothschilds](https://www.youtube.com/watch?v=awCOSRg-gks)
- 158: [A Jew speaks truth about Hitler and Nazi Germany - Full Video](https://www.youtube.com/watch?v=jFDvtzwT-TU)
- 159: [Ahmed Huber : What did the Jews do to Germany in 1930?](https://www.youtube.com/watch?v=co6_y-OBogY)
- 160: [ORIGIN OF SATANIC ZIONISM. MUST WATCH](https://www.youtube.com/watch?v=Lct-RZ3n4t4)
- 161: [New York City: 10,000+ Jews Against Israel (U.S. Media Blackout)](https://www.youtube.com/watch?v=awCOSRg-gks)
- 162: [Rebel Rabbis: Anti-Zionist Jews Against Israel](https://www.youtube.com/watch?v=FKplabTRuak)
- 163: [Fake Jews And The Coming Destruction Of Israel](https://www.youtube.com/watch?v=rgI_cbx35Nc)
- 164: [New Evidence Stuns The Jewish World](https://www.youtube.com/watch?v=r7nEltyhaYM)
- 165: [Get this! 90% of Proclaimed Jews are not Jews at all (KHAZARS Exposed)](https://www.youtube.com/watch?v=DoCNZWIgP7w)
- 166: [Rabbi Ralph Messer teaching that the original jews are black](https://www.youtube.com/watch?v=2h5Ylr4EPH4)
- 167: [the real "jews" are black!! 100% proof that CANNOT be refuted](https://www.youtube.com/watch?v=0iNfs_ReRNc)
- 168: [Texe Marrs - Khazar DNA & the Great Serpent](https://www.youtube.com/watch?v=drErjw5De0o)
- 169: [The Outrageous Racist Hypocrisy of Israel and World Zionism!](https://www.youtube.com/watch?v=-TvSiYu8z2M)
- 170: [THE GREATEST LIE EVER TOLD - History is NOT what you think](https://www.youtube.com/watch?v=43jwrEDxDZQ)
- 171: [Jewish people are not the real descendants of biblical Israel. Jews controlled African Slavery](https://www.youtube.com/watch?v=fsocwUhjL5s)
- 172: [Who Are the Real Jews?](https://www.youtube.com/watch?v=iLRKilCdwyo)
- 173: [THE FAKE JEWS OF ISRAEL ARE KHAZARS, NOT THE TRUE BIBLICAL ISRAELITES](https://www.youtube.com/watch?v=QliT5M5sJSU)
- 174: [Who Are The Real Children Of Israel?](https://www.youtube.com/watch?v=BloNZd3Ib_Q)
- 175: [David Irving - The Faking of Adolf Hitler for History](https://www.youtube.com/watch?v=bwp7tVZuXKM)
- 176: [Jews are Not God's Chosen People - The Truth Will Set You Free - Marching To Zion](https://www.youtube.com/watch?v=HCEQ6kAN9DU)
- 177: [Ernst Zundel - Interviewed by an Israeli journalist (1996) GREAT !!!](https://www.youtube.com/watch?v=A5sbegfCz7o)
- 178: [Khazar : Secret Ruling Empire of The World Exposed : Sheikh Imran Hosein](https://www.youtube.com/watch?v=b6rEts1BuN8)
- 179: [The Truth - Rothschild & the Khazar History - Documentary](https://www.youtube.com/watch?v=hP4bzXfb6Go)
- 180: [Hitler's War - What the Historians Neglect to Mention](https://www.youtube.com/watch?v=7mA0kk29DBA)
- 181: [Israel Banned Documentary](https://www.youtube.com/watch?v=IZZvTZAKgro)
- 182: [Christopher Hitchens on Charlie Rose - On David Irving's controversial biography (May 8, 1996](https://www.youtube.com/watch?v=fdxTsWXZdFc)
- 183: [Hey PewDiePie Watch This The Truth About Nazis / Brown Shirts](https://www.youtube.com/watch?v=tTcMje9Ok7Q)
- 184: [KANYE WEST MK ULTRA PROGRAMMING ERASED! ILLUMINATI MEMORY LOSS MIND CONTROL BREAKDOWN EXPOSED!](https://www.youtube.com/watch?v=q5r8IwaJwo4)
- 185: [Jr Smith Has Glitche, Illuminati, Mk Ultra Mind Control Meltdown W/Alter Ego](https://www.youtube.com/watch?v=9yoVauEuCmc)
- 186: [Celebrities Expose Occult Entertainment Industry. MK Ultra & Disney Exposed. ](https://www.youtube.com/watch?v=AAd0BDc8gtw)
- 187: [The Smithsonian: We Destroyed the Skeletons of Giant Humans...](https://www.youtube.com/watch?v=O5PHM2k0j2E)
- 188: [Tila Tequila "I'm a Super Soldier" MK Ultra Illuminati Breakdown Continues](https://www.youtube.com/watch?v=LlbDlLLj8Ns)
- 189: [The Mass Deception Of Turning Things Upside Down Agenda](https://www.youtube.com/watch?v=mh_5ceDAiCU)
- 190: [Kanye West Rant Decoded (Unedited Version Is BANNED On YouTube)](https://www.youtube.com/watch?v=e6Ii9dUKFVQ)
- 192: [Johnny Depp's Illuminati MK Ultra Meltdown Continues](https://www.youtube.com/watch?v=BrfV75xQuw8)
- 193: [24/7 Flat Earth LIVE! 100% Proof NASA Lies & Earth is Not a Globe Research Flat Earth](https://www.youtube.com/watch?v=kcRlxKW07GA)
- 194: [DICK GREGORY: A $lave CANNOT Know G0D! HUMBLE YO' SELF!!!](https://www.youtube.com/watch?v=59KilX9SNCI)
- 195: [Watch U.S. Soldiers Expose The Illuminati (Illuminati Exposed) (2017)](https://www.youtube.com/watch?v=a8t4LzGwFp4)
- 196: [Tim Allen Exposes What's Going on in Hollywood! (2017)](https://www.youtube.com/watch?v=Z-DkF98uBm8)
- 197: [There is Something Very Strange about This Man! (2017-2018)](https://www.youtube.com/watch?v=39hRGHr0X_k)
- 198: [How Come Nobody is Talking About This?! (2017-2018 EVENT)](https://www.youtube.com/watch?v=6qKHsA2YH0c)
- 199: [The World in 2017: Prophecy Has Begun! (SHOCKING EVENTS)](https://www.youtube.com/watch?v=S5y6IgC5msU)
- 200: [Listen to Trump's eye-opening talk about End Times.. (2017)](https://www.youtube.com/watch?v=v_rpJLqnRv0)
- 201: [Increase Human Energy by Nikola Tesla](https://www.youtube.com/watch?v=PUZ73HqugYg)
- 202: [[ MUST WATCH ] -The lost secrets of Nikola Tesla!](https://www.youtube.com/watch?v=_IWqPV9p0pk)
- 203: [Tesla 369 Law of Attraction, Energy Frequency Vibration](https://www.youtube.com/watch?v=G1gceUefXBc)
- 204: [Magnetism & Frequency (Knowledge is literally POWER !!!)](https://www.youtube.com/watch?v=JQ7ekeTPBWk)
- 205: [The Secrets Of Vibration 528hz) Hidden truths of sound! Law Of Attraction Part 1](https://www.youtube.com/watch?v=cUiSMPHRrhc)
- 206: [Healing Codes for the Biological Apocalypse - Clip 1 of 3](https://www.youtube.com/watch?v=rtZB9zeKDCM&list=PLD6DAFB7B2FE2C9BF)
- 207: [Adolf Hitler vs The Jew World Order](https://www.youtube.com/watch?v=ssCkc8t9sho)
- 208: [Hitler didn't hate Jews. He hated zionism](https://www.youtube.com/watch?v=bYYTp29xA3o)
- 209: [Why Did Adolf Hitler Hate Jews?](https://www.youtube.com/watch?v=PtEzozK9_Ww)
- 210: [THE TIME HAS COME! THE NAKED TRUTH ABOUT JEWS](https://www.youtube.com/watch?v=dTrrHtcdES0)
- 211: [Leonard Horowitz speaks about 528 HZ Healing Frequency in Vancouver, Washington (2008)](https://www.youtube.com/watch?v=A8SMtbQ7mfk)
- 212: [IN LIES WE TRUST - The Secret Pharmaceutical Drug Conspiracy](https://www.youtube.com/watch?v=NkHcEGZ8oVs)
- 213: [ILLUMINATI PASTORS EXPOSED !!!!](https://www.youtube.com/watch?v=k5azmloxpCw)
- 214: [Joel Osteen Exposed - Reptilian False Prophets](https://www.youtube.com/watch?v=Gba8BtJAOqg)
- 215: [JOEL OSTEEN DENIES JESUS CHRIST & OPRAH WINFREY EXPOSED! Joel Osteen hoax ](https://www.youtube.com/watch?v=weEWl52wevI)
- 216: [Beware: The Greatest Deception of All - Billions will be Deceived](https://www.youtube.com/watch?v=8Gsj9Ed8qkU)
- 217: [528 HZ Healing Frequency Of Satan & Vibes New Age Belief Breakdowns Part 4](https://www.youtube.com/watch?v=1OQ-2faooKw)
- 218: [The Secret Satanic Law of Attraction EXPOSED !!! Illuminati Spirituality !!!](https://www.youtube.com/watch?v=Ri2zfQCoTGc)
- 219: [Yoga is a Satanic Spiritual Practice BEWARE !!! X Yoga Instructor Speaks Out !!!](https://www.youtube.com/watch?v=wKwEkXcmEUQ)
- 220: [Did The Illuminati Change or Write The Bible !?!?!](https://www.youtube.com/watch?v=dOMFbsTZVlc)
- 221: [The Third Eye = Satanic Portal to The Demonic Realm](https://www.youtube.com/watch?v=WbnhIL77tPA)
- 222: [Joel Osteen, Oprah, "The Secret," New Age Occultism & Christianity](https://www.youtube.com/watch?v=u0iXw3WnRq8)
- 223: [Yoga and the Occult: Ex Witch Tells All](https://www.youtube.com/watch?v=uoxs8ixsmrk)
- 224: [Think you can be Christian and do Yoga? PLS LISTEN TO THIS!](https://www.youtube.com/watch?v=6DZ7oz_fIq8)
- 225: [Occult Objects In Your House Give Demons Legal Ground](https://www.youtube.com/watch?v=fC6TVczb8Uc)
- 226: [The Secret Dangers Behind Martial Arts !](https://www.youtube.com/watch?v=ZiC8JWoxhqs)
- 227: [High Level Occult Yoga - Woman Experiences a Glimpse of Hell!](https://www.youtube.com/watch?v=uYq7UP25A7g)
- 228: [Recognizing Demonic Activity in your Life](https://www.youtube.com/watch?v=4_ZdKN_MHd0)

## [StopLookThink.com](http://stoplookthink.com)

### [Lesson in Psychology](https://www.youtube.com/watch?v=vo4pMVb0R6M&list=PL8dPuuaLjXtOPRKzVLY0jJY-uHOH9KVU6)

**Note:** If some of the youtube video links above don't work, search for the video by name in the youtube search

## God is so kind that it is impossible to imagine His unbounded kindness

![flat-earth-isaiah40-22](flat-earth-isaiah40-22.jpg)


