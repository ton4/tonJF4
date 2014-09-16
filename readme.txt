/////////////////////////////////////// ---
16-09-2014
tonJF4 Game

Założenia odnośnie pisania kodu:
HTML:
notacja pauzowa: np. wrap-main

CSS j.w

JS:
notacja wielkoLiterowa: np. wrapMain

W przypadku długich nazw zmiennych robimy nazwy skrótowe, np. po 3-4 litery z każdego członu + wyjaśnienie w komentarzu obok deklaracji zmiennej.

Sposób komentowania kodu:

zmienne - tylko w przypadku skomplikowanych części kodu
funkcje -
	/*
	* function nazwa
	* tags (ewentualnie)
	*
	* @return
	*
	* @params
	* param1[type] - ...
	*
	* param2[type] - ...
	*/
	
klasy -
	/*
	* class nazwa
	* tags (ew.)
	* 
	* @constructor
	* opis konstruktora - sposób użycia
	*
	* @params
	*
	* @examples z wyjaśnieniami
	*/
	
funkcje globalne/pomocnicze -
	Mają służyć stricte do ułatwiania kodu, zawierać bardzo często powtarzalny kod i nie dotyczyć klas projektowych (elastyczne).
	Zapisujemy je w pliku js/libs/functions.js - globalnie.
	
Struktura folderów i plików

* configs
* css
	* gfx
* js
	* libs
* media
	* sounds
	* images