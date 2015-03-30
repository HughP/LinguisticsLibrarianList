#Linguistics and language oriented web services
###Purpose
_This list specifically focuses on web services for interacting with linguistic data. By this we mean the business sense of service, rather than the computational sense of a service running on a server machine. Obviously though these business services might also run computational services which might be specialized applications for dealing with linguistic data. By interacting we mean the collaborative (multi human user) co-creation or co-development of corpra and their various annotation tiers. The list might grow into its own thing but it might remain a sub-component for inclusion in other lists._
###Additions
_If you know of something, but wonder if it really fits, open an issue and lets look at it._

##Services with linguistic data
* [LanguageDepot](http://public.languagedepot.org/) - Service Provider: _SIL International_ - a sync service for use with FLEx and WeSay products. It allows multiple people to access the same lexicon data.
* [LanguageForge](https://languageforge.org/) - Service Provider: _SIL International_ - a browser based lexicon builder, useable by multiple users. **Currently in Beta.**
* [LingSync](https://www.lingsync.org/) - Service Provider: _McGill University and Concordia University_ - A tool for creating and maintaining a Shared database... _"of what?"_ (seems mostly like phrases)
* PELDA (unknown URL; provider contacted) - Service Provider: _University of Washington Bothell and University of Montana_ - attempts to do phoneme extraction and transcription from audio corpora. **Currently in Beta.**
* [TypeCraft](http://typecraft.org/tc2wiki/Main_Page) - Service Provider: _Norwegian University of Science and Technology, LingLab_ - A MediaWiki based service allowing annotation and multi language glossing of texts.
* [Webonary](http://www.webonary.org/) - Service Provider: _SIL International_ - a place to easily "publish" and browse a lexicon produced via FLEx.

##Services with meta-language data
* [LL-MAP](http://www.llmap.org) - Service Provider: _LinguistList_ - A tool for looking at the geographical dispersion of language users. Users can provide their own data as well as look at geo-aligned previously claimed data in the form of published maps. **Service is currently not functional.** Former provider was [Institute for Geospatial Research & Education](http://igre.emich.edu/igre/gisresearch/international/ll_map) at [Eastern Michigan University](http://www.emich.edu/) (EMU was also the former host of LinguistList)

##Services which provide "archiving"
* [Mukurtu](http://www.mukurtu.org/) - Hosted "archive" meaning material content access via appropriate restrictions.
* [DuraSpace](http://www.duraspace.org/) - particularly [DuraCloud](http://www.duracloud.org/) specializes in hosting small institutional repositories.

##REST API - Data conversion type services
_Currently(19. March 2015) these services are all offered by Radboud University Nijmegen: http://webservices-lst.science.ru.nl/_
* **Ucto Tokeniser** -	Ucto is a unicode-compliant tokeniser. It is rule-based and supports a variety of languages and can be extended for new languages. It takes input in the form of one or more untokenised texts, and subsequently tokenises them. Output in FoLiA XML format is supported as well. 
 * Developers: Maarten van Gompel, Ko van der Sloot (Tilburg University) 
 * Webservice: http://webservices-lst.science.ru.nl/ucto/ 
 * REST API Specification: http://webservices-lst.science.ru.nl/ucto/info/ 
 * Homepage: http://ilk.uvt.nl/ucto/

* **Frog** - Frog is a suite containing a tokeniser, PoS-tagger, lemmatiser, morphological analyser, and dependency parser for Dutch, developed at Tilburg University. It is the successor of Tadpole. Output in FoLiA XML format is supported. 
 * Developers: Ko van der Sloot (Tilburg University), Antal van den Bosch, Maarten van Gompel 
 * Webservice: http://webservices-lst.science.ru.nl/frog/
 * REST API Specification: http://webservices-lst.science.ru.nl/frog/info/ 
 * Homepage: http://ilk.uvt.nl/frog/

* **Valkuil** -	Valkuil is a Dutch spelling correction system. Output is in FoLiA XML. 
 * Developers: Antal van den Bosch, Maarten van Gompel 
 * Webservice: http://webservices-lst.science.ru.nl/valkuil/ 
 * REST API Specification: http://webservices-lst.science.ru.nl/valkuil/info/ 
 * Homepage: http://valkuil.net

* **Fowlt** -	Fowlt is an English spelling correction system. Output is in FoLiA XML. 
 * Developers: Wessel Stoop, Antal van den Bosch, Maarten van Gompel 
 * Webservice: http://webservices-lst.science.ru.nl/fowlt/ 
 * REST API Specification: http://webservices-lst.science.ru.nl/fowlt/info/ 
 * Homepage: http://fowlt.net

* **Oersetter** -	Oersetter is a Frisian-Dutch, Dutch-Frisian Machine Translation system developed in collaboration with the Fryske Akademy. 
 * Developers: Maarten van Gompel 
 * Webservice: http://webservices-lst.science.ru.nl/oersetter/ 
 * REST API Specification: http://webservices-lst.science.ru.nl/oersetter/info/ 
 * Homepage: http://oersetter.nl

* **T-scan**	T-scan is a Dutch text analytics tool for readability prediction. It outputs FoLiA XML. 
 * Developers: Ko van der Sloot (Tilburg University), Rogier Kraf (Utrecht University), Henk Pander Maat (Utrecht University), Antal van den Bosch 
 * Webservice: http://webservices-lst.science.ru.nl/tscan/ 
 * REST API Specification: http://webservices-lst.science.ru.nl/tscan/info/ 

* **Timbl**	Timbl is a memory-based classifier developed at Tilburg University 
 * Developers: Ko van der Sloot, Antal van den Bosch, Peter Berck, Walter Daelemans, Ton Weijters, Jakub Zavrel, Maarten van Gompel
 * Webservice: http://webservices-lst.science.ru.nl/timbl/ 
 * REST API Specification: http://webservices-lst.science.ru.nl/timbl/info/ 
 * Homepage: http://ilk.uvt.nl/timbl

* **FoLiA-stats** -	Quick computation of n-gram frequency lists on FoLiA XML input 
 * Developers: Ko van der Sloot (Tilburg University) 
 * Webservice: http://webservices-lst.science.ru.nl/foliastats/ 
 * REST API Specification: http://webservices-lst.science.ru.nl/foliastats/info/ 

* **Colibri Core** -	Software suite for the efficient extraction and analysis of patterns (n-grams, skipgrams) on (large) corpus data
 * Developers: Maarten van Gompel
 * Webservice: http://webservices-lst.science.ru.nl/colibricore/ 
 * REST API Specification: http://webservices-lst.science.ru.nl/colibricore/info/ 
 * Homepage: http://proycon.github.io/colibri-core/doc/

## License
[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

Copyright 2015 by Hugh Paterson III and contributors. Licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
####Contributors
* Hugh Paterson III
