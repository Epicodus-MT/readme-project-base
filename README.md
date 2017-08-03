<img src="epicodus.png" align="right" />

# README PROJECT SKELETON [![MT](MT-logo.png?raw=true)](https://github.com/sindresorhus/awesome)

> Technologies Used - Javascript, HTML, Shell. IDE used - Atom.

#### By _**Mara Timberlake**_

README with images, screenshots, GIFs, text formatting, etc.

## Description

_The Forest Service is considering a proposal from a timber company to clearcut a nearby forest of Douglas Fir. Before this proposal may be approved, they must complete an environmental impact study. This application was developed to allow Rangers to track wildlife sightings in the area._

## What's included
Within the repository you'll find the following directories and files:

```
java-wildlife-tracker/
├── src/
│    └── main/
│    │    └── java/
|    │    │     └── Animal.java
|    │    │     └── App.java
|    │    │     └── DB.java
|    │    │     └── EndangeredAnimal.java
|    │    │     └── Sighting.java
|    │    │     └── VelocityTemplateEngine.java
|    |    └── resources/
|    |          └──public/
|    |               └──app.css
|    |               └──tree-pattern.jpeg
|    |          └──templates/
|    |               └──animal-form.vtl
|    |               └──animal.vtl
|    |               └──endangered_animal.vtl
|    |               └──error.vtl
|    |               └──index.vtl
|    |               └──layout.vtl
|    |               └──sighting.vtl
|    |               └──sightings.vtl
|    |               └──success.vtl
|    └── test/
│         └── java/
|               └── AnimalTest.java
|               └── DatabaseRule.java
|               └── EndangeredAnimalTest.java
|               └── SightingTest.java
├── .gitignore
├── build.gradle
└── README.md
```

## Setup/Installation Requirements
To create the necessary databases:
* _LOCAL: Go to Terminal_
* _Clone this repository:_
```
$ cd ~/Desktop
$ git clone https://github.com/Epicodus-MT/java-wildlife-tracker.git
$ cd wildlife-tracker
```
* _Run Postgres with terminal command:_
```
$ postgres
```
* _Open a new tab in terminal by pressing [command ⌘] + [T]_
* _In the new tab, create 'wildlife_tracker' database:_
```
$ psql
* `CREATE DATABASE wildlife_tracker;`
* `\c wildlife_tracker;`
* `CREATE TABLE animals (id serial PRIMARY KEY, name varchar);`
* `CREATE TABLE endangered_animals (id serial PRIMARY KEY, name varchar, health varchar, age varchar);`
* `CREATE TABLE sightings (id serial PRIMARY KEY, animal_id int, location varchar, ranger_name varchar, time timestamp, is_endangered boolean);`
* `CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;`
```
* _Return to original tab where repository was cloned and run gradle:_
```
$gradle run
```
* _Open browser window:_
```
localhost:4567
```
## Specifications
_App does this..._








