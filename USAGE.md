## ![stats](https://c.statcounter.com/11394978/0/d2ce532c/0/) Welcome to [http://audiobible.life](http://audiobible.life) - [KJV](https://github.com/AudioBible/KJV) - [AudioBible](https://github.com/AudioBible/AudioBible) - Therefore Choose Life

[README](README.md) | [USAGE](USAGE.md) | [HELP](HELP.md) | [DEVELOPMENT](DEVELOPMENT.md) | [CHANGES](CHANGES.md) | **We The People** | **Have The Power** | **Don't Be A Clown**

[VIDEOS](VIDEOS.md) | [MUSIC](MUSIC.md) | [CHANNELS](MUSIC.md) | [DOCUMENTS](DOCUMENTS.md) | [IMAGES](IMAGES.md) | [BOOKS](BOOKS.md) | [LINKS](LINKS.md) | [INFO](INFO.md) | **Join The Revolution**

HOW TO USE
==========

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
    
    audiobible init git                                         # git clone all books and data from git repo instead of using spiders in steps
    audiobible init                                             # download data about all books and chapters in the KJV, step 1
    audiobible init bible                                       # download all books and mp3 audiofiles, step 2
    audiobible init speaker                                     # download all the names of speakers from sermonaudio.com, step 3
    audiobible init topics                                      # download all the topics from sermonaudio.com, step 4
    audiobible init words                                       # download all the words from kingjamesbibledictionary.com, step 5
    
    audiobible dict                                             # open browser to http://www.kingjamesbibledictionary.com
    audiobible dict Amen                                        # open browser to "Amen" in the online dictionary
    audiobible dict H2                                          # open browser to Strong's number definition online
    
    audiobible hub mark 4                                       # open browser to interlinear biblehub.com book of "Mark" 
    
    audiobible list                                             # to list all books and the number of chapters each book has
    audiobible list speakers                                    # to list all speakers found on sermonaudio.com
    audiobible list speakers this                               # to list all speakers which have this in there name
    audiobible list topics                                      # to list all topics found on sermonaudio.com
    audiobible list words                                       # to list all words found on kingjamesbibledictionary.com
    audiobible list words this                                  # to list all words and strong's numbers, which have "this" in the word
    audiobible list words H2                                    # to list all words which are associated with the strong's number "H2"
    
    audiobible words this                                       # show definition/s and other data for the word "this"
    audiobible words H2                                         # show definition/s and other data for the strong's number "H2"
    
    audiobible praise                                           # open a browser to a youtube playlist with hymns for praising God
    
    audiobible path daniel                                      # show the path on the hard drive to the book of "Daniel"
    
    audiobible sermons                                          # opens the default browser to http://sermonaudio.com
    audiobible sermons -b mark -s "Charles Lawson"              # open browser to sermon "Charles Lawson" preaching the book of "Mark"
    
    audiobible quote                                            # to output a quote
    audiobible quote -A2 -B1                                    # to output a quote having four verses, two after and one before the random selected quote
    
    audiobible hear mark                                        # to hear the book of "Mark" chapter 1
    audiobible hear mark all                                    # to hear all chapters from the book of "Mark"
    audiobible hear -b mark                                     # to hear the book of "Mark" chapter 1
    audiobible hear mark 4                                      # to hear the book of "Mark" chapter 4
    audiobible hear -b mark -c 4                                # to hear the book of "Mark" chapter 4
    audiobible hear 1_john 3                                    # to hear the book of "1 John" chapter 3
    audiobible hear -b 1_john -c 3                              # to hear the book of "1 John" chapter 3
    audiobible hear -b mark -c all                              # same as hear mark all
    
    audiobible read mark 4                                      # to read Mark 4, (use params like with hear operation)
    
    audiobible show mark 4                                      # to show the book of "Mark" chapter 4 text in the terminal, specify params like with hear operation
    
    audiobible find                                             # to output the whole Bible
    audiobible find REV 22:17                                   # to output a specific verse
    audiobible find -b 2_john                                   # to output the whole book of "2 John"
    audiobible find -b james -c 5                               # to output chapter 5 for the book of "James"
    audiobible find water of life                               # to find water of life, say words to search for as params
    audiobible find water                                       # to find water, say the word to search the whole bible
    audiobible find 'it is done'                                # to find it is done, say the words to search as a string
    audiobible find circle of the earth -a partial              # to find query using fuzzy partial algorithm, also try: 'ratio', 'set', 'sort'; default is 'regex'
                                                                # algorithms are only for the find operation
    
    audiobible find jesus -b luke -c 3 -C 2                     # to find jesus in the book of "Luke" chapter 3, showing 2 verses before and after the matched verse context
    audiobible find circle -A 5 -B 2                            # to show 2 verse before and 5 verses after the matched verse context
    
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

