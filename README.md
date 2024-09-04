# demoBackendSwift

# instalacion de swift 5.10.1 y vapor
# corriendo sobre linux ubuntu 22.04

//api funcional corriendo en http://localhost:8080/api/

//funcional persistencia en base de datos sqlite.

//*****************************************************************
//create (entrada) en http://localhost:8080/api/create

//POST/BODY/JSON (postman)
//	{
//		"nombre": "nombre",
//		"email": "email@email.com"
//	}
	
//*****************************************************************
//listado de entradas en http://localhost:8080/api/getAll

//GET (postman)

//*****************************************************************
//pedido filtrado por email en http://localhost:8080/api/queryEmail

//GET/params/key: (email) /value: (email@email.com)

//*****************************************************************
