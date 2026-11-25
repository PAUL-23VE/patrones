# 🧱 Principios SOLID en C#

Ejercicios de **principios SOLID** en C# (.NET, Visual Studio). Cada principio tiene una versión que lo incumple (**BAD**) y otra que lo aplica correctamente (**GOOD**), para comparar el diseño.

![C#](https://img.shields.io/badge/C#-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square&logo=visualstudio&logoColor=white)

## 📦 Contenido

La solución está en **`Solucion_Principios_SOLID-main.zip`**. Incluye, entre otros:

- **Inversión de dependencias (DIP):** un servicio de notificaciones que depende de la interfaz `IMessageSender` y no de implementaciones concretas (`EmailSender`, `SMSSender`, `WhatsAppSender`).
- **Segregación de interfaces (ISP):** interfaces pequeñas (`IWorkable`, `IEtable`) para que `Robot` y `Human` implementen solo lo que necesitan.
- **Ejemplo integrador:** desarrolladores (`FrontEndDeveloper`, `BackEndDeveloper`, `MobileDevelop`) que comparten la interfaz `IDeveloper` dentro de un proyecto.

## 🚀 Cómo usarlo

1. Descomprime `Solucion_Principios_SOLID-main.zip`.
2. Abre la solución en Visual Studio y ejecuta el proyecto que quieras revisar.

---

<sub>Parte del portafolio de **Paul Velastegui** · [paul-23ve.github.io](https://paul-23ve.github.io) · [GitHub](https://github.com/PAUL-23VE)</sub>
