## asuntos
- ~~agregar a Saul y Cabanillas -> Solangel~~
- ~~correo a maciej para preguntar por el estatus de la FEE (TCM y PM) -> Solangel~~
- Correo para Chistoph, Ildefonos y Guillermo para preguntar su opinión sobre esto (hacer incapié en que es antes de stable-beam): -> Solangel
	* Esperar correo de cabanillas con discucion con tatiana
	*  **Beam tuning** Que necesitamos, investigar que es lo más conveniente para FDD, consultar con expertos de electrónica? 
	*  **Intermediate state** para los canales de HV: Lo necesitamos?

## FEE
	- Control Server -> pruebas preliminares con el GUI provicional <- Juan Carlos 
		* TCM -> installada y conectada
		* IPBus -> conectado
		* GBT cables -> buscar e instalar <- Tonatiuh, Saul
>**Maciej email:**
>Just install them (carefully, because we don't have spares; probably FLP team has some, but within FIT we don't). 
>From the patch-panel on top of the C35 rack to your TCM.
>They are located in our room in point 2 (the place where you left the scope), in the bottommost drawer next to FIT cabinet. Please pay attention and take only the fibers, that are labelled for FDD (there are also fibres for FT0 there). You need to find two fibres: 'Rx' and 'Tx' or 'Data'.

	- ~~Tarjetas: TCM (23.08), PM -> Contactar a Maciej por la tarjeta y atenuador para el GBT (FT0 lab) <- Tonatiuh y David~~
	- DCS 
		Estatus: agegar link del documento excel con el cronograma
		**Integración con el control server -> por aprender <- Saul y Juan Carlos**
	- Readout/QC: **Conexión del FLP para FDD** <- Michal/Guillermo
	- Compartir en el Twiki el manual de usuario de GUI del Control Server <- buscar y agregar el link al twiki

## DCS
- HV DCS, Universal -> red provisional para el primer desarrollo del DCS
- HV DCS, Conexion del crate a la red del DCS de ALICE -> 8-9 de Sept.
	* Una vez conectado: pruebas con los paneles de GUI y con FSM, para probar su desempeño y adaptar los nuevos requisitos de FIT

### HV
	- Instalación de tarjetas -> done 
		Permisos de experto -> done

	- Estatus: 
		a) Se solicitó al DCS-ALICE para instalar/lanzar servidor del OPC (estandar de comunicación) <- Cambio de conexion en la red (DCS-ALICE)
		b) Proyecto listo -> cambios en FSM pendientes por definir -> Se pueden hacer pruebas con el proyecto actual.
		c) Se puede probar el DCS preliminar 2-3 después de tener el permiso (a)
	- Implementar control del PMTs de referencia

### FEE
## FW

## Infraestructura
	- Definir la numeración y nomeclaturas/etiquetas y documentar -> done
	- Documentar las nomeclaturas: Pad, canal de tarjeta (FEE y HV), PMT (No. serie), etc.. <- homogenizar las nomeclaturas a lo largo de la cadena -> done
	- Calibración laser: 
		* ajustar tiempos para sincronizar con FEE -> calcular los delays <- Solangel
		* Instalar: **cable de control (TCM - attenuador/SW), ref.PMT, dos splitters**, **exta delays** <-Tonatiuh y David
		* Instalar placa de aluminio -> Tonatiuh y David\
	- Instalación de las extensiones de los cables de señal en el lado C
	- Cable de señal del PMT de referencia (x - ns extra)
	


### FDD twiki
-  https://twiki.cern.ch/twiki/bin/view/ALICE/ForwardDiffractiveDetector
