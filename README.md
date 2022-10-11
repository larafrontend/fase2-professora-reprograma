# JavaScript <img src="./assets/js.gif" alt="woo young woo" width="120" height="120" />

Na aulona de hoje trataremos de:

- Funções:

    - Regular Functions
    - Arrow Functions


## Apresentações

### Profs - Sôra - Professora

![Professora](./assets/eu.jpg)

* Paraense / Taurina / 28 anos / Transexual / Dorameira & Army & Otakeira / Estudante de coreano
* Residindo no RS / Ex English teacher / Graduada em arquitetura e urbanismo / Em transição de carreira

[Github](https://github.com/laraof)
[LinkedIn](https://www.linkedin.com/in/lara-oliveira-%F0%9F%8F%B3%EF%B8%8F%E2%80%8D%E2%9A%A7%EF%B8%8F-a653a4121/)
[Instagram](https://www.instagram.com/lara.f.arq/)

<img src="./assets/woo.gif" alt="woo young woo" width="374" height="276" />

### Monitoras - Anjas

<img src="./assets/extraordinaria.gif" alt="woo and friend" width="374" height="276" />

### Alunas - Front-enders

<img src="./assets/attorney-woo.gif" alt="woo to the young to the woo" width=374" height="276" />


## Olha a aula - SE LIGA EM...

<img src="./assets/function.gif" alt="woo young woo" width="410" height="320" />

### Funções

Bloco de código com instruções predefinidas, executável e que pode ser reutilizado.

- Regular Function

    <img src="./assets/regular.gif" alt="regular function" width="374" height="276" />

    ```
        function nameOfFunction(parameter1, parameter2, ..., parameterX) {
                // function's body
        };
    ```

    Conhecida por função regular, justamente por ser a forma tradicional de se escrever uma função em javascript.

    ```
        function soma (a, b) {
            return a + b
        };
    ```
    Para que uma função possa ser executada precisamos invocar (chamar), a mesma. 

    ```
        function soma(a, b) {
            return a + b
        };

        soma(3, 4);
    ```

    Outro exemplo...

    ```
        function leguminosasFavoritas(primeiraLeguminosa, segundaLeguminosa) {
            console.log(`Minhas leguminosas favoritas são ${primeiraLeguminosa} e ${segundaLeguminosa}`)
        };

        leguminosasFavoritas(beterraba, rabanete);
    ```

    Mão no código, manas!!!

- Arrow Function 

    <img src="./assets/arrow.gif" alt="arrow function" width="374" height="276" />

    ```
        const variableName = () => {
            // function's body
        };
    ```

    Forma abreviada de escrever uma função, onde temos de omitir a nomenclatura `function` e não precisamos nomear a função.

    ```
        const soma = (a, b) => {
            return a + b
        };

        console.log(soma);
    ```
    Podemos abreviar ainda mais o bloco de código acima:

    ```
        const soma = (a, b) =>  a + b

        console.log(soma);
    ```

    Outro exemplo...

    ```
        const corDaRoupa = () => ({
            Casaco: "Verde",
            Blusa: "Branca",
            Shorts: "Branco"
            Sapato: "Vermelho"
        });

        console.log(corDaRoupa());
    ```

    Bora dá-lhe no código, manas!!!

    <img src="./assets/example.gif" alt="regular function" width="374" height="276" />


## Referências 

* https://betterprogramming.pub/difference-between-regular-functions-and-arrow-functions-f65639aba256
* https://www.freecodecamp.org/news/javascript-function-iife-parameters-code-blocks-explained/
* https://www.w3schools.com/js/js_functions.asp
* https://dmitripavlutin.com/differences-between-arrow-and-regular-functions/