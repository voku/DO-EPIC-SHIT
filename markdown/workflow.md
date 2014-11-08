# Workflow & Toolchain

---
<!-- .slide: data-background="images/backgrounds/shutterstock_200991887_B.jpg" data-state="inverted" -->

# Werkzeugkasten

<div class="width_img_wrapper_60">
  ![Werkzeuge](images/werkzeuge.jpg)
</div>
---
<!-- .slide: data-background="images/backgrounds/shutterstock_200991887_B.jpg" data-state="inverted" -->

# Werkzeugkasten

<div class="width_img_wrapper_80">
  ![Open Source](images/Open-Source.png)
</div>
---

# Shell
## [dotfiles.github.com](http://dotfiles.github.com)

<div class="width_img_wrapper_60">
  ![where the magic happens](images/xkcd/wherethemagichappens.jpg)
</div>
---
<!-- .slide: data-background="images/backgrounds/terminal.jpg" data-state="inverted faded grayscaled" -->

## [github.com/voku/dotfiles/](https://github.com/voku/dotfiles/)
### aliases

<ul>
<li>l / l. / lr / lf
<li>cd.. / .. / ...
<li>sgrep
<li>date_*
<li>lsport / llport
<li>s foo.bar / v foo.bar
<li>getclip / putclip
</ul>
---
<!-- .slide: data-background="images/reactions/rm-rf.gif" data-state="inverted" -->

# rm -rf /

---
<!-- .slide: data-background="images/backgrounds/terminal.jpg" data-state="inverted faded grayscaled" -->

## [github.com/voku/dotfiles/](https://github.com/voku/dotfiles/)
### functions

<ul>
<li>passwdgen
<li>ff
<li>duh
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

