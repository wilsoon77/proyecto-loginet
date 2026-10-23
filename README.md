# LogiNet-CloudTrans - Infraestructura de Telecomunicaciones

Repositorio con los archivos de configuración y topología del proyecto de telecomunicaciones para la empresa LogiGlobal.

## Estructura del Repositorio

* `Proyecto_Final_Telecom_num2.gns3`: Archivo principal de la topología de red para el emulador GNS3.
* `configs/`: Archivos de configuración para los dispositivos de red Cisco IOS:
  * `CORE-A.cfg`: Switch multicapa Core A (HSRP activo, enrutamiento OSPF, SVIs, ACLs).
  * `CORE-B.cfg`: Switch multicapa Core B (HSRP standby, enrutamiento OSPF, SVIs).
  * `SW-DIST-CENTRAL.cfg`: Switch de distribución de Sede Central.
  * `R-BORDE-1.cfg`: Router de borde WAN principal (GRE/IPsec VPN, OSPF).
  * `R-BORDE-2.cfg`: Router de borde WAN de respaldo.
  * `R-NORTE.cfg`: Router de sucursal Centro de Distribución Norte.
  * `R-SUR.cfg`: Router de sucursal Centro de Distribución Sur.
  * `ISP-CLOUD.cfg`: Router emulador de la nube WAN e Internet.
