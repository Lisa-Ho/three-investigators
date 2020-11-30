# About this project

This is a personal project scraping and analysing data on the German audio drama [‘Die drei ???’](https://de.wikipedia.org/wiki/Die_drei_%3F%3F%3F) (orig.: the three investigators). As a huge fan and regular listener since my childhood, I was curious to find out more about the series while expanding my python skills around webscraping. 

Thanks to the fansite [Rocky-Beach.com](https://www.rocky-beach.com/php/wordpress/) I was able to collect data on each episode. I then used [Genderize API](https://github.com/SteelPangolin/genderize) to predict the gender of the show's actors based on their first name. 

The write up of the analysis can be found on [my blog](https://inside-numbers.com/germanys-most-popular-audio-drama-in-numbers). 

## Notebooks

The project has been organised across different jupyter notebooks:

- 1 Web scraping
- 2 actor gender predictions using genderize API
- 3 content analysis of titles
- 4 data cleaning and analysis

## Requirements
This project is run on python 3 and a number of data analysis packages.
The exact packages are specified in ```requirements.txt``` 

## Notes on methodology

### Data cleaning

As with any data, I found some inconsistencies that required additional cleaning, for example renaming roles where different names were used for the same character. 

The majority of data preparation involved deriving variables and merging different data sets.


### Title categories
As part of the title content analysis, words found in episode titles were categorised into the following themes:

- animal: katze, hund, löwe, papagei, spinne, schlange, wal, wolf, tiger, rabe, insekt, cobra, skorpion, motte, vögel, marder, - ameise, hai, gockel
- colour: grün, schwarz, gelb, blau, rot, weiß
- danger: gefahr, schrecken, gefährlich, grauen
- death: tot, grab,tod, tödlich, mumie, särge
- ethnic: volk, wikinger, azteke, pirat,samurai
- fire: feuer, brennen, flamme
- mystery: rätsel, geheimnis, verschwunden, unsichtbar, verschollen, täuschung, heimlich
- paranormal: drache, monster, geist, phantom, teufel, werwolf, spuk, vodoo, vampir, dämon, fluch, untote, hexe, kobold, biest, ungeheuer, jenseits, hölle, höllisch, unterwelt, ufo, magisch
- person: diva, mönch,  madonna, pilot, zauberer, bauchredner,hehler, gaukler, wächter, mann, passagier, segler, maler, filmstar, millionär
- place: stadt, meer, see, straße, bucht, castle, dorf, fels, hollywood, canyon, villa, höhle, schlucht, berg, insel, turm, zirkus, ranch, riff,schloß , mine, tal, moor, haus
- sport: spieler, fussball, fußball, skateboard, poker, quiz, foul
- tech: computer, internet, email, sms, netz, gps, handy
- treasure: gold, diamant, schatz, rubin


