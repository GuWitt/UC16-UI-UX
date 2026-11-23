# Atividade Prática — Avaliação de UX/UI

## 1ª Heurística de Nielsen: Visibilidade do Status do Sistema

**Objetivo:** Navegar por um e-commerce fictício, simulando uma experiência completa de compra. Durante a navegação, vocês deverão identificar problemas relacionados à visibilidade do status do sistema.

---

## 1. Cadastro e Login

- [v] Criar uma nova conta.
- [v] Tentar cadastrar uma conta com dados inválidos.
- [v] Fazer login com os dados corretos.
- [v] Tentar fazer login com senha incorreta.
- [v] Sair da conta e entrar novamente.

## 2. Navegação e Pesquisa

- [v] Pesquisar um produto pelo nome.
- [v] Pesquisar um produto que não existe.
- [v] Aplicar filtros no catálogo.
- [v] Alterar a ordenação dos produtos.
- [v] Navegar entre diferentes produtos.

## 3. Produtos e Favoritos

- [v] Abrir os detalhes de um produto.
- [v] Adicionar um produto aos favoritos.
- [v] Remover um produto dos favoritos.
- [v] Adicionar diferentes produtos ao carrinho.
- [v] Adicionar o mesmo produto mais de uma vez.

## 4. Carrinho de Compras

- [v] Abrir o carrinho.
- [v] Aumentar a quantidade de um produto.
- [v] Diminuir a quantidade de um produto.
- [v] Remover um produto do carrinho.
- [v] Conferir o valor total da compra.

## 5. Finalização da Compra

- [v] Iniciar o processo de checkout.
- [v] Preencher os dados de entrega.
- [v] Tentar continuar com campos incompletos.
- [v] Selecionar uma forma de pagamento.
- [v] Finalizar a compra simulada.
- [v] Verificar se existe confirmação do pedido.

## 6. Conta e Pedidos

- [v] Consultar os dados da conta.
- [v] Procurar o histórico de pedidos.
- [v] Verificar as informações de uma compra.
- [v] Tentar identificar o status do pedido.

---

## 7. O que observar durante os testes?

Durante cada ação, respondam às seguintes perguntas:

1. O sistema informou que recebeu minha ação?
2. Consigo identificar o que está acontecendo?
3. Sei se a operação foi concluída, está em andamento ou apresentou algum erro?
4. O sistema fornece informações suficientes para que eu saiba o que fazer em seguida?

---

## 8. Entrega da Atividade

Cada aluno ou grupo deverá identificar **pelo menos 8 problemas de usabilidade** relacionados à primeira heurística de Nielsen.

Para cada problema encontrado, registre:

| Item | Descrição |
|---|---|
| **Tela ou funcionalidade** | Onde o problema aconteceu? |
| **Ação realizada** | O que vocês estavam tentando fazer? |
| **Problema identificado** | Qual informação o sistema deixou de apresentar? |
| **Solução proposta** | Como a interface poderia ser melhorada? |

### Modelo de Registro dos Problemas

| Nº | Tela/Funcionalidade | Ação realizada | Problema identificado | Solução proposta |
|---|---|---|---|---|
| 1 | criar conta| conta criada | falta de confirmação de cadastro realizado| confirmar com uma interface a criação da conta|
| 2 | entrar na conta| entrou na conta| não muda nada quando eu entro na conta e não dá para saber se entrou ou não| confirmar o login|
| 3 | inserir item no carrinho| adicionado no carrinho| adiciona e não confirma se adicionou ou não| inserir mensagem de "Adicionado ao carrinho com sucesso!"|
| 4 | favoritar item| favoritei o produto| não alterou nada, nem pintou o coração e não tem lugar para ver os favoritos| criar um local onde mostre os favoritos e pintar o coração de vermelho|
| 5 | entrar na conta| inserir a senha ou email errado| não comunica o erro de senha ou email| comunicar o erro ao usuário para ele saber o que fazer|
| 6 | cadastrar na conta| inserir senha e colocar no confirmar senha outra| não comunica o erro das senhas para o usuário| comunicar o erro da senha no confirmar senha|
| 7 | carrinho| aumentar ou diminuir quantidade| a tela não atualiza e você deve sair dela e voltar para atualizar| atualizar a cada clique a tela|
| 8 | compra| finalizar compra| confirmar que a compra foi concluida com sucesso| notificar o comprador sobre a conclusão de compra|
| 9 | loja, historico de compras| tentar ver descrições| as descrições tanto de produto quanto de compra não são exibidos no site| exibir as descrições dos produtos e dados das compras|
| 10 | conta| ver dados da conta| não são exibidos os dados da conta do usuario| exibir mais informações da conta do usuário|

---

## 9. Orientações Importantes

**Atenção:** Não basta escrever que determinada funcionalidade não funcionou. É necessário explicar qual informação está faltando e como o sistema deveria comunicar seu estado ao usuário.

### Desafio Final

O site possui problemas intencionais de usabilidade. Vocês deverão descobri-los sem receber dicas sobre onde estão.

O objetivo não é apenas identificar falhas, mas também **propor soluções que tornem a experiência do usuário mais clara, intuitiva e confiável.**