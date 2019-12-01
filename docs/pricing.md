# Towards an alternative model of pricing

I've long been interested in the rather fickle and unpredictable economics of independent game development and with Sutemi Productions, I'm seeking to explore a somewhat unconventional model for pricing and distribution. Before I explain the particular details, my three main goals with this model are to, in rough order of importance:

a) maximise net income based on holistic evaluation of multiple demographics across distribution platforms (sorry, this is just how things work in this world)

b) provide a low-cost, full-featured version of the game to those who are currently, for whatever reason, unable to pay the full price on Steam

c) encourage consumer participation and interest in alternative distribution platforms to Steam

Essentially, the game will release on three different platforms (w/ prices):

* Steam : $20USD
* itch.io : Pay-what-you-can
* GitHub: Full open-source

Each of these releases will be maintained as regularly as possible to ensure consistent content parity across all platforms. My reasoning for each individual platform follows below.

## Steam

I'll be honest: I fucking hate Steam. The backend distribution tools are a nightmare to work with, there's no meaningful content moderation for community features such as forums or reviews, and I strongly believe that Steam as a platform has, probably intentionally to some degree, significantly accelerated the race-to-the-bottom mentality of pricing which has devalued and continues to devalue in both a cultural and financial sense the work of most independent developers worldwide. On top of all that, the standardised store page UI absolutely fucking blows and it costs $100 just to register one's product on Steamworks.

Nevertheless, Steam represents the primary distribution platform for digital games globally and is generally the best place to sell a game with the intent of making money from it. Although I initially was very reluctant to even consider Steam as an option, I've ultimately decided to reach a compromise which I believe is fair. Based on both my personal philosophies and the [observations](https://drive.google.com/file/d/1W6lZir97bUU0KdvIGNIVWG0O-_A3QrdN/view) of [others](https://galyonk.in/the-indie-games-are-too-damn-cheap-11b8652fad16?gi=94d7c832b3f0) who have far more [experience](http://www.gamesindustry.biz/articles/2017-08-16-devolver-co-founder-relaunches-gambitious-as-good-shepherd) observing and studying the market behaviour of indie releases, I've come to the conclusion that $20 should be the base minimum price for basically *any* full-length (ie, not designed as a short one-off experience) commercial independent game with very few exceptions, regardless of intrinsic quality, length, or production value. 

> For all works distributed under Sutemi Productions meeting the above qualifications, the base price on Steam will be set at $20, and *this price will never decrease, either permanently or temporarily through a discount, sale, or bundle*.

This is to ensure a sense of commitment on the player's part, and to counteract any potential feelings of entitlement one may believe themselves to be deserving of relative to the work or its creator. I strongly believe that Steam is a luxury rather than a necessity, and that consequently, its conveniences should come at a cost. **What you are buying for when you purchase a game on Steam is not just the product, but the conveniences offered to the consumer** -- which oftentimes come at the detriment of the developer in the form of unintuitive interfaces, rigid market-driven design conformity, and severe lack of proper content moderation. 

## itch.io

itch.io is in many ways the antithesis of Steam: a lightweight, zero-cost distribution platform which offers a massive amount of expressive flexibility to developers, with what seems like a genuine focus on the needs and desires of independent developers. Although there are a variety of better alternatives to Steam, itch.io is easily my favourite as it grants me the greatest amount of control over my presence as a developer, allowing me near-total freedom in terms of what can and cannot appear on my store pages in terms of both design layout and moderation. Creating a new page for a project, uploading it, and updating it are incredibly straightforward, intuitive processes that don't require me to struggle with CLIs or app_ids vs content_ids, and when I'm ready to launch there's no lengthy and obscure approval process waiting for me.

On top of all this, itch.io offers an almost unparalleled financial flexibility: not only can I set the price to whatever I want any time I want, most importantly I can give players the option to pay whatever *they* want as well, which is essential to my philosophy of pricing. As someone who's had very little personal spending power almost my entire life, I know what it feels like to be interested in something, but unable to afford it; and the subsequent shame that comes with having to reckon with that in a practical and ethical (and let's not forget social...) sense. I don't really care why you can't afford my game at full price on Steam: whether it's because you're going through some kind of financial crisis this month, or you live in a country with a steep currency conversion rate, or, hell, maybe you just don't know enough about the game yet to feel confident dropping $20 on it... 

