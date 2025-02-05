# README - Controle de LEDs com Botão no Raspberry Pi Pico W

## Descrição
Este projeto utiliza um botão para acionar três LEDs (azul, vermelho e verde) no Raspberry Pi Pico. Quando o botão é pressionado, todos os LEDs acendem simultaneamente e depois desligam em sequência a cada 3 segundos.

## Itens utilizados
- Raspberry Pi Pico W
- 3 LEDs (azul, vermelho e verde) com resistores de 330 Ohms
- 1 pushbutton
- Jumpers

## Funcionamento
1. Inicializa os pinos GPIO para os LEDs e o botão.
2. Monitora o botão, fazendo com que quando pressionado, todos os LEDs sejam acessos simultaneamente.
3. Inicia uma sequência de desligamento dos LEDs a cada 3 segundos usando um temporizador.
4. Garante debounce para evitar leituras erradas do botão.

## Autor
Projeto desenvolvido por Marcelo Freitas para atividade da Embarcatech como exemplo de uso de temporizadores one-shot no Raspberry Pi Pico W.

