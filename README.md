![AHV-Dev banner](assets/profile-banner.svg)

Soy **Alexsandro Hernández Vargas (AHV-Dev)**, desarrollador de software y de bases de datos. Hago programas que se usan todos los días: sistemas de escritorio, bases de datos, herramientas de análisis y modelos predictivos, automatizaciones, bots y firmware para ESP32. Me gusta resolver el problema completo, desde el modelo de datos y la seguridad hasta la pantalla que usa la persona, y también la diseño: el rediseño de DigLab lo hice en Figma.

**Abierto a trabajo** como desarrollador Jr., administrador de bases de datos (DBA) o soporte de sistemas.

> Entender el pasado, para comprender el presente y construir el futuro.

## En corto

- **Sistema institucional en uso:** DigLab registra el uso de los laboratorios de cómputo del TESCHI, con cuatro roles, modo kiosco, modo sin conexión e instalador propio.
- **Bases de datos:** MySQL con migraciones versionadas y cuentas con el mínimo privilegio; PostgreSQL con Prisma; SQLite con EF Core, SQLx y Microsoft.Data.Sqlite; Parquet para análisis de datos.
- **Diseño UI/UX:** rediseño completo de DigLab en Figma, con sistema de diseño propio (variables de color, componentes con variantes y 20 íconos).
- **Modelos predictivos:** Elo, regresión logística, LightGBM y redes neuronales en PyTorch entrenadas en GPU, evaluados sin ver el futuro.
- **Teoría de juegos:** solver push/fold con CFR+ y una biblioteca GTO de 40,365 flops resueltos.
- **Escritorio:** C#/.NET (WPF y WinForms), Java/JavaFX y Tauri (Rust + Svelte).
- **Backend y automatización:** TypeScript, Node.js, Express, FastAPI y Playwright.
- **Seguridad aplicada:** PBKDF2, scrypt y X25519 + AES-256-GCM.
- **Calidad:** pruebas automatizadas (443 en APH, 115 en Account Controller y 96 en TradingLab).
- **Hardware:** ESP32 en C++ con red WiFi propia, servidor web, relevadores y botones físicos.
- **Ofimática:** paquetería Microsoft Office: Word, Excel, PowerPoint, Outlook, Access, OneNote y Teams.

## Caso de estudio: rediseño de DigLab

<a href="https://www.figma.com/design/bxuhltnX8oO6J6i97vIIv3"><img src="assets/diglab-portada.webp" alt="DigLab: rediseño UI/UX en Figma" width="100%"></a>

DigLab es el sistema que lleva las bitácoras de los laboratorios de cómputo. Lo rediseñé desde cero en Figma para que cada rol vea primero lo que necesita:

- **Administración:** los laboratorios en vivo, las fallas reportadas y las estadísticas de toda la escuela.
- **Docentes:** la clase de ahora con su código, la asistencia del grupo y el estado de cada equipo.
- **Estudiantes:** registran su bitácora en segundos con el código que les da su docente.

El archivo incluye 4 pantallas, un sistema de diseño con 30 variables de color, 8 componentes con variantes y 20 íconos. Los nombres y datos son de ejemplo.

