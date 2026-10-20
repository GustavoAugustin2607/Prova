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

### Pelo executável (Windows, sem precisar de Python)

Baixe e abra o arquivo [`executavel/JogoUNO.exe`](executavel/JogoUNO.exe).
Na primeira vez ele pode demorar alguns segundos para abrir.
O Windows pode mostrar o aviso "O Windows protegeu o computador", porque o arquivo não é assinado.
Nesse caso, clique em **Mais informações** e depois em **Executar assim mesmo**.

### Pelo código

```bash
pip install flet
py main.py
```
