##Tarea. 

## Luis Trinidad Ortiz Cisneros.

Una Recicladora es responsable de gestionar vistas desechadas o sueltas para rehuso. 

Una visita "Desechada" es una vista que aún está atada a su RecyclerView padre, pero ahora ha sido marcada para remover o rehusarse.

Un uso típico de una recicladora por RecyclerView.LayoutManager será obtener vistas de un sistema adaptador representando los datos por una posición dada o un item ID. Si la vista a ser usada está considerada "sucia" al adaptador le será pedido reenlazarlo. Si no, la vista puede ser rehusada por el LayoutManager sin más trabajo. Las vistas "limpias" que no tengan "requested layout" pueden ser reposicionadas por un LayoutManager con nueva medición.
