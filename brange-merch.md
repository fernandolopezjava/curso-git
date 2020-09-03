branch merge rama combina los cambios de la rama actual y la rama especificada en un nuevo commit
  en caso de haber editado archivos diferentes, no se presenta conflicto
  y el commit se emitira sin problemas
  en caso de haber editado el mismo archivo en las mismas lineas de codigo
  se pausara el merge, indicando que se presento un conflicto a resolver
por ende debemos editar dichos archivos, que tendran en su codigo apuntadores
que indiquen cual es el codigo de head y cual es el codigo de la otra rama
