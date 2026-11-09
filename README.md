# Planetitas

Proyecto de Unity 6 con el Universal Render Pipeline (URP).

> **Estado:** recién iniciado. Por ahora el repositorio contiene la plantilla base de URP y todavía no incluye mecánicas, arte ni scripts propios.

## Requisitos

- **Unity 6.6** (rama `6000.6`). La versión exacta está en [`ProjectSettings/ProjectVersion.txt`](ProjectSettings/ProjectVersion.txt).
- **Git LFS**. El repositorio lo usa para imágenes, audio, modelos 3D y otros binarios (ver [`.gitattributes`](.gitattributes)).
- Un editor de C#: Visual Studio o Rider.

## Cómo empezar

1. Instala Git LFS, si todavía no lo tienes:

   ```bash
   git lfs install
   ```

2. Clona el repositorio:

   ```bash
   git clone https://github.com/DerekMerlo/Planetitas.git
   ```

3. En Unity Hub, elige **Add project from disk** y selecciona la carpeta `Planetitas`.
4. Abre `Assets/Scenes/SampleScene.unity` y pulsa **Play**.

La primera vez que abras el proyecto, Unity tardará un poco más porque debe descargar los paquetes y regenerar la carpeta `Library`.

## Estructura

| Ruta | Contenido |
| --- | --- |
| `Assets/Scenes/` | `SampleScene`, con una cámara, una luz direccional y un volumen global |
| `Assets/Settings/` | Configuración de URP, con perfiles para PC y móvil, y perfiles de volumen |
| `Assets/InputSystem_Actions.inputactions` | Acciones de entrada del Input System |
| `Assets/TutorialInfo/` y `Assets/Readme.asset` | Material de bienvenida de la plantilla de Unity |
| `Packages/` | Manifiesto y versiones fijadas de los paquetes |
| `ProjectSettings/` | Configuración del proyecto |

## Tecnologías

- Universal Render Pipeline 17.5
- Input System
- uGUI y Timeline
- AI Navigation
- Visual Scripting
- Unity Test Framework
