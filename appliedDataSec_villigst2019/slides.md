## Angewandter Datenschutz und IT-Sicherheit


<br>
<br>

> Dennis Kröger  
> Patrik Tesarik  
> [LABOR e.V.](https://das-labor.org) Bochum

<small> Villigst, 09.06.2019 </small>

---

## Wer wir sind

<br>

#### [Dennis Kröger](https://wiki.das-labor.org/w/Projekt/Labor-Mentoren)
* [Matrix](https://matrix.to/#/@d2ns:das-labor.org)
* [Mail](mailto:d2ns@das-labor.org)

---

## Wer wir sind

<br>

#### [Patrik Tesarik](https://patrik-tesarik.de)
* [XMPP](xmpp://depate@trashserver.net)
* [Matrix](https://matrix.to/#/@depate:das-labor.org)
* [Mastodon](https://social.tchncs.de/@patrik)
* [@gutluft](https://twitter.com/gutluft)
* [Mail](mailto:mail@patrik-tesarik.de) / [GPG: E680ACBF](https://pgp.mit.edu/pks/lookup?op=get&search=0x93992161E680ACBF)

---

## Was erwartet euch? 
    
* Impulsvortrag
* Diskussion
* Hands-on 

---

## IT-Sicherheit & Datenschutz

<br> 

#### Was kann passieren?

* Datenverlust 
* Fremdzugang 
* Überwachung 
* Verknüpfung

Note:
* Datenverlust (permanent)
    * Daten von Dritten
    * Wegverschlüsselt
* Fremdzugang (vereinzelt)
* Überwachung (langfristig)
* Verknüpfung
    * Metadaten

---

### Datenverlust
* [Dropbox (Sep. 2013)](https://www.businessinsider.com.au/professor-suffers-dropbox-nightmare-2013-9)
* [Windows-Update (Oct. 2018)](https://redmondmag.com/articles/2018/10/09/microsoft-lost-files-issue-windows-10.aspx )
* [Crypto-Trojaner (2012-today)](https://www.heise.de/thema/WannaCry)

---

### Fremdzugang
* [500px (Jun.18)](https://www.engadget.com/2019/02/13/500px-2018-breach-exposed-user-data/?guccounter=1&guce_referrer=aHR0cHM6Ly9kdWNrZHVja2dvLmNvbS8&guce_referrer_sig=AQAAANLW5Dho3H6jImo6Lxxj-B5SaNif9GNo8_2vEP9-234to1v1LJu6IfkNj4tLJLX-ulj_aHMbtikf2IvIuXl5BfW4Ti21zzlJnuapHK3CUn4NMc9Hi11hFTds87eHCDADnA_gSekbixs9AEO_6WavZ0v2qGmaYj4lwgYL3amUk5br)
* [Political Doxxing (Dez.18)](https://www.heise.de/newsticker/meldung/Massen-Doxxing-Datenklau-moeglicherweise-nicht-von-Hacker-alleine-4278619.html)
* [Google (Mai.19)](https://thehackernews.com/2019/05/google-gsuite-plaintext-password.html)

---

### Überwachung
* [Facebook & Cambridge Analytica (Mar.18)](https://www.theguardian.com/news/2018/mar/17/cambridge-analytica-facebook-influence-us-election)
* [Windows 10 is spying on you](https://www.hackread.com/windows-10-is-spying-on-you/ )

---

### Verknüpfung
* [Collection #1-#5 (Jan.19)](https://www.heise.de/security/meldung/Neue-Passwort-Leaks-Insgesamt-2-2-Milliarden-Accounts-betroffen-4287538.html)
* [Social Network Fotos mit realen Personen verknüpfen](https://birdinflight.com/ru/vdohnovenie/fotoproect/06042016-face-big-data.html )
* [How your Facebook 'likes' could reveal more about your personality than you think](https://www.independent.co.uk/news/your-facebook-likes-can-reveal-your-personality-traits-if-you-use-this-tool-10481372.html)

---

### Lösungen I

* Datenverlust:
    * verschlüsselte Backups
* Fremdzugang:
    * Updates
    * App-Berechtigungen nutzen

---

### Lösungen II

* Überwachung:
    * SocialMedia-Konten schließen
        * Dezentrale Dienste nutzen:
            - [Fediverse](https://de.wikipedia.org/wiki/Fediverse), z.B. [Mastodon](https://joinmastodon.org)
    * Wechsel zu Linux/OpenSource-Software
* Verknüpfung:
    * Anti-Tracker Add-Ons im Browser
    * Einzelne Logins / Absichern von "Hauptaccounts"
    * VPN-Anbieter, wie [mullvad](https://www.mullvad.net/de/ )

---

# Fragen?

---

## Umfrage & Diskussion
* Welche Lösungen habt ihr schon selber umgesetzt und wie?
* Welche Fragen habt ihr bzgl. der Lösungen?
* Wer kennt OpenSource Software bzw. setzt sie ein?
* Welches praktische Datenschutzproblem wollt ihr konkret angehen?

---

##  Themen: 
### IT-Sicherheit im Alltag

---

###### 2-Faktor-Authentifikation

* Für Google, Facebook, Twitter, PayPal und Co
* Soft- und Hardware ([Google Auth](https://play.google.com/store/search?q=google%20authenticator), [Aegis](https://play.google.com/store/apps/details?id=com.beemdevelopment.aegis), Hardware-[Tokens](https://www.yubico.com/))
* Nicht auf SMS-Basis!

---

###### Passwortmanager

* [KeepassXC](https://keepassxc.org) (OpenSource!)
* [Bitwarden](https://bitwarden.com) (OpenSource!)
* [1Password](https://1password.com/)
* Bin ich von einem Leak betroffen?:
    * [haveibeenpwnd](http://haveibeenpwnd.com/ )

---

###### Browser
* [Tor](https://torproject.org)/ [Onion-Routing](https://de.wikipedia.org/wiki/Onion-Routing) (Anonymitaet)
* Browser-Plugins 
    * [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/), [NoScript](https://addons.mozilla.org/de/firefox/addon/noscript/), [Facebook-Container](https://addons.mozilla.org/de/firefox/addon/facebook-container/ )

---

###### Dateicrypto

* im Android-System integriert
* Windows
    * Bitlocker (Windows 7 & 10 Pro)
    * [VeraCrypt](https://veracrypt.fr) 
    * B-Sticks / Dropbox

---

###### Nachrichtencrypto

* [Signal](https://signal.org) für Komfort
* [Matrix](https://matrix.org) für Mutige
* Telegram für Esoteriker
    * E2E-Kryptografie nur Opt-in
    * Kryptografie selbstgebaut
    * Gruppenchats ohne Ende-zu-Ende-Verschluesselung
* [Threema](https://threema.ch)
    * Closed-Source, aber geprueft
* [E-Mail-Krypto](https://enigmail.net), kaputt aber besser als nichts.

---

###### Updates, Updates, Updates
* Windows 7 
    * RIP @ 01/2020 (Supportende)
* Windows 10 Update-Desasters

---

###### [Umstieg auf Linux](http://www.linux-presentation-day.de/)
* LinuxMint
* Ubuntu
* Manjaro 

---

###### Virenschutz, Trojaner, (Spear-)Phishing
* Snake-Oils
    * Integrierte Antivirussoftware (Windows) reicht meistens aus
* Faktor: Mensch in IT-Sicherheit
    * Öffnen von malicious Links aus E-Mails
    * Öffnen von makrohaltigen Office (Word, Excel) Dateien
* Sensibilisierung
    * [Social Engineering](https://de.wikipedia.org/wiki/Social_Engineering_(Sicherheit))

---

###### Nicht bei den "Großen"
* Datenspeicher ([Nextcloud](https://nextcloud.org), ownCloud)
* E-Mail-Anbieter ([posteo.de])
* Suchmaschinen: DuckDuckGo / Startpage
* "Eigener" Blog
    * [wordpress](https://wordpress.org)
* Alternativer AppStore
    * [f-droid](https://fdroid.org)
* Ideengeber: 
    * [Prismbreak](https://prism-break.org), [EFF](https://eff.org), [Digitalcourage](https://digitalcourage.de/digitale-selbstverteidigung)

---

### Grundsätzliche Orientierung

> Nutzt (Freie) OpenSource Software!

> Kryptographie schützt!

> Dezentralität vor Zentralität!

---

### Merksätze

> Convenience vs. Freiheit vs. Sicherheit

> Man kann sich an jedes Nutzungsverhalten gewöhnen.

---

<blockquote class="twitter-tweet" data-lang="de"><p lang="en" dir="ltr">.<a href="https://twitter.com/Snowden?ref_src=twsrc%5Etfw">@snowden</a>
OPSEC guide:<br>- use Signal<br>- use Tor<br>- use full disk encryption<br>- use a password manager<br>- use two factor auth<br><br>Solid basics.</p>&mdash; (@thegrugq) <a href="https://twitter.com/thegrugq/status/668767879299399682?ref_src=twsrc%5Etfw">23. November 2015</a></blockquote>

---

### Wohin kann ich mich wenden?:

[hackerspaces](https://wiki.hackerspaces.org/)  
[SpaceAPI](https://spacer.nooitaf.nl/)  
[Frauen*: Haecksen](https://www.haecksen.org/mediawiki/index.php/Main_Page)  
[LinuxUserGroups](https://www.linux-magazin.de/Heft-Abo/Linux-User-Groups/)

> Support your local spaces and be part of them!


