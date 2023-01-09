# Chirp

To start your Phoenix server:

  * Setup the project with `mix setup`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix

------------------------
steps to create an app

-------------------

* mix phx.new [project_name] --live
* y to dependencies
* cd [project_name]
* git init
* code . 
* mix phx.gen.live [module_name] [resource_we _want_to_persist] [resource_we _want_to_persist_in_lower_case_and_plural_form] [field1]:[type] [field2]:[type] [field3]:[type] ...  
* add the live routes by copy-pasting all the routes starting with live... to the location provided
* mix phx.server
* create database
* run migrations for repo
* 