## audiobible show ps 101


    PS 101:1 I will sing of mercy and judgment: unto thee, O LORD, will I sing.
    
    PS 101:2 I will behave myself wisely in a perfect way. O when wilt thou come unto me? I will walk within my house with a perfect heart.
    
    PS 101:3 I will set no wicked thing before mine eyes: I hate the work of them that turn aside; it shall not cleave to me.
    
    PS 101:4 A froward heart shall depart from me: I will not know a wicked person.
    
    PS 101:5 Whoso privily slandereth his neighbour, him will I cut off: him that hath an high look and a proud heart will not I suffer.
    
    PS 101:6 Mine eyes shall be upon the faithful of the land, that they may dwell with me: he that walketh in a perfect way, he shall serve me.
    
    PS 101:7 He that worketh deceit shall not dwell within my house: he that telleth lies shall not tarry in my sight.
    
    PS 101:8 I will early destroy all the wicked of the land; that I may cut off all wicked doers from the city of the LORD.
    

## audiobible dict froward


    Froward
    FRO'WARD, adjective [Latin versus:turned or looking from.]
    
    Perverse, that is, turning from, with aversion or reluctance; not willing to yield or comply with what is required; unyielding; ungovernable; refractory; disobedient; peevish; as a froward child.
    
    They are a very froward generation, children in whom is no faith. Deuteronomy 32:20.
    
    
    Frowardly
    FRO'WARDLY, adverb Perversely; in a peevish manner.
    
    Frowardness
    FRO'WARDNESS, noun Perverseness; reluctance to yield or comply; disobedience; peevishness.


# audiobible find way of holiness


    IS 35:8 And an highway shall be there, and a way, and it shall be called The way of holiness; the unclean shall not pass over it; but it shall be for those: the wayfaring men, though fools, shall not err therein.


# audiobible find many things to say


    JN 8:26 I have many things to say and to judge of you: but he that sent me is true; and I speak to the world those things which I have heard of him.
    
    JN 16:12 I have yet many things to say unto you, but ye cannot bear them now.
    
    HEB 5:11 Of whom we have many things to say, and hard to be uttered, seeing ye are dull of hearing.


# audiobible hear 2_th all

