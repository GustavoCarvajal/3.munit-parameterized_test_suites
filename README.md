Observaciones:
-Mulesoft tiene un bug que cuando agregas un parametro en global elements de munit, 
va a replicar todos los parametros en el archivo xml, es importante eliminarlos para no generar error.

- Es importante tener en cuenta que si el parametro es creado pero no hay un property file,
  el test case arrojara un error de ese escenario.


  -Se definieron 5 ambientes, en el cual el global xml tiene un configuration properties para el property file y un global properties
  para determinar cual ambiente sera guardado en esa propiedad.
  
