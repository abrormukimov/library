# R Lib

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<br />
<p align="center">
  <a href="https://github.com/abrormukimov/library">
    <img src="resources/images/microverse.png" alt="Microverse Logo" width="80" height="80">
  </a>
  
  <h3 align="center">R Lib Application</h3>
  
  <p align="center">
    This project is part of the Microverse curriculum in JavaScript course!
    <br />
    <a href="https://github.com/abrormukimov/library"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://abrormukimov.github.io/"><strong>View Live</strong></a>
    <br />
  </p>
</p>

This is a small Library application where the user can add or remove books, edit their author, title, number of pages and toggle a 'Have Read' switch  

<hr />

## Table of Contents

- [About the Project](#about-the-project)
- [Live Version](#live-version)
- [Application Instructions](#application-instructions)
- [System Requierments](#system-requierments)
- [Development](#development)
- [Built With](#built-with)
- [Contributors](#contributors)
- [Acknowledgements](#acknowledgements)

## About The Project  

  The project uses two main classes, Library and Book.  
  The Library class holds an array of Books, manages the additions and deletions of Books, provides information about the total number of Books and the number of Books being read, supplies new IDs for new Books, and stores its data in localStorage.  
  The Book class holds information about a Book, which is the author, the title, the number of pages, and a status denoting if the book has been read.  
  The application's interface is a single view showing a scrolling table of all Books in the storage, a button at the top-right to add new books, a home button at the top-left (usefull when all books are deleted, to re-initialise the library) and an instruction note at the footer to inform the user how to add new Books.  
  Each Book entry in the table shows the Book's data and a trash button to delete the relevant book.  

  The Library and Book classes are implemented in app.js file.

<hr/>

## Live Version

  [View Live](https://abrormukimov.github.io/)

<hr/>

## System Requierments
  - JavaScript Enabled

<hr/>

## Development
  * Clone the project
  ```
    git@github.com:abrormukimov/library.git
    
    Use VSCode and Live Server to show index.html
  ``` 
<hr/>

## Built With

This project was built using these technologies.

  - JavaScript (ES6)
  - HTML5
  - CSS3
  - Git - GitHub
  - ESLint
  - Stylelint

<hr/>

## Contributors

:bust_in_silhouette:
​
## Abror Mukimov

- Github: [@abrormukimov](https://github.com/abrormukimov)
- Twitter: [@abrormukimov](https://twitter.com/abrormukimov)
- Linkedin: [Abror Mukimov](https://www.linkedin.com/in/abror-mukimov/)
​
<hr/>

## Acknowledgements

  - [Microverse](https://www.microverse.org/)
  - [The Odin Project](https://www.theodinproject.com/)
