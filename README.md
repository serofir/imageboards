# List of BBS scripts
Overview of popular imageboard software

Statuses and links were verified in **September 2026**.
Markers: ☠️ = dead / closed (закрыто, сайт не открывается).

* [Popular](#popular)
* [Various other](#various-other)
* [Development in foreign languages](#development-in-foreign-languages)
* [Legacy, inactive or abandoned](#legacy-inactive-or-abandoned)
* [Last forks of old board engines](#last-forks-of-old-board-engines)
* [Closed source](#closed-source)

## Popular
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[LynxChan](https://gitgud.io/LynxChan/LynxChan) | NodeJS + MongoDB | All functionality exposed via JSON based RPC; actively developed | [Official board](https://lynx.farted.net/lynx/) (lynx.farted.net) · [LynxHub](http://lynxhub.com/) ☠️ dead · [Endchan](https://endchan.net/) (Kohlchan, also on LynxChan, lost its domain in 2026 ☠️)
[jschan](https://gitgud.io/fatchan/jschan) | NodeJS + MongoDB | Actively developed; classic look, user-created boards, works without JavaScript and over Tor/I2P/Lokinet, built-in webring | [ptchan](https://ptchan.org/), [27chan](https://27chan.org/), [niuchan](https://niuchan.org/), [heolkek](https://heolkek.cafe/), [zzzchan](https://zzzchan.xyz/), [sportschan](https://sportschan.org/)
[Gochan](https://github.com/gochan-org/gochan) | Go + MySQL/PostgreSQL | Actively developed; imageboard server that generates static HTML, Lua plugin API | [Gochan demo](https://gochan.org/)
[Vichan](https://github.com/vichan-devel/vichan/) | PHP + MySQL | Fork of Tinyboard. ☠️ End-of-life: repository archived on 6 Jul 2026 (*in memory of Fredrick Brennan, 1994–2026*); still the codebase of most PHP chans via its forks | [Brchan](http://www.brchan.org/)
[NPFChan](https://github.com/fallenPineapple/NPFchan) | PHP + MySQL | Fork of Vichan; no longer developed since ~2021 but still powers its boards | [Wizardchan](https://wizchan.org/), [MLPol](https://mlpol.net/)
[Infinity-next](https://github.com/infinity-next/infinity-next) | PHP + MySQL | Rewrite of infinity, built on the Laravel. ☠️ Archived (2023), never widely deployed |
[TinyIB](https://code.rocketnine.space/tslocum/tinyib) | PHP + MySQL | Lightweight single-file engine, textboard mode supported; supports MySQL/PostgreSQL/SQLite. Moved from GitLab ([archived copy](https://gitlab.com/tslocum/tinyib)) to code.rocketnine.space | See [DEMOS.md](https://code.rocketnine.space/tslocum/tinyib/src/branch/master/DEMOS.md)
[Meguca](https://github.com/bakape/meguca) | Go + NodeJS + PgSQL | Real-time features. ☠️ Rebranded as [Shamichan](https://github.com/bakape/shamichan) after 2019, both repositories archived (2023) | [Meguca](https://meguca.org/all/) ☠️ dead · [Shamichan](https://shamik.ooo/) (public instance)
[Sriracha](https://codeberg.org/tslocum/sriracha) | Go + PostgreSQL | Imageboard and forum server by tslocum (author of TinyIB); supports plugins and custom templates; actively developed | See demo at [sriracha.rocket9labs.com](https://sriracha.rocket9labs.com/)
[FChannel](https://github.com/FChannel0/FChannel-Server) | Go + PostgreSQL | Libre, self-hostable, federated imageboard platform utilizing ActivityPub | See [instance index](https://fchannel.org/instance-index.html)

## Various other
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[Open-IB](https://github.com/OpenIB/OpenIB) | PHP + MySQL | fork of infinity, security-focused, de facto engine of 8kun | [8chan](http://8ch.net) (now 8kun; served on both 8ch.net and 8kun.top, still online)
[Livechan-js](https://github.com/emgram769/livechan-js) | NodeJS + MongoDB | live IRC like imageboard written in NodeJS; not developed since 2020 | [Kotchan](https://kotchan.org/chat/int)
[Minichan](https://github.com/Minichan/Minichan) | PHP + MySQL | Modern textboard; GitHub repo has been removed, the site continues at minichan.net (minichan.org redirects there) | [Minichan](http://minichan.org/)
[Iyagi-bbs](https://github.com/153/iyagi-bbs) | Python + RDBMS | Simple textboard |
[4taba](https://github.com/4taba/4taba) | Python + PgSQL | Python imageboard |
[Cutechan](https://github.com/cutechan/cutechan) | Go + NodeJS + PgSQL | Started as a fork of Meguca; K-pop oriented board engine, still developed | 
[FoolFooka](https://github.com/FoolCode/FoolFuuka) | PHP + MySQL | imageboard with front-end interface for Asagi (Fuuka archive family). ☠️ Archived |
[Lapis-chan](https://github.com/karai17/lapis-chan/) | Lua + Docker | imageboard written in Lua by the Lapis web framework |
[Weabot](https://github.com/z411/weabot) | Python + MySQL | Fork of PyIB | [BaI](https://bienvenidoainternet.org/world/)
[Wakarimasen](https://github.com/weedy/wakarimasen) | Python + SQLAlchemy | Python imageboard; no activity since 2017 | [Desuchan](https://desuchan.net/) ☠️ dead (domain expired in 2023)
[4jhan](https://github.com/phikal/4jhan-server) | NodeJS + RDBMS | Board engine only (JSON-based server-client architecture). ☠️ Archived |
[Doushio](https://github.com/lalcmellkmal/doushio) | NodeJS + Redis | Real-time features | [Moe](http://doushio.com/moe/)
[Mei](https://github.com/lulalala/mei) | Ruby on Rails + RDBMS | Futaba-styled board on Ruby |  
[Maniwani](https://github.com/DangerOnTheRanger/maniwani) | Python + Docker | REST-API, still pre-alpha | [Futatsu](https://futatsu.org/)
[µchan](https://github.com/Floens/uchan) | Python + PgSQL + TypeScript + Memcache + Varnish | Lightweight and scalable |
[Lainchan](https://github.com/lainchan/lainchan/) | PHP + MySQL | Fork of vichan maintained for lainchan.org | [Lainchan](https://lainchan.org/)
[Picoboard](https://github.com/anonim-legivon/picoboard) | Python + Django + React (Django REST Framework) | Imageboard engine. ☠️ Archived (2021), no longer developed |
[Hexchan](https://github.com/binakot/hexchan-engine) | Python + Django | Django-based imageboard engine (MIT); original repo under hexchan org is gone, maintained copy at binakot | [Hexchan](https://hexchan.org/)
[Double Plus](https://gitgud.io/odilitime/lynxphp) | PHP + MySQL/PostgreSQL | Modular modern imageboard, works without JS; works on shared hosting | [wrongthink](https://wrongthink.net/)

## Development in foreign languages
Name | Language/Stack | Country |  Comments | Notable deployments
-----| -------------- | - | ------ | --------
[Ponyach](https://github.com/acilsd/ponyach.ru) | PHP + MySQL | 🇷🇺 | Kusaba styled imageboard | [Ponyach](https://ponyach.ru/b/)
[Fukuro](https://github.com/twiforce/fukuro) | PHP + MySQL | 🇷🇺 | fork of Tinyboard | [Syn-Ch](https://syn-ch.com/b/)
[Neochan](https://github.com/neochaner/neochan) | PHP + MySQL | 🇷🇺 | fork of infinity | [Neochan](https://neochan.ru/)
[Kurisaba](https://github.com/kurisaba-dev/kurisaba) | PHP + MySQL | 🇷🇺 | fork of Kusaba (nullchan-kusaba X lineage), still developed | [Kurisach](https://kurisa.ch/)
[Fbe-410](https://bitbucket.org/Therapont/fbe-410/src/master/) | PHP + MySQL | 🇷🇺 | Flower Bus Engine | [410chan](https://410chan.org/)
[Ololord.js](https://github.com/ololoepepe/ololord.js) | NodeJS + Redis | 🇷🇺 | Javascript imageboard. ☠️ Archived; its Allchan board is dead (domain expired) | [Allchan](https://allchan.su/) ☠️ dead
[Tumbach](https://github.com/rngnrs/tumbach) | NodeJS + Redis | 🇷🇺 | fork of ololord.js. ☠️ Archived | [Tumbach](https://github.com/rngnrs/tumbach)
[Erlach](https://github.com/m-2k/erlach) | Erlang + Websocket | 🇷🇺 | SPA Imageboad on WebSockets written on Erlang | [Erlach](https://erlach.co/)
[Newneboard](https://bitbucket.org/neko259/newneboard/src/default/) | Python + Django | 🇷🇺 | python imageboard; the neboard.me community merged into 9ch in 2025 | [Neboard](https://neboard.me/) ☠️ dead (now redirects to [9ch](https://9ch.site/))
[Monaba](https://gitlab.com/ahushh/Monaba) | Haskell + Yesod | 🇷🇺 | Haskell imageboard | [Haibane](https://haibane.ru/b/) ☠️ dead (domain parked)
[Kropyva](https://gitlab.com/Kropyva/engine) | Python + MySQL | 🇺🇦 | Vichan styled python imageboard | [Kropyvach](https://www.kropyva.ch/)
[Buryak](https://github.com/the-sashko/buryak) | PHP + MySQL | 🇺🇦 | Modern imageboard engine | [Fajno](https://fajno.in/int/)


## Legacy, inactive or abandoned
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[MiniBBS](https://github.com/whiteplastic/MiniBBS) | PHP + MySQL | simple textboard |
[Infinity](https://github.com/ctrlcctrlv/infinity) | PHP + MySQL |  ☠️ Archived; engine of 8chan's user-created boards, lineage continued by OpenIB/8kun | 
[Kusaba X](http://kusabax.cultnet.net/) | PHP + RDBMS |  no updates since 2013; its Operatorchan imageboard is offline (placeholder site since 2022) | [Operatorchan](https://operatorchan.org/) ☠️ dead (board replaced by a placeholder in 2022)
[Edaha](https://github.com/Edaha/Edaha) | PHP + RDBMS |  Fork of Kusaba X; dormant since 2013, development resumed in 2025–2026 |
[Tinyboard](https://github.com/savetheinternet/Tinyboard) | PHP + MySQL | | [Merorin](https://merorin.com/jp/) 
[Futaba](http://jun.2chan.net/script/) | PHP + MySQL | The godfather of imageboard scripts, used on 2chan |
[Futallaby](http://www.1chan.net/futallaby/) | PHP + MySQL | Fork of Futaba
[Wakaba](http://wakaba.c3.cx/s/web/wakaba_kareha) | Perl + RDBMS | Inspired by Futaba and Futallaby |
[Kareha](http://wakaba.c3.cx/s/web/wakaba_kareha) | Perl + RDBMS | Textboard-only version of Wakaba |
[Kareha-psgi](https://github.com/marlencrabapple/kareha-psgi) | Perl + RDBMS | psgi version of Kareha; still occasionally updated |
[PyIB](https://github.com/tslocum/PyIB) | Python + MySQL | Python imageboard | |

## Last forks of old board engines
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[Kareha*](https://github.com/Flameborn/Kareha) | Perl + RDBMS | fork of Kareha-psgi by Flameborn, renamed to Kiramoji | [Kiramoji](https://kiramoji.ga/) ☠️ dead
[Wakaba*](https://github.com/emmausrs/Wakaba) | Perl + MySQL | fork of Wakaba by Emma |
[Tinyboard*](https://github.com/Circlepuller/Tinyboard) | PHP + MySQL | fork of Tinyboard by Circlepuller |
[Futallaby*](https://github.com/NellielProject/Nelliel) | PHP + RDBMS | fork of Futallaby by Nelliel; Nelliel is still developed |


## Closed source
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[Taimaba](https://taimapedia.org/index.php?title=Taimaba) | Perl + MySQL | Fork of Wakaba | [420chan](http://420chan.org) ☠️ dead (the domain now redirects to leftypol.org)


### Other resources
* http://www.9ch.in/overscript/ (now redirects to [overscript.net](https://overscript.net/), actively maintained catalogue of ~116 anonymous BBS scripts)
* http://9ch.in/over/index2.pl (now redirects to [overscript.net](https://overscript.net/))
* https://tanami.org/overscript/ (now redirects to [overscript.net](https://overscript.net/))
* https://flash.moe/overscript/ ☠️ dead (404)
* https://github.com/topics/imageboard-engine — GitHub topic with up-to-date engines
