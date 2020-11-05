---
id: 1244
title: Jednoduché
date: 2015-05-21T07:00:02+01:00
author: Martin Maly
layout: post
guid: http://kcc.uelectronics.info/?p=1244
permalink: /2015/05/21/jednoduche/
xyz_lnap:
  - "1"
categories:
  - Kuřecí
---
Mám rád, když jsou věci jednoduché tak, jak mohou jednoduché být.

Každá věc má svůj &#8222;júzkejs&#8220;, čili způsob, jak se používá, a je důležité, aby ho naplnila co nejefektivněji, a přitom byla pro uživatele co nejjednodušší. V tomhle souhlasím s filosofií (brr) Applu a rozcházím se s názorem technicistních lidí (občas je tu nazývám _inžinýři_, což neoznačuje nositele titulu Ing., ale nositele určitého způsobu myšlení). Pěkná ironie je, když titíž používají iPhone a pochvalují si, jak je to &#8222;jednoduché a logické&#8220;. Ale to nechme stranou.

Teď jsem četl moc pěkný článek (a děkuji [@JindroushCZ za tip](https://twitter.com/JindroushCZ/status/600379456281309184)), ve kterém Phil Torrone popisuje, [co je Arduino a proč uspělo](http://makezine.com/2011/02/10/why-the-arduino-won-and-why-its-here-to-stay/). Rád bych sem hodil pár výpisků k zamyšlení &#8211; článek je z roku 2011 a fakt, že o čtyři roky později Arduino stále dominuje, hovoří jasně&#8230;

Proč Arduino uspělo a dalších X set klonů a _Arduino killers_, co chodí tempem &#8222;každý měsíc jeden&#8220;, moc ne? Co rozhodlo o úspěchu Arduina?

Arduino je cokoli! Ať vás napadne sebevětší pitominka, gadget, od WTF counteru po všechny ty &#8222;cool&#8220; vychytávky s poměrně moderními technologiemi, odpověď zní: Arduino.

Z Arduina netrčí dráty, cín a kalafuna. Je to elektronický kit se vším všudy, ale nemáte pocit, že si musíte nejdřív připájet něco k něčemu a šermovat voltmetrem. Je to kit, který použije trošku technicky zdatný programátor, když si chce pohrát s GPS modulama ([zdravím Marcela](http://marcel.sulek.eu/)); kit, který použije kolega Zandl, když si bude chtít udělat svoji vysněnou váhu na kafe, co bude po internetu říkat všem kolegům, že mají dorazit s hrnkama; kit, po kterém sáhne Štěpán Bechynský, když si chce nabastlit [sledování vlastní garáže](http://www.zdrojak.cz/serialy/moje-garaz-muj-hrad/). Proč? No protože ten kit není navržený tak, aby byl přívětivý k elektronikům! On je přívětivý k uživatelům.

Odborníci &#8211; technici velmi často zkoumají, jak věci lze udělat a jak je udělat nelze. Naproti tomu právě ta masa uživatelů jsou ti pověstní _blbci, co nevědí, že to nejde, a tak to udělají_. Slušněji řečeno: díky Arduinu neřeší JAK, ale CO. Což odborníky irituje: &#8222;To přeci není ta elektronika!&#8220; &#8211; &#8222;Lidi se nedozvědí nic o tom, jak to funguje!!!&#8220; Ano, lidi to nechtějí vědět, chtějí něco dělat. Rigidita _inženýrů_ dosahuje v tomhle ohledu asi svého maxima: &#8222;Nedovolte, aby do našeho oboru fušovali lidi, co nestudovali, jako my, mnoho let!&#8220; Barbaři před branami Avalonu nechtějí znát podstatu mystérií, chtějí jen něco dělat. A s Arduinem mohou. Je tedy logické, že Zasvěcení budou Arduino intenzivně nenávidět. &#8222;Arduino je žvatlavé programování pro zhulence,&#8220; nechal se slyšet jeden z nich na AVR fóru.

Na druhou stranu, píše Phil, je to velká výhoda. Tím, že komunita odborníků Arduino odvrhla, donutila jeho uživatele vytvořit si vlastní, méně elitářskou a víc orientovanou na tvoření a radost z tvoření, než na znalosti, vědomosti a &#8222;zasvěcení&#8220;.

Další důvod je, že IDE funguje všude, na Win, Lin, i Mac. Drivery taky. Návrháři použili ten nejjednodušší způsob komunikace. Mohli navrhovat vlastní protokoly, které by byly efektivní, ale oni prostě použili známý a ověřený FTDI převodník, a bylo!

Věci jsou tak jednoduché, jak jen mohou být. Sériová komunikace 9600 Bd? &#8222;Serial.begin(9600)&#8220; &#8211; a nic víc! Všechno to protivné nastavování registrů a počítání konstant se děje někde na pozadí, vy jen říkáte, že se použije sériový port.

Přesto, že je vše jednoduché a nekomplikované, je zároveň velmi snadné připojit docela sofistikované komponenty. Ethernet? Video řadič? Motory? Serva? SD kartu? No prosím, nic z toho není problém. Většina se dokonce dá v rozumné míře kombinovat.

Navíc je to všechno levné a otevřené. Otevřenost prorostla celým konceptem, takže uživatelé sdílí své vlastní kódy. Existuje obrovská knihovna použitelných komponent. Čínské manufaktury chrlí statisíce kusů všeho možného &#8222;for Arduino&#8220; (po pravdě leckdy to je jen marketingový kec), od nejrůznějších snímačů po pozoruhodné obvody&#8230; ale všechno je to stále na stejném principu: Zapojím to &#8211; oživím to &#8211; používám to.

Podle autora se v Itálii vedou, podobně jako u nás, plačtivé diskuse o tom, kdo bude tím italským Googlem, velkým technologickým inovátorem&#8230; a nikoho nenapadlo, že to je právě Arduino!

Pravda je, že &#8222;české Arduino&#8220; taky nevidím.

Jen těch odborných diskusí, kde _je jasně dokázáno_, že Arduino (popřípadě cokoli jiného) je nesmysl, hype, bublina a nikdy se to neuchytí, máme srovnatelně se světem.