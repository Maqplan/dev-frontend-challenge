# Teste desenvolvedor front-end

## SAAS usando Angular 2+ para cadastro de lançamentos financeiros

Obs: Você pode salvar os dados de duas formas:

- Criando uma API usando [essas recomendações](https://www.npmjs.com/package/json-server). ( De preferência )
- Excute ***npm run api*** para iniciar um servidor json-server. Você pode saber como usar [aqui](https://www.npmjs.com/package/json-server);

## A Aplicação deverá ter as seguintes telas:

### Crud de lançamentos

Cadastro de despesas e receitas e seus relacionamentos.

    - Descrição
    - Valor
    - Status (Em aberto, quitado, pago)
    - Data vencimento
    - Data pagamento
    - Categoria (id da categoria)
    - Pessoa (id da pessoa)
    - Tipo (debito/credito)

### Crud de pessoa

Pessoa que poderá ser vinculada ao lançamento e se será pessoa física ou jurídica.

    - Nome
    - CPF/CNPJ
    - Tipo de pessoa

### Crud de categorias

Tipo de lançamento, ex: Conta de água, Salário etc.

    - Descrição
    - Tipo (debito/credito)

### Dashboard

Como não existe rota específica para dashboard, você pode usar as rotas GET e fazer a totalização diretamente no component.

    - Descrição
    - Gráfico de despesas x Receitas
    - Lançamentos por categoria
    - Lançamentos por pessoa

### Recomendações

<hr>

- Usar última versão do Angular.
- Usar Bootstap e Angular Material.
- Usar ao máximo tipagem de dados.

### Diferênciais

<hr>

- Usar lazy loading.
- Usar práticas e conceitos Clean Code. Você pode encontrar ajuda com esse assunto [aqui]().
