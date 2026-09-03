# List of BBS scripts
Overview of popular imageboard software

Statuses, repositories and deployments were verified in **September 2026**.

* [Popular](#popular)
* [Various other](#various-other)
* [Development in foreign languages](#development-in-foreign-languages)
* [Legacy, inactive or abandoned](#legacy-inactive-or-abandoned)
* [Last forks of old board engines](#last-forks-of-old-board-engines)
* [Closed source](#closed-source)

## Popular
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[LynxChan](https://gitgud.io/LynxChan/LynxChan) | NodeJS + MongoDB | Actively developed; all functionality exposed via JSON based RPC | [Endchan](https://endchan.net/) (demo site LynxHub is defunct; Kohlchan, formerly on LynxChan, lost its domain in 2026)
[jschan](https://gitgud.io/fatchan/jschan) | NodeJS + MongoDB | Actively developed; classic look, user-created boards, works without JavaScript and over Tor/I2P/Lokinet, built-in webring | [ptchan](https://ptchan.org/), [27chan](https://27chan.org/), [niuchan](https://niuchan.org/)
[Gochan](https://github.com/gochan-org/gochan) | Go + MySQL/PostgreSQL | Imageboard server written in Go that generates static HTML; Lua plugin API; active releases | [Gochan demo](https://gochan.org/)
[TinyIB](https://code.rocketnine.space/tslocum/tinyib) | PHP + MySQL/PostgreSQL/SQLite | Lightweight single-file engine, can run in textboard mode; repository moved from GitLab to code.rocketnine.space (GitLab copy archived) | See [DEMOS.md](https://code.rocketnine.space/tslocum/tinyib/src/branch/master/DEMOS.md)
[NPFchan](https://github.com/fallenPineapple/NPFchan) | PHP + MySQL | Fork of Vichan; no longer developed since ~2021 but still powers its boards | [Wizardchan](https://wizchan.org/), [MLPol](https://mlpol.net/)

## Various other
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[Open-IB](https://github.com/OpenIB/OpenIB) | PHP + MySQL | Security-focused fork of infinity, de facto engine of 8kun | [8kun](https://8kun.top/) (formerly 8chan; served on both 8kun.top and 8ch.net)
[Edaha](https://github.com/Edaha/Edaha) | PHP + RDBMS | Modular fork of Kusaba X; dormant 2013–2024, development resumed in 2025–2026 | 
[Livechan-js](https://github.com/emgram769/livechan-js) | NodeJS + MongoDB | Live IRC-like media chat; not developed since 2020 | [Kotchan](https://kotchan.org/)
[Minichan](https://minichan.net/) | PHP + MySQL | Modern textboard; original GitHub repo has been removed, the site continues at minichan.net (formerly .org) | [Minichan](https://minichan.net/)
[Iyagi-bbs](https://github.com/153/iyagi-bbs) | Python + RDBMS | Simple textboard | 
[4taba](https://github.com/4taba/4taba) | Python + PgSQL | Python imageboard | 
[Cutechan](https://github.com/cutechan/cutechan) | Go + NodeJS + PgSQL | Started as a fork of Meguca; K-pop oriented board engine, still developed | 
[FoolFooka](https://github.com/FoolCode/FoolFuuka) | PHP + MySQL | Imageboard archive front-end for Asagi (Fuuka family); archived | 
[Lapis-chan](https://github.com/karai17/lapis-chan/) | Lua + Docker | Imageboard written in Lua by the Lapis web framework | 
[Weabot](https://github.com/z411/weabot) | Python + MySQL | Fork of PyIB | [BaI](https://bienvenidoainternet.org/world/)
[Doushio](https://github.com/lalcmellkmal/doushio) | NodeJS + Redis | Real-time features | [Moe](http://doushio.com/moe/)
[Mei](https://github.com/lulalala/mei) | Ruby on Rails + RDBMS | Futaba-styled board on Ruby |  
[Maniwani](https://github.com/DangerOnTheRanger/maniwani) | Python + Docker | REST-API, still pre-alpha | [Futatsu](https://futatsu.org/)
[µchan](https://github.com/Floens/uchan) | Python + PgSQL + TypeScript + Memcache + Varnish | Lightweight and scalable | 
[Lainchan](https://github.com/lainchan/lainchan/) | PHP + MySQL | Fork of vichan maintained for lainchan.org, which is still running | [Lainchan](https://lainchan.org/)

## Development in foreign languages
Name | Language/Stack | Country |  Comments | Notable deployments
-----| -------------- | - | ------ | --------
[Ponyach](https://github.com/acilsd/ponyach.ru) | PHP + MySQL | 🇷🇺 | Kusaba styled imageboard | [Ponyach](https://ponyach.ru/b/)
[Fukuro](https://github.com/twiforce/fukuro) | PHP + MySQL | 🇷🇺 | Fork of Tinyboard | [Syn-Ch](https://syn-ch.com/b/)
[Neochan](https://github.com/neochaner/neochan) | PHP + MySQL | 🇷🇺 | Fork of infinity | [Neochan](https://neochan.ru/)
[Kurisaba](https://github.com/kurisaba-dev/kurisaba) | PHP + MySQL | 🇷🇺 | Fork of Kusaba (nullchan-kusaba X lineage); still developed | [Kurisach](https://kurisa.ch/)
[Fbe-410](https://bitbucket.org/Therapont/fbe-410/src/master/) | PHP + MySQL | 🇷🇺 | Flower Bus Engine | [410chan](https://410chan.org/)
[Ololord.js](https://github.com/ololoepepe/ololord.js) | NodeJS + Redis | 🇷🇺 | JavaScript imageboard; repo archived, its Allchan deployment is offline (domain expired) | 
[Tumbach](https://github.com/rngnrs/tumbach) | NodeJS + Redis | 🇷🇺 | Fork of ololord.js; archived | 
[Erlach](https://github.com/m-2k/erlach) | Erlang + Websocket | 🇷🇺 | SPA Imageboard on WebSockets written in Erlang | [Erlach](https://erlach.co/)
[Newneboard](https://bitbucket.org/neko259/newneboard/src/default/) | Python + Django | 🇷🇺 | Python imageboard; the neboard.me community merged into 9ch in 2025 | [9ch](https://9ch.site/)
[Monaba](https://gitlab.com/ahushh/Monaba) | Haskell + Yesod | 🇷🇺 | Haskell imageboard; demo site haibane.ru is offline | 
[Kropyva](https://gitlab.com/Kropyva/engine) | Python + MySQL | 🇺🇦 | Vichan-frontend-compatible Python imageboard | [Kropyvach](https://www.kropyva.ch/)
[Buryak](https://github.com/diogenes-33/buryak) | PHP + MySQL | 🇺🇦 | Modern imageboard engine | [Fajno](https://fajno.in/int/)

## Legacy, inactive or abandoned
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[Vichan](https://github.com/vichan-devel/vichan) | PHP + MySQL | The most widely forked engine (Tinyboard lineage). Declared end-of-life: repository archived on 6 Jul 2026 (*in memory of Fredrick Brennan, 1994–2026*). Most PHP chans still run it or its forks (Lainchan, NPFchan, OpenIB…) | 
[Meguca](https://github.com/bakape/meguca) | Go + NodeJS + PgSQL | Real-time features; rebranded as [Shamichan](https://github.com/bakape/shamichan) after 2019; both repositories archived (2023), a public instance survives at shamik.ooo | [Shamichan](https://shamik.ooo/)
[Infinity-next](https://github.com/infinity-next/infinity-next) | PHP + MySQL | Rewrite of infinity on the Laravel framework; never widely deployed, archived (2023) | 
[Wakarimasen](https://github.com/weedy/wakarimasen) | Python + SQLAlchemy | Python imageboard; no activity since 2017; its Desuchan deployment is offline (domain expired in 2023) | 
[4jhan](https://github.com/phikal/4jhan-server) | NodeJS + RDBMS | Board engine only (JSON-based server-client architecture); archived | 
[MiniBBS](https://github.com/whiteplastic/MiniBBS) | PHP + MySQL | Simple textboard | 
[Infinity](https://github.com/ctrlcctrlv/infinity) | PHP + MySQL |  User-created boards engine of 8chan; superseded by OpenIB (8kun) and vichan, repo archived | 
[Kusaba X](http://kusabax.cultnet.net/) | PHP + RDBMS |  No updates since 2013; its Operatorchan deployment switched to a placeholder site in 2022 | [Operatorchan](https://operatorchan.org/)
[Tinyboard](https://github.com/savetheinternet/Tinyboard) | PHP + MySQL | The ancestor of vichan and most modern PHP engines; no activity since 2014 | [Merorin](https://merorin.com/jp/)
[Futaba](http://jun.2chan.net/script/) | PHP + MySQL | The godfather of imageboard scripts, used on 2chan | 
[Futallaby](http://www.1chan.net/futallaby/) | PHP + MySQL | Fork of Futaba | 
[Wakaba](http://wakaba.c3.cx/s/web/wakaba_kareha) | Perl + RDBMS | Inspired by Futaba and Futallaby | 
[Kareha](http://wakaba.c3.cx/s/web/wakaba_kareha) | Perl + RDBMS | Textboard-only version of Wakaba | 
[Kareha-psgi](https://github.com/marlencrabapple/kareha-psgi) | Perl + RDBMS | PSGI version of Kareha; still occasionally updated | 
[PyIB](https://github.com/tslocum/PyIB) | Python + MySQL | Python imageboard | 

## Last forks of old board engines
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[Kareha* (Kiramoji)](https://github.com/Flameborn/Kiramoji) | Perl + RDBMS | Fork of Kareha-psgi by Flameborn, renamed Kiramoji; demo site kiramoji.ga is offline | 
[Wakaba*](https://github.com/emmausrs/Wakaba) | Perl + MySQL | Fork of Wakaba by Emma | 
[Tinyboard*](https://github.com/Circlepuller/Tinyboard) | PHP + MySQL | Fork of Tinyboard by Circlepuller | 
[Futallaby* (Nelliel)](https://github.com/NellielProject/Nelliel) | PHP + RDBMS | Originally a fork of Futallaby; Nelliel is still developed | 

## Closed source
Name | Language/Stack | Comments | Notable deployments
-----| -------------- | ------ | --------
[Taimaba](https://taimapedia.org/index.php?title=Taimaba) | Perl + MySQL | Fork of Wakaba | 420chan.org (the domain now redirects to leftypol.org)


### Other resources
* https://overscript.net/ — actively maintained catalogue of anonymous BBS scripts (116 catalogued; [source](https://github.com/tanami/overscript))
* https://github.com/topics/imageboard-engine — GitHub topic with up-to-date engines
* https://www.chans.top/ — live directory and uptime tracker of imageboards
