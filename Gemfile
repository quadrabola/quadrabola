source 'https://rubygems.org'

gem 'rails', '4.1.4'    # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'pg'                # Use postgresql as the database for Active Record
gem 'jquery-rails'      # Use jquery as the JavaScript library
gem 'turbolinks'        # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'rabl'              # Trabalhando com JSON
gem 'oj'                # Trabalhando com JSON
gem 'json'              # Trabalhando com JSON
gem 'devise'            # Gema para controle do login

group :development do
  gem 'annotate'          # Comentários nos models
  gem 'better_errors'     # Melhor output de erros no browser
  gem 'binding_of_caller' # Melhor output de erros no browser
  gem 'spring'            # Comandos mais rápidos
  gem 'rb-fsevent' if `uname` =~ /Darwin/ # Para MAC OS/X
  gem 'pry'
  gem 'rails-erd'         # Para geração dinâmica do MER
end

group :test do
  gem 'rspec-rails'           # Suite para testes
  gem 'factory_girl_rails'    # Criação de massa de teste
  gem 'spring-commands-rspec' # Integração Spring com RSpec
  gem 'guard'                 # Testes executados durante a alteração dos arquivos
  gem 'guard-rspec'           # Testes executados durante a alteração dos arquivos (plugin para RSpec)
  gem 'guard-spring'          # Testes executados durante a alteração dos arquivos com o Spring
  gem 'database_cleaner'      # Limpa a base de dados a cada execução dos testes
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 4.0.3'    # Use SCSS for stylesheets
  gem 'uglifier', '>= 1.3.0'      # Use Uglifier as compressor for JavaScript assets
  gem 'coffee-rails', '~> 4.0.0'  # Use CoffeeScript for .js.coffee assets and views
end