> Whatever your reason is, I will do my best to treat you in good faith by offering you the ability to play the entirety of my game via itch.io *at whatever price you feel comfortable with paying, even if it's nothing*.

Although I hope for both our sakes that your financial situation will improve enough or that you'll appreciate the experience enough to convince you that my work is worth purchasing at full price, whether via Steam or itch.io; at the end of the day, **the only thing I expect in exchange for my good faith as a developer is your good faith as a consumer: that you'll genuinely try your best to engage my work on its own terms before arriving at a conclusion about it, and that in discussions about or appraisals of it you'll speak with sincerity and good will rather than irony or malice.**

# GitHub

(This option is less directly applicable to most players and will mostly appeal to either fellow developers, or technical enthusiasts who are particularly interested in how certain things work within the game.)

I got my start in game development working off of an illegitimately decompiled (for better or worse, I was blissfully unaware of either the legal or ethical implications of my actions at the time) copy of a popular commercial game and much of what I currently know has been directly and irrevocably influenced by those experiences as a modder. It's with that in mind that I've decided to open-source as many projects released under Sutemi Productions as possible as open-source projects (I've yet to determine a specific license, I've been investigating the various options for some time now and will update this document once I arrive at a conclusion with which I'm fully comfortable).

In order to accomplish this, all development is being documented using the [MDMA](https://www.gamesasresearch.com/mdma) framework by Pippin Barr, Rilla Khaled and Jonathan Lessard, which offers a philosophy of design promoting transparency, growth over time, and continuous self-reflection. Documentation is split between each project's respective commit history (which will be made fully available shortly after release), and an ongoing [log[(https://spncryn.tumblr.com/), which I maintain daily.

> In fully open-sourcing my projects, I hope to provide first and foremost an exhaustive, full-length documentation of what it's like to develop a game over an extended time period; and second, a foundation from which other developers can build off or take where they see fit, whether in terms of specific technical issues/effects, or just in terms of inspiration. 

In terms of the former, for whatever reason, there still remains to this day a good amount of mystique surrounding certain development teams or developers which far more often than not work towards the detriment of many other developers, for reasons both predictable and otherwise. A whole lot of words get thrown around all the time, some good, some bad, all equally harmful and without meaning: "passion", "laziness", "greed", "ambition"... you know kinds of shit I'm talking about. Similarly I've observed a lot of resentment between developers and consumers online (some developers are definitely complicit in this as well, which is particularly shameful), which seems to result from a consistent tendency to dramatically underestimate the degree of labour involved in various implementations or processes, both technical and design-related. My goal is to help demystify the development process into very concrete, day-by-day and even moment-to-moment blocks of time, focusing not just on the technical dimensions of development but also the emotional and occasionally physical aspects as well, which are rarely presented as is, with proper frankness and directness.

In terms of the latter, I wish to extend as an act of good faith my trust to other developers who hopefully may be able to derive something meaningful or inspirational out of some aspect of my work, however obscure. I know I've certainly encountered in the past slices of someone's code or some implementation that've particularly impressed me to the point where I've found myself arriving at major revelations about my own work.

Lastly, by open-sourcing my work I effectively inoculate myself against having to deal with requests that I either have no interest in implementing or would take too much of my time and effort to justify attempting to implement them. Examples include translations, minor tweaks to mechanics, or technical adjustments for esoteric hardware (ie, if you can afford a 4k144hz curved 21.6" ultrawide monitor and my games for whatever reason aren't scaling properly, sorry, but that's your problem, not mine). In short, with the full source code being fully available, I can finally safely tell people to fuck off and do it themselves.

---

*Disclaimer: The information contained within this entry is accurate and relevant up to the date of the last recorded edit: 01 December 2019.*
