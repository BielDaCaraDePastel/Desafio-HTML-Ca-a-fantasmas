# Caçador de Fantasmas: A Masmorra Esquecida

Mini jogo em um único arquivo HTML. Você é um guerreiro que entra em uma masmorra para encontrar um fantasma. O jogo termina quando você chega ao cômodo onde ele está.

## Como jogar

1. Abra `GhostHunter.html` no navegador.
2. Clique em **Entrar na masmorra**.
3. Em cada cômodo, escolha uma saída clicando no cartão ou apertando a tecla **1**, **2**, **3**...
4. Explore até encontrar o fantasma. O jogo não dá dicas.

## O mapa

| Cômodo | Saídas |
|---|---|
| Entrada da Masmorra | Portão de ferro |
| Salão das Tochas | Portão ao sul, Corredor ao norte, Porta a leste |
| Corredor Estreito | Passagem ao sul, Passagem ao norte |
| Refeitório Abandonado | Corredor, Porta central, Porta à direita |
| Cela do Carcereiro | Porta ao norte |
| Cisterna Inundada | Porta ao norte |
| Cripta Antiga (**destino**) | Porta a oeste, Janela gradeada |

A Cela do Carcereiro e a Cisterna Inundada são becos sem saída.

## Personalizar

- **Mudar o destino:** altere `const goalRoom = 'crypt'` no arquivo.
- **Criar um cômodo:** adicione uma entrada em `rooms` (`name`, `desc`, `color`, `exits`) e ligue-o a uma saída existente.
- **Mudar as cores:** edite o campo `color` de cada cômodo.
