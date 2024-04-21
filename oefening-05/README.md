# 💻 08. API's uitlezen > oefening 05

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een API-sleutel voor toegang.

### Postman opstarten

 - Start Postman.

### authentificatie met api key

 - [API: News API](https://newsapi.org)
 - endpoint: /top-headlines

---

1. Maak een nieuw verzoek naar de API.
2. Gebruik de endpoint /top-headlines.
3. Voeg een X-Api-Key header toe met je API-sleutel.
4. Voer het verzoek uit en bekijk de respons.
https://newsapi.org/v2/top-headlines?country=us

value = 096644e47d1b4796854acb6ffa10b9b1

key = X-Api-Key{
    



    {
    "status": "ok",
    "totalResults": 34,
    "articles": [
        {
            "source": {
                "id": null,
                "name": "KABC-TV"
            },
            "author": null,
            "title": "USC cancels outside commencement speakers after valedictorian controversy - KABC-TV",
            "description": "Among those who had been slated to speak at USC were tennis legend Billie Jean King and filmmaker Jon M. Chu (\"Crazy Rich Asians\").",
            "url": "https://abc7.com/videoClip/14699561/",
            "urlToImage": "https://cdn.abcotvs.com/dip/images/14699560_041924-kabc-11pm-usc-commencement-vid.jpg?w=1600",
            "publishedAt": "2024-04-20T07:42:37Z",
            "content": "Woman found dead in trash bin in Sunland identified"
        },
        {
            "source": {
                "id": null,
                "name": "Sacramento Bee"
            },
            "author": "Sacramento Bee",
            "title": "Over and out: Play-in loss to New Orleans Pelicans costs Sacramento Kings trip to playoffs - Sacramento Bee",
            "description": null,
            "url": "https://www.sacbee.com/sports/nba/sacramento-kings/article287852700.html",
            "urlToImage": null,
            "publishedAt": "2024-04-20T07:36:59Z",
            "content": null
        },
        {
            "source": {
                "id": "axios",
                "name": "Axios"
            },
            "author": "Axios",
            "title": "Title IX : Biden expands protections for LGBTQ+ students - Axios",
            "description": null,
            "url": "https://www.axios.com/2024/04/19/biden-lgbtq-title-ix-changes-rules-protection-trans",
            "urlToImage": null,
            "publishedAt": "2024-04-20T05:50:27Z",
            "content": null
        },
        {
            "source": {
                "id": "associated-press",
                "name": "Associated Press"
            },
            "author": "FARNOUSH AMIRI, MARY CLARE JALONICK",
            "title": "Senate passes reauthorization of key US surveillance program after midnight deadline - The Associated Press",
            "description": "The Senate has voted to reauthorize a key U.S. surveillance law after divisions over whether the FBI should be restricted from using the program to search for Americans’ data nearly forced the statute to lapse. The legislation approved 60-34 with bipartisan s…",
            "url": "https://apnews.com/article/fisa-donald-trump-surveillance-congress-johnson-81e991c9f82e77b2fe13f8a3e0e25349",
            "urlToImage": "https://dims.apnews.com/dims4/default/08b2cc0/2147483647/strip/true/crop/7000x3937+0+364/resize/1440x810!/quality/90/?url=https%3A%2F%2Fassets.apnews.com%2Ffc%2F52%2F4dcb1ac3e5299758db4926fac6f3%2Fbfe855f61039478c93033cc058878295",
            "publishedAt": "2024-04-20T05:30:00Z",
            "content": "WASHINGTON (AP) After its midnight deadline, the Senate voted early Saturday to reauthorize a key U.S. surveillance law after divisions over whether the FBI should be restricted from using the progra… [+5559 chars]"
        },
        {
            "source": {
                "id": "associated-press",
                "name": "Associated Press"
            },
            "author": "ELLEN KNICKMEYER",
            "title": "Israel and Iran's apparent strikes and counterstrikes give new insights into both militaries - The Associated Press",
            "description": "This month’s unprecedented direct attacks between Iran and Israel are revealing deeper insights into both militaries. Experts say Friday’s apparent precision strike by Israel deep into Iran demonstrated Israel’s military dominance on almost all fronts. Israel…",
            "url": "https://apnews.com/article/israel-iran-missiles-war-hezbollah-fdc927f764375fabf88041f5a63f3e0f",
            "urlToImage": "https://dims.apnews.com/dims4/default/3b7f4a4/2147483647/strip/true/crop/4500x2531+0+229/resize/1440x810!/quality/90/?url=https%3A%2F%2Fassets.apnews.com%2F23%2F31%2F758c11f129ae22b1b7af509fa6cd%2F0afb8bf42903465c9eee0cafae235ac4",
            "publishedAt": "2024-04-20T04:39:00Z",
            "content": "WASHINGTON (AP) Israel demonstrated its military dominance over adversary Iran in its apparent precision strikes that hit near military and nuclear targets deep in the heart of the country, meeting l… [+6235 chars]"
        },
        {
            "source": {
                "id": "associated-press",
                "name": "Associated Press"
            },
            "author": "TOM KRISHER, KRISTIN M. HALL",
            "title": "Tennessee Volkswagen employees overwhelmingly vote to join United Auto Workers union - The Associated Press",
            "description": "Employees at a Volkswagen factory in Chattanooga, Tennessee, have voted overwhelmingly in favor of joining the United Auto Workers union, boosting the UAW's nationwide effort to organize nonunion factories. The union wound up getting 73% of the ballots cast i…",
            "url": "https://apnews.com/article/volkswagen-union-vote-united-auto-workers-chattanooga-51544590d8a06efddfa2f6ac7db00fbe",
            "urlToImage": "https://dims.apnews.com/dims4/default/d618f9d/2147483647/strip/true/crop/4500x2531+0+234/resize/1440x810!/quality/90/?url=https%3A%2F%2Fassets.apnews.com%2Fbe%2F9c%2Faf38a82cacd27f1a2f32e18a63dc%2Ff12ff2331c174ffe917eed91a632557c",
            "publishedAt": "2024-04-20T04:37:00Z",
            "content": "CHATTANOOGA, Tenn. (AP) Employees at a Volkswagen factory in Chattanooga, Tennessee, overwhelmingly voted to join the United Auto Workers union Friday in a historic first test of the UAWs renewed eff… [+6174 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "BBC News"
            },
            "author": null,
            "title": "Taylor Swift: How The Tortured Poets Department captured modern dating despair - BBC.com",
            "description": "From partners who wasted our time, to comfort-eating after a breakup. We've all been there and so has Swift.",
            "url": "https://www.bbc.com/news/entertainment-arts-68856232",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/E5FC/production/_133167885_swiftd25aae345df60fae3730067b3d9205cd144d41ff.jpg",
            "publishedAt": "2024-04-20T04:24:59Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Deadline"
            },
            "author": "Dominic Patten, Ted Johnson, Greg Evans",
            "title": "Man Who Set Himself On Fire Outside Trump NYC Trial Dies In Hospital; Self-Immolation Captured On CNN In Real Time – Update - Deadline",
            "description": "The \"independent researcher\" who set himself ablaze in Manhattan did not violate security zone around ex-POTUS trial, police say",
            "url": "http://deadline.com/2024/04/fire-trump-trial-1235890365/",
            "urlToImage": "https://deadline.com/wp-content/uploads/2024/04/Max-Azzarello-Getty-April-18.jpeg?w=1024",
            "publishedAt": "2024-04-20T03:59:00Z",
            "content": "2nd UPDATE, 8:59 PM: Approximately 10 hours after Max Azzarello set himself on fire across the street from Donald Trump‘s criminal trial in Manhattan, the 37-year-old man has died. \r\nAzzarello passed… [+5586 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Cointelegraph"
            },
            "author": "Cointelegraph",
            "title": "Bitcoin users spend record $2.4M in fees on halving block - Cointelegraph",
            "description": null,
            "url": "https://cointelegraph.com/news/bitcoin-halving-users-spend-record-millions-block-space-runes-rare-satoshis",
            "urlToImage": null,
            "publishedAt": "2024-04-20T02:16:53Z",
            "content": null
        },
        {
            "source": {
                "id": "fox-news",
                "name": "Fox News"
            },
            "author": "Charles Creitz",
            "title": "Anti-Israel Columbia student protesters stonewall, directing Fox News reporter to 'media team' - Fox News",
            "description": "Anti-Israel protesters at Columbia University in New York City refused to be interviewed by Fox News unless filming was halted and a \"media team\" was called.",
            "url": "https://www.foxnews.com/media/anti-israel-columbia-students-stonewall-fox-news-directing-fox-news-reporter-media-team",
            "urlToImage": "https://static.foxnews.com/foxnews.com/content/uploads/2024/04/Columbia-University-NYPD-Israel-Palestine-Protests-NYC_34_1.jpg",
            "publishedAt": "2024-04-20T01:51:00Z",
            "content": "When Fox News correspondent CB Cotton attempted to interview some of the anti-Israel protesters milling about on Columbia University's campus in Upper Manhattan, she was confronted and told to speak … [+2999 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Eonline.com"
            },
            "author": "Gabrielle Chung",
            "title": "Morgan Wallen Breaks Silence on Arrest Over Alleged Chair-Throwing Incident - E! Online - E! NEWS",
            "description": "Morgan Wallen addressed his recent arrest in Nashville, where he was charged with reckless endangerment and disorderly conduct for allegedly throwing a chair off a rooftop bar.",
            "url": "https://www.eonline.com/news/1399851/morgan-wallen-breaks-silence-on-arrest-over-alleged-chair-throwing-incident",
            "urlToImage": "https://akns-images.eonline.com/eol_images/Entire_Site/2024319/cr_1200x1200-240419180004-GettyImages-1783043278.jpg?fit=around%7C1080:1080&output-quality=90&crop=1080:1080;center,top",
            "publishedAt": "2024-04-20T01:40:00Z",
            "content": "Morgan Wallen is taking accountability in his arrest.\r\nNearly two weeks after he was booked on reckless endangerment and disorderly conduct charges in Nashville for allegedly throwing a chair off the… [+839 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Yahoo Entertainment"
            },
            "author": null,
            "title": "Musk's India Trip May See Breakthroughs for Starlink, Tesla - Yahoo Finance",
            "description": null,
            "url": "https://finance.yahoo.com/news/musk-india-trip-may-see-013123465.html",
            "urlToImage": null,
            "publishedAt": "2024-04-20T01:31:00Z",
            "content": "If you click 'Accept all', we and our partners, including 238 who are part of the IAB Transparency &amp; Consent Framework, will also store and/or access information on a device (in other words, use … [+678 chars]"
        },
        {
            "source": {
                "id": "fox-news",
                "name": "Fox News"
            },
            "author": "Brie Stimson",
            "title": "Chinese hackers preparing to ‘physically wreak havoc’ on US critical infrastructure: FBI director - Fox News",
            "description": "Chinese hackers who have gained access to critical American infrastructure systems plan to \"wreak havoc\" on them with the intention of inducing \"panic,\" the FBI director said this week.",
            "url": "https://www.foxnews.com/politics/chinese-hackers-preparing-physically-wreak-havoc-us-critical-infrastructure-fbi-director",
            "urlToImage": "https://static.foxnews.com/foxnews.com/content/uploads/2024/04/christopher-wray-scaled.jpg",
            "publishedAt": "2024-04-20T01:30:00Z",
            "content": "Chinese hackers are developing the \"ability to physically wreak havoc on our critical infrastructure at a time of its choosing,\" FBI director Christopher Wray said this week.\r\nHe added that the hacke… [+2486 chars]"
        },
        {
            "source": {
                "id": "usa-today",
                "name": "USA Today"
            },
            "author": "Ayrton Ostly",
            "title": "NFL mock draft: Vikings trade up for QB, Bills move up for WR in latest predictions - USA TODAY",
            "description": "There's less than a week until the 2024 NFL mock draft and USA Today's draft experts predict chaos in Round 1. Here's what they think will happen.",
            "url": "https://www.usatoday.com/story/sports/nfl/2024/04/19/nfl-mock-draft-2024-round-1-trades-qb/73386874007/",
            "urlToImage": "https://www.usatoday.com/gcdn/authoring/authoring-images/2024/04/17/USAT/73361428007-2024-nf-ldrafttopper-v-2.jpg?crop=9053,5095,x0,y391&width=3200&height=1801&format=pjpg&auto=webp",
            "publishedAt": "2024-04-20T01:11:50Z",
            "content": "The 2024 NFL Draft is almost here. In less than a week, hundreds of former college football players will live out their dreams at the highest level of the sport. Team officials will make key decision… [+36118 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "[Removed]"
            },
            "author": null,
            "title": "[Removed]",
            "description": "[Removed]",
            "url": "https://removed.com",
            "urlToImage": null,
            "publishedAt": "1970-01-01T00:00:00Z",
            "content": "[Removed]"
        },
        {
            "source": {
                "id": null,
                "name": "BBC News"
            },
            "author": null,
            "title": "What we know about Israel's missile attack on Iran - BBC.com",
            "description": "There are competing claims about the scale of Friday's attack on the Isfahan region.",
            "url": "https://www.bbc.com/news/world-middle-east-68853402",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/4360/production/_133184271_6f488fd5-acf8-49b2-a325-b0a5cab8a0fa.jpg",
            "publishedAt": "2024-04-19T23:40:15Z",
            "content": null
        },
        {
            "source": {
                "id": "cnn",
                "name": "CNN"
            },
            "author": "Michael Rios",
            "title": "Dengue cases top 5.2 million in the Americas as outbreak passes yearly record, PAHO says - CNN",
            "description": "Dengue cases are surging in the Americas, with cases reported topping 5.2 million as of this week, surpassing a yearly record set in 2023, according to the Pan American Health Organization (PAHO).",
            "url": "https://www.cnn.com/2024/04/19/americas/americas-record-dengue-cases-paho-intl-latam/index.html",
            "urlToImage": "https://media.cnn.com/api/v1/images/stellar/prod/ap24096501069945.jpg?c=16x9&q=w_800,c_fill",
            "publishedAt": "2024-04-19T22:40:00Z",
            "content": "Dengue cases are surging in the Americas, with cases reported topping 5.2 million as of this week, surpassing a yearly record set in 2023, according to the Pan American Health Organization (PAHO).\r\nP… [+3369 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "[Removed]"
            },
            "author": null,
            "title": "[Removed]",
            "description": "[Removed]",
            "url": "https://removed.com",
            "urlToImage": null,
            "publishedAt": "1970-01-01T00:00:00Z",
            "content": "[Removed]"
        },
        {
            "source": {
                "id": "bleacher-report",
                "name": "Bleacher Report"
            },
            "author": "zach bachar",
            "title": "Schefter: Jayden Daniels Has 'An Interest' in Being Drafted By Non-Commanders Team - Bleacher Report",
            "description": "Former LSU quarterback Jayden Daniels doesn't appear to be enthused about potentially getting selected by the Washington Commanders in the 2024 NFL draft.…",
            "url": "https://bleacherreport.com/articles/10117707-schefter-jayden-daniels-has-an-interest-in-being-drafted-by-non-commanders-team",
            "urlToImage": "https://media.bleacherreport.com/image/upload/c_fill,g_faces,w_3800,h_2000,q_95/v1713561550/tyijfvnkqcitisy4alxh.jpg",
            "publishedAt": "2024-04-19T21:46:21Z",
            "content": "Michael Hickey/Getty Images\r\nFormer LSU quarterback Jayden Daniels doesn't appear to be enthused about potentially getting selected by the Washington Commanders in the 2024 NFL draft.\r\nESPN's Adam Sc… [+2843 chars]"
        },
        {
            "source": {
                "id": "usa-today",
                "name": "USA Today"
            },
            "author": "Anthony Robledo",
            "title": "'Pulp Fiction' reunion: Travolta, Thurman, Jackson mark 30 years - USA TODAY",
            "description": "John Travolta, Samuel L. Jackson, Harvey Keitel and Uma Thurman reunited to celebrate the 30 years of their cinematic triumph \"Pulp Fiction.\"",
            "url": "https://www.usatoday.com/story/entertainment/movies/2024/04/19/pulp-fiction-30th-anniversary-reunion/73387378007/",
            "urlToImage": "https://www.usatoday.com/gcdn/authoring/authoring-images/2024/04/19/USAT/73387872007-pulp-fiction-reunion.jpg?crop=3275,1842,x0,y0&width=3200&height=1800&format=pjpg&auto=webp",
            "publishedAt": "2024-04-19T21:34:10Z",
            "content": "John Travolta, Samuel L. Jackson and Uma Thurman and Harvey Keitel reunited to celebrate the 30 year-anniversary of their cinematic triumph, \"Pulp Fiction.\"\r\nThe stars attended a screening of Quentin… [+2591 chars]"
        }
    ]
}