# hellomusic

<!DOCTYPE html>
<html>

<head>
    <title>
        HELLOMUSIC
    </title>
    <style>
        .logo {
            list-style-type: none;
            background-color: #e2ffe2;
            overflow: hidden;
            text-shadow: 5px 5px 5px #5f9ea0;
            height: 75px;
        }


        .logo div a:hover {
            background-color: #7fdacd;
        }

        .yi {
            float: left;
        }

        .er {
            float: left;
        }

        .si {
            float: left;
        }

        .wu {
            float: left;
        }

        .san {
            float: left;
        }

        .c1 {
            float: left;
        }

        .c2 {
            float: left;
        }

        .c3 {
            float: left;
        }

        .c4 {
            float: left;
        }

        .c5 {
            float: left;
        }

        .c6 {
            float: left;
        }

        #sou {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        .faxian {
            float: left;
        }

        .lo a {
            padding: 0px;
            text-decoration: none;
            background-color: #4CAF50;
            color: black;
            color: white;
            padding: 16px;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }

        .lo a:hover {
            background-color: #3e8e41;
        }

        .dropbtn {
            background-color: #4CAF50;
            color: white;
            padding: 16px;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }

        /* 容器 <div> - 需要定位下拉内容 */
        .dropdown {
            position: relative;
            top: 20px;
            left: 37px;
            display: inline-block;
        }

        /* 下拉内容 (默认隐藏) */
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
        }

        /* 下拉菜单的链接 */
        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        /* 鼠标移上去后修改下拉菜单链接颜色 */
        .dropdown-content a:hover {
            background-color: #f1f1f1
        }

        /* 在鼠标移上去后显示下拉菜单 */
        .dropdown:hover .dropdown-content {
            display: block;
        }

        /* 当下拉内容显示后修改下拉按钮的背景颜色 */
        .dropdown:hover .dropbtn {
            background-color: #3e8e41;
        }

        div.float1 {
            float: left;
            width: 570px;
            height: auto;
            margin-left: 3%;
        }

        div.float2 {
            float: right;
            width: 600px;
            height: auto;
        }

        .tiao {
            font-size: 20px;
            color: #912ea5;
            text-align: center;
            background-color: rgb(173, 190, 196);
        }
    </style>
</head>

