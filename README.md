# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version : 2.6.5

* System dependencies : Install Elastic Search

* Gems to install : Used "searchkick" for searching user, used "kaminari" for pagination

* rails db:create, rails db:migrate, rails db:seed

* rails s

APIS

- user index
	GET "/api/users"

- user show
	Get 'api/user/:id'

- user create
	post 'api/user'

- user update
	put 'api/user/:id'

- user destroy
	delete 'api/user/:id'

- user search
	get 'api/typeahead/:input'

POSTMAN COLLECTION:
https://www.getpostman.com/collections/b404ed5b3f6232a6ce6c

default post : 3000