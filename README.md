[![Logo Image](https://cdn.pterodactyl.io/logos/new/pterodactyl_logo.png)](https://pterodactyl.io)

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/pterodactyl/panel/tests?label=Tests&style=for-the-badge)
![Discord](https://img.shields.io/discord/122900397965705216?label=Discord&logo=Discord&logoColor=white&style=for-the-badge)
![GitHub Releases](https://img.shields.io/github/downloads/pterodactyl/panel/latest/total?style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/pterodactyl/panel?style=for-the-badge)

# Modified By Marije
This is a modified install of pterodactyl. This is an install i use personally but i dont mind it being open source so therefore it is publically avalible. Currently only mild visual changes are being made so i dont have to apply them every time i update my server using this package.

If you are looking for the official pterodactyl panel install please head over to https://github.com/pterodactyl/panel instead.

Current planned features for this fork:
* Plugin manager connected to the panel
* Permission manager via LuckPerms intergrated into the panel
* Server statistics visible in the panel
* Clustered minecraft server (for scalable instances like minigames, lobbies and whatever else you can think of)
* More native support for other installs i prioritize (discord bots, valheim, rust)
* automatic port forwarding in the firewall/(router?)
* DNS management
* Possibly support for website hosting or specific types of websites such as nextcloud
* Whatever else i want to add to the panel

Overall this install of pterodactyl will be more focussed on big public servers that mostly run minigames.
Since i am a team of 1 and a beginner programmer (but a fast learner) it might take a while to implement these features. Feel free to collaborate or do other suggestions that could be useful in this install

I am aware there are paid options that add some of these features but i find them to often be overpriced and i want to offer a free option and mabye even a better option.

# Pterodactyl Panel
Pterodactyl is an open-source game server management panel built with PHP 7, React, and Go. Designed with security 
in mind, Pterodactyl runs all game servers in isolated Docker containers while exposing a beautiful and intuitive
UI to end users.

Stop settling for less. Make game servers a first class citizen on your platform.

![Image](https://cdn.pterodactyl.io/site-assets/pterodactyl_v1_demo.gif)

## Sponsors
I would like to extend my sincere thanks to the following sponsors for helping fund Pterodactyl's developement.
[Interested in becoming a sponsor?](https://github.com/sponsors/DaneEveritt)

| Company | About |
| ------- | ----- |
| [**WISP**](https://wisp.gg) | Extra features. |
| [**MixmlHosting**](https://mixmlhosting.com) | MixmlHosting provides high quality Virtual Private Servers along with game servers, all at a affordable price. |
| [**BisectHosting**](https://www.bisecthosting.com/) | BisectHosting provides Minecraft, Valheim and other server hosting services with the highest reliability and lightning fast support since 2012. |
| [**Bloom.host**](https://bloom.host) | Bloom.host offers dedicated core VPS and Minecraft hosting with Ryzen 9 processors. With owned-hardware, we offer truly unbeatable prices on high-performance hosting. |
| [**MineStrator**](https://minestrator.com/) | Looking for a French highend hosting company for you minecraft server? More than 14,000 members on our discord, trust us. |
| [**DedicatedMC**](https://dedicatedmc.io/) | DedicatedMC provides Raw Power hosting at affordable pricing, making sure to never compromise on your performance and giving you the best performance money can buy. |
| [**Skynode**](https://www.skynode.pro/) | Skynode provides blazing fast game servers along with a top-notch user experience. Whatever our clients are looking for, we're able to provide it! |
| [**XCORE**](https://xcore-server.de/) | XCORE offers High-End Servers for hosting and gaming since 2012. Fast, excellent and well-known for eSports Gaming. |
| [**RoyaleHosting**](https://royalehosting.net/) | Build your dreams and deploy them with RoyaleHosting’s reliable servers and network. Easy to use, provisioned in a couple of minutes. |
| [**Spill Hosting**](https://spillhosting.no/) | Spill Hosting is a Norwegian hosting service, which aims for inexpensive services on quality servers. Premium i9-9900K processors will run your game like a dream. |
| [**DeinServerHost**](https://deinserverhost.de/) | DeinServerHost offers Dedicated, vps and Gameservers for many popular Games like Minecraft and Rust in Germany since 2013. |
| [**HostBend**](https://hostbend.com/) | HostBend offers a variety of solutions for developers, students, and others who have a tight budget but don't want to compromise quality and support. |
| [**Capitol Hosting Solutions**](https://capitolsolutions.cloud/) | CHS is *the* budget friendly hosting company for Australian and American gamers, offering a variety of plans from Web Hosting to Game Servers; Custom Solutions too! |
| [**ByteAnia**](https://byteania.com/?utm_source=pterodactyl) | ByteAnia offers the best performing and most affordable **Ryzen 5000 Series hosting** on the market for *unbeatable prices*! |
| [**Aussie Server Hosts**](https://aussieserverhosts.com/) | No frills Australian Owned and operated High Performance Server hosting for some of the most demanding games serving Australia and New Zealand. |
| [**VibeGAMES**](https://vibegames.net/) | VibeGAMES is a game server provider that specializes in DDOS protection for the games we offer. We have multiple locations in the US, Brazil, France, Germany, Singapore, Australia and South Africa.|

## Documentation
* [Panel Documentation](https://pterodactyl.io/panel/1.0/getting_started.html)
* [Wings Documentation](https://pterodactyl.io/wings/1.0/installing.html)
* [Community Guides](https://pterodactyl.io/community/about.html)
* Or, get additional help [via Discord](https://discord.gg/pterodactyl)

### Supported Games
We support a huge variety of games by utilizing Docker containers to isolate each instance, giving you the power to
host your games across the world without having to bloat each physical machine with additional dependencies.

Some of our core supported games include:

* Minecraft — including Paper, Sponge, Bungeecord, Waterfall, and more
* Rust
* Terraria
* Teamspeak
* Mumble
* Team Fortress 2
* Counter Strike: Global Offensive
* Garry's Mod
* ARK: Survival Evolved

In addition to our standard nest of supported games, our community is constantly pushing the limits of this software
and there are plenty more games available provided by the community. Some of these games include:

* Factorio
* San Andreas: MP
* Pocketmine MP
* Squad
* Xonotic
* Starmade
* Discord ATLBot, and most other Node.js/Python discord bots
* [and many more...](https://github.com/parkervcp/eggs)

## License
```
Copyright (c) 2015 - 2021 Dane Everitt <dane@daneeveritt.com> and Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

Some Javascript and CSS used within the panel are licensed under a `MIT` or `Apache 2.0` license. Please check their
respective header files for more information.
