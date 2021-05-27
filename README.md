# kabug-rb
Repositório do projeto Kabug com Cucumber, Capybara e Ruby

## Como executar o projeto

* Importante que o Ruby esteja instalado (versão 2.5 ou superior)

### Instalar o Bundler
`
gem install bundler
`

### Instalar as dependências do Ruby(projeto)
`
bundle install
`

### Executar locamente(minha maquina)
`
bundle exec cucumber
`

### Executar no servidor de CI (gerendo reportes JSON)
`
bundler exec cucumber -p ci
`

