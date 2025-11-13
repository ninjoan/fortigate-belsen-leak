# Referencias y Recursos Adicionales

## Avisos Oficiales

* [Aviso de Fortinet PSIRT](https://www.fortiguard.com/psirt/FG-IR-22-377) - Divulgación oficial de la vulnerabilidad.
* [Registro en NIST NVD](https://nvd.nist.gov/vuln/detail/CVE-2022-40684) - Detalles en la Base de Datos Nacional de Vulnerabilidades.

## Análisis Técnico

`CVE-2022-40684` es una vulnerabilidad de **omisión de autenticación** (*authentication bypass*) que afecta a FortiOS, FortiProxy y FortiSwitchManager.

**Versiones Afectadas:**

* **FortiOS:** 7.2.0 a 7.2.1, 7.0.0 a 7.0.6
* **FortiProxy:** 7.2.0, 7.0.0 a 7.0.6
* **FortiSwitchManager:** 7.2.0, 7.0.0

## Cronología

| Fecha | Evento |
| :--- | :--- |
| **Octubre 2022** | Descubrimiento inicial y explotación de la vulnerabilidad. |
| **Enero 2025** | Publicación de las configuraciones de los dispositivos afectados. |

## Pasos de Mitigación

Se debe actualizar *inmediatamente* a las siguientes versiones parcheadas:

* **FortiOS**
    * `7.2.2` o superior
    * `7.0.7` o superior
* **FortiProxy**
    * `7.2.1` o superior
    * `7.0.7` o superior
* **FortiSwitchManager**
    * `7.2.1` o superior
    * `7.0.1` o superior

## Medidas de Seguridad Adicionales

Se recomienda implementar las siguientes acciones como *checklist* de seguridad:

- [ ] Revisar y actualizar todas las credenciales de administrador.
- [ ] Auditar las configuraciones del firewall en busca de cambios no autorizados.
- [ ] Monitorear activamente en busca de indicios de acceso no autorizado.
- [ ] Habilitar y revisar los registros (*logs*) de auditoría y acceso.