**[Ver el diseño en Figma →](https://www.figma.com/design/bxuhltnX8oO6J6i97vIIv3)**

## Proyectos destacados

Cada proyecto público tiene capturas reales del programa funcionando (con datos de demostración) en su carpeta `docs/evidencia/`.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://www.figma.com/design/bxuhltnX8oO6J6i97vIIv3"><img src="assets/proyectos/diglab.webp" alt="DigLab: pantalla de administración (rediseño)" width="100%"></a><br>
      <a href="https://www.figma.com/design/bxuhltnX8oO6J6i97vIIv3"><strong>DigLab</strong></a> · <sub>código privado (institucional) · diseño en Figma</sub><br>
      Bitácoras de los laboratorios de cómputo del TESCHI: horarios por laboratorio, cuatro roles, modo kiosco, modo sin conexión e instalador propio.<br>
      <sub>C# · WinForms · MySQL · PowerShell · Figma</sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/proyectos/aph.webp" alt="APH: panel principal" width="100%"><br>
      <strong>APH · Analyzer Poker Hands</strong> · <sub>código privado</sub><br>
      Analítica de historiales de póker para Windows: dashboards, perfiles de rivales, reportes PDF y solvers de teoría de juegos (CFR+ y GTO postflop).<br>
      <sub>C# · .NET 8 · WPF · SQLite · 443 pruebas</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/proyectos/lolpred.webp" alt="LoLPred: red neuronal contra regresión logística" width="100%"><br>
      <strong>LoLPred</strong> · <sub>código privado</sub><br>
      Probabilidad de victoria en partidos profesionales de esports con Elo, regresión logística, LightGBM y redes neuronales: 66.5 % de acierto en 53,793 partidas, evaluado sin ver el futuro.<br>
      <sub>Python · PyTorch · LightGBM · scikit-learn · pandas</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/ALL-PUBLISHER"><img src="assets/proyectos/all-publisher.webp" alt="All Publisher: vista previa en cuatro redes" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/ALL-PUBLISHER"><strong>All Publisher</strong></a><br>
      Publica una vez en YouTube, TikTok, Instagram y Facebook: valida cada red, muestra la vista previa en el móvil, programa la publicación y reintenta solo la red que falló.<br>
      <sub>TypeScript · React · Express · Playwright</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/RTA"><img src="assets/proyectos/rta.webp" alt="RTA: backtest con velas e indicadores" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/RTA"><strong>RTA · Real Time Analysis</strong></a><br>
      Análisis de mercado cripto: datos OHLCV, indicadores, 12 estrategias, walk-forward y operación en papel en un panel web.<br>
      <sub>Python · FastAPI · ccxt · Plotly</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/TradingLab"><img src="assets/proyectos/tradinglab.webp" alt="TradingLab: backtest contra referencias" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/TradingLab"><strong>TradingLab</strong></a><br>
      Laboratorio de estrategias sin dinero real: backtests con costos reales, walk-forward y comparación obligatoria contra no operar y contra comprar y mantener.<br>
      <sub>Python · pandas · SQLite · FastAPI · 96 pruebas</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/RFD"><img src="assets/proyectos/rfd.webp" alt="RFD: trámite de CURP" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/RFD"><strong>RFD · Rapid Fetch Desk</strong></a><br>
      Expedientes de clientes: captura los datos una vez, automatiza siete trámites web y guarda cada PDF en su expediente, listo para imprimir.<br>
      <sub>Tauri 2 · Svelte 5 · Rust · SQLx</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/Account-Controller"><img src="assets/proyectos/account-controller.webp" alt="Account Controller: mini app de la bóveda" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/Account-Controller"><strong>Account Controller</strong></a><br>
      Bóveda personal de contraseñas en Telegram: bot y mini app con cifrado protegido por una contraseña maestra.<br>
      <sub>TypeScript · Node.js · Prisma · PostgreSQL · 115 pruebas</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/TaskNotifierApp"><img src="assets/proyectos/task-notifier.webp" alt="Task Notifier: panel principal" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/TaskNotifierApp"><strong>Task Notifier App</strong></a><br>
      Tareas diarias, eventos y notas desde la bandeja de Windows, con recordatorios anticipados y modo oscuro.<br>
      <sub>Java · JavaFX · Gradle</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/esp32-water-doser"><img src="assets/proyectos/esp32-water-doser.webp" alt="ESP32 Water Doser: diagrama de conexiones" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/esp32-water-doser"><strong>ESP32 Water Doser</strong></a><br>
      Firmware que llena un tinaco: crea su propia red WiFi con una página para configurar tiempos y controla la bomba con relevador y botones físicos.<br>
      <sub>C++ · ESP32 · PlatformIO · Arduino</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/proyectos/miaval.webp" alt="MiAval: panel de préstamos" width="100%"><br>
      <strong>MiAval</strong> · <sub>código privado</sub><br>
      Control de préstamos personales: calendario de pagos automático, semáforo por persona y totales del mes.<br>
      <sub>C# · .NET 10 · WPF · EF Core · SQLite</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/Narralynk"><img src="assets/proyectos/narralynk.webp" alt="Narralynk: tablero de capítulos" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/Narralynk"><strong>Narralynk</strong></a> · <sub>prototipo</sub><br>
      Tablero visual para escribir historias por capítulos y escenas, con arrastrar y soltar.<br>
      <sub>React 19 · Zustand · dnd-kit</sub>
    </td>
  </tr>
</table>

## Habilidades

**Lenguajes**<br>
![CSharp](https://img.shields.io/badge/C%23-4cff20?style=for-the-badge&logo=csharp&logoColor=0d1117)
![Python](https://img.shields.io/badge/Python-e8dec2?style=for-the-badge&logo=python&logoColor=0d1117)
![TypeScript](https://img.shields.io/badge/TypeScript-58a6ff?style=for-the-badge&logo=typescript&logoColor=0d1117)
![Java](https://img.shields.io/badge/Java-f2cc60?style=for-the-badge&logo=openjdk&logoColor=0d1117)
![Rust](https://img.shields.io/badge/Rust-21262d?style=for-the-badge&logo=rust&logoColor=f0f3f6)
![CPP](https://img.shields.io/badge/C%2B%2B-39d353?style=for-the-badge&logo=cplusplus&logoColor=0d1117)
![SQL](https://img.shields.io/badge/SQL-4479a1?style=for-the-badge&logoColor=white)

**Bases de datos**<br>
![MySQL](https://img.shields.io/badge/MySQL-4479a1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-58a6ff?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-e8dec2?style=for-the-badge&logo=sqlite&logoColor=0d1117)
![Prisma](https://img.shields.io/badge/Prisma-0f7a55?style=for-the-badge&logo=prisma&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512bd4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQLx](https://img.shields.io/badge/SQLx-39d353?style=for-the-badge&logo=rust&logoColor=0d1117)

**Backend**<br>
![DotNet](https://img.shields.io/badge/.NET-512bd4?style=for-the-badge&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-4cff20?style=for-the-badge&logo=node.js&logoColor=0d1117)
![Express](https://img.shields.io/badge/Express-21262d?style=for-the-badge&logo=express&logoColor=f0f3f6)
![FastAPI](https://img.shields.io/badge/FastAPI-0f7a55?style=for-the-badge&logo=fastapi&logoColor=white)

**Escritorio**<br>
![WPF](https://img.shields.io/badge/WPF-512bd4?style=for-the-badge&logo=dotnet&logoColor=white)
![WinForms](https://img.shields.io/badge/WinForms-512bd4?style=for-the-badge&logo=dotnet&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-f2cc60?style=for-the-badge&logo=openjdk&logoColor=0d1117)
![Tauri](https://img.shields.io/badge/Tauri-24c8db?style=for-the-badge&logo=tauri&logoColor=0d1117)
![Electron](https://img.shields.io/badge/Electron-9feaf9?style=for-the-badge&logo=electron&logoColor=0d1117)

**Web y frontend**<br>
![React](https://img.shields.io/badge/React-58a6ff?style=for-the-badge&logo=react&logoColor=0d1117)
![Next.js](https://img.shields.io/badge/Next.js-21262d?style=for-the-badge&logo=nextdotjs&logoColor=f0f3f6)
![Svelte](https://img.shields.io/badge/Svelte-ffab70?style=for-the-badge&logo=svelte&logoColor=0d1117)
![Astro](https://img.shields.io/badge/Astro-ffab70?style=for-the-badge&logo=astro&logoColor=0d1117)
![Tailwind](https://img.shields.io/badge/Tailwind-58a6ff?style=for-the-badge&logo=tailwindcss&logoColor=0d1117)
![Recharts](https://img.shields.io/badge/Recharts-4cff20?style=for-the-badge&logo=chartdotjs&logoColor=0d1117)

**Datos e inteligencia artificial**<br>
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-f7931e?style=for-the-badge&logo=scikitlearn&logoColor=0d1117)
![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-21262d?style=for-the-badge&logoColor=f0f3f6)

**Automatización y hardware**<br>
![Playwright](https://img.shields.io/badge/Playwright-0f7a55?style=for-the-badge&logo=playwright&logoColor=white)
![PyAutoGUI](https://img.shields.io/badge/PyAutoGUI-e8dec2?style=for-the-badge&logo=python&logoColor=0d1117)
![ESP32](https://img.shields.io/badge/ESP32-21262d?style=for-the-badge&logo=espressif&logoColor=4cff20)
![Arduino](https://img.shields.io/badge/Arduino-00878f?style=for-the-badge&logo=arduino&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-f5822a?style=for-the-badge&logo=platformio&logoColor=0d1117)

**Diseño y herramientas**<br>
![Figma](https://img.shields.io/badge/Figma-a259ff?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/Git-f05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-21262d?style=for-the-badge&logo=github&logoColor=f0f3f6)
![PowerShell](https://img.shields.io/badge/PowerShell-012456?style=for-the-badge&logoColor=white)

**Ofimática (Microsoft Office)**<br>
![Word](https://img.shields.io/badge/Word-2b579a?style=for-the-badge&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logoColor=white)
![PowerPoint](https://img.shields.io/badge/PowerPoint-b7472a?style=for-the-badge&logoColor=white)
![Outlook](https://img.shields.io/badge/Outlook-0078d4?style=for-the-badge&logoColor=white)
![Access](https://img.shields.io/badge/Access-a4373a?style=for-the-badge&logoColor=white)
![OneNote](https://img.shields.io/badge/OneNote-7719aa?style=for-the-badge&logoColor=white)
![Teams](https://img.shields.io/badge/Teams-6264a7?style=for-the-badge&logoColor=white)

## Cómo trabajo

1. **Entender el problema:** hablo con quien lo va a usar y escribo qué debe pasar antes de escribir código.
2. **Diseñar la pantalla:** primero en Figma, con componentes reutilizables, para validar la idea antes de programarla.
3. **Modelar la información:** esquemas versionados por migraciones y datos que sobreviven a errores, cortes de red y apagones.
4. **Construir por fases:** entregas pequeñas, cada una probada antes de pasar a la siguiente.
5. **Medir:** pruebas automatizadas, comparación contra referencias (por ejemplo, contra «no operar») y una bitácora de decisiones.

## Lenguajes

![Gráfica de lenguajes](assets/language-chart.svg)

## Estadísticas

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Alexsandro215&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4cff20&text_color=c9d1d9&icon_color=39d353)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Alexsandro215&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4cff20&text_color=c9d1d9)

## Contacto

[![GitHub](https://img.shields.io/badge/GitHub-Alexsandro215-0d1117?style=for-the-badge&logo=github&logoColor=4cff20)](https://github.com/Alexsandro215)
[![Figma](https://img.shields.io/badge/Portafolio-DigLab%20en%20Figma-0d1117?style=for-the-badge&logo=figma&logoColor=a259ff)](https://www.figma.com/design/bxuhltnX8oO6J6i97vIIv3)
