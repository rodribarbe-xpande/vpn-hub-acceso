# Acceso a VPN Hub (Xpande)

Este repositorio existe para **pedir acceso** al repositorio privado de VPN Hub, el concentrador de VPN de Xpande.

👉 [Pedir acceso](https://github.com/rodribarbe-xpande/vpn-hub-acceso/issues/new?template=acceso.yml)

Abrís el pedido con tu cuenta de GitHub. Rodrigo recibe el aviso al instante (correo y app de GitHub), responde
«ok», y te llega por correo la invitación al repositorio `rodribarbe-xpande/vpn-hub`. Después seguís la guía de
instalación que te mandaron.

Cómo funciona por dentro: `.github/workflows/aviso.yml` comenta cada pedido mencionando al dueño;
`.github/workflows/aprobar.yml` invita al autor cuando el dueño comenta «ok» (usa el secreto `VPN_HUB_ADMIN_TOKEN`).

No pongas contraseñas ni claves de VPN acá: no hacen falta para nada.
