rails new extinctions

bin/rails generate model Classification name:string

bin/rails generate model Animal classification:references name:string range:string extinction_date:integer

bin/rails generate model CommonName animal:references name:string

bin/rake db:drop db:create db:migrate
bin/rake db:seed

bin/rails console

bin/rails generate controller Classifications name:string

