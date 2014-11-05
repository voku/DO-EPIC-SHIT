# Open Source Workflow
## Praxis

---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted" -->

# Werkzeugkasten

<div class="width_img_wrapper_60">
  ![Werkzeuge](images/werkzeuge.jpg)
</div>
---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted" -->

# Werkzeugkasten

<div class="width_img_wrapper_80">
  ![Open Source](images/Open-Source.png)
</div>
---
<!-- .slide: data-background="images/backgrounds/system-fail.jpg" data-state="inverted" -->

# Shell
## [dotfiles.github.com](http://dotfiles.github.com)

<div class="width_img_wrapper_60">
  ![where the magic happens](images/xkcd/wherethemagichappens.jpg)
</div>
---
<!-- .slide: data-background="images/reactions/rm-rf.gif" data-state="inverted" -->

# rm -rf /
---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted faded" -->

## [github.com/voku/dotfiles/](https://github.com/voku/dotfiles/)
### aliases

<ul>
<li>l / .l / lf / la / ll
<li>cd / cd.. / cd ..
<li>sgrep
<li>ps / psx / pst / pstree
<li>date_*
<li>lsport / llport
<li>s foo.bar / v foo.bar
<li>getclip / putclip
</ul>


---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted faded" -->

## [github.com/voku/dotfiles/](https://github.com/voku/dotfiles/)
### functions

<ul>
<li>passwdgen
<li>ff
<li>duh
<li>netstat_*
<li>phpserver / server
<li>targz / extract
</ul>


---
<!-- .slide: data-background="images/reactions/tumblr_inline_mxzcnayKCb1raprkq.gif" data-state="inverted faded grayscaled" -->

# lerne deine Wekzeuge gut zu nutzen

<h3 class="fragment">
  . . . und selber anzupassen!
</h3>

---
## mehr als jedes andere Werkzeug, solltest du deinen Editor kennen

z.B.:

| Editor        | Lizenz                  |
|---------------|-------------------------|
| vi(m)         | GPL (Charityware)       |
| Notepad++     | GPL                     |
| Sublime Text  | proprietär (Shareware)  |
| Brackets      | MIT                     |
| Atom          | MIT                     |

---
## mehr als jedes andere Werkzeug, solltest du deine <span style="color: red;">IDE</span> kennen

z.B.:

| Editor        | Lizenz      |
|---------------|-------------|
| Eclipse       | EPL         |
| NetBeans      | CDDL & GPLv2|
| PHPStorm      | Proprietär  |
| WebStorm      | Proprietär  |

---
# IDE || Editor
## Welche Einstellungen und Plugins sollte man nutzen?

* Code Linting / Code Hints
* Code Highlighter
* EditorConfig
* Git (Git-Gutter)
* Emmet (Zen-Coding)

---
<!-- .slide: data-background="images/reactions/iTIoSEWMoiHEZ.gif" data-state="inverted faded" -->
# git?

---
# git!

```
git status
git branch
git commit
git pull
git push
git log
git diff
git blame
```

---

# git - Tipps

* ~/.gitconfig
* core.autocrlf (true = Windows || input = Unix)
* [github.com](http://github.com) / [gitlab.com](http://gitlab.com/)
* [gitignore.io](http://gitignore.io/)
* ["git bash" für Windows](http://msysgit.github.io/)

---
# git (GUI)

z.B.: SourceTree

![SourceTree](images/SourceTree.jpg)

---
# deploment via FTP

![:)](images/reactions/tumblr_inline_n78ix43xHY1raprkq.gif)
---
# deploment via Jenkins

![:)](images/reactions/tumblr_inline_muzu6hREgn1raprkq.gif)

<div class="fragment">
  <ul>
    <li>automatische Tests <!--(z.B.: Unit-Tests, UI-Tests, Integration-Tests)-->
    <li>Code-Qualität <!--(z.B.: kopierte Codeteile, globale Variablen)-->
    <li>prüfe auf Debug-Ausgaben <!--(z.B.: "var_dump()", "console.log()")-->
    <li>Statistiken über die Code-Qualität
    <li>automatisches Deployment
  </ul>
</div>

---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted faded" -->

# Statistiken über Mobile-Traffic
## 2012 - 2014

![mobile stats](images/mobile-stats_v1.jpg)

<span>[www.trivago.com](http://www.codetalks.de/session_post/was-nicht-passt-wird-responsive-gemacht/)</span>

---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted faded" -->

# Statistiken über Mobile-Traffic
## 2012 - 2017

![mobile stats](images/mobile-stats_v2.jpg)

<span>[statista.com](http://www.statista.com/statistics/284202/mobile-phone-internet-user-penetration-worldwide/)</span>
---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted faded" -->
<div class="width_img_wrapper_70">
  ![mobile stats](images/rwd-iceberg.png)
</div>
---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted faded" -->

# OpenSource-Software für Frontend-Developer
<ul>
<li class="fragment">Bower
<li class="fragment">Grunt / Gulp
<li class="fragment">Autoprefixer / CSSWring
<li class="fragment">LiveReload
<li class="fragment">DevTools
<li class="fragment">Frontend-Testing (z.B.: Mocha / Karma / DalekJS)
<li class="fragment">Yeoman
</ul>
---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted faded" -->

# OpenSource-Software für Frontend-Developer

<ul>
<li class="fragment">Preprocessor (z.B.: SASS / LESS)
<li class="fragment">UI-Toolkit (z.B.: normalize / Bootstrap / Foundation)
<li class="fragment">Modernizr & [Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)
<li class="fragment">Fonts (z.B.: Google Fonts)
<li class="fragment">JavaScript-Frameworks (z.B.: jQuery, AngularJS)
<li class="fragment">App-Frameworks (z.B.: Apache Cordova, Ionic)
</ul>
---
# OpenSource-Software für Developer
## Vagrant

z.B.: für Web-Entwicklung (MySQL, PostgreSQL, PHP, Ruby, Python ...)
[PuPHPet.com](https://puphpet.com/)

<img src="images/logo_vagrant.png" class="no_border" alt="Vagrant" />
---
# OpenSource-Software für Backend-Developer

<ul>
<li class="fragment">Design-Pattern <!--(z.B.: Factory Pattern, Observer Pattern, Strategy Pattern ...)-->
<li class="fragment">Frameworks <!--(z.B.: Symfony, Laravel)--> / Mico-Frameworks <!--(z.B.: Slim Framework)-->
<li class="fragment">MVC {Model-View-Controller}
<li class="fragment">ORM {Object-Relational Mapping}
<li class="fragment">Datenbank-Migration
<li class="fragment">Hook-System
<li class="fragment">Unit-Tests <!--(z.B.: PHPUnit, JUnit, PyUnit ...)-->
</ul>

---
# OpenSource-Software für Backend-Developer (PHP)
---
## Composer

Install:
```
curl -sS https://getcomposer.org/installer | php
```

Beispiel:
```
composer create-project voku/DO-EPIC-SHIT-Demo orr
```
---
## XDebug

* Breakpoints
* Stacktrace
* Profiling
* IDE-Integration

---
## CacheGrind

Analyse der Profiling-Daten via "Kcachegrind" (Linux) || "WinCacheGrind" (Windows)

![Kcachegrind](images/Kcachegrind.jpg)