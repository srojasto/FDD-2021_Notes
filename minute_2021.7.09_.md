## asuntos
- agregar a Saul y Cabanillas
- correo a maciej para preguntar por el estatus de la FEE (TCM y PM)
-  **Beam tuning** Que necesitamos, investigar que es lo más conveniente para FDD, consultar con expertos de electrónica?
- 

## FEE
	- Control Server -> pruebas preliminares con el GUI provicional <- Juan Carlos 
		* TCM -> installada y conectada
		* IPBus -> conectado
		* GBT cables -> buscar e instalar <- Tonatiuh, 
		Maciej email: 
		**Just install them (carefully, because we don't have spares; probably FLP team has some, but within FIT we don't). 
		From the patch-panel on top of the C35 rack to your TCM.
They are located in our room in point 2 (the place where you left the scope), in the bottommost drawer next to FIT cabinet. Please pay attention and take only the fibers, that are labelled for FDD (there are also fibres for FT0 there). You need to find two fibres: 'Rx' and 'Tx' or 'Data'.**
	- ~~Tarjetas: TCM (23.08), PM -> Contactar a Maciej por la tarjeta y atenuador para el GBT (FT0 lab) <- Tonatiuh y David~~
	- DCS 
		Estatus: agegar link del documento excel con el cronograma
		Integración con el control server -> por aprender
	- Conexión del FLP para FDD
	- Compartir en el Twiki el manual de usuario de GUI del Control Server <- buscar y agregar el link al twiki

## DCS
- HV DCS, Universal -> red provisional para el primer desarrollo del DCS
- HV DCS, Conexion del crate a la red del DCS de ALICE -> 8-9 de Sept.
	* Una vez conectado: pruebas con los paneles de GUI y con FSM, para probar su desempeño y adaptar los nuevos requisitos de FIT


## HV
	- Instalación de tarjetas -> done 
		Permisos de experto:  Juan Carlos -> Mario Ivan, Juan Manuel, Saúl (por definir por Peter Chochula y curso?) -> aplica para todo el DCS incluyendo FEE
	- Estatus: 
		a) Se solicitó al DCS-ALICE para instalar/lansar servidor del OPC (estandar de comunicación)
		b) Proyecto listo -> cambios en FSM pendientes por definir -> Se pueden hacer pruebas con el proyecto actual.
		c) Se puede probar el DCS preliminar 2-3 después de tener el permiso (a)
	- Implementar control del PMTs de referencia


## FW

## Infraestructura
	- Definir la numeración y nomeclaturas/etiquetas y documentar
	- Documentar las nomeclaturas: Pad, canal de tarjeta (FEE y HV), PMT (No. serie), etc.. <- homogenizar las nomeclaturas a lo largo de la cadena
	- Calibración laser: ajustar tiempos para sincronizar con FEE


### FDD twiki
-  https://twiki.cern.ch/twiki/bin/view/ALICE/ForwardDiffractiveDetector
