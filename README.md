# 🎴 Jogo da Memória

Um jogo da memória simples feito com HTML, CSS e JavaScript puro, sem dependências. Vire as cartas e encontre todos os pares!

## Como jogar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` no navegador (é só dar dois cliques).
3. Clique em duas cartas para virá-las. Se forem iguais, ficam abertas; se não, voltam a se esconder.
4. Encontre todos os pares com o menor número de jogadas e no menor tempo possível.

## Níveis

| Nível   | Pares | Cartas |
|---------|-------|--------|
| Fácil   | 6     | 12     |
| Médio   | 8     | 16     |
| Difícil | 12    | 24     |

O botão **🔄 Reiniciar** embaralha as cartas e começa uma nova partida.

## Recordes

O melhor resultado de cada nível (menos jogadas e, em caso de empate, menor tempo) fica salvo no próprio navegador, usando `localStorage`. Ele não é enviado para nenhum servidor e some se você limpar os dados do site.

## Recursos

- Tema claro e escuro automático, seguindo a configuração do sistema
- Layout que se adapta ao celular
- Animação ao virar as cartas e ao formar um par
