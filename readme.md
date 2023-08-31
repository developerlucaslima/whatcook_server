# App

What Cook

## RFs (Requisitos funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível consultar receitas a partir de ingredientes selecionados;
- [ ] Deve ser possível enviar dicas de receitas;
- [ ] Deve ser possível filtrar receitas por refeição (café da manhã, almoço, jantar...);
- [ ] Deve ser possível filtrar receitas por região e culturas;
- [ ] Deve ser possível obter o perfil de um usuário logado;

## RNs (Regras de negócio)

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O cadastro não deve ser obrigatório;
- [ ] As receitas podem ou não terem ingredientes além dos selecionados, o usuário escolhe;
- [ ] As receitas devem conter informações nutricionais a partir da tabela TACO;

## RNFs (Requisitos não-funcionais)

- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);