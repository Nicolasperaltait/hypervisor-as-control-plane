# Contexto - hypervisor-as-control-plane

Ficha de lectura rapida: que es, por que existe y que muestra.

## 1. Que es

Diseno y operacion de la capa de virtualizacion de una infraestructura productiva personal (homelab): un hipervisor tratado como control plane, zonas funcionales y storage de maquinas virtuales.

## 2. Por que existe

Mostrar criterio, no codigo: que problema habia, por que importaba, que se
decidio y por que, que salio mal en el camino y como se resolvio. El entorno es
infraestructura productiva -chica, pero con todas sus piezas y funcionando
24/7-; su documentacion es privada y este repo es su version transformada.

## 3. Que muestra

- Hipervisor como pieza critica de infraestructura
- Organizacion del storage de VMs
- Cambios sensibles con evidencia y rollback

## 4. Ficha

| Item | Valor |
| --- | --- |
| Formato | Markdown y diagramas Mermaid, sin codigo |
| Casos de estudio | 1 (migracion de storage con reboot controlado) |
| Perfil al que apunta | Administrador de sistemas, infraestructura, plataforma |
| Estado | Completo, se amplia con casos nuevos |

Ultima actualizacion: 2026-10-04 (criterio del portfolio).
