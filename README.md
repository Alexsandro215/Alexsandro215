![AHV-Dev banner](assets/profile-banner.svg)

Soy **Alexsandro Hernández Vargas (AHV-Dev)**, Ingeniero en Sistemas Computacionales. Construyo software que se usa todos los días: apps de escritorio, herramientas de datos y modelos predictivos, automatizaciones, bots y firmware para ESP32. Me gusta resolver el problema completo, desde la base de datos y la seguridad hasta la pantalla que usa la persona.

> Entender el pasado, para comprender el presente y construir el futuro.

## En corto

- **Sistema institucional en uso:** DigLab registra el uso de los laboratorios de cómputo del TESCHI (roles, modo kiosco, modo sin conexión, instalador propio).
- **Modelos predictivos:** Elo, regresión logística, LightGBM y redes neuronales en PyTorch entrenadas en GPU, evaluados sin ver el futuro.
- **Teoría de juegos:** solver push/fold con CFR+ y una biblioteca GTO de 40,365 flops resueltos.
- **Escritorio:** C#/.NET (WPF y WinForms), Java/JavaFX y Tauri (Rust + Svelte).
- **Backend y automatización:** TypeScript, Node.js, Prisma, PostgreSQL, FastAPI y Playwright.
- **Seguridad aplicada:** PBKDF2, scrypt, X25519 + AES-256-GCM, cuentas de base de datos con el mínimo privilegio.
- **Persistencia:** PostgreSQL con Prisma, MySQL con migraciones versionadas, SQLite (EF Core, SQLx y Microsoft.Data.Sqlite), Parquet y localStorage.
- **Hardware:** ESP32 en C++ con red WiFi propia, servidor web, relevadores y botones físicos.

## Proyectos destacados

Cada proyecto tiene capturas reales del programa funcionando (con datos de demostración) en su carpeta `docs/evidencia/`.

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/proyectos/diglab.webp" alt="DigLab: panel de administración" width="100%"><br>
      <strong>DigLab</strong> · <sub>código privado (institucional)</sub><br>
      Bitácoras de los laboratorios de cómputo del TESCHI: horarios por laboratorio, cuatro roles, modo kiosco y modo sin conexión.<br>
      <sub>C# · WinForms · MySQL · PowerShell</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/APH"><img src="assets/proyectos/aph.webp" alt="APH: panel principal" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/APH"><strong>APH · Analyzer Poker Hands</strong></a><br>
      Analítica de historiales de póker con dashboards, perfiles de rivales, reportes PDF y solvers de teoría de juegos.<br>
      <sub>C# · .NET 8 · WPF · SQLite · 443 pruebas</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/proyectos/lolpred.webp" alt="LoLPred: red neuronal contra regresión logística" width="100%"><br>
      <strong>LoLPred</strong> · <sub>código privado</sub><br>
      Probabilidad de victoria en partidos profesionales de esports. Redes neuronales entrenadas en una RTX 3060: 66.5 % de acierto en 53,793 partidas.<br>
      <sub>Python · PyTorch · LightGBM · scikit-learn</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/ALL-PUBLISHER"><img src="assets/proyectos/all-publisher.webp" alt="All Publisher: vista previa en cuatro redes" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/ALL-PUBLISHER"><strong>All Publisher</strong></a><br>
      Publica una vez en YouTube, TikTok, Instagram y Facebook: valida cada red, vista previa en el móvil y reintenta solo la red que falló.<br>
      <sub>TypeScript · React · Express · Playwright</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/RTA"><img src="assets/proyectos/rta.webp" alt="RTA: backtest con velas e indicadores" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/RTA"><strong>RTA · Real Time Analysis</strong></a><br>
      Análisis de mercado cripto: indicadores, 12 estrategias, walk-forward y operación en papel en un panel web.<br>
      <sub>Python · FastAPI · ccxt · Plotly</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/TradingLab"><img src="assets/proyectos/tradinglab.webp" alt="TradingLab: backtest contra referencias" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/TradingLab"><strong>TradingLab</strong></a><br>
      Laboratorio de estrategias sin dinero real: backtests con costos reales, walk-forward y comparación obligatoria contra no operar.<br>
      <sub>Python · pandas · SQLite · 96 pruebas</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/RFD"><img src="assets/proyectos/rfd.webp" alt="RFD: trámite de CURP" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/RFD"><strong>RFD · Rapid Fetch Desk</strong></a><br>
      Expedientes de clientes y siete trámites web automatizados; cada PDF queda en el expediente, listo para imprimir.<br>
      <sub>Tauri 2 · Svelte 5 · Rust · SQLx</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/Account-Controller"><img src="assets/proyectos/account-controller.webp" alt="Account Controller: mini app de la bóveda" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/Account-Controller"><strong>Account Controller</strong></a><br>
      Bóveda de contraseñas en Telegram con bot y mini app, cifrada con una contraseña maestra.<br>
      <sub>TypeScript · Node.js · Prisma · PostgreSQL · 115 pruebas</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/TaskNotifierApp"><img src="assets/proyectos/task-notifier.webp" alt="Task Notifier: panel principal" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/TaskNotifierApp"><strong>Task Notifier App</strong></a><br>
      Tareas, eventos y notas desde la bandeja de Windows, con avisos anticipados y modo oscuro.<br>
      <sub>Java · JavaFX · Gradle</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alexsandro215/esp32-water-doser"><img src="assets/proyectos/esp32-water-doser.webp" alt="ESP32 Water Doser: diagrama de conexiones" width="100%"></a><br>
      <a href="https://github.com/Alexsandro215/esp32-water-doser"><strong>ESP32 Water Doser</strong></a><br>
      Firmware que llena un tinaco: red WiFi propia con página de configuración, relevador y botones físicos.<br>
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