## Examples
- [aimeos/aimeos-typo3](https://github.com/aimeos/aimeos-typo3) - Project logo. Clear description of what the project does. Demo screenshot. TOC for easy navigation. Easy installation and setup sections with screenshots. Links for further reading.
- [amitmerchant1990/electron-markdownify](https://github.com/amitmerchant1990/electron-markdownify) - Project logo. Minimalist description of what it is. GIF demo of the project. Key features. How to install guide. Credits.
- [anfederico/Clairvoyant](https://github.com/anfederico/Clairvoyant) - Multiple badges. Clean logo. Simple install instructions. Clear overview of the project accompanied by a schematic. GIF demo. Extensive code examples.
- [angular-medellin/meetup](https://github.com/angular-medellin/meetup) - Project banner. Badges for stats. Well placed emoticons. Contributor's photos.
- [Day8/re-frame](https://github.com/Day8/re-frame) - Badges, logo, TOC, etc. Stands out by being a giant, well-written essay about the tech, how to use it, the philosophy behind it, and how it fits into the greater ecosystem.
- [iharsh234/WebApp](https://github.com/iharsh234/WebApp) - Project landing page. Clear description of what the project does. Demo screenshot. Simple install and usage sections. Includes an examples section with common uses and a mobile demo section.
- [jakubroztocil/httpie](https://github.com/jakubroztocil/httpie) - Description of what the project does. Demo screenshots. Project logo. TOC for easy navigation. Build badges. Quick and simple installation and usage sections. Includes an examples section.
- [karan/joe](https://github.com/karan/joe) - Project logo. Clear description of what the project does. GIF demo. Easy install and usage sections.
- [Martinsos/edlib](https://github.com/Martinsos/edlib) - Informative badges (build, version, publication). Concise description. Feature list. TOC. Screenshots. Concise instructions with examples for building and including in your project. Common code examples to get you started quickly.
- [node-chat](https://github.com/IgorAntun/node-chat) - Project screenshot. Informative badges. Clear description. Easy installation/use instructions. Live demo.
- [NSRare/NSGIF](https://github.com/NSRare/NSGIF) - Project logo. GIF Demo. Usage artwork. Usage code samples.
- [petkaantonov/bluebird](https://github.com/petkaantonov/bluebird) - Build badges. Clear description of what the project does. TOC for easy navigation. Project logo. Extensive explanations and examples.
- [rstacruz/hicat](https://github.com/rstacruz/hicat) - GIF demo. Easy installation and setup sections with screenshots. Build badges. Great examples of use cases.
- [ryanoasis/nerd-fonts](https://github.com/ryanoasis/nerd-fonts) - Clean project logo. Brief description at top. Sankey diagram, quick links, badges, OS specific icons, TOC, detailed release changelog.
- [sebyddd/SDVersion](https://github.com/sebyddd/SDVersion) - Project logo. Build badges. Documentation structuring for multiple programming languages. Usage examples.
- [shama/gaze](https://github.com/shama/gaze) - Project logo. Concise description. Feature list. Usage section. FAQ. Great API documentation. Release history.
- [sindresorhus/pageres](https://github.com/sindresorhus/pageres) - Project logo. Clear description of what the project does. Build badges. Demo screenshot. Simple install and usage sections. Includes an examples section with common uses.
- [skywinder/github-changelog-generator](https://github.com/skywinder/github-changelog-generator) - TOC for easy navigation. Concise project description. Installation and usage sections. Output example. Great feature overview. List of alternatives. FAQ.
- [choojs/choo](https://github.com/choojs/choo) - Badges, clean, clear. Beautiful little menu above the fold with useful links. An FAQ inside of it for the main questions. Backers. Good language.

## Articles
- ["Art of Readme - Learn the art of writing quality READMEs."](https://github.com/noffle/art-of-readme) - *Stephen Whitmore*
- ["How To Write A Great README"](https://robots.thoughtbot.com/how-to-write-a-great-readme) - *Caleb Thompson (thoughtbot)*
- ["How To Write A Readme"](http://jfhbrook.github.io/2011/11/09/readmes.html) - *Joshua Holbrook*
- ["Readme Driven Development"](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) - *Tom Preston-Werner*
- ["Top ten reasons why I won’t use your open source project"](https://changelog.com/posts/top-ten-reasons-why-i-wont-use-your-open-source-project) - *Adam Stacoviak*

## Tools

- [Common Readme](https://github.com/noffle/common-readme) - A common readme style for Node. Includes a guide and a readme generator.
- [Feedmereadmes](https://github.com/lappleapple/feedmereadmes) - README editing and project analysis/feedback.
- [Standard Readme](https://github.com/RichardLitt/standard-readme) - A standard README style specification. Has a generator to help creat spec-compliant READMEs, too.
- [Zalando's README Template](https://github.com/zalando/zalando-howto-open-source/blob/master/READMEtemplate.md) - Simple template to help you cover all the basics.

## Creating GIFs

Embedding an animated gif in your README quickly demonstrates what your project does and catches the reader's eye.  Here are a few programs that can help you quickly create gifs for your project:

- [Gifox](https://gifox.io) - **$4** - Cleanest UI, hotkeys, lots of advanced features
- [Giphy Capture](https://giphy.com/apps/giphycapture) - **FREE** - Easy to upload to giphy.com, slightly annoying UX.
- [LICEcap](http://www.cockos.com/licecap/) - **FREE** - Less intuitive, more features
- [Recordit](http://recordit.co/) - **FREE** - Simple, clean UI, but auto-uploads to [recordit.co](http://recordit.co)
- [ttystudio](https://github.com/chjj/ttystudio) - **FREE** - For commandline tools, a terminal-to-gif recorder minus the headaches.






## Known Bugs
_No known bugs at this time._

## Support and Contact Details
For questions or feedback, please contact [Mara Timberlake](<contact-info.md>).

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://opensource.org/licenses/MIT)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
