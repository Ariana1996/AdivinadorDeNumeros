
diferencia entre && y el ternario ? : 
el && valida con cada render, en cambio con el condicional hasta que no modifique
la variable no valida. 

se renderiza cuando cambia un estado o una propiedad que recibe el componente

si pasamos un setter de estado como prop a otro componente hace un render cíclico

memoizar: una copia en memoria de lo anterior

dimensions.get () windows -> todo el dispositivo, screen solo la app

ciclo de vida de componente en react ? 
en que etapa se altera los estados? 
useState hace un renderizado de lo q está afectado.
useRef solo altera ese valor dentro del componente, menor coste que el useState.

useEffect -> función q permite hacer un efecto al momento de algún ciclo de vida del componente. 

el hook pierde su funcionalidad si están en un ciclo de repetición.

usestate = referencia en memoria q permite alterar ese valor para q react sepa q elemento cambió dentro del componente.
la prop se altera el momento de montar el componente 