## Stack técnico

![CSharp](https://img.shields.io/badge/C%23-4cff20?style=for-the-badge&logo=csharp&logoColor=0d1117)
![DotNet](https://img.shields.io/badge/.NET-512bd4?style=for-the-badge&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-e8dec2?style=for-the-badge&logo=python&logoColor=0d1117)
![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-f7931e?style=for-the-badge&logo=scikitlearn&logoColor=0d1117)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0f7a55?style=for-the-badge&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-58a6ff?style=for-the-badge&logo=typescript&logoColor=0d1117)
![Node.js](https://img.shields.io/badge/Node.js-4cff20?style=for-the-badge&logo=node.js&logoColor=0d1117)
![Express](https://img.shields.io/badge/Express-21262d?style=for-the-badge&logo=express&logoColor=f0f3f6)
![Prisma](https://img.shields.io/badge/Prisma-0f7a55?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-58a6ff?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479a1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-e8dec2?style=for-the-badge&logo=sqlite&logoColor=0d1117)
![Java](https://img.shields.io/badge/Java-f2cc60?style=for-the-badge&logo=openjdk&logoColor=0d1117)
![Rust](https://img.shields.io/badge/Rust-21262d?style=for-the-badge&logo=rust&logoColor=f0f3f6)
![Tauri](https://img.shields.io/badge/Tauri-24c8db?style=for-the-badge&logo=tauri&logoColor=0d1117)
![React](https://img.shields.io/badge/React-58a6ff?style=for-the-badge&logo=react&logoColor=0d1117)
![Next.js](https://img.shields.io/badge/Next.js-21262d?style=for-the-badge&logo=nextdotjs&logoColor=f0f3f6)
![Svelte](https://img.shields.io/badge/Svelte-ffab70?style=for-the-badge&logo=svelte&logoColor=0d1117)
![Astro](https://img.shields.io/badge/Astro-ffab70?style=for-the-badge&logo=astro&logoColor=0d1117)
![Tailwind](https://img.shields.io/badge/Tailwind-58a6ff?style=for-the-badge&logo=tailwindcss&logoColor=0d1117)
![Electron](https://img.shields.io/badge/Electron-9feaf9?style=for-the-badge&logo=electron&logoColor=0d1117)
![Playwright](https://img.shields.io/badge/Playwright-0f7a55?style=for-the-badge&logo=playwright&logoColor=white)
![PyAutoGUI](https://img.shields.io/badge/PyAutoGUI-e8dec2?style=for-the-badge&logo=python&logoColor=0d1117)
![SQLx](https://img.shields.io/badge/SQLx-39d353?style=for-the-badge&logo=rust&logoColor=0d1117)
![Recharts](https://img.shields.io/badge/Recharts-4cff20?style=for-the-badge&logo=chartdotjs&logoColor=0d1117)
![ESP32](https://img.shields.io/badge/ESP32-21262d?style=for-the-badge&logo=espressif&logoColor=4cff20)
![CPP](https://img.shields.io/badge/C%2B%2B-39d353?style=for-the-badge&logo=cplusplus&logoColor=0d1117)

## Cómo trabajo

1. **Entender el problema:** hablo con quien lo va a usar y escribo qué debe pasar antes de escribir código.
2. **Modelar la información:** esquemas versionados por migraciones y datos que sobreviven a errores, cortes de red y apagones.
3. **Construir por fases:** entregas pequeñas, cada una probada antes de pasar a la siguiente.
4. **Medir:** pruebas automatizadas, comparación contra referencias (por ejemplo, contra "no operar" o contra el mercado) y una bitácora de decisiones.

## Lenguajes

![Gráfica de lenguajes](assets/language-chart.svg)

## Estadísticas

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Alexsandro215&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4cff20&text_color=c9d1d9&icon_color=39d353)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Alexsandro215&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4cff20&text_color=c9d1d9)

## Contacto

[![GitHub](https://img.shields.io/badge/GitHub-Alexsandro215-0d1117?style=for-the-badge&logo=github&logoColor=4cff20)](https://github.com/Alexsandro215)
