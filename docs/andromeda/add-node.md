# Añadir nodo a Andromeda
## Preparar dependencias
### mDNS
Debes de editar `/etc/avahi/avahi-daemon.conf` para activar `reflector`:

```toml
[reflector]
enable-reflector=yes
```

y reiniciar el proceso ejecutando
```bash
sudo systemctl restart avahi-daemon
```
### Instala Pimox-7
!!! warning "WIP"

    Por el momento no se ha acabado esta sección.
