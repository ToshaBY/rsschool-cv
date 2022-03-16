# Anton Rybakov

## Contacts
* Phone: +375 33 683 20 24
* E-mail: [anton.rybakou@gmail.com](mailto:anton.rybakou@gmail.com)
* GitHub: [ToshaBY](https://github.com/ToshaBY)
* LinkenIn: [Anton Rybakov](https://www.linkedin.com/in/tosharybakov/)
* Discord: Tosha (@toshaby)

## Skills
* HTML-5 / CSS-3
* JavaScript
* Git / GitHub
* Reactjs / Redux
* Project management

## Code examples
```
// ver 1.0
let arr = [[1, 2, '^^', 5], [3, '^^', '^^'], ['^^', 4, '^^'], ['^^', 5, 6]];

function countCats(array) {
    let count = 0;
    for (let x = 0; x < array.length; x++) {
        for (let y = 0; y < array[x].length; y++) {
            if (array[x][y] === '^^')
                count++
        }
    }
    return count;
}

console.log(countCats(arr));
```
```
// ver final
let arr = [[1, 2, '^^', 5], [3, '^^', '^^'], ['^^', ['^^', 1, 2, ['^^']], '^^'], ['^^', 5, 6]];

function countCats() {
    const result = arr.flat(Infinity).filter(word => word === '^^');
    return result.length;
}

console.log(countCats(arr));
```

## Language
* Russian (native)
* English (B2)

## Education

### X-RAY diffraction analisys of inorganic materials (2014)

> **Lomonosov Moscow State University**
>
> Additional education

### Bachelor of science (2007-2012)

>**Francisk Skorina Gomel State University**
>
>Physicist. Engineer
>
>Laser physics and spectrometry

## Work experience
### Consulting engineer (2018-Present)
>**Theseus Lab s.r.o.**

### Deputy Chief of Central Plant Lab (2017-2018)

### Head of steelcord and wire production department of Central Plant Lab (2016-2017)

### Engineer of X-RAY analysis (2012-2016)
>**OJSC “BSW - management company of “BMC” holding”**