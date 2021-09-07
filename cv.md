## Andrii Skydanenko

### Contact information

* Address: Mayakovskogo street, Kyiv, Ukraine;
* Phone: [+38 068-944-15-12](tel:+380689441512);
* Email: [Skydanenkoandrii@gmail.com](mailto:Skydanenkoandrii@gmail);
* GitHub: [https://github.com/Skydanenko](https://github.com/Skydanenko).

### About me

I work in EVO.company as content-manager/markup developer. My responsibilities include

* Creation of responsive websites;
* Improvement of existing pages;
* Correction of mistakes and errors in HTML layouts.

My strength are perseverance, attention to details and enthusiasm.

### Skills

* HTML;
* CSS and preprocessors: Stylus/Sass;
* JS(base);
* Webstorm;
* Webpack;
* Zeplin;
* Avocode;
* Figma;
* GitHub.

### Code example

```
const board = document.querySelector('#board');

const colorNumber = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9', 'a', 'b', 'c', 'd', 'e', 'f'];

const SQUARES_NUMBER = 500;


for (let i = 0; i < SQUARES_NUMBER; i++) {
    const square = document.createElement('div');
    square.classList.add('square');
    square.addEventListener('mouseover', () => setColor(square));
    square.addEventListener('mouseleave', () => removeColor(square));
    board.append(square);
}

function setColor(element) {
    const color = getRandomColor();
    element.style.backgroundColor = color;
    element.style.boxShadow = `0 0 2px ${color}, 0 0 10px ${color}`;
}

function removeColor(element) {
    element.style.backgroundColor = '#1d1d1d';
    element.style.boxShadow = `0 0 2px #000`;
}


function getRandomColor() {
    let randomColor = [];
    for (let i = 0; i < 6; i++) {
        const colorNumberIndex = Math.floor(Math.random() * colorNumber.length);
        randomColor.push(colorNumber[colorNumberIndex]);
    }
    return `#${randomColor.join('')}`
}
```

### Work experience

* Content-manager/markup developer - EVO.company;
* Freelance
  * [http://tablichki.com.ua](http://tablichki.com.ua);
  * [http://school.happy-market.com.ua](http://school.happy-market.com.ua).
* Course work
  * [https://skidanenkoandrey.github.io/homeWork8-HTML5-CSS3-/dist](https://skidanenkoandrey.github.io/homeWork8-HTML5-CSS3-/dist);
  * [https://skidanenkoandrey.github.io/homeWork10-Frameworks-/dist](https://skidanenkoandrey.github.io/homeWork10-Frameworks-/dist);

### Education

#### Kiev National University of Technology and Design

* **2007-2011**

Bachelor degree “Enterprise economy”.

* **2011-2012**

Master degree “Enterprise economy”.

#### Courses

* **Cursor Education**

Course Front-End Basic.

### English

* Pre-intermediate (A2);
* I'm learning english words and improving my vocabulary.


