# Project 1: Amusectionary

This project was developed by:
Regina Franco, Alfonso Núñez and Víctor Vallejo.

Why is Amusectionary the best option? 

Nowadays, english is the language of international communication, commerce and finances, as well as the official language of many organizations such as the European Union, the United Nations or UNESCO. 

My team and I understand the importance of learning new languages, especially english, as well as we know that conventional ways of learning are boring, that is why we decided to create Amusectionary, with the aim of providing clients a fun way to learn English. 

With only 5 minutes a day, you can increase your vocabulary in a fun way, all you have to do is enter a word in the search engine and Amusectionary will present you the definition and pronunciation as well as a song with its lyrics so that the user can see the usage of the word. If that weren't enough, a starred screen is also presented so that the user can save the words and see its information again by only clicking at it. 

Learning english has never been so easy, so, what are you waiting for?

The goal of our project was to: 
* Provide the user with a search interface for a word.
* Give the definition to that word and if available the pronunciation.
* Find a song that has the word in the title.
* Give the user the lyrics of that song.
* Allow the user to save the word as a "Favorite".
* In the "Favorite" section allow the user to click the saved items and give the results again.

The user story that we use to develop this application:
* As an english speaker, I want to learn new words and their definitions, so that I can increase my vocabulary.

Description
The design of our application allows the user to search for words, the word can be saved to local storage. That would send a request to get that word's definition and pronunciation. Then the UI gives the option to search for a song with that word in the title, in the Spotify catalogue. If there is a result, the application gives a 30 second preview of the song, and if there are lyrics available they can be displayed.

To develop this application we used the CSS framework Tailwind. It allowed us to have clean and intuitive UI.
The functionality of the application in the beginning was planned with only 2 API's, a dictionary API and Lyrics API. We ended using 3 API's, listed below:

* LinguaRobot API to get the definition of the word: <https://lingua-robot.p.rapidapi.com/language/v1/entries/en/>
* Spotify API to search for the generated word in the title of a song and to give a 30 second preview: <https://api.spotify.com/v1/search?q=>
* Lyrics API to get lyrics with the title of the song and the artist name found by the Spotify API: <https://api.lyrics.ovh/v1/>

There is also the functionality to let the user save the words into Local Storage.

![Screen capture](./Images/Homepage.png)
![Screen capture](./Images/WordSearched.png)
![Screen capture](./Images/MusicResult.png)
![Screen capture](./Images/LyricsResult.png)
![Screen capture](./Images/Favorites.png)

[Link to website](https://reginaafc.github.io/amusectionary/)