# audiobible show 2_th all


    2THESS 1:1 Paul, and Silvanus, and Timotheus, unto the church of the Thessalonians in God our Father and the Lord Jesus Christ:

    2THESS 1:2 Grace unto you, and peace, from God our Father and the Lord Jesus Christ.
    
    2THESS 1:3 We are bound to thank God always for you, brethren, as it is meet, because that your faith groweth exceedingly, and the charity of every one of you all toward each other aboundeth;
    
    2THESS 1:4 So that we ourselves glory in you in the churches of God for your patience and faith in all your persecutions and tribulations that ye endure:
    
    2THESS 1:5 Which is a manifest token of the righteous judgment of God, that ye may be counted worthy of the kingdom of God, for which ye also suffer:
    
    2THESS 1:6 Seeing it is a righteous thing with God to recompense tribulation to them that trouble you;
    
    2THESS 1:7 And to you who are troubled rest with us, when the Lord Jesus shall be revealed from heaven with his mighty angels,
    
    2THESS 1:8 In flaming fire taking vengeance on them that know not God, and that obey not the gospel of our Lord Jesus Christ:
    
    2THESS 1:9 Who shall be punished with everlasting destruction from the presence of the Lord, and from the glory of his power;
    
    2THESS 1:10 When he shall come to be glorified in his saints, and to be admired in all them that believe (because our testimony among you was believed) in that day.
    
    2THESS 1:11 Wherefore also we pray always for you, that our God would count you worthy of this calling, and fulfil all the good pleasure of his goodness, and the work of faith with power:
    
    2THESS 1:12 That the name of our Lord Jesus Christ may be glorified in you, and ye in him, according to the grace of our God and the Lord Jesus Christ.
    
    
    2THESS 2:1 Now we beseech you, brethren, by the coming of our Lord Jesus Christ, and by our gathering together unto him,
    
    2THESS 2:2 That ye be not soon shaken in mind, or be troubled, neither by spirit, nor by word, nor by letter as from us, as that the day of Christ is at hand.
    
    2THESS 2:3 Let no man deceive you by any means: for that day shall not come, except there come a falling away first, and that man of sin be revealed, the son of perdition;
    
    2THESS 2:4 Who opposeth and exalteth himself above all that is called God, or that is worshipped; so that he as God sitteth in the temple of God, shewing himself that he is God.
    
    2THESS 2:5 Remember ye not, that, when I was yet with you, I told you these things?
    
    2THESS 2:6 And now ye know what withholdeth that he might be revealed in his time.
    
    2THESS 2:7 For the mystery of iniquity doth already work: only he who now letteth will let, until he be taken out of the way.
    
    2THESS 2:8 And then shall that Wicked be revealed, whom the Lord shall consume with the spirit of his mouth, and shall destroy with the brightness of his coming:
    
    2THESS 2:9 Even him, whose coming is after the working of Satan with all power and signs and lying wonders,
    
    2THESS 2:10 And with all deceivableness of unrighteousness in them that perish; because they received not the love of the truth, that they might be saved.
    
    2THESS 2:11 And for this cause God shall send them strong delusion, that they should believe a lie:
    
    2THESS 2:12 That they all might be damned who believed not the truth, but had pleasure in unrighteousness.
    
    2THESS 2:13 But we are bound to give thanks alway to God for you, brethren beloved of the Lord, because God hath from the beginning chosen you to salvation through sanctification of the Spirit and belief of the truth:
    
    2THESS 2:14 Whereunto he called you by our gospel, to the obtaining of the glory of our Lord Jesus Christ.
    
    2THESS 2:15 Therefore, brethren, stand fast, and hold the traditions which ye have been taught, whether by word, or our epistle.
    
    2THESS 2:16 Now our Lord Jesus Christ himself, and God, even our Father, which hath loved us, and hath given us everlasting consolation and good hope through grace,
    
    2THESS 2:17 Comfort your hearts, and stablish you in every good word and work.
    
    
    2THESS 3:1 Finally, brethren, pray for us, that the word of the Lord may have free course, and be glorified, even as it is with you:
    
    2THESS 3:2 And that we may be delivered from unreasonable and wicked men: for all men have not faith.
    
    2THESS 3:3 But the Lord is faithful, who shall stablish you, and keep you from evil.
    
    2THESS 3:4 And we have confidence in the Lord touching you, that ye both do and will do the things which we command you.
    
    2THESS 3:5 And the Lord direct your hearts into the love of God, and into the patient waiting for Christ.
    
    2THESS 3:6 Now we command you, brethren, in the name of our Lord Jesus Christ, that ye withdraw yourselves from every brother that walketh disorderly, and not after the tradition which he received of us.
    
    2THESS 3:7 For yourselves know how ye ought to follow us: for we behaved not ourselves disorderly among you;
    
    2THESS 3:8 Neither did we eat any man's bread for nought; but wrought with labour and travail night and day, that we might not be chargeable to any of you:
    
    2THESS 3:9 Not because we have not power, but to make ourselves an ensample unto you to follow us.
    
    2THESS 3:10 For even when we were with you, this we commanded you, that if any would not work, neither should he eat.
    
    2THESS 3:11 For we hear that there are some which walk among you disorderly, working not at all, but are busybodies.
    
    2THESS 3:12 Now them that are such we command and exhort by our Lord Jesus Christ, that with quietness they work, and eat their own bread.
    
    2THESS 3:13 But ye, brethren, be not weary in well doing.
    
    2THESS 3:14 And if any man obey not our word by this epistle, note that man, and have no company with him, that he may be ashamed.
    
    2THESS 3:15 Yet count him not as an enemy, but admonish him as a brother.
    
    2THESS 3:16 Now the Lord of peace himself give you peace always by all means. The Lord be with you all.
    
    2THESS 3:17 The salutation of Paul with mine own hand, which is the token in every epistle: so I write.
    
    2THESS 3:18 The grace of our Lord Jesus Christ be with you all. Amen.


