# Plantilla de Taller – Nombre del Taller
> Rellena los campos marcados con «TODO».

## 1. Descripción general
- **Título del taller:** TODO  
- **Duración:** TODO (ej. 3 h 30 m)  
- **Modalidad:** TODO (virtual / presencial / híbrida)  
- **Audiencia objetivo:** TODO (nivel y roles)  

## 2. Estructura del repositorio
| Carpeta | ¿Qué colocar aquí? | Fecha límite (relativa) |
|---------|--------------------|-------------------------|
| `01-info` | `objetivos.md`, `esquema.md` | T-4 sem |
| `02-slides/draft` | PDF/PPTX borrador | T-2 sem |
| `03-labs` | VM OVA **o** scripts cloud + `guia-lab.md` | T-2 sem |
| `05-ensayo` | Vídeo ensayo 15 min | T-10 d |
| `06-entregable-final` | Slides PDF + guías + quiz | T-7 d |

> Las carpetas `00-admin` y `99-logs` las gestiona el coordinador.

## 3. Convenciones de archivo
- **Slides**: `nombre_taller_vX.pdf`  
- **VM**: `lab-nombre_taller_vX.ova`  
- **Scripts**: prefijo numérico para orden (`01_recon.ps1`)  
- **Vídeos**: `ensayo-15min.mp4` (máx. 200 MB)

## 4. Pasos para colaborar
1. **Fork** este repositorio en tu cuenta.  
2. Trabaja en una branch `feature/<tu-nombre>`.  
3. Haz *commit* frecuente; cada cambio significativo ⇒ `git push`.  
4. Abre un **pull request** hacia `main` antes de cada checkpoint.  
5. El coordinador hará *merge* tras la revisión.

## 5. Cronograma resumido
```text
T-6 sem   Kick-off
T-4 sem   Objetivos & esquema
T-3 sem   Labs/plataforma cerrados
T-2 sem   Slides borrador + recursos
T-10 d    Vídeo ensayo
T-7 d     Paquete final
T-5 d     Tech-check asistentes
T-0       Taller en vivo
```

## 6. Checklist previo a envío final
- [ ] Slides en PDF sin animaciones excesivas  
- [ ] Lab verificado en host limpio / sandbox OK  
- [ ] Guías incluyen respuestas y tiempos estimados  
- [ ] Credenciales **dummy** y reseteables  
- [ ] Vídeo ensayo reproduce todas las demos sin fallos  

## 7. Contacto
Cualquier duda abre un *Issue* etiquetado **question** o escribe a `coordinador@ejemplo.com`.
