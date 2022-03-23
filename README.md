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
- [Terms of Service](#terms-of-service)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Links

* [INVITE THE BOT TO YOUR SERVER](https://discord.com/api/oauth2/authorize?client_id=795063486988156958&permissions=2147609664&scope=bot)
* [JOIN THE BOTS SUPPORT & DEV SERVER](https://discord.gg/hq8VPdjFPb)
* The bot is not currently open source, but if it is in the future - it'll be here.

## **Introduction**

@AsterieBot is a divination-focused bot, specialising in providing in-depth meanings and explanation behind the cards (tarot, oracle, and lenormand), runes, and other divinatory systems it's capable of.

Asterie is the only Tarot bot on discord that allows you to choose between 1) long, detailed descriptions, 2) short, easier to read descriptions or, 3) keyword-only tarot pulls. The bot has a wide variety of decks and multiple rune sets, as well as an 8-Ball command, hieroglyphic divination, daily horoscopes (with multiple horoscope providers), astrology & tarot memes, & other misc commands.

I will always strive to add more decks (tarot, oracle, lenormand, etc), if possible more runic systems, and other divinatory systems (e.g hieroglyphic divination, ancient greek letter divination, i-ching, etc). This is a time consuming task but the bot is a long-term project that will be continually added to.

## **Key Features**