---
## mehr als jedes andere Werkzeug, solltest du deine <span style="color: #e7ad52;">IDE</span> kennen

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
* [EditorConfig](http://editorconfig.org/)
* Git (Git-Gutter)
* Emmet (Zen-Coding)

---
<!-- .slide: data-background="images/reactions/iTIoSEWMoiHEZ.gif" data-state="inverted faded" -->
# git?

---
<!-- .slide: data-background="images/backgrounds/terminal.jpg" data-state="inverted faded grayscaled" -->

# git!

```
git status
```
```
git branch
```
```
git commit
```
```
git pull
```
```
git push
```

---
<!-- .slide: data-background="images/backgrounds/terminal.jpg" data-state="inverted faded grayscaled" -->

# git!

```
git log
```
```
git diff
```
```
git blame
```
```
git cherry-pick
```

---
# git - Tipps

* ~/.gitconfig
* core.autocrlf (true = Windows || input = Unix)
* [github.com](http://github.com) / [gitlab.com](http://gitlab.com/)
* [gitignore.io](http://gitignore.io/)
* ["git bash" für Windows](http://msysgit.github.io/)

---
# git - GUI

z.B.: SourceTree (Proprietär)

![SourceTree](images/SourceTree.jpg)

---
<!-- .slide: data-background="images/reactions/wrong-box.gif" data-state="inverted faded" -->

# deployment via "ftp"

---
<!-- .slide: data-background="images/reactions/tumblr_inline_muzu6hREgn1raprkq.gif" data-state="inverted faded" -->

# deployment via "git"

---
<!-- .slide: data-background="images/reactions/tumblr_inline_mmawrllsKw1qz4rgp.gif" data-state="inverted faded" -->

# deployment via "Jenkins"

---
# deployment via "Jenkins"

<ul>
  <li>automatische Tests (z.B.: Unit-Tests, UI-Tests, Integrationstest)
  <li class="fragment">Code-Qualität (z.B.: kopierte Codeteile, globale Variablen)
  <li class="fragment">prüfe auf Debug-Ausgaben (z.B.: "var_dump()", "console.log()")
  <li class="fragment">Statistiken über die Code-Qualität
  <li class="fragment">automatisches Deployment
</ul>

---
<!-- .slide: data-background="images/backgrounds/shutterstock_195671744.jpg" data-state="inverted faded" -->

# Statistiken über Mobile-Traffic
## 2012 - 2014

![mobile stats](images/mobile-stats_v1.jpg)

<span>[www.trivago.com](http://www.codetalks.de/session_post/was-nicht-passt-wird-responsive-gemacht/)</span>

---
<!-- .slide: data-background="images/backgrounds/shutterstock_195671744.jpg" data-state="inverted faded" -->

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

# Open-Source-Software für Frontend-Entwickler
<ul>
  <li class="fragment">[Bower](http://bower.io/)
  <li class="fragment">[Grunt](http://gruntjs.com/) / [Gulp](http://gulpjs.com/)
  <li class="fragment">[Autoprefixer](https://github.com/postcss/autoprefixer) / [CSSWring](https://github.com/hail2u/node-csswring)
  <li class="fragment">[LiveReload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei)
  <li class="fragment">[DevTools](http://discover-devtools.codeschool.com/)
  <li class="fragment">Frontend-Testing (z.B.: [Karma](https://www.npmjs.org/package/karma) / [DalekJS](http://dalekjs.com/))
  <li class="fragment">[Yeoman](http://yeoman.io/)
</ul>
---
<!-- .slide: data-background="images/backgrounds/shutterstock_4021051.jpg" data-state="inverted faded" -->

# Open-Source-Software für Frontend-Entwickler

<ul>
  <li class="fragment">Preprocessor (z.B.: [SASS](http://sass-lang.com/guide))
  <li class="fragment">UI-Toolkit (z.B.: [normalize](https://github.com/necolas/normalize.css/) / [Bootstrap](http://getbootstrap.com/) / [Foundation](http://foundation.zurb.com/))
  <li class="fragment">[Modernizr](http://modernizr.com/) & [Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)
  <li class="fragment">Fonts (z.B.: [Google Fonts](http://www.google.com/fonts#AboutPlace:about))
  <li class="fragment">JavaScript-Frameworks (z.B.: [jQuery](http://jquery.com/), [AngularJS](https://angularjs.org/))
  <li class="fragment">App-Frameworks (z.B.: [Apache Cordova](http://cordova.apache.org/), [Ionic](http://ionicframework.com/))
</ul>
---
# Entwicklungsumgebung via [Vagrant](https://www.vagrantup.com/)

<img src="images/logo_vagrant.png" class="no_border" alt="Vagrant" />

<div class="fragment">
  <strong>Tipp für Web-Entwickler:</strong>
  <br />
  [PuPHPet.com](https://puphpet.com/)  (MySQL, PostgreSQL, PHP, Ruby, Python ...)
</div>
---
# Open-Source-Software für Backend-Entwickler (PHP)

<ul>
  <li class="fragment">[Design-Pattern](https://github.com/domnikl/DesignPatternsPHP) (z.B.: Factory Pattern, Observer Pattern, Strategy Pattern ...)
  <li class="fragment">Frameworks (z.B.: [Symfony](symfony.com), [Laravel](http://laravel.com/)) / Mico-Frameworks (z.B.: [Slim Framework](http://www.slimframework.com/))
  <li class="fragment">ORM {Object-Relational Mapping} (z.B.: [RedBeanPHP](http://redbeanphp.com/))
  <li class="fragment">Datenbank-Migration (z.B.: [Ruckusing](https://github.com/ruckus/ruckusing-migrations))
  <li class="fragment">Hook-System (z.B.: [von WordPress](https://github.com/voku/php-hooks))
  <li class="fragment">Unit-Tests (z.B.: [PHPUnit](https://phpunit.de), JUnit, PyUnit ...)
</ul>

---
# Open-Source-Software für Backend-Entwickler (PHP)
---
## Composer

Installation:
```
curl -sS https://getcomposer.org/installer | php
```

Beispiel:
```
composer create-project voku/DO-EPIC-SHIT-Demo orr
```
---
## Xdebug

* Breakpoints
* Stacktrace
* Profiling
* IDE-Integration

---
## CacheGrind

Analyse der Profiling-Daten via "[Kcachegrind](http://kcachegrind.sourceforge.net/html/Home.html)" (Linux) || "[WinCacheGrind](http://ceefour.github.io/wincachegrind/)" (Windows)

![Kcachegrind](images/Kcachegrind.jpg)