# audiobible show 1_john 5


    1JN 5:1 Whosoever believeth that Jesus is the Christ is born of God: and every one that loveth him that begat loveth him also that is begotten of him.
    
    1JN 5:2 By this we know that we love the children of God, when we love God, and keep his commandments.
    
    1JN 5:3 For this is the love of God, that we keep his commandments: and his commandments are not grievous.
    
    1JN 5:4 For whatsoever is born of God overcometh the world: and this is the victory that overcometh the world, even our faith.
    
    1JN 5:5 Who is he that overcometh the world, but he that believeth that Jesus is the Son of God?
    
    1JN 5:6 This is he that came by water and blood, even Jesus Christ; not by water only, but by water and blood. And it is the Spirit that beareth witness, because the Spirit is truth.
    
    1JN 5:7 For there are three that bear record in heaven, the Father, the Word, and the Holy Ghost: and these three are one.
    
    1JN 5:8 And there are three that bear witness in earth, the Spirit, and the water, and the blood: and these three agree in one.
    
    1JN 5:9 If we receive the witness of men, the witness of God is greater: for this is the witness of God which he hath testified of his Son.
    
    1JN 5:10 He that believeth on the Son of God hath the witness in himself: he that believeth not God hath made him a liar; because he believeth not the record that God gave of his Son.
    
    1JN 5:11 And this is the record, that God hath given to us eternal life, and this life is in his Son.
    
    1JN 5:12 He that hath the Son hath life; and he that hath not the Son of God hath not life.
    
    1JN 5:13 These things have I written unto you that believe on the name of the Son of God; that ye may know that ye have eternal life, and that ye may believe on the name of the Son of God.
    
    1JN 5:14 And this is the confidence that we have in him, that, if we ask any thing according to his will, he heareth us:
    
    1JN 5:15 And if we know that he hear us, whatsoever we ask, we know that we have the petitions that we desired of him.
    
    1JN 5:16 If any man see his brother sin a sin which is not unto death, he shall ask, and he shall give him life for them that sin not unto death. There is a sin unto death: I do not say that he shall pray for it.
    
    1JN 5:17 All unrighteousness is sin: and there is a sin not unto death.
    
    1JN 5:18 We know that whosoever is born of God sinneth not; but he that is begotten of God keepeth himself, and that wicked one toucheth him not.
    
    1JN 5:19 And we know that we are of God, and the whole world lieth in wickedness.
    
    1JN 5:20 And we know that the Son of God is come, and hath given us an understanding, that we may know him that is true, and we are in him that is true, even in his Son Jesus Christ. This is the true God, and eternal life.
    
    1JN 5:21 Little children, keep yourselves from idols. Amen.
    

# audiobible find choose life -A1

    DEUT 30:19 I call heaven and earth to record this day against you, that I have set before you life and death, blessing and cursing: therefore choose life, that both thou and thy seed may live:
    
    DEUT 30:20 That thou mayest love the LORD thy God, and that thou mayest obey his voice, and that thou mayest cleave unto him: for he is thy life, and the length of thy days: that thou mayest dwell in the land which the LORD sware unto thy fathers, to Abraham, to Isaac, and to Jacob, to give them.