* In-depth Tarot, lenormand, and oracle card divination
* Customisable tarot details - choose between long, short, or keyword-only tarot pulls.
* In-depth runic divination, with multiple rune sets
* A growing list of decks to choose from
* Deck customizability: curate your own favourites list, ban decks from appearing (either for yourself or for your server)
* Ability to search for individual cards along with their full detailed descriptions (useful for study groups, or if you need a reminder, or during specific-card discussions!)
* Astrology & tarot memes
* In-depth horoscope feature, with multiple horoscope providers.
* Standard 8-ball & a more fun version
* Unique divination systems (greek letter, hiroglyphic)
* Misc fun commands such as random quotes, jokes, compliment other users, yes/no coinflips, a choose command, etc
* Customizable bot prefix. Users can also customize the level of detail they receive on tarot/rune readings and horoscopes. Mods can also turn off the full-embed details completely in certain channels
* Fully supported /slash commands
* Maintained [support server](https://discord.gg/hq8VPdjFPb) so you can get help if you need it


## **Demo**

[Video Demonstration](https://vimeo.com/537121128)

---
# **Sample Commands**

(note: slash commands are also supported. You can use slash commands by typing `/`, instead of `@AsterieBot#7609 `, and a list of them should pop up explaining what they do and how to use them)

Command Name (`[]` = replace with answer) | What it does
-----------------------------------------|------------
`@AsterieBot#7609 8ball` | Simple command that outputs an answer from a Magic-8 Ball. There's also a more 'fun' sub-command ;)
`@AsterieBot#7609 astrology [sign]` | Horoscopes!
`@AsterieBot#7609 astromeme` | Astrology memes!
`@AsterieBot#7609 cardsearch [deck] [cardname]` | Search for a specific card!
`@AsterieBot#7609 choose [option 1], [option 2], [option 3]` | Asterie will pick one of your specified options for you
`@AsterieBot#7609 compliment [@user]` | Compliment your fellow discorders!
`@AsterieBot#7609 greekoracle` | A unique divination system based on greek letters.
`@AsterieBot#7609 hieroglyphics` | A unique divination system based on Egyptian hieroglyphics
`@AsterieBot#7609 joke` | Asterie's capable of giving out simple jokes :)
`@AsterieBot#7609 runes [rune_set]` | This command is used for runic divination. You can either choose a rune set directly, or use `random`. You can also optionally pull up-to four runes.
`@AsterieBot#7609 tarot [deck]` | This command is used for cartomancy with Tarot, lenormand, or oracle decks. It gives you various options on how many cards you wish to pull, what deck you wish to pull, or what type of random deck you want.
`@AsterieBot#7609 tarotmeme` | Tarot memes!

# FAQ

## FAQ 1: GENERAL

**What's the primary goal/purpose of @AsterieBot?**

~~to go where no man has gone before~~ Asterie's goal is pretty simple: make divination accessible (without oversimplifying) and fun - her divination commands therefore contain plenty of detail about the cards, runes, etc it pulls. There are - of course - also other fun commands, such as memes (`@AsterieBot#7609 astromeme` or `/astromeme`) or jokes (`@AsterieBot#7609 joke` or `/joke`), etc.

**What permissions does the bot require? Is it dangerous?**

The bot requires `read messages`, `send messages`, `embed link`, `attach files`, and `add reactions` permissions. These permissions don't allow the bot to do anything damaging to your server - it only allows the bot to read and send messages, send embed messages (many commands use embeds), attach files (e.g images, which many commands use), and add emoji reactions. Removing these permissions may break important functionality.

**Does the bot have slash commands?**

Yes it does! Type `/` to view them. Slash commands are an alternative and simpler way of interacting with bots, as opposed to using a bots message prefix (e.g `/tarot pull` instead of `@AsterieBot#7609 tarot`).

**I don't see slash commands in my server?**

Try re-inviting the bot with this link https://discord.com/api/oauth2/authorize?client_id=795063486988156958&permissions=277025516608&scope=bot%20applications.commands (you should see this https://i.imgur.com/0rHELKG.png first, which allows the bot to use slash in your server).

**Is there any functional difference between "message" and "slash commands"**

From a practical standpoint, slash commands are probably more user-friendly and easy to use.

I tried to make them as similar to the normal, "message" commands as possible but some differences were needed. For example, instead of using `@AsterieBot#7609 deckban` to ban a deck, you'd have to use `/tarot ban`. To pull a card, you'd use `/tarot pull` instead of just `/tarot`, etc.

**Does the bot do runes?**

Yes, type `@AsterieBot#7609 rune list` or `/runes list`

**Does the bot do horoscopes?**

Yes, type `@AsterieBot#7609 astrology` or `/astrology` 

I also support Chinese horoscopes via the `astrochina` command!

## FAQ 2: TAROT FAQ

**What kinds of decks does the bot have?**

The bot has tarot, lenormand, and oracle decks. Type `@AsterieBot#7609 tarot list` or `/tarot list`

**I like tarot/runes, but I don't need a large embed of details**

You're in luck! You can use the `-noembed` setting to display a simpler output with just keywords, e.g `@AsterieBot#7609 tarot rand -noembed`. You can also turn `-noembed` on as your default by using `@AsterieBot#7609 tarot detailset` It also supports short descriptions+keywords with the `-short` tag (e.g `@AsterieBot#7609 tarot rand -short`), which can also be set as your default via the `detailset`  command (note: this is simpler if you use `/` slash commands, as you can simply click on the detail option instead of manually typing it)

If you're a mod in your server, you can also force-disable full embeds in particular channels via the `detailset` command.

**What if I want to search for a specific card?**

By nature, the bot is educational - it displays a healthy amount of information about the cards it pulls, and is therefore accessible to beginners who may not be familiar with the ins and outs of particular cards - or simply as a refresher for those that are.

But what if you've drawn a card in real life, but lack the booklet for it? What if you're in a discussion about a particular card? What if you have a tarot study group?

This is where the `@AsterieBot#7609 cardsearch` or `/cardsearch` command comes in - you can pull a specific card and it will display detailed information about said card, e.g `@AsterieBot#7609 cardsearch randt fool` - search for a random tarot deck, for the 'Fool' card.

**How do I draw a card**

`@AsterieBot#7609 tarot rand` or `/tarot pull deck:rand` for a random card from a random deck 
`@AsterieBot#7609 tarot whimsical` or `/tarot pull deck:whimsical` - input the deckname to get a random card from your specified deck - in this case, Whimsical Tarot.
`@AsterieBot#7609 tarot urw 3` or `/tarot pull deck:urw num:3`- input a number (Up-to 4) to draw more than one card

**Can I ban a deck?**

Yes - see `@AsterieBot#7609 help deckban`. You can ban decks from appearing during random pulls, or - if you're a mod - you can ban decks from your entire server for everyone

**Can I create a list of favourite decks to pull from?**

Yes! See `@AsterieBot#7609 help tarot` - you can use the `addfaves` subcommand to create a list of decks that are your 'faves'. You can then pull cards from these decks via `@AsterieBot#7609 tarot fave`. E.g, `@AsterieBot#7609 tarot addfave urw rrw` would add the URW and RRW decks to my fave list.

# Privacy Policy

The only data stored in the bot is 1) Name/id of the servers that the bot is in 2) the bot's prefix in a server 3) user bot settings, such as your tarot embed setting, along with discord ID's associated with these settings. Servers are removed from the database once the bot leaves the server.
None of this is ever shared with anybody other than the sole bot owner (who can be contacted via the support server https://discord.gg/hq8VPdjFPb).

# Terms of Service

1) Don't use the bot to violate Discords ToS or Community Guidelines.
2) Your access to the bot may be removed at any point. Likewise, features may be added, removed, changed at the whim of the creator.
