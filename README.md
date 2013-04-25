Wtyczki do programu PopClip
===========================

Repozytorium zawiera wtyczki:

1. CriticMarks - narzędzie dla korektorów wykorzystujące multimarkdown
2. Znajdz Aukcje - pozwala wyszukiwać tekst w serwisie Allegro
3. Lastfm - zestaw narzędzi do parsowania informacji z Last.FM i konwertowania ich na Markdown


This repository contains plugins for PopClip.

1. CriticMarks - tools for editors to use with multimarkdown syntax
2. Znajdz Aukcje - allows searching for items in popular polish auction portal Allegro.
3. Lastfm - set of tools for using Last.Fm information and converting them to Markdown format.


## Usage ##

### Critic Marks ###
Services run by "ACM" and "RCM" buttons seems to be laggy and not always gives desired output. For unknown reason (at least 
on my machine) it's better to run them from right-click menu.

### Last.FM ###
Plugin need system ruby with version at least 1.8.7. Should also work with 1.9.3.


Clone repository and use `*.popclipextz` files to install plugins into [PopClip](https://itunes.apple.com/us/app/popclip/id445189367?mt=12&uo=4&partnerId=30&siteID=vRL5rYo4h5A "PopClip")

## To-do ##

- [ ] Rewrite System Services for accepting and rejecting critic marks
- [ ] Add actions for accepting/rejecting marks in whole document at once
- [X] Actions should not appear in Firefox,Opera and Chrome
- [ ] Except in textarea inside those browsers
- [X] First commit of Last.FM extension
- [ ] Scrobbling selected data to Last.FM
- [ ] alernative action with Option Key for downloading cover arts

## Credits ##

Extension and icons made by [Sebastian Szwarc](https://twitter.com/Behinder).
                                                                                                               

