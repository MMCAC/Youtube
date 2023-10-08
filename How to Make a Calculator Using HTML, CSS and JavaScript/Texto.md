HTML ----------------

- 1 div para o background;
- 1 div para a calculadora;
- Criar 1 form;
    - Dentro do form:
        - Criar 6 divs, as quais corresponderão as linhas da calculadora;
        - Dentro da primeira div, colocar um input do tipo "text";
        - Nas divs restantes, criar os inputs como do tipo "button";
        - Dados das divs:
            - Dentro de cada input, deve-se colocar "value" e o "onclick";
                - O "onclick = display.value += 'n'" fará com que, ao clicar, o número venha a ser colocado na div de classe "display"

        - Inputs operadores:
            - Os operadores devem apresentar um comportamento diferente dos demais inputs quando forem acionados.
                - O "AC" deve conter "display.value = ''";
                - O "DE" deve conter "display.value.toString().slice(0, -1)"
                - 0 "=" deve conter "display.value = eval(display.value)"