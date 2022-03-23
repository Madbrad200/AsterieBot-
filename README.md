<a href="https://www.buymeacoffee.com/AsterieBot"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=AsterieBot&button_colour=5F7FFF&font_colour=ffffff&font_family=Cookie&outline_colour=000000&coffee_colour=FFDD00"></a>

# AsterieBot

- [Links](#links)
- [**Introduction**](#introduction)
- [**Key Features**](#key-features)
  * Demo
- [**Sample Commands**](#sample-commands)
- [FAQ](#faq)
  * FAQ 1: GENERAL
  * FAQ 2: TAROT FAQ
- [Privacy Policy](#privacy-policy)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Links

* [INVITE THE BOT TO YOUR SERVER](https://discord.com/api/oauth2/authorize?client_id=795063486988156958&permissions=2147609664&scope=bot)
* [JOIN THE BOTS SUPPORT & DEV SERVER](https://discord.gg/hq8VPdjFPb)
* The bot is not currently open source, but if it is in the future - it'll be here.

## **Introduction**

@AsterieBot is primarily a divination-focused bot, specialising in providing in-depth meanings and explanations behind the cards, runes, and other divinatory systems it’s capable of. It doesn’t just pull, say, a tarot card - rather, it will pull a Tarot card and provide keywords, the card image (including possible reversals), and a description - enough to give you a healthy understanding. The bot has a wide variety of decks and multiple rune sets, as well as an 8-Ball command, hieroglyphic divination, daily horoscopes, astrology & tarot memes, & other misc commands.

I will always strive to add more decks (tarot, oracle, lenormand, etc), if possible more runic systems, and other divinatory systems (e.g hieroglyphic divination, ancient greek letter divination, i-ching, etc). This is a time consuming task but the bot is a long-term project that will be continually added to.

## **Key Features**

* In-depth Tarot, lenormand, and oracle card divination
* In-depth runic divination, with multiple rune sets
* A growing list of decks to choose from
* Astrology & tarot memes
* In-depth horoscope feature
* Standard 8-ball & a more fun version
* Unique divination systems (greek letter, hiroglyphic)
* Ability to search for individual cards along with their full detailed descriptions (useful for study groups, or if you need a reminder, or during specific-card discussions!)
* Misc fun commands such as random quotes, jokes, compliment other users, yes/no coinflips, a choose command, etc


* Customizable bot prefix. Users can also customize the level of detail they receive on tarot/rune readings and horoscopes. Mods can also turn off the full-embed details completely in certain channels.
* Maintained [support server](https://discord.gg/hq8VPdjFPb) so you can get help if you need it


## **Demo**

[Video Demonstration](https://vimeo.com/537121128)

---
# **Sample Commands**

Command Name (`[]` = replace with answer) | What it does
-----------------------------------------|------------
`?8ball` | Simple command that outputs an answer from a Magic-8 Ball. There's also a more 'fun' sub-command ;)
`?astrology [sign]` | Horoscopes!
`?astromeme` | Astrology memes!
`?cardsearch [deck] [cardname]` | Search for a specific card!
`?choose [option 1], [option 2], [option 3]` | Asterie will pick one of your specified options for you
`?compliment [@user]` | Compliment your fellow discorders!
`?greekoracle` | A unique divination system based on greek letters.
`?hieroglyphics` | A unique divination system based on Egyptian hieroglyphics
`?joke` | Asterie's capable of giving out simple jokes :)
`?runes [rune_set]` | This command is used for runic divination. You can either choose a rune set directly, or use `random`. You can also optionally pull up-to four runes.
`?tarot [deck]` | This command is used for cartomancy with Tarot, lenormand, or oracle decks. It gives you various options on how many cards you wish to pull, what deck you wish to pull, or what type of random deck you want.
`?tarotmeme` | Tarot memes!

# FAQ

## FAQ 1: GENERAL

**What's the primary goal/purpose of @AsterieBot?**

~~to go where no man has gone before~~ Asterie's goal is pretty simple: make divination accessible (without oversimplifying) and fun  - her divination commands therefore contain plenty of detail about the cards, runes, etc it pulls. There are - of course - also other fun commands, such as memes (?astromeme) or discussion starters (?discuss), etc.

**What permissions does the bot require? Is it dangerous?**

The bot requires read messages, send messages, embed link, attach files, and add reactions permissions. These permissions don't allow the bot to do anything damaging to your server - it only allows the bot to read and send messages, send embed messages (many commands use embeds), attach files (e.g images, which many commands use), and add emoji reactions (a couple commands, e.g `?astromeme`, use reactions). Removing these permissions may break important functionality.

**Does the bot do runes?**

Yes, see `?rune list` - there are a variety of rune sets

**Does the bot do horoscopes?**

Yes, see ?astrology - also provides lucky time, feeling, colour, & info about mercury retrograde.

## FAQ 2: TAROT FAQ

**What kinds of decks does the bot have?**

The bot has tarot, lenormand, and oracle decks. See `?tarot list` - this is continually being added to.

**I like tarot/runes, but I don't need a large embed of details**

You're in luck!  You can use the `-noembed` setting to display a simpler output with just keywords, e.g `?tarot rand -noembed`. You can also turn `-noembed` on as your default by using `?tarot embedset noembed` (now, using `?tarot` will display the noembed mode by default).

If you're a mod in your server, you can also force-disable full embeds in particular channels - `?tarot embedset noembed [#channelname]`

**What if I want to search for a specific card?**

By nature, the bot is educational  - it displays a healthy amount of information about the cards it pulls, and is therefore accessible to beginners who may not be familiar with the ins and outs of particular cards - or simply as a refresher for those that are.

But what if you've drawn a card in real life, but lack the booklet for it? What if you're in a discussion about a particular card? What if you have a tarot study group?

This is where `?cardsearch` comes in - you can pull a specific card and it will display detailed information about said card, `?cardsearch randt fool` - search for a random tarot deck, for the 'Fool' card.

**How do I draw a card**

?tarot rand for a random card from a random deck  
?tarot rand 3 - input a number (Up-to 4) to draw more than one card

You can also call a specific deck if you wish.

**Can I ban a deck?**

Yes - see `?help deckban`. You can ban decks from appearing during random pulls, or - if you're a mod - you can ban decks from your entire server for everyone

**Can I create a list of favourite decks to pull from?**

Yes! See `?help tarot` - you can use the `addfaves` subcommand to create a list of decks that are your 'faves'. You can then pull cards from these decks via `?tarot fave`

# Privacy Policy

The only data stored in the bot is 1) Name/id of the servers that the bot is in 2) the bot's prefix in a server 3) user bot settings, such as your tarot embed setting, along with discord ID's associated with these settings. Servers are removed from the database once the bot leaves the server.
None of this is ever shared with anybody other than the sole bot owner (who can be contacted via the support server https://discord.gg/hq8VPdjFPb).