<body bgcolor="#dcf0dc ">
    <div class="logo" style="text-align: center; font-size: 50px;color:#4CAF50;">HELLOMUSIC</div>
    <br />
    <nav style="margin-left: 3%;">
        <div class="lo">
            <a href="#">首页</a>
            <a href="#">发现</a>
            <a href="#">歌单</a>
            <a href="#">排行榜</a>
            <a href="#">动态</a>
            <a href="#">最新音乐</a>
        </div>
    </nav>
    <div class="dropdown">
        <button class="dropbtn">下拉菜单</button>
        <div class="dropdown-content">
            <a href="#">发现音乐</a>
            <a href="#">推荐</a>
            <a href="#">歌单</a>
            <a href="#">排行榜</a>
            <a href="#">最新音乐</a>
            <a href="#">动态</a>
        </div>
    </div>
    <br />
    <div style="margin-left: 3%;">
        <br />
        <input type="text" maxlength="100" style="width:405px;height:32px;">&nbsp<input id="sou" type="submit"
            value="搜索音乐" style="width:100px;height:37px;">
        <br />
    </div>
    <div class="jieshao">
        <h1 style="margin-left: 3%;">最新音乐</h1>
        <div class="yi" style="margin-left: 3%;">
            <a href="http://music.163.com/song?id=1480280185&userid=1304030662"><img
                    src="http://p1.music.126.net/aGyqZ7Ns2rB9IIKose6VOg==/109951165339779758.jpg?param=525x10000"
                    topmargin="7%" target="_blank" width=200px></a>
        </div>
        <div class="er" style="margin-left: 3%;">
            <a href="http://music.163.com/song?id=1421443440&userid=1304030662"><img
                    src="http://p1.music.126.net/IB2nqkD3GIMhZhMO_3Y8mw==/109951165341064755.jpg?param=525x10000"
                    topmargin="7%" target="_blank" width=200px></a>
        </div>
        <div class="san" style="margin-left: 3%;">
            <img src="IMG_3170(20190812-183346).JPG" topmargin="7%" target="_blank" width=200px>
        </div>
        <div class="si" style="margin-left: 3%;">
            <img src="IMG_3196(20200615-001951).JPG" topmargin="7%" target="_blank" width=200px>
        </div>
        <div class="wu" style="margin-left: 3%;">
            <img src="IMG_3169(20200915-141312).JPG" topmargin="7%" target="_blank" width=200px>
        </div>
    </div>
    <div class="faxian">
        <br />
        <br />
        <br />
        <h1 style="margin-left: 3%;">发现音乐</h1>
        <br />
        <MARQUEE onmouseover=stop() onmouseout=start() scrollAmount=10 hspace="15px">
            <IMG src="IMG_3169(20200915-141312).JPG" target="_blank" width=200px"><IMG
                src="IMG_3170(20190812-183346).JPG" target="_blank" width=200px"><IMG
                src="IMG_3187(20190812-183345).JPG" target="_blank" width=200px"><IMG
                src="IMG_3196(20200615-001951).JPG" target="_blank" width=200px"><IMG src="diyi.JPG" target="_blank"
                width=200px"><IMG src="IMG_3197(20200615-001951).JPG" target="_blank" width=200px"><IMG
                src="IMG_3170(20190812-183346).JPG" target="_blank" width=200px">
        </MARQUEE>
    </div>
    <br />
    <div>
        <p style="font-size: 25px;margin-left: 3%;">&nbsp &nbsp &nbsp &nbsp&nbsp &nbsp &nbsp &nbsp</p>
    </div>
    <br />
    <div>
        <h1 style="margin-left: 3%;">今日推荐</h1>
    </div>
    <h1 style="text-align: center;">LABRINTH, SIA & DIPLO PRESENT... LSD</h1>
    <br />
    <br />
    <br />
    <div class="float1">
        <h2 style="font: larger;color: black;">Music List</h2>
        <hr />
        <ul>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">Welcome to the Wonderful World Of
                    (feat. Sia, Diplo & Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">Angel in Your Eyes (feat. Sia,
                    Diplo & Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank>">Genius (feat. Sia, Diplo &
                    Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">Audio (feat. Sia, Diplo &
                    Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">Thunderclouds (feat. Sia, Diplo &
                    Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">Mountains (feat. Sia, Diplo &
                    Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">No New Friends (feat. Sia, Diplo &
                    Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">Heaven Can Wait (feat. Sia, Diplo &
                    Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">It's Time (feat. Sia, Diplo &
                    Labrinth)</a></li>
            <li><a href="https://music.douban.com/subject/33407365/" target="_blank">Genius (feat. Lil Wayne, Sia, Diplo
                    & Labrinth) [Lil Wayne Remix]
                </a></li>
        </ul>
        <hr />
    </div>
    <div class="float2">
        <img id="LSD" align='left' class="transition-all" src="IMG_3169(20200915-141312).JPG" width="160">
        　 “When you put Lab and Sia in a room, it’s the craziest concoction,” Diplo told Beats 1 host Zane Lowe. “Two of
        the most creative people I’ve ever met, like in a boxing match: bam-bam-bam-bam!” Following hits like
        “Thunderclouds” and “Mountains,” the A-list supergroup—made up of visionary songwriter/producers Labrinth and
        Diplo alongside the extraordinary Sia—present their first collaborative full-length of shape-shifting,
        hyperactive pop. Full of left turns and flamboyant instrumental flair, the songs here value largesse: You can
        hear Diplo’s dancehall rhythms, Sia’s dramatic balladry, and Labrinth’s taste for oddball pairings like
        gospel-inspired choruses over skittering trap breaks. The intro track, “Welcome to the Wonderful World Of,”
        swirls together chopped vocals, Jock Jams synths, dizzying digital pings, and a grinding bassline—an
        amuse-bouche for what follows. It's not quite the vision quest the name suggests; with catchy hooks, soaring
        melodies, and an appearance from Lil Wayne, the project is closer to classic pop. But it's just strange enough
        to open a door: Mainstream music just got a little bit weirder.
    </div>
    <br />
    <br />
    <br />
    <br />
    <p style="font-size: 50px;margin-left: 20%;">&nbsp &nbsp &nbsp &nbsp&nbsp &nbsp &nbsp &nbsp</p>
    <center>
        <h1>Origins (Deluxe)Imagine Dragons</h1>
    </center>
    <br />
    <br />
    <br />
    <div class="float1">
        <h2 style="font: larger;color: black;">Music List</h2>
        <hr />
        <ul>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Natural</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Boomerang</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Machine</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Cool Out</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Bad Liar</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">West Coast</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Zero</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Bullet In A Gun</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Digital</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Only</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Stuck</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Love</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Birds</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Burn Out</a></li>
            <li><a href="https://music.douban.com/subject/30341963/" target="_blank">Real Life</a></li>

        </ul>
        <hr />
    </div>
    <div class="float2">
        <img id="LSD" align='left' class="transition-all" src="IMG_0008(20201125-123025).JPG" width="160">
        　 Tenth Anniversary of the Army* National Diamond Record Certification, Grammy Awards "Best Rock Performance"
        brand new album dominates the charts* "Natural" strongly rushed to the billboard rock chart champion Hollywood
        designation* "Invincible Destruction King 2: The Internet "Theme song "Zero" 　　 In 2017, the last album "Evolve"
        received more than 8 billion views worldwide. In 2018, the rock band Imagine Dragons, the highest streaming
        media player, once again made a big hit. Created a new genre of rock music in the current era. Through the
        blending of melody, the profound meaning of the lyrics is highlighted. The first work directly hits the hearts
        of the people and impressed hundreds of millions of music fans around the world. Imagine Dragons is now the
        world-dominant band, written in the digital age. Various records make them the new music vane of the 21st
        Century Orchestra. This year they released a new album "Origins", which will once again shock the music scene.
        The Imagine Dragons, composed of vocal and guitarist Dan Reynolds, guitarist Wayne Sermon, bassist Ben McKee and
        drummer Daniel Platzman, has just reached its 10th anniversary since their debut. They rely on "Night Visions"
        and "Smoke + Mirrors".
    </div>
    <br />
    <br />
    <br />
    <br />
    <p style="font-size: 50px;margin-left: 20%;">&nbsp &nbsp &nbsp &nbsp&nbsp &nbsp</p>
    <center>
        <h1>Random Access Memories Daft Punk</h1>
    </center>
    <br />
    <br />
    <br />
    <div class="float1">
        <h2 style="font: larger;color: black;">Music List</h2>
        <hr />
        <ul>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Give Life Back to Music</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">The Game of Love</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank"> Giorgio by Moroder</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Within</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Instant Crush</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Lose Yourself to Dance</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Touch </a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Get Lucky</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Beyond</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Motherhood</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Fragments of Time</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Doin’ It Right</a></li>
            <li><a href="https://music.douban.com/subject/22951704/" target="_blank">Contact(featuring DJ Falcon)</a>
            </li>
        </ul>
        <hr />
    </div>
    <div class="float2">
        <img id="LSD" align='left' class="transition-all" src="IMG_0009(20201125-123037).JPG" width="160">
        &nbsp &nbsp &nbsp"Random Access Memories" is the fourth official album released by the French duo duo duo punk.
        The album is
        supervised by orchestra members Thomas Bengut and Guy-Manuel de Homan-Christo. It is a standard record. A total
        of
        13 songs were recorded, and they were released on May 17, 2013 through Daft Life Records. The album won the
        Grammy
        Awards for "Album of the Year" and "Best Electronic Dance Album" in January 2014. Silly Punk’s original
        intention of
        making "Random Access Memories" was to pay tribute to the Michael Jackson, Car Chorus, and Stilidan Chorus in
        the
        late 1970s and early 1980s. However, when silly punk recorded "Random Access Memories", it used a different
        recording method from previous studio albums, that is, in the process of recording the album, many musicians
        were
        invited to perform live recording in professional recording studios. Instead of directly sampling other people's
        song fragments. "Random Access Memories" is mainly composed of Chic lead singer Nile Rogers. In terms of
        planning,
        both dumb punk and Nile Rogers respect each other's opinions.
    </div>
    <p style="font-size: 60px;margin-left: 3%;">&nbsp &nbsp &nbsp &nbsp&nbsp &nbsp &nbsp &nbsp</p>
    <br />
    <h1 style="margin-left: 3%;">歌曲介绍</h1>
    <div class="c1" style="margin-left: 5%;">
        <a href="#Holy"><img src="IMG_5535(20201015-145412).JPG" width="160"></a>
    </div>
    <div class="c2" style="margin-left: 3%;">
        <a href="#Love yourself"><img src="IMG_3197(20200615-001951).JPG" width="160"></a>
    </div>
    <div class="c3" style="margin-left: 3%;">
        <a href="#What do you mean"><img src="IMG_5536(20201015-145445).JPG" width="160"></a>
    </div>
    <div class="c4" style="margin-left: 3%;">
        <a href="#Sorry"><img src="IMG_5452(20200924-134609).JPG" width="160"></a>
    </div>
    <div class="c5" style="margin-left: 3%;">
        <a href="#Intentions"><img src="IMG_3187(20190812-183345).JPG" width="160"></a>
    </div>
    <div class="c6" style="margin-left: 3%;">
        <a href="#Come Around Me"><img src="IMG_0009(20201125-123037).JPG" width="160"></a>
    </div>
    <br />
    <br />
    <p style="font-size: 50px;margin-left: 20%;">&nbsp &nbsp &nbsp &nbsp&nbsp &nbsp &nbsp &nbsp</p>
    <div class="tiao">
        <b id="Holy">Holy</b>
        <p>&nbsp &nbsp &nbsp &nbspOn September 15, New York, Grammy Award winner and global superstar Justin Bieber
            officially confirmed the release of a new music. He cooperated with rapper chance the rapper to release
            a
            new
            single "holy". This song marks Bieber's return to pop music. Just a few months ago, Bieber and quavo's
            8x
            platinum single "ideas" topped the radio charts in June, the seventh time in his career that he won the
            billboard pop songs chart. The single was also featured in a short film directed by Colin Tilley.</p>
        <br />
        <b id="Love yourself">Love yourself</b>
        <p>&nbsp &nbsp &nbsp &nbspLove yourself is a popular song sung by Canadian male singer Justin Bieber. The
            lyrics
            are
            jointly composed by Justin Bieber, ed Hiran and Benny blank. The composition is in charge of ED Hiran.
            Benny
            blank is the music producer. Josie Godwin is responsible for the mixing of singing and music. The song
            was
            included in Justin Bieber's fourth studio album, purpose, and released through Isle records on November
            9,
            2015
            as the third single to promote the album.

            The song is Justin Bieber's third No. 1 single on the Billboard's top 100 singles list and won the No. 1
            spot on
            February 13, 2016 for two weeks. In other countries, the song is ranked in Australia, the United
            Kingdom,
            Canada, New Zealand and other regions of the music version champion [6]. In January 2016, the song was
            certified
            as double platinum single with more than 2 million sales in the United States. In May 2016, the song won
            the
            "most popular pop rock song" award at the National Music Awards.</p>
        <br />
        <b id="What do you mean">What do you mean</b>
        <p>&nbsp &nbsp &nbsp《What Do You Mean？ 》It is a popular song sung by Canadian male singer Justin Bieber. The
            lyrics
            and music score of the song are jointly written by Jason Boyd, Justin Bieber and Mason levy. 《What Do
            You
            Mean？
            》As the first single to promote the album, it was released through Island Records on August 28, 2015 and
            included in Justin Bieber's fourth studio album "purpose" released on November 13, 2015.
            《What Do You Mean？ 》It is the 23rd American billboard song to win the first week of the top 100 single,
            and
            it
            is also Justin Bieber's first single on the list. In other regions, the song has won the music charts of
            Britain, France, Europe, Australia, Austria and other 20 regions. January 6, 2015, what do you mean?
            》Won
            the
            "most popular song" award from the 42nd people's Choice Award.

            The single was named one of "101 best songs of 2015" by spin magazine and ranked No.1.</p>
        <br />
        <b id="Sorry">Sorry</b>
        <p>&nbsp &nbsp &nbsp"Sorry" is a popular song sung by Canadian male singer Justin Bieber. The lyrics and
            music
            score
            are jointly written by Julia Mack, Justin Bieber, skyrex, sonny Moore and Michael Tucker. Skyrex and
            blood
            are
            responsible for the music publishing. As the second single to promote the album, the song was released
            by
            Isla
            records on October 23, 2015, and was included in Justin Bieber's fourth studio album, purpose.
            "Sorry" is Justin Bieber's second top 100 single on the billboard of the United States. It won the top
            of
            the
            list on January 23, 2016 and won the title for three consecutive weeks. In other regions, the song also
            won
            the
            top of 13 national music charts, including Ireland, Denmark, the Netherlands, Canada, South Africa,
            Slovakia,
            Sweden and the United Kingdom. In May 2016, the song was nominated for the Billboard Music Award "best
            selling
            song".

            In December 2015, the song was named one of the "top 25 songs of the year" by Billboard magazine,
            ranking
            15th.
        </p>
        <br />
        <b id="Intentions">Intentions</b>
        <p>&nbsp &nbsp &nbsp"Intentions" is a song jointly recorded and sung by Canadian pop singer Justin Bieber
            and
            American rap group migos member quavo. The single was released through universal records on February 14,
            2020
        </p>
        <br />
        <b id="Come Around Me">Come Around Me</b>
        <p>&nbsp &nbsp &nbsp"Come around me" is a song recorded and sung by Canadian pop male singer Justin Bieber.
            It
            is
            included in Justin Bieber's fifth studio album "changes", which is the third song in the album .The song
            is
            one
            of 17 songs from Justin Bieber's fifth studio album changes</p>
    </div>
</body>

</html>
