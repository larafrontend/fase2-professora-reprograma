# JavaScript

Na aulona de hoje trataremos de:

- Funções:


## Apresentações

### Profs - Sôra - Professora

![Professora](./assets/eu.jpg)

* Paraense / Taurina / 28 anos / Transexual / Dorameira & Army & Otakeira / Estudante de coreano
* Residindo no RS / Ex English teacher / Graduada em arquitetura e urbanismo / Em transição de carreira

<img src="./assets/extraordinaria.gif" alt="woo young woo" width="374" height="276" />

### Monitoras - Anjas

<img src="" alt="" width="" height="" />

### Alunas - Front-enders

<img src="" alt="" width="" height="" />


## Olha a aula - SE LIGA EM...

<img src="./assets/function.gif" alt="woo young woo" width="512" height="399" />

### Funções

Bloco de código com instruções predefinidas, executável e que pode ser reutilizado.

- Regular Function

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

        leguminosasFavoritas(:eggplant:, :corn:);
    ```

    Mão no código, manas!!!

- Arrow Function 

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

## Referências 

* https://betterprogramming.pub/difference-between-regular-functions-and-arrow-functions-f65639aba256