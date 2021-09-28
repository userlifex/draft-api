
public endpoints

  > get '/posts' todos posts 
  > get '/posts/:postId/comments'
  > get '/comments'
  > get 'accounts/:accountId/posts' trae todos los posts de un usuario

endpoints

- accounts

  > get '/' traer todas las cuentas
  *solo moderador*

  > get '/:accountId' trae cuenta especifica
  *solo moderador*

  > put '/:accountId' actualiza cuenta
  *only user*

  > post '/:accountId/posts' crea un post del usuario
  > put '/:accountId/posts/:postId' editar solo los posts que le pertenecen a un usuario

  > get '/:accountId/:postId' editar solo los posts que le pertenecen a un usuario


  > delete '/:accountId/posts' elimina todos los posts de un usuario

  > post '/' crea cuenta
  > delete '/:id' elimina cuenta

- posts
  > get '/' traer todas los post

  > post '/' crear un post con el usuario identificado logeado
  > delete '/:postId' elimina un post del usuario logueado 


- comments


# si eres moderador puedes eliminar comentarios de otros
