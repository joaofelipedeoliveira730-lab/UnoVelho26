# UNO Velho Matematixa — Renovação 7.0

A versão 7.0 mantém o servidor, PostgreSQL, autenticação, inventário, salas e regras existentes. A reforma concentra-se na apresentação e na experiência.

## Direção
- Identidade visual exclusiva em azul + roxo.
- Interface sem emojis: tipografia, luz, geometria e microinterações substituem ícones pictográficos.
- Lobby com profundidade, piso em perspectiva, cartas flutuantes e parallax por ponteiro.
- Mesa com atmosfera cinematográfica, névoa, poeira, cone de luz e vinheta.
- Cartas com elevação, brilho e resposta física ao toque.
- Personagens mantidos como sistema procedural existente, agora apresentados como parte do universo visual.
- Novo arquivo de história dentro do próprio jogo.
- Sons de interface e a trilha existente continuam compatíveis com o sistema atual.

## Banco de dados
Nenhuma tabela principal foi removida ou renomeada. O PostgreSQL continua sendo inicializado pelo `server.js` como antes.

## Compatibilidade
A aplicação continua sendo servida pelo mesmo `server.js` e pelos mesmos endpoints `/api`.
