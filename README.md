## Navigation Bar with HTML CSS
<p>
This is a basic web development project that creates a navigation bar with HTML and CSS, using the BEM methodology for class structure in CSS. The bar includes a hover effect on the links, which improves the user experience.
</p>

## Table of Contents
1. [Description](#description)
2. [Project Structure](#project-structure)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Installation](#installation)
6. [Screenshot](#screenshot)
7. [Use](#use)
8. [Future Improvements](#future-improvements)
9. [Contributions](#contributions)
10. [License](#license)

### Description
<p>
The navigation bar is designed for websites and allows users to navigate through different sections of a page. It includes four links: Home, About me, contact, blog. In addition to that it has a Button. Hover effects on links change color with a shadow effect when you hover over them, offering an interactive visual experience.
</p>


### Project Structure
The project is organized in the following files and folders:
navigation-bar-project/ │ ├── index.html # Navigation bar HTML structure ├── styles.css # CSS styles and hover effects └── README.md # Project documentation
The structure of this project follows the BEM convention:

- **Bloque Principal**: `.nav` (la barra de navegación completa).
- **Elementos del Bloque**:
- `.list__list`: la lista que contiene los enlaces.
- `.nav__item`: cada elemento de la lista.
- `.nav__link`: el enlace dentro de cada elemento.
- - `.nav__button`: el botón de **Login**.

## Characteristics
- **Interactivity with Hover Effects**: Highlight links when you hover over them.
- **Modularity with BEM**: Use of the BEM methodology to make CSS more structured and reusable.
- **Adaptability**: Easy to customize for different projects and visual styles.
- **Login Button**: Includes a button that simulates a login option.

### Technologies Used
- **HTML**: for the basic structure of the project.
- **CSS3**: for hover styles and effects in the navigation bar.
- **BEM Methodology**: to structure CSS classes in an organized and modular way.

## Facility
To run the project, clone this repository and open `index.html` in your browser:

```
git bash
git clone https://github.com/tuusuario/nombre-del-repositorio.git
cd nombre-del-repositorio
open index.html
```

### Screenshot

### Use
This project can be used as a starting point for a navigation bar on any website, with options to:
- **Home**: Go to the main page of the site.
- **About me**: Provides information about the company or creator.
- **Contact**: Allows users to contact each other.
- **Blog**: Shows a list of posts and projects.
- **Login**: Access to the system (only simulated in this project).

### Future Improvements
Some ideas to improve this project in the future are:
1. Add Responsiveness: Use media queries to optimize the navigation bar on mobile devices.
2. Additional Effects: Add more complex animations or transitions.
3. Dropdown Menus: Include dropdown menus for sections with sublinks.
4. Real Login Functionality: Implement a login form with HTML, CSS and JavaScript.

### Contributions
Contributions are welcome. If you want to improve the project, create a fork, make your changes, and submit a pull request.

### License
This project is licensed under the MIT License.
