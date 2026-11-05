# Central de Controle

Painel do escritório Latinos: a Deborah organiza e o Humberto acompanha.

Site: https://humbertozz.github.io/sistema-organiza-o/

- **Modo Deborah:** pendências, saldos e Pix dos clientes, prospecção (Lumen ERP e Captação), resultados do Facebook, reuniões, operações externas e projetos.
- **Modo Humberto:** pendências pra concluir, Pix pra repassar, contatos pra ligar, pedidos de saldo, resultados e andamento dos projetos.

## Como funciona

- `index.html` é o painel inteiro (uma página só).
- Os dados ficam no Supabase, na tabela `cc_docs`, protegida por login. Só os e-mails cadastrados na tabela `cc_acesso` conseguem ler ou gravar.
- Nenhum dado de cliente fica neste repositório. A chave que aparece no código é a chave pública do Supabase, que sozinha não dá acesso a nada.
