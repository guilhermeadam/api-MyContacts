--> Controller: *Serve para centralizar toda regra de negocio que está relacionado a uma entidade da nossa aplicação.*

-> É uma conveção usar o nome do controller no singular, Ex: ContactController, ProductController...etc.
-> É uma conveção usar nomenclaturas para os metodos dos nossos controllers:

- Métodos -
-> index: Serve para listar todos os registros.
-> show: Serve para obter um registros.
-> store: Serve para criar novo registro.
-> update: Serve para editar um registro.
-> delete: Serve para deletar um registro.

--> Data Source: Fonte de dados (SQL, NoSQL, .Json, API).

--> Repository Pattern: Layer (camada) de abstração de acesso ao Data Source.

Controller <--> Data Source [❌]
Controller <--> Repository <--> Data Source [✅]

--> uuid: Universal Unique ID

--> yarn remove "lib": Para remover libs do projeto.

--> 404 http status code: Not Found.
--> 204 http status code: Sucess, but No Content.

--> Lifecycle de uma requisição: Request <--> Controller <--> Response

--> Middlewares: Serve para manipular os objetos (Request e Response)

Request <--> Middlewares -> Controller -> Response

---> Docker: Comandos basicos.
-> docker image ls: Mostra todas as imagens baixadas.

