# Jogo de cartas com Drag and Drop (Flet) — versão simples com cartas de UNO

## Integrantes

| Nome | RA |
|---|---|
| Gustavo Augustin | 2600865 |
| Gustavo Dutra | 2600766 |
| Antonio Mesquita | 2601815 |
| Danilo Chaves | 2600050 |
| Guilherme Fernando | 2601227 |

## Sobre o projeto

Versão simplificada do [tutorial de Paciência (Solitaire) do Flet](https://flet.dev/docs/tutorials/solitaire/).
A mesa tem 2 slots: o da esquerda começa com 3 cartas de UNO e o da direita começa vazio.
O jogador pega qualquer carta da esquerda, arrasta e solta no slot da direita.
Se a carta for solta longe de um slot, ela volta para a posição original.

## Arquivos

- `main.py`: inicia o aplicativo e adiciona a mesa na página.
- `solitaire.py`: classe `Solitaire` (a mesa, um `ft.Stack`). Cria as cartas e os slots.
- `slot.py`: classe `Slot` (um `ft.Container`). É o lugar onde as cartas ficam.
- `card.py`: classe `Card` (um `ft.GestureDetector`). Contém o drag and drop.
- `assets/images`: imagens das cartas de UNO.

## Como executar

```bash
pip install flet
py main.py
```