# audiobible find spake often -A1
    
    
    MAL 3:16 Then they that feared the LORD spake often one to another: and the LORD hearkened, and heard it, and a book of remembrance was written before him for them that feared the LORD, and that thought upon his name.
    
    MAL 3:17 And they shall be mine, saith the LORD of hosts, in that day when I make up my jewels; and I will spare them, as a man spareth his own son that serveth him.


# audiobible find "false apostles" -A2


    2COR 11:13 For such are false apostles, deceitful workers, transforming themselves into the apostles of Christ.
    
    2COR 11:14 And no marvel; for Satan himself is transformed into an angel of light.
    
    2COR 11:15 Therefore it is no great thing if his ministers also be transformed as the ministers of righteousness; whose end shall be according to their works.


# audiobible find dwelleth not in temples made with hands -A4
    
    
    ACTS 7:48 Howbeit the most High dwelleth not in temples made with hands; as saith the prophet,
    
    ACTS 7:49 Heaven is my throne, and earth is my footstool: what house will ye build me? saith the Lord: or what is the place of my rest?
    
    ACTS 7:50 Hath not my hand made all these things?
    
    ACTS 7:51 Ye stiffnecked and uncircumcised in heart and ears, ye do always resist the Holy Ghost: as your fathers did, so do ye.
    
    ACTS 7:52 Which of the prophets have not your fathers persecuted? and they have slain them which shewed before of the coming of the Just One; of whom ye have been now the betrayers and murderers:
    
    ACTS 17:24 God that made the world and all things therein, seeing that he is Lord of heaven and earth, dwelleth not in temples made with hands;
    
    ACTS 17:25 Neither is worshipped with men's hands, as though he needed any thing, seeing he giveth to all life, and breath, and all things;
    
    ACTS 17:26 And hath made of one blood all nations of men for to dwell on all the face of the earth, and hath determined the times before appointed, and the bounds of their habitation;
    
    ACTS 17:27 That they should seek the Lord, if haply they might feel after him, and find him, though he be not far from every one of us:
    
    ACTS 17:28 For in him we live, and move, and have our being; as certain also of your own poets have said, For we are also his offspring.
    

# audiobible find "thy brother's ass" -A1

    
    DEUT 22:4 Thou shalt not see thy brother's ass or his ox fall down by the way, and hide thyself from them: thou shalt surely help him to lift them up again.

    DEUT 22:5 The woman shall not wear that which pertaineth unto a man, neither shall a man put on a woman's garment: for all that do so are abomination unto the LORD thy God.


# audiobible find third heaven


    2COR 12:2 I knew a man in Christ above fourteen years ago, (whether in the body, I cannot tell; or whether out of the body, I cannot tell: God knoweth;) such an one caught up to the third heaven.
    

# audiobible find one in Christ Jesus


    GAL 3:28 There is neither Jew nor Greek, there is neither bond nor free, there is neither male nor female: for ye are all one in Christ Jesus.
    

# audiobible find well spoken -A5


    DEUT 18:17 And the LORD said unto me, They have well spoken that which they have spoken.
    
    DEUT 18:18 I will raise them up a Prophet from among their brethren, like unto thee, and will put my words in his mouth; and he shall speak unto them all that I shall command him.
    
    DEUT 18:19 And it shall come to pass, that whosoever will not hearken unto my words which he shall speak in my name, I will require it of him.
    
    DEUT 18:20 But the prophet, which shall presume to speak a word in my name, which I have not commanded him to speak, or that shall speak in the name of other gods, even that prophet shall die.
    
    DEUT 18:21 And if thou say in thine heart, How shall we know the word which the LORD hath not spoken?
    
    DEUT 18:22 When a prophet speaketh in the name of the LORD, if the thing follow not, nor come to pass, that is the thing which the LORD hath not spoken, but the prophet hath spoken it presumptuously: thou shalt not be afraid of him.
    
