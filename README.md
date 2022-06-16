# Mission Statement
Learning a new language from scratch is incredibly hard. Anki provides an easy and effective way to expand your vocabulary, and practice listening skills. Building an anki deck from scratch can be intimidating for someone who is new to the program, and new to language learning, but using a premade deck from the community may not have all the features you want and may feel impersonal.

**Super giga deck builder 9000** Provides a one stop shop for custom building a language deck with all the things you want. With **Super giga deck builder 9000** your able to pick _(or build)_ a word list, and create a card for each word picking from a list of pictures, and audio samples.

After building your deck you can download it as an anki file and use it in your anki program.

# Technical details
[ankisync2](https://github.com/patarapolw/ankisync2)
Ankisync2 acts as an ORM wrapper for the underlying sqlite database, and media storage.

[Forvo API](https://api.forvo.com/)
Forvo is a website where people can upload clips of them pronouncing words in languages. From Forvo we can use the api to get and store the audio clips of the words we need.

## Image API
Not sure which API I want to use here. It’s important that your able to search the api using a foreign language so that is shows results that are relevant to the meaning of the word in that language. Here are some considerations: 
https://pypi.org/project/Google-Images-Search/
https://www.microsoft.com/en-us/bing/apis/bing-image-search-api
https://usearch.com/image-search-api/
https://usearch.com/image-search-api/

## backend database

## backend REST API


# References
[Anki Database Structure] (https://github.com/ankidroid/Anki-Android/wiki/Database-Structure)
.anki files are just zipped files containing a sqlite database, a json file which contains all of the information about the media files, and the media files themselves.

[Anki SRS](https://apps.ankiweb.net/)
A Spaced Repetition System for flashcards.
