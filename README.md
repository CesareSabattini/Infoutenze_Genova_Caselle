# Infoutenze Genova Caselle
Custom website realized for Davide Gambaro, TEA s.r.l.


## Pages
* Dynamic User Interface, meant to be shown on stations screens.
* Multipage, fully responsive, editor section with transport timetables and ads insertion-deletion feature.
* Language selection interface.


## Main Features:
* The HomePage features: 
1) dynamic timetables insertion and display, with ease-in/ease-out soft animations.
2)  dynamically inserted scrolling text.
3)  Variadic text, automatically translated, based on language selection.

* The Editor features:
1) intuitive interface to compile, modify, insert and delete timetables.
2) ads text management section.
3) minimal sidebar for inner navigation.

* The LanguagePage features:
1) language selection for the HomePage.


## Technologies:
This frontend application is based on ReactJS, mainly styled using CSS and annexed frameworks, such as TailwindCSS and MUI.
The app state is managed with Redux Toolkit, while the traslation feature is brought by DeepL API.
The application is connected to OpenWeatherMap API as well, to serve the HomePage.
