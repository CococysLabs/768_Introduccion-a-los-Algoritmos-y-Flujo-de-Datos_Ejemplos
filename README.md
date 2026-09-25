# [768] Introducción a los Algoritmos y Flujo de Datos

Contenido, ejemplos y recursos del curso de Introducción a los Algoritmos y Flujo de Datos, organizado por ciclo académico.

## 📁 Contenido

Cada ciclo tiene su propia carpeta (`Ciclo-AAAA-Semestre`) con el material del curso organizado según la estructura del profesor/catedrático de ese ciclo:

- [Ciclo 2024 - Primer Semestre](Ciclo-2024-Primer-Semestre/Contenido)
- [Ciclo 2024 - Segundo Semestre](Ciclo-2024-Segundo-Semestre/Contenido)
- [Ciclo 2025 - Primer Semestre](Ciclo-2025-Primer-Semestre/Contenido)
- [Ciclo 2025 - Segundo Semestre](Ciclo-2025-Segundo-Semestre/Contenido)
- [Ciclo 2026 - Primer Semestre](Ciclo-2026-Primer-Semestre/Contenido)
- [Ciclo 2026 - Segundo Semestre](Ciclo-2026-Segundo-Semestre/Contenido)

Dentro de cada ciclo se puede encontrar material de clase, proyectos, tareas, prácticas y recursos adicionales.

## 📥 Clonar

### Descargar el repositorio completo

```bash
git clone https://github.com/CococysLabs/768_Introduccion-a-los-Algoritmos-y-Flujo-de-Datos_Ejemplos.git
```

### Descargar solamente un ciclo específico

Si solo necesitas el material de un ciclo, puedes usar sparse-checkout para no traer todo el repositorio:

```bash
git clone --filter=blob:none --sparse https://github.com/CococysLabs/768_Introduccion-a-los-Algoritmos-y-Flujo-de-Datos_Ejemplos.git nombre-carpeta
cd nombre-carpeta
git sparse-checkout set Ciclo-AAAA-Semestre
```

Donde:

- `nombre-carpeta` es el nombre que tendrá la carpeta descargada en tu computadora.
- `Ciclo-AAAA-Semestre` es el ciclo específico que deseas descargar (por ejemplo, `Ciclo-2025-Segundo-Semestre`).

## 🤝 Contribuir

Si deseas contribuir con material para este curso:

1. Fork este repositorio
2. Crea una rama: `git checkout -b feature/agregar-contenido`
3. Agrega tu contenido en el ciclo correspondiente (o crea uno nuevo siguiendo la estructura existente)
4. Commit: `git commit -m "feat: agregar [descripción]"`
5. Push y crea un Pull Request

## 📧 Contacto

- Email: cococys@ingenieria.usac.edu.gt
- Organización: [CococysLabs](https://github.com/CococysLabs)
