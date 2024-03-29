# Teste desenvolvedor front-end

## SAAS usando Angular 2+ para cadastro de lançamentos financeiros

Obs: Você pode salvar os dados de duas formas:

- Criando uma API usando [essas recomendações](https://github.com/Maqplan/dev-backend-challenge). ( De preferência )
- Execute ***npm run api*** para iniciar um servidor json-server. Você pode saber como usar [aqui](https://www.npmjs.com/package/json-server), e também existe no repositório uma collection de exemplo;

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
- Usar práticas e conceitos Clean Code. Você pode encontrar ajuda com esse assunto [aqui](https://github.com/Maqplan/dev-backend-challenge/blob/main/helpers/Apresenta%C3%A7%C3%A3o%20geral.pdf).


### Entrega

<hr>

- Compartilhar link do repositório público para o e-mail: engenharia.sistemas@maqplan.com.br;
- Publicar resultado em um servidor de hospedagem gratuito de sua preferência, pode ser Heroko, AWS, GitHub etc;
