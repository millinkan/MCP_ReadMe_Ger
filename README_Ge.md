# Fantastische MCP-Server [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![ไทย](https://img.shields.io/badge/Thai-Click-blue)](README-th.md)
[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![繁體中文](https://img.shields.io/badge/繁體中文-點擊查看-orange)](README-zh_TW.md)
[![Duetsch](https://img.shields.io/badge/German-Click-blueviolet)](README.md)
[![简体中文](https://img.shields.io/badge/简体中文-点击查看-orange)](README-zh.md)
[![日本語](https://img.shields.io/badge/日本語-クリック-青)](README-ja.md)
[![한국어](https://img.shields.io/badge/한국어-클릭-yellow)](README-ko.md)
[![Português Brasileiro](https://img.shields.io/badge/Português_Brasileiro-Clique-green)](README-pt_BR.md)
[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)

Eine kuratierte Liste fantastischer Model Context Protocol (MCP) Server.

* [Was ist MCP?](#what-is-mcp)
* [Clients](#clients)
* [Tutorials](#tutorials)
* [Community](#community)
* [Legende](#legend)
* [Server-Implementierungen](#server-implementations)
* [Frameworks](#frameworks)
* [Tipps & Tricks](#tips-and-tricks)

## Was ist MCP?

[MCP](https://modelcontextprotocol.io/) ist ein offenes Protokoll, das es KI-Modellen ermöglicht, sicher mit lokalen und entfernten Ressourcen über standardisierte Server-Implementierungen zu interagieren. Diese Liste konzentriert sich auf produktionsreife und experimentelle MCP-Server, die KI-Fähigkeiten durch Dateizugriff, Datenbankverbindungen, API-Integrationen und andere kontextbezogene Dienste erweitern.

## Clients

Schauen Sie sich [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients/) und [glama.ai/mcp/clients](https://glama.ai/mcp/clients) an.

> \[!TIP]
> [Glama Chat](https://glama.ai/chat) ist ein multimodaler KI-Client mit MCP-Unterstützung & [AI Gateway](https://glama.ai/gateway).

## Tutorials

* [Model Context Protocol (MCP) Schnellstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)
* [Einrichtung der Claude Desktop App zur Verwendung einer SQLite-Datenbank](https://youtu.be/wxCCzo9dGj0)

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

## Legende

* 🎖️ – Offizielle Implementierung
* Programmiersprache
    * 🐍 – Python-Codebasis
    * 📇 – TypeScript (oder JavaScript) Codebasis
    * 🏎️ – Go-Codebasis
    * 🦀 – Rust-Codebasis
    * #️⃣ - C#-Codebasis
    * ☕ - Java-Codebasis
* Geltungsbereich
    * ☁️ - Cloud-Dienst
    * 🏠 - Lokaler Dienst
    * 📟 - Eingebettete Systeme
* Betriebssystem
    * 🍎 – Für macOS
    * 🪟 – Für Windows
    * 🐧 - Für Linux

> \[!NOTE]
> Unsicher bezüglich Lokal 🏠 vs. Cloud ☁️?
> * Verwenden Sie Lokal, wenn der MCP-Server mit lokal installierter Software kommuniziert, z. B. die Kontrolle über den Chrome-Browser übernimmt.
> * Verwenden Sie Netzwerk, wenn der MCP-Server mit entfernten APIs kommuniziert, z. B. Wetter-API.

## Server-Implementierungen

> \[!NOTE]
> Wir haben jetzt ein [webbasiertes Verzeichnis](https://glama.ai/mcp/servers), das mit dem Repository synchronisiert ist.

* 🔗 - [Aggregatoren](#aggregators)
* 🎨 - [Kunst & Kultur](#art-and-culture)
* 📂 - [Browser-Automatisierung](#browser-automation)
* ☁️ - [Cloud-Plattformen](#cloud-platforms)
* 👨‍💻 - [Code-Ausführung](#code-execution)
* 🤖 - [Coding-Agenten](#coding-agents)
* 🖥️ - [Befehlszeile](#command-line)
* 💬 - [Kommunikation](#communication)
* 👤 - [Kundendatenplattformen](#customer-data-platforms)
* 🗄️ - [Datenbanken](#databases)
* 📊 - [Datenplattformen](#data-platforms)
* 🚚 - [Lieferung](#delivery)
* 🛠️ - [Entwicklerwerkzeuge](#developer-tools)
* 🧮 - [Data-Science-Werkzeuge](#data-science-tools)
* 📟 - [Eingebettetes System](#embedded-system)
* 📂 - [Dateisysteme](#file-systems)
* 💰 - [Finanzen & Fintech](#finance--fintech)
* 🎮 - [Gaming](#gaming)
* 🧠 - [Wissen & Gedächtnis](#knowledge--memory)
* 🗺️ - [Ortungsdienste](#location-services)
* 🎯 - [Marketing](#marketing)
* 📊 - [Überwachung](#monitoring)
* 🎥 - [Multimedia-Prozess](#multimedia-process)
* 🔎 - [Suche & Datenextraktion](#search)
* 🔒 - [Sicherheit](#security)
* 🌐 - [Soziale Medien](#social-media)
* 🏃 - [Sport](#sports)
* 🎧 - [Support & Service Management](#support-and-service-management)
* 🌎 - [Übersetzungsdienste](#translation-services)
* 🎧 - [Text-zu-Sprache](#text-to-speech)
* 🚆 - [Reisen & Transport](#travel-and-transportation)
* 🔄 - [Versionskontrolle](#version-control)
* 🛠️ - [Andere Werkzeuge und Integrationen](#other-tools-and-integrations)

### 🔗 <a name="aggregators"></a>Aggregatoren

Server für den Zugriff auf viele Apps und Tools über einen einzigen MCP-Server.

* [julien040/anyquery](https://github.com/julien040/anyquery) 🏎️ 🏠 ☁️ - Fragen Sie mehr als 40 Apps mit einer einzigen Binärdatei über SQL ab. Es kann auch eine Verbindung zu Ihrer PostgreSQL-, MySQL- oder SQLite-kompatiblen Datenbank herstellen. Lokal-zuerst und privat konzipiert.
* [metatool-ai/metatool-app](https://github.com/metatool-ai/metatool-app) 📇 ☁️ 🏠 🍎 🪟 🐧 - MetaMCP ist der eine vereinheitlichte Middleware-MCP-Server, der Ihre MCP-Verbindungen mit einer GUI verwaltet.
* [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) - Verbinden und vereinheitlichen Sie Daten über verschiedene Plattformen und Datenbanken hinweg mit [MindsDB als einzigem MCP-Server](https://docs.mindsdb.com/mcp/overview).
* [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) ☁️ 📇 🍎 🪟 🐧 - Eine Liste von MCP-Servern, damit Sie Ihren Client fragen können, welche Server Sie zur Verbesserung Ihres täglichen Arbeitsablaufs verwenden können.
* [wegotdocs/open-mcp](https://github.com/wegotdocs/open-mcp) 📇 🏠 🍎 🪟 🐧 - Verwandeln Sie eine Web-API in 10 Sekunden in einen MCP-Server und fügen Sie ihn dem Open-Source-Register hinzu: https://open-mcp.org
* [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream/tree/master/modelcontextprotocol) ☁️ 🏠 - Verbinden Sie sich mit 2.500 APIs mit über 8.000 vorgefertigten Tools und verwalten Sie Server für Ihre Benutzer in Ihrer eigenen App.
* [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) 📇 🏠 - Ein umfassender Proxy-Server, der mehrere MCP-Server in einer einzigen Schnittstelle mit umfangreichen Sichtbarkeitsfunktionen kombiniert. Er bietet Erkennung und Verwaltung von Tools, Prompts, Ressourcen und Vorlagen über Server hinweg sowie einen Playground zum Debuggen beim Erstellen von MCP-Servern.
* [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) 📇 🏠 - Ein Proxy-Tool zum Zusammensetzen mehrerer MCP-Server zu einem vereinheitlichten Endpunkt. Skalieren Sie Ihre KI-Tools durch Lastverteilung von Anfragen über mehrere MCP-Server, ähnlich wie Nginx für Webserver funktioniert.
* [MetaMCP](https://github.com/metatool-ai/metatool-app) 📇 ☁️ 🏠 🍎 🪟 🐧 - MetaMCP ist der eine vereinheitlichte Middleware-MCP-Server, der Ihre MCP-Verbindungen mit einer GUI verwaltet.
* [WayStation-ai/mcp](https://github.com/waystation-ai/mcp) ☁️ 🍎 🪟 - Verbinden Sie Claude Desktop und andere MCP-Hosts nahtlos und sicher mit Ihren bevorzugten Apps (Notion, Slack, Monday, Airtable usw.). Dauert weniger als 90 Sekunden.
* [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) 📇 ☁️ 🏠 🍎 🪟 🐧 - Verwandeln Sie einen Webdienst mit einem Klick in einen MCP-Server, ohne Codeänderungen vorzunehmen.
* [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) 📇 🏠 🪟 🍎 🐧 - Ein leistungsstarkes Bildgenerierungstool unter Verwendung der Imagen 3.0 API von Google über MCP. Generieren Sie hochwertige Bilder aus Textaufforderungen mit erweiterten Steuerelementen für Fotografie, künstlerische und fotorealistische Darstellungen.
* [SureScaleAI/openai-gpt-image-mcp](https://github.com/SureScaleAI/openai-gpt-image-mcp) 📇 ☁️ - OpenAI GPT Bildgenerierungs-/Bearbeitungs-MCP-Server.

### 🎨 <a name="art-and-culture"></a>Kunst & Kultur

Zugriff und Erkundung von Kunstsammlungen, Kulturerbe und Museumsdatenbanken. Ermöglicht KI-Modellen die Suche und Analyse von künstlerischen und kulturellen Inhalten.

* [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) 🐍 🏠 🪟 🐧 - Ein lokaler MCP-Server, der Animationen mit Manim generiert.
* [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) 🐍 - Hinzufügen, Analysieren, Suchen und Generieren von Videobearbeitungen aus Ihrer Video-Jungle-Sammlung.
* [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) 📇 ☁️ - MCP-Server zur Interaktion mit der Discogs-API.
* [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server) 📇 ☁️ MCP-Server zur Interaktion mit dem Quran.com-Korpus über die offizielle REST-API v4.
* [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) 📇 ☁️ - Integration der Metropolitan Museum of Art Collection API zur Suche und Anzeige von Kunstwerken in der Sammlung.
* [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) 📇 ☁️ - Rijksmuseum API-Integration für Kunstwerksuche, Details und Sammlungen.
* [r-huijts/oorlogsbronnen-mcp](https://github.com/r-huijts/oorlogsbronnen-mcp) 📇 ☁️ - Oorlogsbronnen (Kriegsquellen) API-Integration für den Zugriff auf historische WWII-Aufzeichnungen, Fotos und Dokumente aus den Niederlanden (1940-1945).
* [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) 🐍 - MCP-Server-Integration für DaVinci Resolve, die leistungsstarke Werkzeuge für Videobearbeitung, Farbkorrektur, Medienverwaltung und Projektsteuerung bietet.
* [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) 📇 ☁️ - Ein MCP-Server, der die AniList-API für Anime- und Manga-Informationen integriert.
* [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) 🐍 🏠 - MCP-Server, der die Aseprite-API zur Erstellung von Pixelkunst verwendet.
* [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) 📇 ☁️ - Ein MCP-Server und eine Erweiterung ermöglichen die Steuerung von NVIDIA Isaac Sim, Lab, OpenUSD usw. in natürlicher Sprache.
* [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library) 📇 ☁️ - Ein MCP-Server für die Open Library API, der es KI-Assistenten ermöglicht, nach Buchinformationen zu suchen.
* [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) 🐍 🏠 - MCP-Server für Autodesk Maya.
* [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) 📇 🏠 ☁️ 🍎 🪟 - Bietet umfassende und genaue Bazi (Chinesische Astrologie) Charting- und Analysefunktionen.

### 📂 <a name="browser-automation"></a>Browser-Automatisierung

Funktionen für den Zugriff auf Webinhalte und deren Automatisierung. Ermöglicht das Suchen, Scraping und Verarbeiten von Webinhalten in KI-freundlichen Formaten.

* [xspadex/bilibili-mcp](https://github.com/xspadex/bilibili-mcp.git) 📇 🏠 - Ein FastMCP-basiertes Tool, das die angesagtesten Videos von Bilibili abruft und über eine standardmäßige MCP-Schnittstelle bereitstellt.
* [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) 📇 🏠 - Ein MCP-Server, der die Suche nach Bilibili-Inhalten unterstützt. Bietet LangChain-Integrationsbeispiele und Testskripte.
* [aircodelabs/grasp](https://github.com/aircodelabs/grasp) 📇 🏠 - Selbstgehosteter Browser mit Agenten mit integrierter MCP- und A2A-Unterstützung.
* [automatalabs/mcp-server-playwright](https://github.com/Automata-Labs-team/MCP-Server-Playwright) 🐍 - Ein MCP-Server für die Browser-Automatisierung mit Playwright.
* [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) 🐍 - Ein MCP-Python-Server mit Playwright für die Browser-Automatisierung, besser geeignet für LLMs.
* [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) 🎖️ 📇 - Automatisieren Sie Browser-Interaktionen in der Cloud (z. B. Webnavigation, Datenextraktion, Formularausfüllung und mehr).
* [browsermcp/mcp](https://github.com/browsermcp/mcp) 📇 🏠 - Automatisieren Sie Ihren lokalen Chrome-Browser.
* [co-browser/browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server) 🐍 - browser-use verpackt als MCP-Server mit SSE-Transport. Enthält ein Dockerfile zum Ausführen von Chromium in Docker + einen VNC-Server.
* [executeautomation/playwright-mcp-server](https://github.com/executeautomation/mcp-playwright) 📇 - Ein MCP-Server mit Playwright für Browser-Automatisierung und Webscraping.
* [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) 📇 🏠 - Ein MCP-Server gepaart mit einer Browser-Erweiterung, die es LLM-Clients ermöglicht, den Browser des Benutzers (Firefox) zu steuern.
* [fradser/mcp-server-apple-reminders](https://github.com/FradSer/mcp-server-apple-reminders) 📇 🏠 🍎 - Ein MCP-Server zur Interaktion mit Apple Reminders unter macOS.
* [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp) 🐍 🏠 - Extrahieren Sie strukturierte Daten von jeder Website. Einfach prompten und JSON erhalten.
* [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) 📇 ☁️ - Rufen Sie YouTube-Untertitel und Transkripte für die KI-Analyse ab.
* [kimtth/mcp-aoai-web-Browse](https://github.com/kimtth/mcp-aoai-web-Browse) 🐍 🏠 - Eine `minimale` Server/Client-MCP-Implementierung mit Azure OpenAI und Playwright.
* [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) - Offizieller Microsoft Playwright MCP-Server, der es LLMs ermöglicht, über strukturierte Zugänglichkeits-Snapshots mit Webseiten zu interagieren.
* [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) 📇 🏠 - Browser-Automatisierung für Web-Scraping und Interaktion.
* [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) 📇 🏠 - Ein MCP-Server zur Interaktion mit Manifest v2-kompatiblen Browsern.
* [pskill9/web-search](https://github.com/pskill9/web-search) 📇 🏠 - Ein MCP-Server, der kostenlose Websuchen über Google-Suchergebnisse ermöglicht, ohne dass API-Schlüssel erforderlich sind.
* [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) 📇 🏠 🍎 - Eine MCP-Server-Integration mit Apple Shortcuts.

### ☁️ <a name="cloud-platforms"></a>Cloud-Plattformen

Integration von Cloud-Plattformdiensten. Ermöglicht die Verwaltung und Interaktion mit Cloud-Infrastruktur und -Diensten.

* [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) 🐍 ☁️ - Ein MCP, der auf Qiniu Cloud-Produkten basiert und den Zugriff auf Qiniu Cloud Storage, Medienverarbeitungsdienste usw. unterstützt.
* [alexbakers/mcp-ipfs](https://github.com/alexbakers/mcp-ipfs) 📇 ☁️ - Hochladen und Bearbeiten von IPFS-Speicher.
* [VmLia/books-mcp-server](https://github.com/VmLia/books-mcp-server) 📇 ☁️ - Dies ist ein MCP-Server zum Abfragen von Büchern, der in gängigen MCP-Clients wie Cherry Studio angewendet werden kann.
* [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) 🐍 ☁️ - Ein leichter, aber leistungsstarker Server, der es KI-Assistenten ermöglicht, AWS CLI-Befehle auszuführen, Unix-Pipes zu verwenden und Prompt-Vorlagen für gängige AWS-Aufgaben in einer sicheren Docker-Umgebung mit Multi-Architektur-Unterstützung anzuwenden.
* [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) 🐍 - Ein leichter, aber robuster Server, der KI-Assistenten befähigt, Kubernetes-CLI-Befehle (`kubectl`, `helm`, `istioctl` und `argocd`) sicher über Unix-Pipes in einer sicheren Docker-Umgebung mit Multi-Architektur-Unterstützung auszuführen.
* [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) 🎖️ 🐍 ☁️ - Ein MCP-Server, der es KI-Assistenten ermöglicht, Ressourcen in der Alibaba Cloud zu betreiben und ECS, Cloud Monitor, OOS sowie weit verbreitete Cloud-Produkte unterstützt.
* [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) 🐍 ☁️ - Ein VMware ESXi/vCenter-Verwaltungsserver basierend auf MCP (Model Control Protocol), der einfache REST-API-Schnittstellen für die Verwaltung virtueller Maschinen bereitstellt.
* [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) 🎖️ 📇 ☁️ - Integration mit Cloudflare-Diensten einschließlich Workers, KV, R2 und D1.
* [flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) - 📇 ☁️/🏠 TypeScript-Implementierung von Kubernetes-Cluster-Operationen für Pods, Deployments, Services.
* [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) - 📇 ☁️/🏠 - Ein Model Context Protocol-Server zum Abfragen und Analysieren von Azure-Ressourcen im großen Maßstab mithilfe von Azure Resource Graph, der es KI-Assistenten ermöglicht, die Azure-Infrastruktur zu erkunden und zu überwachen.
* [jdubois/azure-cli-mcp](https://github.com/jdubois/azure-cli-mcp) - Ein Wrapper um die Azure CLI-Befehlszeile, der es Ihnen ermöglicht, direkt mit Azure zu kommunizieren.
* [johnneerdael/netskope-mcp](https://github.com/johnneerdael/netskope-mcp) 🔒 ☁️ - Ein MCP, um Zugriff auf alle Netskope Private Access-Komponenten innerhalb einer Netskope Private Access-Umgebung zu gewähren, einschließlich detaillierter Setup-Informationen und LLM-Beispielen zur Verwendung.
* [manusa/Kubernetes MCP Server](https://github.com/manusa/kubernetes-mcp-server) - 🏎️ 🏠 Ein leistungsstarker Kubernetes MCP-Server mit zusätzlicher Unterstützung für OpenShift. Neben der Bereitstellung von CRUD-Operationen für **jede** Kubernetes-Ressource bietet dieser Server spezielle Tools zur Interaktion mit Ihrem Cluster.
* [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) - 🦀 🏠 - Ein Terraform MCP-Server, der es KI-Assistenten ermöglicht, Terraform-Umgebungen zu verwalten und zu betreiben, einschließlich Lesen von Konfigurationen, Analysieren von Plänen, Anwenden von Konfigurationen und Verwalten des Terraform-Status.
* [pulumi/mcp-server](https://github.com/pulumi/mcp-server) 🎖️ 📇 🏠 - MCP-Server zur Interaktion mit Pulumi über die Pulumi Automation API und die Pulumi Cloud API. Ermöglicht MCP-Clients die programmatische Durchführung von Pulumi-Operationen wie das Abrufen von Paketinformationen, das Anzeigen von Änderungen in der Vorschau, das Bereitstellen von Updates und das Abrufen von Stack-Ausgaben.
* [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) - 🐍 ☁️/🏠 Ein Model Context Protocol (MCP) Server für Kubernetes, der es KI-Assistenten wie Claude, Cursor und anderen ermöglicht, über natürliche Sprache mit Kubernetes-Clustern zu interagieren.
* [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) - 🏎️ ☁️/🏠 Kubernetes-Cluster-Operationen über MCP.
* [thunderboltsid/mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix) - 🏎️ 🏠/☁️ Go-basierter MCP-Server zur Interaktion mit Nutanix Prism Central-Ressourcen.
* [weibaohui/k8m](https://github.com/weibaohui/k8m) - 🏎️ ☁️/🏠 Bietet MCP-Multi-Cluster-Kubernetes-Management und -Operationen, mit einer Verwaltungsschnittstelle, Protokollierung und fast 50 integrierten Tools für gängige DevOps- und Entwicklungsszenarien. Unterstützt sowohl Standard- als auch CRD-Ressourcen.
* [weibaohui/kom](https://github.com/weibaohui/kom) - 🏎️ ☁️/🏠 Bietet MCP-Multi-Cluster-Kubernetes-Management und -Operationen. Es kann als SDK in Ihr eigenes Projekt integriert werden und enthält fast 50 integrierte Tools für gängige DevOps- und Entwicklungsszenarien. Unterstützt sowohl Standard- als auch CRD-Ressourcen.
* [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) 🏎️ ☁️/🏠 MCP-Server für Kubernetes-Management und Analyse der Cluster- und Anwendungsgesundheit.
* [erikhoward/adls-mcp-server](https://github.com/erikhoward/adls-mcp-server) - 🐍 ☁️/🏠 MCP-Server für Azure Data Lake Storage. Kann Container verwalten, Lese-/Schreib-/Upload-/Download-Operationen für Containerdateien durchführen und Dateimetadaten verwalten.
* [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) 🏎️ ☁️/🏠 MCP-K8S ist ein KI-gesteuertes Kubernetes-Ressourcenmanagement-Tool, das es Benutzern ermöglicht, beliebige Ressourcen in Kubernetes-Clustern durch natürliche Sprachinteraktion zu bedienen, einschließlich nativer Ressourcen (wie Deployment, Service) und benutzerdefinierter Ressourcen (CRD). Sie müssen sich keine komplexen Befehle merken - beschreiben Sie einfach Ihre Anforderungen, und die KI führt die entsprechenden Cluster-Operationen präzise aus, was die Benutzerfreundlichkeit von Kubernetes erheblich verbessert.
* [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) 📇 ☁️ - Verwalten Sie Ihre Redis Cloud-Ressourcen mühelos über natürliche Sprache. Erstellen Sie Datenbanken, überwachen Sie Abonnements und konfigurieren Sie Cloud-Bereitstellungen mit einfachen Befehlen.
* [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) - 🏎️ ☁️/🏠 Ein leistungsstarker MCP-Server, der es KI-Assistenten ermöglicht, nahtlos mit Portainer-Instanzen zu interagieren und natürlichen Sprachzugriff auf Container-Management, Bereitstellungsoperationen und Infrastrukturüberwachungsfunktionen bietet.

### 👨‍💻 <a name="code-execution"></a>Code-Ausführung

Code-Ausführungsserver. Ermöglichen LLMs die Ausführung von Code in einer sicheren Umgebung, z.B. für Coding-Agenten.

* [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai/tree/main/mcp-run-python) 🐍 🏠- Führen Sie Python-Code über MCP-Tool-Aufrufe in einer sicheren Sandbox aus.
* [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) 🎖️ 📇 ☁️ - Führen Sie jeden von LLMs generierten Code in einer sicheren und skalierbaren Sandbox-Umgebung aus und erstellen Sie Ihre eigenen MCP-Tools mit JavaScript oder Python, mit voller Unterstützung für NPM- und PyPI-Pakete.
* [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) 🏎️ ☁️ - OpenAPI-MCP: Dockerisierter MCP-Server, der es Ihrem KI-Agenten ermöglicht, auf jede API mit vorhandener API-Dokumentation zuzugreifen.
* [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) 📇 🏠 – Ein Node.js MCP-Server, der isolierte Docker-basierte Sandboxes zur Ausführung von JavaScript-Snippets mit On-the-fly-Installation von npm-Abhängigkeiten und sauberem Teardown startet.

### 🤖 <a name="coding-agents"></a>Coding-Agenten

Vollständige Coding-Agenten, die es LLMs ermöglichen, Code zu lesen, zu bearbeiten und auszuführen sowie allgemeine Programmieraufgaben völlig autonom zu lösen.

* [oraios/serena](https://github.com/oraios/serena)🐍🏠 - Ein voll ausgestatteter Coding-Agent, der auf symbolischen Code-Operationen durch die Verwendung von Sprachservern basiert.
* [ezyang/codemcp](https://github.com/ezyang/codemcp) 🐍🏠 - Coding-Agent mit grundlegenden Lese-, Schreib- und Befehlszeilenwerkzeugen.
* [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) 📇 ☁️ - Ein MCP-Server, der es KI-Modellen ermöglicht, LeetCode-Probleme zu suchen, abzurufen und zu lösen. Unterstützt Metadatenfilterung, Benutzerprofile, Einreichungen und Zugriff auf Wettbewerbsdaten.
* [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) 📇 ☁️ - MCP-Server, der automatisierten Zugriff auf die Programmierprobleme, Lösungen, Einreichungen und öffentlichen Daten von **LeetCode** ermöglicht, mit optionaler Authentifizierung für benutzerspezifische Funktionen (z. B. Notizen), unterstützt sowohl `leetcode.com` (global) als auch `leetcode.cn` (China).
* [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) 📇 🏠 - Ein MCP-Server, der es KIs wie Claude ermöglicht, die Verzeichnisstruktur in einem VS Code-Arbeitsbereich zu lesen, von Linter(n) und dem Sprachserver erkannte Probleme anzuzeigen, Codedateien zu lesen und Änderungen vorzunehmen.

### 🖥️ <a name="command-line"></a>Befehlszeile

Führen Sie Befehle aus, erfassen Sie die Ausgabe und interagieren Sie anderweitig mit Shells und Befehlszeilenwerkzeugen.

* [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) 🖥️ 🛠️ 💬 - Ein Model Context Protocol-Server, der Zugriff auf iTerm bietet. Sie können Befehle ausführen und Fragen zu dem stellen, was Sie im iTerm-Terminal sehen.
* [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) 📇 🏠 - Führen Sie beliebige Befehle mit den Tools `run_command` und `run_script` aus.
* [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) - Sicherer Python-Interpreter basierend auf HF Smolagents `LocalPythonExecutor`.
* [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) 🐍 🏠 - Befehlszeilenschnittstelle mit sicherer Ausführung und anpassbaren Sicherheitsrichtlinien.
* [OthmaneBlial/term_mcp_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) 🐍 🏠 - Ein DeepSeek MCP-ähnlicher Server für das Terminal.
* [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) - Ein sicherer Shell-Befehlsausführungsserver, der das Model Context Protocol (MCP) implementiert.
* [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) - Cisco pyATS-Server, der strukturierte, modellgetriebene Interaktion mit Netzwerkgeräten ermöglicht.
* [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) 📇 🏠 🍎 🪟 🐧 - Ein Schweizer Taschenmesser, das Programme verwalten/ausführen und Code- sowie Textdateien lesen/schreiben/suchen/bearbeiten kann.

### 💬 <a name="communication"></a>Kommunikation

Integration mit Kommunikationsplattformen für Nachrichtenverwaltung und Kanaloperationen. Ermöglicht KI-Modellen die Interaktion mit Teamkommunikationswerkzeugen.

* [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) ☁️ - Ein Nostr MCP-Server, der die Interaktion mit Nostr ermöglicht, das Posten von Notizen und mehr erlaubt.
* [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) 🐍 ☁️ - Interagieren Sie mit der Twitter-Suche und der Timeline.
* [agentmail-toolkit/mcp](https://github.com/agentmail-to/agentmail-toolkit/tree/main/mcp) 🐍 💬 - Ein MCP-Server zum Erstellen von Posteingängen im Handumdrehen zum Senden, Empfangen und Ausführen von Aktionen für E-Mails. Wir sind keine KI-Agenten für E-Mail, sondern E-Mail für KI-Agenten.
* [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) 📇 ☁️ - Ein MCP-Server zur Anbindung an die Google Tasks API.
* [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) 🏠 🍎 🚀 - Ein MCP-Server, der sicher über das Model Context Protocol (MCP) mit Ihrer iMessage-Datenbank kommuniziert und es LLMs ermöglicht, iMessage-Konversationen abzufragen und zu analysieren. Er umfasst eine robuste Telefonnummernvalidierung, Anhangverarbeitung, Kontaktverwaltung, Gruppenchat-Handhabung sowie volle Unterstützung für das Senden und Empfangen von Nachrichten.
* [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) 🏎️ 🏠 - Telegram API-Integration für den Zugriff auf Benutzerdaten, Verwaltung von Dialogen (Chats, Kanäle, Gruppen), Abrufen von Nachrichten und Handhabung des Lesestatus.
* [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) 🐍 🏠 - Telegram API-Integration für den Zugriff auf Benutzerdaten, Verwaltung von Dialogen (Chats, Kanäle, Gruppen), Abrufen von Nachrichten, Senden von Nachrichten und Handhabung des Lesestatus.
* [elie222/inbox-zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) 🐍 ☁️ - Ein MCP-Server für Inbox Zero. Fügt Gmail Funktionen hinzu, wie z.B. herauszufinden, auf welche E-Mails Sie antworten müssen oder bei denen Sie nachhaken müssen.
* [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) 📇 ☁️ 🏠 - Ein ntfy MCP-Server zum Senden/Abrufen von ntfy-Benachrichtigungen an Ihren selbst gehosteten ntfy-Server von KI-Agenten 📤 (unterstützt sichere Token-Authentifizierung & mehr - Verwendung mit npx oder docker!).
* [gotoolkits/wecombot](https://github.com/gotoolkits/mcp-wecombot-server.git) 🚀 ☁️ - Eine MCP-Serveranwendung, die verschiedene Arten von Nachrichten an den WeCom-Gruppenroboter sendet.
* [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) 🐍 🏠 🍎 - Ein MCP-Server, der sicheren Zugriff auf Ihre iMessage-Datenbank über das Model Context Protocol (MCP) bietet und es LLMs ermöglicht, iMessage-Konversationen mit korrekter Telefonnummernvalidierung und Anhangbehandlung abzufragen und zu analysieren.
* [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) 🐍 🏠 - Ein MCP-Server zusammen mit einem MCP-Host, der Zugriff auf Mattermost-Teams, -Kanäle und -Nachrichten bietet. Der MCP-Host ist als Bot in Mattermost integriert und hat Zugriff auf konfigurierbare MCP-Server.
* [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) 🐍 🏎️ - Ein MCP-Server zum Durchsuchen Ihrer persönlichen WhatsApp-Nachrichten, Kontakte und zum Senden von Nachrichten an Einzelpersonen oder Gruppen.
* [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) 🎖 📇 ☁️ - MCP-Server zur Integration des LINE Official Account.
* [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) 🐍 ☁️ - Integration mit Gmail und Google Kalender.
* [modelcontextprotocol/server-bluesky](https://github.com/keturiosakys/bluesky-context-server) 📇 ☁️ - Bluesky-Instanzintegration zur Abfrage und Interaktion.
* [modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) 📇 ☁️ - Slack-Workspace-Integration für Kanalmanagement und Nachrichtenübermittlung.
* [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) 📇 ☁️ - Der leistungsstärkste MCP-Server für Slack Workspaces.
* [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) - 📇 🏠 Dies ist ein MCP-Server zur Interaktion mit der VRChat-API. Sie können Informationen über Freunde, Welten, Avatare und mehr in VRChat abrufen.
* [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) 📇 ☁️ - Ein MCP-Server zur Anbindung an die Google Kalender API. Basiert auf TypeScript.
* [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) - Der MCP-Server, der Sie informiert hält, indem er Benachrichtigungen über ntfy an Ihr Telefon sendet.
* [userad/didlogic_mcp](https://github.com/UserAd/didlogic_mcp) 🐍 ☁️ - Ein MCP-Server für [DIDLogic](https://didlogic.com). Fügt Funktionen zur Verwaltung von SIP-Endpunkten, Nummern und Zielen hinzu.
* [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) 📇 ☁️ - Ein MCP-Server zur Verwaltung von Google Tasks.
* [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) 🐍 ☁️ - MCP-Server, der Microsoft Teams Messaging integriert (lesen, posten, erwähnen, Mitglieder und Threads auflisten).
* [softeria/ms-365-mcp-server](https://github.com/softeria/ms-365-mcp-server) 📇 ☁️ - MCP-Server, der sich über die Graph-API mit der gesamten Microsoft 365 Suite verbindet (einschließlich Mail, Dateien, Excel, Kalender).
* [YCloud-Developers/ycloud-whatsapp-mcp-server](https://github.com/YCloud-Developers/ycloud-whatsapp-mcp-server) 📇 🏠 - MCP-Server für die WhatsApp Business Platform von YCloud.
* [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) 🐍 🏠 - MCP-Server für Product Hunt. Interagieren Sie mit Trendbeiträgen, Kommentaren, Sammlungen, Benutzern und mehr.

### 👤 <a name="customer-data-platforms"></a>Kundendatenplattformen

Bietet Zugriff auf Kundenprofile innerhalb von Kundendatenplattformen.

* [iaptic/mcp-server-iaptic](https://github.com/iaptic/mcp-server-iaptic) 🎖️ 📇 ☁️ - Verbinden Sie sich mit [iaptic](https://www.iaptic.com), um nach Kundeneinkäufen, Transaktionsdaten und App-Umsatzstatistiken zu fragen.
* [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) 🐍 ☁️ - Verbinden Sie beliebige offene Daten mit jedem LLM über das Model Context Protocol.
* [sergehuber/inoyu-mcp-unomi-server](https://github.com/sergehuber/inoyu-mcp-unomi-server) 📇 ☁️ - Ein MCP-Server zum Zugriff auf und zur Aktualisierung von Profilen auf einem Apache Unomi CDP-Server.
* [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) 🐍 ☁️ - Ein MCP-Server zur Interaktion mit einem Tinybird Workspace von jedem MCP-Client aus.
* [@antv/mcp-server-chart](https://github.com/antvis/mcp-server-chart) 🎖️ 📇 ☁️ - Ein Model Context Protocol-Server zur Generierung visueller Diagramme mit [AntV](https://github.com/antvis).

### 🗄️ <a name="databases"></a>Datenbanken

Sicherer Datenbankzugriff mit Schema-Inspektionsfunktionen. Ermöglicht das Abfragen und Analysieren von Daten mit konfigurierbaren Sicherheitskontrollen einschließlich schreibgeschütztem Zugriff.

* [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven) - 🐍 ☁️ 🎖️ - Navigieren Sie durch Ihre [Aiven-Projekte](https://go.aiven.io/mcp-server) und interagieren Sie mit den Diensten PostgreSQL®, Apache Kafka®, ClickHouse® und OpenSearch®.
* [alexanderzuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) - Supabase MCP-Server mit Unterstützung für SQL-Abfrageausführung und Datenbank-Explorationswerkzeugen.
* [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) ☕ 🐍 ☁️ - MCP-Dienst für Tablestore, Funktionen umfassen das Hinzufügen von Dokumenten, semantische Suche nach Dokumenten basierend auf Vektoren und Skalaren, RAG-freundlich und serverless.
* [benborla29/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) ☁️ 🏠 - MySQL-Datenbankintegration in NodeJS mit konfigurierbaren Zugriffskontrollen und Schema-Inspektion.
* [bytebase/dbhub](https://github.com/bytebase/dbhub) 📇 🏠 – Universeller Datenbank-MCP-Server, der gängige Datenbanken unterstützt.
* [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) 🐍 ☁️ - TiDB-Datenbankintegration mit Schema-Inspektion und Abfragefunktionen.
* [Canner/wren-engine](https://github.com/Canner/wren-engine) 🐍 🦀 🏠 - Die semantische Engine für Model Context Protocol (MCP) Clients und KI-Agenten.
* [centralmind/gateway](https://github.com/centralmind/gateway) 🏎️ 🏠 🍎 🪟 - MCP- und MCP SSE-Server, der automatisch eine API basierend auf Datenbankschema und Daten generiert. Unterstützt PostgreSQL, Clickhouse, MySQL, Snowflake, BigQuery, Supabase.
* [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) 🐍 ☁️ 🏠 - DICOM-Integration zum Abfragen, Lesen und Verschieben von medizinischen Bildern und Berichten von PACS und anderen DICOM-konformen Systemen.
* [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) 🎖️ 🐍 ☁️ 🏠 - Chroma MCP-Server für den Zugriff auf lokale und Cloud-Chroma-Instanzen für Abruffunktionen.
* [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) 🐍 ☁️ - ClickHouse-Datenbankintegration mit Schema-Inspektion und Abfragefunktionen.
* [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) 🐍 ☁️ - Confluent-Integration zur Interaktion mit Confluent Kafka und Confluent Cloud REST APIs.
* [Couchbase-Ecosystem/mcp-server-couchbase](https://github.com/Couchbase-Ecosystem/mcp-server-couchbase) 🎖️ 🐍 ☁️ 🏠 - Der Couchbase MCP-Server bietet einheitlichen Zugriff auf sowohl Capella Cloud- als auch selbstverwaltete Cluster für Dokumentoperationen, SQL++-Abfragen und Datenanalyse in natürlicher Sprache.
* [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) 🐍 🏠 - MCP-Server-Implementierung, die Elasticsearch-Interaktion bereitstellt.
* [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) 🐍 🏠 - All-in-One MCP-Server für Postgres-Entwicklung und -Betrieb, mit Werkzeugen für Leistungsanalyse, Tuning und Gesundheitsprüfungen.
* [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) 🐍 ☁️ - Trino MCP-Server zum Abfragen und Zugreifen auf Daten aus Trino-Clustern.
* [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) 🏎️ ☁️ - Eine Go-Implementierung eines Model Context Protocol (MCP) Servers für Trino.
* [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) 🐍 🏠 - MySQL-Datenbankintegration mit konfigurierbaren Zugriffskontrollen, Schema-Inspektion und umfassenden Sicherheitsrichtlinien.
* [wenb1n-dev/mysql_mcp_server_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro) 🐍 🏠 - Unterstützt SSE, STDIO; nicht nur auf MySQLs CRUD-Funktionalität beschränkt; beinhaltet auch Datenbank-Ausnahmeanalysefähigkeiten; steuert Datenbankberechtigungen basierend auf Rollen; und erleichtert Entwicklern die Erweiterung von Werkzeugen durch Anpassung.
* [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) 📇 🏠 - Airtable-Datenbankintegration mit Schema-Inspektion, Lese- und Schreibfähigkeiten.
* [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) 📇 ☁️ - Nocodb-Datenbankintegration, Lese- und Schreibfähigkeiten.
* [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) 📇 ☁️ - Server-Implementierung für die Google BigQuery-Integration, die direkten BigQuery-Datenbankzugriff und Abfragefähigkeiten ermöglicht.
* [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) 📇 🏠 - Node.js-basierte MySQL-Datenbankintegration, die sichere MySQL-Datenbankoperationen bietet.
* [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) 📇 ☁️ - Fireproof Ledger-Datenbank mit Multi-User-Synchronisation.
* [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) 🏎️ 🏠 – Ein hochleistungsfähiger Multi-Datenbank-MCP-Server, der mit Golang erstellt wurde und MySQL & PostgreSQL unterstützt (NoSQL folgt in Kürze). Enthält integrierte Werkzeuge für Abfrageausführung, Transaktionsmanagement, Schema-Erkundung, Abfrageerstellung und Leistungsanalyse, mit nahtloser Cursor-Integration für verbesserte Datenbank-Workflows.
* [furey/mongodb-lens](https://github.com/furey/mongodb-lens) 📇 🏠 - MongoDB Lens: Voll ausgestatteter MCP-Server für MongoDB-Datenbanken.
* [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) 🔥 ⛅️ - Firebase-Dienste einschließlich Auth, Firestore und Storage.
* [get-convex/convex-backend](https://stack.convex.dev/convex-mcp-server) 📇 ☁️ - Convex-Datenbankintegration zur Introspektion von Tabellen, Funktionen und Ausführung einmaliger Abfragen ([Quelle](https://github.com/get-convex/convex-backend/blob/main/npm-packages/convex/src/cli/mcp.ts)).
* [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) 🏎️ ☁️ - Open-Source-MCP-Server, spezialisiert auf einfache, schnelle und sichere Werkzeuge für Datenbanken.
* [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) 🐍 🏠 - MCP-Server zum Abfragen von GreptimeDB.
* [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) 🐍 🏠 - Ein MCP-Server, der sicheren, schreibgeschützten Zugriff auf SQLite-Datenbanken über das Model Context Protocol (MCP) bietet. Dieser Server basiert auf dem FastMCP-Framework, das es LLMs ermöglicht, SQLite-Datenbanken mit integrierten Sicherheitsfunktionen und Abfragevalidierung zu erkunden und abzufragen.
* [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) 📇 ☁️ 🏠 - Führen Sie Abfragen gegen die InfluxDB OSS API v2 aus.
* [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) 🐍 ☁️ - Snowflake-Integration, die Lese- und (optionale) Schreiboperationen sowie Insight-Tracking implementiert.
* [joshuarileydev/supabase-mcp-server](https://github.com/joshuarileydev/supabase) - Supabase MCP-Server zur Verwaltung und Erstellung von Projekten und Organisationen in Supabase.
* [jovezhong/mcp-timeplus](https://github.com/jovezhong/mcp-timeplus) 🐍 ☁️ - MCP-Server für Apache Kafka und Timeplus. Kann Kafka-Topics auflisten, Kafka-Nachrichten abrufen, Kafka-Daten lokal speichern und Streaming-Daten mit SQL über Timeplus abfragen.
* [KashiwaByte/vikingdb-mcp-server](https://github.com/KashiwaByte/vikingdb-mcp-server) 🐍 ☁️ - VikingDB-Integration mit Einführung in Sammlungen und Indizes, Vektorspeicher- und Suchfähigkeiten.
* [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) 📇 🏠 - Ein Model Context Protocol Server für MongoDB.
* [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) 🐍 🏠 - DuckDB-Datenbankintegration mit Schema-Inspektion und Abfragefähigkeiten.
* [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) 🐍 ☁️ - BigQuery-Datenbankintegration mit Schema-Inspektion und Abfragefähigkeiten.
* [quarkiverse/mcp-server-jdbc](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc) ☕ 🏠 - Verbinden Sie sich mit jeder JDBC-kompatiblen Datenbank und fragen Sie ab, fügen Sie ein, aktualisieren, löschen Sie und mehr.
* [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) 📇 🏠 - Model Context Protocol (MCP) Server, der umfassende Interaktionsmöglichkeiten mit SQLite-Datenbanken bietet.
* [memgraph/mcp-memgraph](https://github.com/memgraph/mcp-memgraph) 🐍 🏠 - Memgraph MCP-Server - enthält ein Werkzeug zum Ausführen einer Abfrage gegen Memgraph und eine Schema-Ressource.
* [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) 📇 🏠 - PostgreSQL-Datenbankintegration mit Schema-Inspektion und Abfragefähigkeiten.
* [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) 🐍 🏠 - SQLite-Datenbankoperationen mit integrierten Analysefunktionen.
* [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) 🐍 🏠 - Model Context Protocol mit Neo4j (Abfragen ausführen, Knowledge Graph Memory, Neo4j Aura-Instanzen verwalten).
* [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) 📇 ☁️ — Ein MCP-Server zum Erstellen und Verwalten von Postgres-Datenbanken mit Neon Serverless Postgres.
* [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) MCP-Server für Nikes Postgres-Plattform - Verwalten und Abfragen von Postgres-Datenbanken, Mandanten, Benutzern, Authentifizierung mit LLMs.
* [openlink/mcp-server-odbc](https://github.com/OpenLinkSoftware/mcp-odbc-server) 🐍 🏠 - Ein MCP-Server für generische Konnektivität zu Datenbankmanagementsystemen (DBMS) über das Open Database Connectivity (ODBC) Protokoll.
* [openlink/mcp-server-sqlalchemy](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) 🐍 🏠 - Ein MCP-Server für generische Konnektivität zu Datenbankmanagementsystemen (DBMS) über SQLAlchemy mittels Python ODBC (pyodbc).
* [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) 🐍 ☁️ - Abfragen und Analysieren von Azure Data Explorer-Datenbanken.
* [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) 🐍 ☁️ - Abfragen und Analysieren von Prometheus, dem Open-Source-Überwachungssystem.
* [prisma/prisma](https://github.com/prisma/prisma) 🐍 🏠 - Gibt LLMs die Möglichkeit, Prisma Postgres-Datenbanken zu verwalten (z. B. neue Datenbankinstanzen starten oder Schemamigrationen ausführen).
* [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) 🐍 🏠 - Ein Qdrant MCP-Server.
* [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) 📇 🏠 - MongoDB-Integration, die es LLMs ermöglicht, direkt mit Datenbanken zu interagieren.
* [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) 🐍 ☁️ - Verbinden Sie KI-Tools direkt mit Airtable. Fragen Sie Datensätze ab, erstellen, aktualisieren und löschen Sie sie mithilfe natürlicher Sprache. Zu den Funktionen gehören Basisverwaltung, Tabellenoperationen, Schemamanipulation, Datensatzfilterung und Datenmigration über eine standardisierte MCP-Schnittstelle.
* [redis/mcp-redis](https://github.com/redis/mcp-redis) 🐍 🏠 - Der offizielle Redis MCP-Server bietet eine Schnittstelle zur Verwaltung und Suche von Daten in Redis.
* [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) 🐍 🏠 - Universelle SQLAlchemy-basierte Datenbankintegration, die PostgreSQL, MySQL, MariaDB, SQLite, Oracle, MS SQL Server und viele weitere Datenbanken unterstützt. Bietet Schema- und Beziehungsinspektion sowie Analysefunktionen für große Datensätze.
* [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) 🐍 ☁️ - Pinecone-Integration mit Vektorsuchfähigkeiten.
* [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) 🎖️ 📇 ☁️ - Offizieller Supabase MCP-Server, um KI-Assistenten direkt mit Ihrem Supabase-Projekt zu verbinden und ihnen zu ermöglichen, Aufgaben wie Tabellenverwaltung, Konfigurationsabruf und Datenabfragen durchzuführen.
* [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) 🐍 🏠 Universeller Datenbank-MCP-Server, der mehrere Datenbanktypen unterstützt, einschließlich PostgreSQL, Redshift, CockroachDB, MySQL, RDS MySQL, Microsoft SQL Server, BigQuery, Oracle DB und SQLite.
* [tradercjz/dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server) 🐍 ☁️ - TDolphinDB-Datenbankintegration mit Schema-Inspektion und Abfragefähigkeiten.
* [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) 🐍 📇 ☁️ - Ein MCP-Server zur Verbindung mit Ihren Weaviate-Sammlungen als Wissensbasis sowie zur Verwendung von Weaviate als Chat-Speicher.
* [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) 📇 ☁️ — Ein MCP-Server, der das Abrufen von Daten aus einer Datenbank mithilfe von Abfragen in natürlicher Sprache unterstützt, angetrieben von XiyanSQL als Text-zu-SQL-LLM.
* [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) 🐍 ☁️ - Ein Model Context Protocol-Server zur Interaktion mit Google Sheets. Dieser Server bietet Werkzeuge zum Erstellen, Lesen, Aktualisieren und Verwalten von Tabellenkalkulationen über die Google Sheets API.
* [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) 🏎️ 🏠 – Einfach zu bedienender, abhängigkeitsfreier MySQL MCP-Server, der mit Golang erstellt wurde, mit konfigurierbarem Schreibschutzmodus und Schema-Inspektion.
* [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) 🐍 🏠 ☁️ - MCP-Server für Milvus / Zilliz, der die Interaktion mit Ihrer Datenbank ermöglicht.
* [openlink/mcp-server-jdbc](https://github.com/OpenLinkSoftware/mcp-jdbc-server) 🐍 🏠 - Ein MCP-Server für generische Konnektivität zu Datenbankmanagementsystemen (DBMS) über das Java Database Connectivity (JDBC) Protokoll.
* [yincongcyincong/VictoriaMetrics-mcp-server](https://github.com/yincongcyincong/VictoriaMetrics-mcp-server) 🐍 🏠 - Ein MCP-Server zur Interaktion mit der VictoriaMetrics-Datenbank.
* [hydrolix/mcp-hydrolix](https://github.com/hydrolix/mcp-hydrolix) 🎖️ 🐍 ☁️ - Hydrolix Zeitreihen-Datalake-Integration, die Schema-Erkundung und Abfragefähigkeiten für LLM-basierte Workflows bereitstellt.
* [davewind/mysql-mcp-server](https://github.com/dave-wind/mysql-mcp-server) 🏎️ 🏠 A – benutzerfreundlicher, schreibgeschützter MySQL MCP-Server für Cursor und n8n...

### 📊 <a name="data-platforms"></a>Datenplattformen

Datenplattformen für Datenintegration, Transformation und Pipeline-Orchestrierung.

* [flowcore/mcp-flowcore-platform](https://github.com/flowcore-io/mcp-flowcore-platform) 🎖️ 📇 ☁️ 🏠 - Interagieren Sie mit Flowcore, um Aktionen durchzuführen, Daten aufzunehmen und Daten in Ihren Datenkernen oder öffentlichen Datenkernen zu analysieren, querzuverweisen und zu nutzen; alles in menschlicher Sprache.
* [JordiNei/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) 🐍 ☁️ - Verbindet sich mit der Databricks-API und ermöglicht LLMs das Ausführen von SQL-Abfragen, das Auflisten von Jobs und das Abrufen des Jobstatus.
* [yashshingvi/databricks-genie-MCP](https://github.com/yashshingvi/databricks-genie-MCP) 🐍 ☁️ - Ein Server, der sich mit der Databricks Genie API verbindet und es LLMs ermöglicht, Fragen in natürlicher Sprache zu stellen, SQL-Abfragen auszuführen und mit Databricks-Konversationsagenten zu interagieren.
* [jwaxman19/qlik-mcp](https://github.com/jwaxman19/qlik-mcp) 📇 ☁️ - MCP-Server für die Qlik Cloud API, der das Abfragen von Anwendungen, Blättern und das Extrahieren von Daten aus Visualisierungen mit umfassender Authentifizierungs- und Ratenbegrenzungsunterstützung ermöglicht.
* [keboola/keboola-mcp-server](https://github.com/keboola/keboola-mcp-server) 🐍 - Interagieren Sie mit der Keboola Connection Data Platform. Dieser Server bietet Werkzeuge zum Auflisten und Zugreifen auf Daten über die Keboola Storage API.
* [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) 🎖️ 🐍 🏠 ☁️ - Offizieller MCP-Server für [dbt (data build tool)](https://www.getdbt.com/product/what-is-dbt), der Integration mit dbt Core/Cloud CLI, Projekt-Metadaten-Erkennung, Modellinformationen und semantische Layer-Abfragefähigkeiten bietet.

### 💻 <a name="developer-tools"></a>Entwicklerwerkzeuge

Werkzeuge und Integrationen, die den Entwicklungs-Workflow und das Umgebungsmanagement verbessern.

* [21st-dev/Magic-MCP](https://github.com/21st-dev/magic-mcp) - Erstellen Sie maßgeschneiderte UI-Komponenten, inspiriert von den besten 21st.dev Design-Ingenieuren.
* [Hypersequent/qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp) 🎖️ 📇 ☁️ - Integration mit dem [QA Sphere](https://qasphere.com/) Testmanagementsystem, die es LLMs ermöglicht, Testfälle direkt aus KI-gestützten IDEs zu entdecken, zusammenzufassen und mit ihnen zu interagieren.
* [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP) 🐍 📇 🦀 - Analysiert Ihre Codebasis und identifiziert wichtige Dateien basierend auf Abhängigkeitsbeziehungen. Generiert Diagramme und Wichtigkeitsbewertungen, um KI-Assistenten beim Verständnis der Codebasis zu helfen.
* [ambar/simctl-mcp](https://github.com/ambar/simctl-mcp) 📇 🏠 🍎 Eine MCP-Server-Implementierung zur Steuerung des iOS Simulators.
* [api7/apisix-mcp](https://github.com/api7/apisix-mcp) 🎖️ 📇 🏠 MCP-Server, der das Abfragen und Verwalten aller Ressourcen in [Apache APISIX](https://github.com/apache/apisix) unterstützt.
* [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) 🏎️ 🏠 - Integrieren Sie jede API nahtlos mit KI-Agenten (mit OpenAPI Schema).
* [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) 📇 🏠 - Analysieren Sie React-Code lokal, generieren Sie Dokumentationen / llm.txt für das gesamte Projekt auf einmal.
* [davidlin2k/pox-mcp-server](https://github.com/davidlin2k/pox-mcp-server) 🐍 🏠 - MCP-Server für den POX SDN-Controller zur Bereitstellung von Netzwerksteuerungs- und Verwaltungsfähigkeiten.
* [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) 🎖️ 🐍 ☁️ 🍎 🪟 🐧 - Offizieller MCP-Server für CodeLogic, der Zugriff auf Code-Abhängigkeitsanalysen, Architekturelle Risikoanalysen und Auswirkungsbewertungswerkzeuge bietet.
* [Comet-ML/Opik-MCP](https://github.com/comet-ml/opik-mcp) 🎖️ 📇 ☁️ 🏠 - Verwenden Sie natürliche Sprache, um LLM-Observability, Traces und Überwachungsdaten zu untersuchen, die von Opik erfasst wurden.
* [CircleCI/mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci) 📇 ☁️ Ermöglichen Sie KI-Agenten, Build-Fehler von CircleCI zu beheben.
* [currents-dev/currents-mcp](https://github.com/currents-dev/currents-mcp) 🎖️ 📇 ☁️ Ermöglichen Sie KI-Agenten, Playwright-Testfehler zu beheben, die an [Currents](https://currents.dev) gemeldet wurden.
* [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) 📇 ☁️ - Interagieren Sie mit der [Postman API](https://www.postman.com/postman/postman-public-workspace/).
* [flipt-io/mcp-server-flipt](https://github.com/flipt-io/mcp-server-flipt) 📇 🏠 - Ermöglichen Sie KI-Assistenten, mit Ihren Feature-Flags in [Flipt](https://flipt.io) zu interagieren.
* [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) 📇 🏠 - Geben Sie Coding-Agenten direkten Zugriff auf Figma-Daten, um ihnen bei der One-Shot-Designimplementierung zu helfen.
* [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) 🎖️ 📇 ☁️ - Integriert, entdeckt, verwaltet und kodifiziert Cloud-Ressourcen mit [Firefly](https://firefly.ai).
* [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) 🦀 🏠 - Stellt LLMs über ein MCP-Tool aktuellen Dokumentationskontext für ein bestimmtes Rust-Crate bereit, unter Verwendung semantischer Suche (Embeddings) und LLM-Zusammenfassung.
* [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) 🐍 🏠 - Ein Excel-Manipulationsserver, der Arbeitsmappenerstellung, Datenoperationen, Formatierung und erweiterte Funktionen (Diagramme, Pivot-Tabellen, Formeln) bietet.
* [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) 🐍 🏠 - MCP-Server, der umfassende Werkzeuge zur Verwaltung von [Higress](https://github.com/alibaba/higress) Gateway-Konfigurationen und -Operationen bereitstellt.
* [hijaz/postmancer](https://github.com/hijaz/postmancer) 📇 🏠 - Ein MCP-Server zum Ersetzen von Rest-Clients wie Postman/Insomnia, indem er Ihrem LLM ermöglicht, API-Sammlungen zu pflegen und zu verwenden.
* [hloiseaufcms/mcp-gopls](https://github.com/hloiseaufcms/mcp-gopls) 🏎️ 🏠 - Ein MCP-Server zur Interaktion mit [Go's Language Server Protocol (gopls)](https://github.com/golang/tools/tree/master/gopls) und zur Nutzung fortschrittlicher Go-Code-Analysefunktionen.
* [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) 📇 🏠 - Ein MCP-Server zur Interaktion mit dem [Bruno API Client](https://www.usebruno.com/).
* [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) 🐍 🏠 - Steuern Sie Android-Geräte mit KI über MCP, was Gerätesteuerung, Debugging, Systemanalyse und UI-Automatisierung mit einem umfassenden Sicherheitsframework ermöglicht.
* [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server) 🐍 🏠 - Steuern Sie HarmonyOS-next-Geräte mit KI über MCP. Unterstützt Gerätesteuerung und UI-Automatisierung.
* [IlyaGulya/gradle-mcp-server](https://github.com/IlyaGulya/gradle-mcp-server) 🏠 - Gradle-Integration unter Verwendung der Gradle Tooling API zur Inspektion von Projekten, Ausführung von Aufgaben und Durchführung von Tests mit Ergebnisberichterstattung pro Test.
* [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) 🐍 🏠 - MCP-Server zur lokalen Komprimierung verschiedener Bildformate.
* [ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) 📇 🏠 🍎 - Ein Model Context Protocol (MCP) Server zur Interaktion mit iOS-Simulatoren. Dieser Server ermöglicht Ihnen die Interaktion mit iOS-Simulatoren, indem Sie Informationen darüber erhalten, UI-Interaktionen steuern und UI-Elemente inspizieren.
* [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb) 📇 🏠 🍎 - Ein Model Context Protocol (MCP) Server, der es LLMs ermöglicht, über Befehle in natürlicher Sprache mit iOS-Simulatoren (iPhone, iPad usw.) zu interagieren.
* [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) 📇 🏠 - Ein Model Context Protocol (MCP) Server, der KI-gestützte Such- und Abfragefunktionen für die Vercel AI SDK-Dokumentation bereitstellt.
* [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) 🐍 - MCP-Server, der SQL-Analyse, Linting und Dialektkonvertierung mittels [SQLGlot](https://github.com/tobymao/sqlglot) bereitstellt.
* [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) 📇 🏠 - Ein MCP-Server und eine VS Code-Erweiterung, die (sprachunabhängiges) automatisches Debugging über Breakpoints und Ausdrucksauswertung ermöglicht.
* [jetbrains/mcpProxy](https://github.com/JetBrains/mcpProxy) 🎖️ 📇 🏠 - Verbindung zur JetBrains IDE herstellen.
* [qainsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) 🐍 🏠 - JMeter MCP-Server für Leistungstests.
* [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) 📇 🏠 🍎 - Ein persönlicher MCP (Model Context Protocol) Server zur sicheren Speicherung und zum Zugriff auf API-Schlüssel über Projekte hinweg unter Verwendung des macOS Keychain.
* [joshuarileydev/app-store-connect-mcp-server](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) 📇 🏠 - Ein MCP-Server zur Kommunikation mit der App Store Connect API für iOS-Entwickler.
* [joshuarileydev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) 📇 🏠 - Ein MCP-Server zur Steuerung von iOS-Simulatoren.
* [qainsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) 🐍 🏠 - Grafana k6 MCP-Server für Leistungstests.
* [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) 📇 🏠 🛠️ - Ein Middleware-Server, der es ermöglicht, dass mehrere isolierte Instanzen derselben MCP-Server unabhängig voneinander mit eindeutigen Namespaces und Konfigurationen koexistieren.
* [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) 🐍 🏠 - MCP-Server zum Zugriff und zur Verwaltung von LLM-Anwendungs-Prompts, die mit [Langfuse](https://langfuse.com/docs/prompts/get-started) Prompt Management erstellt wurden.
* [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) 📇 🏠 🐧 🍎 - MCP-Server für Android/iOS-Anwendungs- und Geräteautomatisierung, Entwicklung und App-Scraping. Simulator/Emulator/Physische Geräte wie iPhone, Google Pixel, Samsung werden unterstützt.
* [qainsights/locust-mcp-server](https://github.com/QAInsights/locust-mcp-server) 🐍 🏠 - Locust MCP-Server für Leistungstests.
* [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) 🐍 🏠 - Einfacher MCP-Server zur Ermöglichung eines Human-in-the-Loop-Workflows in Tools wie Cline und Cursor.
* [OctoMind-dev/octomind-mcp](https://github.com/OctoMind-dev/octomind-mcp) 📇 ☁️ - Lässt Ihren bevorzugten KI-Agenten vollständig verwaltete [Octomind](https://www.octomind.dev/) End-to-End-Tests aus Ihrer Codebasis oder anderen Datenquellen wie Jira, Slack oder TestRail erstellen und ausführen.
* [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) 📇 ☁️ 🏠 - Token-effizienter Zugriff auf OpenAPI/Swagger-Spezifikationen über MCP-Ressourcen.
* [pskill9/website-downloader](https://github.com/pskill9/website-downloader) 🗄️ 🚀 - Dieser MCP-Server bietet ein Werkzeug zum Herunterladen ganzer Websites mit wget. Er bewahrt die Website-Struktur und konvertiert Links, damit sie lokal funktionieren.
* [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) 🐍 🏠 - MCP-Server, der genaue Informationen über NixOS-Pakete, Systemoptionen, Home Manager-Konfigurationen und nix-darwin macOS-Einstellungen bereitstellt, um KI-Halluzinationen zu verhindern.
* [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) 🏎️ 🏠 - Docker-Container-Verwaltung und -Operationen über MCP.
* [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) 🐍 🏠 - Integration mit Docker zur Verwaltung von Containern, Images, Volumes und Netzwerken.
* [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) 📇 🏠 🍎 - Xcode-Integration für Projektmanagement, Dateioperationen und Build-Automatisierung.
* [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) 📇 🏠 - MCP-Server, der LLMs alles über Ihre OpenAPI-Spezifikationen wissen lässt, um Code/Mock-Daten zu entdecken, zu erklären und zu generieren.
* [Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server) 🎖️ 🐍 ☁️ 🍎 - MCP-Server für die Incident-Management-Plattform [Rootly](https://rootly.com/).
* [sammcj/mcp-package-version](https://github.com/sammcj/mcp-package-version) 📇 🏠 - Ein MCP-Server, der LLMs hilft, die neuesten stabilen Paketversionen beim Schreiben von Code vorzuschlagen.
* [sapientpants/sonarqube-mcp-server](https://github.com/sapientpants/sonarqube-mcp-server) 🦀 ☁️ 🏠 - Ein Model Context Protocol (MCP) Server, der sich mit SonarQube integriert, um KI-Assistenten Zugriff auf Codequalitätsmetriken, Probleme und Quality Gate-Status zu ermöglichen.
* [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) 🐍 🏠 - Eine Implementierung von Claude Code-Fähigkeiten mittels MCP, die KI-Codeverständnis, -modifikation und Projektanalyse mit umfassender Werkzeugunterstützung ermöglicht.
* [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) 🏎️ 🏠 - Verbinden Sie jeden HTTP/REST-API-Server mithilfe einer Open API-Spezifikation (v3).
* [stass/lldb-mcp](https://github.com/stass/lldb-mcp) 🐍 🏠 🐧 🍎 - Ein MCP-Server für LLDB, der KI-Binär- und Core-Datei-Analyse, Debugging und Disassemblierung ermöglicht.
* [TencentEdgeOne/edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp) 📇 ☁️ - Ein MCP-Dienst zum Bereitstellen von HTML-Inhalten auf EdgeOne Pages und zum Erhalten einer öffentlich zugänglichen URL.
* [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) 🐍 🏠 - Ein zeilenorientierter Textdatei-Editor. Optimiert für LLM-Tools mit effizientem teilweisen Dateizugriff zur Minimierung der Token-Nutzung.
* [vivekvells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) 🗄️ 🚀 - MCP-Server für nahtlose Dokumentformatkonvertierung mit Pandoc, unterstützt Markdown, HTML, PDF, DOCX (.docx), CSV und mehr.
* [VSCode Devtools](https://github.com/biegehydra/BifrostMCP) 📇 - Verbindung zur VSCode IDE herstellen und semantische Werkzeuge wie `find_usages` verwenden.
* [xcodebuild](https://github.com/ShenghaiWang/xcodebuild) 🍎 Erstellen Sie iOS Xcode Workspace/Projekt und geben Sie Fehler an LLM zurück.
* [xzq.xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) 📇 🏠  - Ein Implementierungsprojekt eines JVM-basierten MCP (Model Context Protocol) Servers.
* [yangkyeongmo@/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) 🐍 🏠 - MCP-Server, der sich über den offiziellen Client mit [Apache Airflow](https://airflow.apache.org/) verbindet.
* [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) 🐍 🏠 - Ein Model Context Protocol (MCP) Server zur Generierung einer schönen interaktiven Mindmap.
* [YuChenSSR/multi-ai-advisor](https://github.com/YuChenSSR/multi-ai-advisor-mcp) 📇 🏠 - Ein Model Context Protocol (MCP) Server, der mehrere Ollama-Modelle abfragt und deren Antworten kombiniert, um verschiedene KI-Perspektiven zu einer einzigen Frage zu liefern.
* [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) 📇 🏠 - MCP-Server, der dem Agenten effizient Typescript-API-Informationen bereitstellt, damit er mit untrainierten APIs arbeiten kann.
* [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) 📇 🏠 - Ein MCP-Server zum flexiblen Abrufen von JSON-, Text- und HTML-Daten.
* [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) 🐍 🏠 ☁️ - Ein MCP-Server zur Verbindung mit Ihren [ZenML](https://www.zenml.io) MLOps- und LLMOps-Pipelines.
* [idosal/git-mcp](https://github.com/idosal/git-mcp) 📇 ☁️ - [gitmcp.io](https://gitmcp.io/) ist ein generischer Remote-MCP-Server zur Verbindung mit JEDEM [GitHub](https://www.github.com) Repository oder Projekt zur Dokumentation.
* [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) 📇 ☁️ - Ein MCP-Server zur Interaktion mit [Bugsnag](https://www.bugsnag.com/).
* [jordandalton/restcsv-mcp-server](https://github.com/JordanDalton/RestCsvMcpServer) 📇 ☁️ - Ein MCP-Server für CSV-Dateien.
* [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) 📇 ☁️ 🏠 – Ein programmierorientiertes Aufgabenverwaltungssystem, das Coding-Agenten wie Cursor AI mit erweitertem Aufgabenspeicher, Selbstreflexion und Abhängigkeitsmanagement verbessert. [ShrimpTaskManager](https://cjo4m06.github.io/mcp-shrimp-task-manager)
* [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner) 📇 🏠 - Ein MCP-Server zum lokalen Ausführen von Code über Docker und zur Unterstützung mehrerer Programmiersprachen.
* [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) 🏎️ ☁️ 🪟 🐧 🍎 - Fragen Sie Go-Paketinformationen auf pkg.go.dev ab.
* [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) 🏎️ ☁️ 📟 🪟 🐧 🍎 - Eine Go-Bibliothek ohne Konfigurationsaufwand, um vorhandene Gin Web-Framework-APIs automatisch als MCP-Tools bereitzustellen.
* [ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp) 📇 ☁️ 🪟 🐧 🍎 - GitHub Repo MCP ermöglicht Ihren KI-Assistenten das Durchsuchen von GitHub-Repositories, das Erkunden von Verzeichnissen und das Anzeigen von Dateiinhalten.
* [alimo7amed93/webhook-tester-mcp](https://github.com/alimo7amed93/webhook-tester-mcp) 🐍 ☁️ – Ein FastMCP-basierter Server zur Interaktion mit webhook-test.com. Ermöglicht Benutzern das Erstellen, Abrufen und Löschen von Webhooks lokal mit Claude.
* [lpigeon/ros-mcp-server](https://github.com/lpigeon/ros-mcp-server) 🐍 🏠 🍎 🪟 🐧 - Der ROS MCP-Server unterstützt die Robotersteuerung, indem er vom Benutzer ausgegebene Befehle in natürlicher Sprache in ROS- oder ROS2-Steuerbefehle umwandelt.

### 🔒 <a name="delivery"></a>Lieferung

* [https://github.com/jordandalton/doordash-mcp-server](https://github.com/JordanDalton/DoorDash-MCP-Server) 🐍 – DoorDash Lieferung (Inoffiziell)

### 🧮 <a name="data-science-tools"></a>Data-Science-Werkzeuge

Integrationen und Werkzeuge zur Vereinfachung der Datenexploration, Analyse und Verbesserung von Data-Science-Workflows.

* [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) 🐍 ☁️ - Sagen Sie alles mit Chronulus AI Prognose- und Vorhersageagenten voraus.
* [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) 🐍 ☁️ - Ermöglicht autonome Datenexploration auf .csv-basierten Datensätzen und liefert intelligente Einblicke mit minimalem Aufwand.
* [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) 📇 🏠 - Ein MCP-Server zur Konvertierung fast jeder Datei oder Webinhalts in Markdown.
* [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) 🐍 🏠 - Model Context Protocol (MCP) Server für Jupyter.
* [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) 🐍 🏠 - verbindet Jupyter Notebook mit Claude AI und ermöglicht Claude die direkte Interaktion mit und Steuerung von Jupyter Notebooks.
* [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) 🐍 ☁️ - Verbindet sich mit Kaggle, Fähigkeit zum Herunterladen und Analysieren von Datensätzen.
* [kdqed/zaturn](https://github.com/kdqed/zaturn) 🐍 🏠 🪟 🐧 🍎 - Verknüpfen Sie mehrere Datenquellen (SQL, CSV, Parquet usw.) und bitten Sie die KI, die Daten auf Einblicke und Visualisierungen zu analysieren.

### 📟 <a name="embedded-system"></a>Eingebettetes System

Bietet Zugriff auf Dokumentation und Verknüpfungen für die Arbeit an eingebetteten Geräten.

* [horw/esp-mcp](https://github.com/horw/esp-mcp) 📟 - Workflow zur Behebung von Build-Problemen bei Chips der ESP32-Serie mit ESP-IDF.
* [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) 🐍 📟 - Ein MCP-Server, der industrielle Modbus-Daten standardisiert und kontextualisiert.
* [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) 🐍 📟 - Ein MCP-Server, der sich mit OPC UA-fähigen Industriesystemen verbindet.
* [yoelbassin/gnuradioMCP](https://github.com/yoelbassin/gnuradioMCP) 🐍 📟 🏠 - Ein MCP-Server für GNU Radio, der es LLMs ermöglicht, RF `.grc`-Flussdiagramme autonom zu erstellen und zu ändern.

### 📂 <a name="file-systems"></a>Dateisysteme

Bietet direkten Zugriff auf lokale Dateisysteme mit konfigurierbaren Berechtigungen. Ermöglicht KI-Modellen das Lesen, Schreiben und Verwalten von Dateien innerhalb angegebener Verzeichnisse.

* [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) 🐍 🏠 - Teilen Sie Code-Kontext mit LLMs über MCP oder die Zwischenablage.
* [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) 🏎️ 🏠 - Datei-Zusammenführungswerkzeug, geeignet für Längenbeschränkungen im KI-Chat.
* [filesystem@quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/filesystem) ☕ 🏠 - Ein Dateisystem, das das Durchsuchen und Bearbeiten von Dateien ermöglicht, implementiert in Java mit Quarkus. Verfügbar als Jar oder natives Image.
* [hmk/box-mcp-server](https://github.com/hmk/box-mcp-server) 📇 ☁️ - Box-Integration zum Auflisten, Lesen und Suchen von Dateien.
* [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) 🐍 🏠 🪟 - Schnelle Windows-Dateisuche mit dem Everything SDK.
* [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) 🏎️ 🏠 - Golang-Implementierung für den Zugriff auf das lokale Dateisystem.
* [mickaelkerjean/filestash](https://github.com/mickael-kerjean/filestash/tree/master/server/plugin/plg_handler_mcp) 🏎️ ☁️ - Remote-Speicherzugriff: SF

**Standortbezogene Dienste und Kartierungswerkzeuge.** Ermöglicht KI-Modellen die Arbeit mit geografischen Daten, Wetterinformationen und standortbasierten Analysen.

- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) 🐍 ☁️ - Geolokalisierung von IP-Adressen und Netzwerkinformationen mithilfe der IPInfo-API
- [devilcoder01/weather-mcp-server](https://github.com/devilcoder01/weather-mcp-server) 🐍 ☁️ - Zugriff auf Echtzeit-Wetterdaten für jeden Standort über die WeatherAPI.com-API, mit detaillierten Vorhersagen und aktuellen Bedingungen.
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) 🐍 🏠 - Ein OpenStreetMap MCP-Server mit standortbezogenen Diensten und Geodaten.
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) 🐍 ☁️ - Ein MCP-Server für die Suche nach Orten in der Nähe mit IP-basierter Standorterkennung.
- [modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) 📇 ☁️ - Google Maps-Integration für Standortdienste, Routenplanung und Ortsdetails.
- [QGIS MCP](https://github.com/jjsantos01/qgis_mcp) - Verbindet QGIS Desktop über MCP mit Claude AI. Diese Integration ermöglicht die Prompt-gestützte Projekterstellung, das Laden von Layern, die Codeausführung und mehr.
- [SaintDoresh/Weather-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Weather-MCP-ClaudeDesktop.git) 🐍 ☁️ - Ein MCP-Tool, das Echtzeit-Wetterdaten, Vorhersagen und historische Wetterinformationen mithilfe der OpenWeatherMap-API bereitstellt.
- [rossshannon/Weekly-Weather-mcp](https://github.com/rossshannon/weekly-weather-mcp.git) 🐍 ☁️ - Wöchentlicher Wetter-MCP-Server, der detaillierte Wettervorhersagen für 7 volle Tage weltweit liefert.
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) 🐍 🏠 - Zugriff auf die Uhrzeit in jeder Zeitzone und Abruf der aktuellen Ortszeit.
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) 🐍 🏠 - Geocoding MCP-Server für Nominatim, ArcGIS, Bing.
- [ipfind/ipfind-mcp-server](https://github.com/ipfind/ipfind-mcp-server) 🐍 ☁️ - IP-Adressen-Standortdienst mithilfe der [IP Find](https://ipfind.com)-API.
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) 🏠 – Eine Model Context Protocol (MCP)-Serverimplementierung, die LLMs mit der GeoServer REST API verbindet und KI-Assistenten die Interaktion mit Geodaten und -diensten ermöglicht.

### 🎯 <a name="marketing"></a>Marketing

Werkzeuge zur Erstellung und Bearbeitung von Marketinginhalten, zur Arbeit mit Web-Metadaten, Produktpositionierung und Bearbeitungsleitfäden.

- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) 🐍 ☁️ - MCP-Server, der als Schnittstelle zu Facebook Ads dient und programmatischen Zugriff auf Facebook Ads-Daten und Verwaltungsfunktionen ermöglicht.
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) 🐍 🏠 - Eine Suite von Marketing-Tools von Open Strategy Partners, einschließlich Schreibstil, Bearbeitungscodes und Erstellung von Produktmarketing-Wertversprechen-Karten (Value Map).
- [nictuku/meta-ads-mcp](https://github.com/nictuku/meta-ads-mcp) 🐍 ☁️ 🏠 - Ermöglicht KI-Agenten die Überwachung und Optimierung der Leistung von Meta-Anzeigen, die Analyse von Kampagnenmetriken, die Anpassung des Zielgruppen-Targetings, die Verwaltung von Kreativ-Assets und die Erstellung datengesteuerter Empfehlungen für Werbeausgaben und Kampagneneinstellungen durch nahtlose Graph API-Integration.

### 📊 <a name="monitoring"></a>Überwachung

Zugriff auf und Analyse von Anwendungsüberwachungsdaten. Ermöglicht KI-Modellen die Überprüfung von Fehlerberichten und Leistungsmetriken.

- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) 🎖️ 🐍 🏠 ☁️ - Durchsuchen Sie Dashboards, untersuchen Sie Vorfälle und fragen Sie Datenquellen in Ihrer Grafana-Instanz ab.
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) 🐍 🏠 - Ein MCP-Server, der das Abfragen von Loki-Logs über die Grafana-API ermöglicht.
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) 🐍 🏠 - Verbessern Sie die Qualität von KI-generiertem Code durch intelligente, Prompt-basierte Analysen über 10 kritische Dimensionen, von Komplexität bis hin zu Sicherheitslücken.
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) - Bringen Sie nahtlos Echtzeit-Produktionskontext – Logs, Metriken und Traces – in Ihre lokale Umgebung, um Code schneller automatisch zu korrigieren.
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) 🎖️ 🏎️ ☁️ - Abfragen und Interagieren mit Kubernetes-Umgebungen, die von Metoro überwacht werden.
- [MindscapeHQ/server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) 📇 ☁️ - Raygun API V3-Integration für Crash-Reporting und Real User Monitoring.
- [modelcontextprotocol/server-sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) 🐍 ☁️ - Sentry.io-Integration für Fehlerverfolgung und Leistungsüberwachung.
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) 🎖️ 🐍 ☁️ - Bietet Zugriff auf OpenTelemetry-Traces und -Metriken über Logfire.
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) 🏎️ 🏠 - Ein Systemüberwachungstool, das Systemmetriken über das Model Context Protocol (MCP) bereitstellt. Dieses Tool ermöglicht LLMs den Abruf von Echtzeit-Systeminformationen über eine MCP-kompatible Schnittstelle. (unterstützt CPU, Speicher, Festplatte, Netzwerk, Host, Prozesse)

### 🎥 <a name="multimedia-process"></a>Multimedia-Verarbeitung

Bietet die Möglichkeit zur Handhabung von Multimedia, wie z.B. Audio- und Videobearbeitung, Wiedergabe, Formatkonvertierung, einschließlich Videofilter, Verbesserungen usw.

- [video-creator/ffmpeg-mcp](https://github.com/video-creator/ffmpeg-mcp.git) 🎥 🔊 - Verwendung der FFmpeg-Befehlszeile zur Realisierung eines MCP-Servers, ermöglicht sehr bequem über Dialog die lokale Videosuche, das Schneiden, Zusammenfügen, die Wiedergabe und andere Funktionen.

### 🔎 <a name="search"></a>Suche & Datenextraktion

- [ricocf/mcp-wolframalpha](https://github.com/ricocf/mcp-wolframalpha) 🐍 🏠 ☁️ - Ein MCP-Server ermöglicht KI-Assistenten die Nutzung der Wolfram Alpha API für Echtzeitzugriff auf Berechnungswissen und Daten.
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) 🐍 ☁️ - Der Scrapeless Model Context Protocol-Dienst fungiert als MCP-Server-Connector zur Google SERP API und ermöglicht die Websuche innerhalb des MCP-Ökosystems, ohne dieses zu verlassen.
- [0xdaef0f/job-searchoor](https://github.com/0xDAEF0F/job-searchoor) 📇 🏠 - Ein MCP-Server zur Suche nach Stellenangeboten mit Filtern für Datum, Schlüsselwörter, Remote-Arbeitsoptionen und mehr.
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) 📇 ☁️ - Kagi Search API-Integration.
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) - 🐍 ☁️ MCP für LLMs zur Suche und zum Lesen von Papieren von arXiv.
- [hbg/mcp-paperswithcode](https://github.com/hbg/mcp-paperswithcode) - 🐍 ☁️ MCP zur Suche über die PapersWithCode-API.
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) - 🐍 ☁️ MCP zur Suche und zum Lesen von medizinischen / biowissenschaftlichen Papieren von PubMed.
- [angheljf/nyt](https://github.com/angheljf/nyt) 📇 ☁️ - Suche nach Artikeln mithilfe der NYTimes-API.
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) 📇 ☁️ - Ein MCP-Server für Apifys Open-Source RAG Web Browser Actor zur Durchführung von Websuchen, zum Scrapen von URLs und zur Rückgabe von Inhalten in Markdown.
- [Bigsy/Clojars-MCP-Server](https://github.com/Bigsy/Clojars-MCP-Server) 📇 ☁️ - Clojars MCP-Server für aktuelle Abhängigkeitsinformationen von Clojure-Bibliotheken.
- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) ☁️ 🐍 - Suche nach ArXiv-Forschungspapieren.
- [chanmeng/google-news-mcp-server](https://github.com/ChanMeng666/server-google-news) 📇 ☁️ - Google News-Integration mit automatischer Themenkategorisierung, Unterstützung mehrerer Sprachen und umfassenden Suchfunktionen einschließlich Schlagzeilen, Artikeln und verwandten Themen über [SerpAPI](https://serpapi.com/).
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp/) 🐍 🏠 ☁️ - Dies ist ein Python-basierter MCP-Server, der das integrierte OpenAI `web_search`-Tool bereitstellt.
- [dealx/mcp-server](https://github.com/DealExpress/mcp-server) ☁️ - MCP-Server für die DealX-Plattform.
- [devflowinc/trieve](https://github.com/devflowinc/trieve/tree/main/clients/mcp-server) 🎖️ 📇 ☁️ 🏠 - Crawlen, Einbetten, Segmentieren, Suchen und Abrufen von Informationen aus Datensätzen über [Trieve](https://trieve.ai).
- [Dumpling-AI/mcp-server-dumplingai](https://github.com/Dumpling-AI/mcp-server-dumplingai) 🎖️ 📇 ☁️ - Zugriff auf Daten-, Web-Scraping- und Dokumentkonvertierungs-APIs von [Dumpling AI](https://www.dumplingai.com/).
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) 🐍 ☁️ - Ein MCP-Server zur Suche auf Hacker News, zum Abrufen von Top-Stories und mehr.
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) 🎖️ 📇 ☁️ – Ein Model Context Protocol (MCP)-Server ermöglicht KI-Assistenten wie Claude die Nutzung der Exa AI Search API für Websuchen. Diese Einrichtung ermöglicht KI-Modellen den sicheren und kontrollierten Abruf von Echtzeit-Webinformationen.
- [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp) 📇 ☁️ - Suche über search1api (kostenpflichtiger API-Schlüssel erforderlich).
- [genomoncology/biomcp](https://github.com/genomoncology/biomcp) 🐍 ☁️ - Biomedizinischer Forschungsserver mit Zugriff auf PubMed, ClinicalTrials.gov und MyVariant.info.
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server)) 🐍 ☁️ - Ein MCP-Server für die Unsplash-Bildsuche.
- [Ihor-Sokoliuk/MCP-SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng) 📇 🏠/☁️ - Ein Model Context Protocol Server für [SearXNG](https://docs.searxng.org).
- [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) 📇 ☁️ - MCP-Server für die Integration der Naver Search API, unterstützt Blog-, Nachrichten-, Shopping-Suche und DataLab-Analysefunktionen.
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) 📇 🏠 - MCP-Server zum Abrufen von Webseiteninhalten mithilfe des Playwright Headless-Browsers, unterstützt Javascript-Rendering und intelligente Inhalts-Extraktion sowie die Ausgabe im Markdown- oder HTML-Format.
- [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp) 📇 🏠 - Ein leistungsstarker MCP-Server für die Google-Suche, der parallele Suchen mit mehreren Schlüsselwörtern gleichzeitig ermöglicht.
- [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) 📇 ☁️ - Websuchfunktionen mithilfe der Microsoft Bing Search API.
- [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) ☁️ 📇 – Offizieller Kagi Search MCP Server.
- [kshern/mcp-tavily](https://github.com/kshern/mcp-tavily.git) ☁️ 📇 – Tavily AI Search API.
- [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp) 📇 ☁️ - Web-, Bild-, Nachrichten-, Video- und lokale Point-of-Interest-Suchfunktionen mithilfe der Brave Search API.
- [emicklei/melrose-mcp](https://github.com/emicklei/melrose/tree/master/cmd/melrose-mcp) 🏎️ 🏠 - Spielt [Melrōse](https://melrōse.org)-Musikausdrücke als MIDI ab.
- [modelcontextprotocol/server-brave-search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) 📇 ☁️ - Websuchfunktionen mithilfe der Brave Search API.
- [modelcontextprotocol/server-fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) 🐍 🏠 ☁️ - Effizientes Abrufen und Verarbeiten von Webinhalten für die KI-Nutzung.
- [mzxrai/mcp-webresearch](https://github.com/mzxrai/mcp-webresearch) 🔍📚 - Google durchsuchen und tiefgreifende Webrecherche zu jedem Thema durchführen.
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) 🐍 ☁️ - Websuche mit DuckDuckGo.
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) 📇 ☁️ - Zugriff auf Informationen des niederländischen Parlaments (Tweede Kamer), einschließlich Dokumenten, Debatten, Aktivitäten und Gesetzgebungsfällen über strukturierte Suchfunktionen (basiert auf dem opentk-Projekt von Bert Hubert).
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) 📇 ☁️ - MCP-Server, der autonome Tiefenrecherche im Stil von OpenAI/Perplexity, strukturierte Abfrageausarbeitung und prägnante Berichterstattung bietet.
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) 🐍 🏠 - Ein MCP-Server zur Verbindung mit SearXNG-Instanzen.
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) 🐍 ☁️ - Ruft den LaTeX-Quellcode von arXiv-Papieren ab, um mathematische Inhalte und Gleichungen zu verarbeiten.
- [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) 🐍 ☁️ - Ein MCP-Server, der Nachrichtendaten von der GeekNews-Website abruft und verarbeitet.
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) 🎖️ 📇 ☁️ - MCP-Server, der die Datenextraktionsfähigkeiten von [AgentQL](https://agentql.com) bereitstellt.
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) ☁️ 🐍 – Tavily AI Search API.
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server/) ☁️ 📇 - [Vectorize](https://vectorize.io) MCP-Server für erweiterte Suche, private Tiefenrecherche, Anything-to-Markdown-Dateiextraktion und Textsegmentierung.
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) 🎖️ 📇 ☁️ - Interagieren Sie mit [WebScraping.ai](https://webscraping.ai) für Webdatenextraktion und Scraping.
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mpc-server/) 📇 🏠 ☁️ - Dies ist ein TypeScript-basierter MCP-Server, der DuckDuckGo-Suchfunktionalität bereitstellt.
- [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) 📇 ☁️ - Abfragen von Netzwerkanlageninformationen über den ZoomEye MCP Server.
- [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) 📇 🏠 - MCP-Server, der den Baseline-Status mithilfe der Web Platform API durchsucht.

### 🔒 <a name="security"></a>Sicherheit

- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) ☕ 🏠 - Ein Model Context Protocol-Server für Ghidra, der LLMs ermöglicht, Anwendungen autonom zu reverse engineeren. Bietet Werkzeuge zum Dekompilieren von Binärdateien, Umbenennen von Methoden und Daten sowie Auflisten von Methoden, Klassen, Importen und Exporten.
- [dkvdm/onepassword-mcp-server](https://github.com/dkvdm/onepassword-mcp-server) - Ein MCP-Server, der den sicheren Abruf von Anmeldeinformationen aus 1Password zur Verwendung durch agentische KI ermöglicht.
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) 🐍 ☕ 🏠 - MCP-Server zur Integration von Ghidra mit KI-Assistenten. Dieses Plugin ermöglicht Binäranalyse und bietet Werkzeuge zur Funktionsinspektion, Dekompilierung, Speichererkundung und Import-/Exportanalyse über das Model Context Protocol.
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) 🐍 🪟 🏠 MCP-Server zur Analyse von ROADrecon-Ergebnissen aus der Azure-Tenant-Enumeration.
- [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist) 📇 🪟 ☁️ - MCP-Server für dnstwist, ein leistungsstarkes DNS-Fuzzing-Tool, das hilft, Typosquatting, Phishing und Unternehmensspionage zu erkennen.
- [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) 📇 🪟 ☁️ - MCP-Server für maigret, ein leistungsstarkes OSINT-Tool, das Benutzerkontoinformationen aus verschiedenen öffentlichen Quellen sammelt. Dieser Server bietet Werkzeuge zur Suche nach Benutzernamen in sozialen Netzwerken und zur Analyse von URLs.
- [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) 📇 🪟 ☁️ - MCP-Server zur Abfrage der Shodan API und Shodan CVEDB. Dieser Server bietet Werkzeuge für IP-Lookups, Gerätesuchen, DNS-Lookups, Schwachstellenabfragen, CPE-Lookups und mehr.
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) 📇 🪟 ☁️ - MCP-Server zur Abfrage der VirusTotal API. Dieser Server bietet Werkzeuge zum Scannen von URLs, Analysieren von Datei-Hashes und Abrufen von IP-Adressberichten.
- [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) 🐍 🏠 🍎 🪟 🐧 - Ein Binary Ninja-Plugin, MCP-Server und Bridge, die [Binary Ninja](https://binary.ninja) nahtlos in Ihren bevorzugten MCP-Client integriert. Es ermöglicht Ihnen, den Prozess der Binäranalyse und des Reverse Engineerings zu automatisieren.
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) 📇 ☁️ - MCP-Server zur Abfrage der ORKL-API. Dieser Server bietet Werkzeuge zum Abrufen von Bedrohungsberichten, zur Analyse von Bedrohungsakteuren und zum Abrufen von Geheimdienstquellen.
- [jyjune/mcp_vms](https://github.com/jyjune/mcp_vms) 🐍 🏠 🪟 - Ein Model Context Protocol (MCP)-Server, der zur Verbindung mit einem CCTV-Aufzeichnungsprogramm (VMS) entwickelt wurde, um aufgezeichnete und Live-Videostreams abzurufen. Er bietet auch Werkzeuge zur Steuerung der VMS-Software, z. B. das Anzeigen von Live- oder Wiedergabedialogen für bestimmte Kanäle zu bestimmten Zeiten.
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) 📇 ☁️ Ein leistungsstarker MCP (Model Context Protocol) Server, der npm-Paketabhängigkeiten auf Sicherheitslücken überprüft. Entwickelt mit Remote-npm-Registry-Integration für Echtzeit-Sicherheitsprüfungen.
- [semgrep/mcp](https://github.com/semgrep/mcp) 📇 ☁️ Ermöglicht KI-Agenten, Code mithilfe von [Semgrep](https://semgrep.dev) auf Sicherheitslücken zu scannen.
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) 🐍 ☁️ - MCP-Server zur Interaktion mit der CyberChef-Server-API, die es einem MCP-Client ermöglicht, die CyberChef-Operationen zu nutzen.
- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) 🐍 🏠 - MCP-Server für IDA Pro, mit dem Sie Binäranalysen mit KI-Assistenten durchführen können. Dieses Plugin implementiert Dekompilierung, Disassemblierung und ermöglicht die automatische Generierung von Malware-Analyseberichten.
- [rad-security/mcp-server](https://github.com/rad-security/mcp-server) 📇 ☁️ - MCP-Server für RAD Security, der KI-gestützte Sicherheitseinblicke für Kubernetes- und Cloud-Umgebungen bietet. Dieser Server bietet Werkzeuge zur Abfrage der Rad Security API und zum Abrufen von Sicherheitsergebnissen, Berichten, Laufzeitdaten und vielem mehr.
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) 🐍 🏠 - All-in-One-Sicherheitstest-Toolbox, die beliebte Open-Source-Tools über eine einzige MCP-Schnittstelle zusammenführt. Verbunden mit einem KI-Agenten ermöglicht sie Aufgaben wie Pentesting, Bug-Bounty-Jagd, Bedrohungssuche und mehr.
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) 🐍 🏠 - Ein Model Context Protocol (MCP)-Server zur Abfrage der CVE-Search API. Dieser Server bietet umfassenden Zugriff auf CVE-Search, Durchsuchen von Herstellern und Produkten, Abrufen von CVEs pro CVE-ID, Abrufen der zuletzt aktualisierten CVEs.
- [rember/rember-mcp](https://github.com/rember/rember-mcp) 📇 🏠 - Erstelle Spaced-Repetition-Karteikarten in [Rember](https://rember.com), um alles, was du in deinen Chats lernst, zu behalten.
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) - 📇 ☁️ Diese Model Context Protocol Server-Implementierung für Asana ermöglicht dir die Kommunikation mit der Asana API von MCP Clients wie Anthropic's Claude Desktop Anwendung und vielen mehr.
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw/blob/main/src/wcgw/client/mcp_server/Readme.md) 🐍 🏠 - Autonome Shell-Ausführung, Computersteuerung und Coding-Agent. (Mac)
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) 🐍 ☁️ - Ein MCP Server zum Abfragen der Wolfram Alpha API.
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) 📇 ☁️ - Interagiere mit TikTok Videos.
- [Shopify/dev-mcp](https://github.com/Shopify/dev-mcp) 📇 ☁️ - Model Context Protocol (MCP) Server, der mit Shopify Dev interagiert.
- [sirmews/apple-notes-mcp](https://github.com/sirmews/apple-notes-mcp) 🐍 🏠 - Ermöglicht der KI, aus deiner lokalen Apple Notizen-Datenbank zu lesen (nur macOS).
- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) 🐍 ☁️ - MCP Server für Atlassian-Produkte (Confluence und Jira). Unterstützt Confluence Cloud, Jira Cloud und Jira Server/Data Center. Bietet umfassende Werkzeuge zum Suchen, Lesen, Erstellen und Verwalten von Inhalten in Atlassian Workspaces.
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) 📇 🏠 - Interagiert mit der Notion API.
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) 📇 ☁️ 🍎 🪟 🐧 - Integriert sich mit dem Linear Projektmanagementsystem.
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) 🐍 ☁️ - Interagiert mit der Perplexity API.
- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) 📇 🏠 - Greife auf Home Assistant Daten zu und steuere Geräte (Lichter, Schalter, Thermostate, etc.).
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) 🐍 ☁️ - Ein MCP Server für Oura, eine App zur Schlafüberwachung.
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) 📇 ☁️ - Ein MCP Server für Strava, eine App zur Aufzeichnung körperlicher Betätigung.
- [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku) - ☁️ 🏠 Der Wanaku MCP Router ist ein SSE-basierter MCP Server, der eine erweiterbare Routing-Engine bereitstellt, die die Integration deiner Unternehmenssysteme mit KI-Agenten ermöglicht.
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) 📇 🏠 - CLI-Tool zum Testen von MCP Servern.
- [ws-mcp](https://github.com/nick1udwig/ws-mcp) - Umhülle MCP Server mit einem WebSocket (zur Verwendung mit [kitbitz](https://github.com/nick1udwig/kibitz)).
- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) 📇 ☁️ - Ermöglicht KI-Modellen die Interaktion mit [HackMD](https://hackmd.io).
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) - MCP Server, der Datums- und Zeitfunktionen in verschiedenen Formaten bereitstellt.
- [zueai/mcp-manager](https://github.com/zueai/mcp-manager) 📇 ☁️ - Einfache Web-Oberfläche zur Installation und Verwaltung von MCP Servern für die Claude Desktop App.
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) - 📇 ☁️ Ein Model-Context-Protocol (MCP) Server zur Integration mit der Yuque API, der KI-Modellen ermöglicht, Dokumente zu verwalten, mit Wissensdatenbanken zu interagieren, Inhalte zu durchsuchen und auf Analysedaten von der Yuque-Plattform zuzugreifen.
- [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) 🐍 🏠 - Ermöglicht KI die vollständige Steuerung und den Zugriff auf GUI-Interaktionen durch Bereitstellung von Werkzeugen für Maus und Tastatur, ideal für allgemeine Automatisierung, Bildung und Experimente.
- [tumf/web3-mcp](https://github.com/tumf/web3-mcp) 🐍 ☁️ - Eine MCP Server-Implementierung, die die Ankr Advanced API umschließt. Zugriff auf NFT-, Token- und Blockchain-Daten über mehrere Ketten, einschließlich Ethereum, BSC, Polygon, Avalanche und mehr.
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) 🐍 - Dienstprogramme zum Herunterladen, Anzeigen und Bearbeiten von PDFs.
- [dotemacs/domain-lookup-mcp](https://github.com/dotemacs/domain-lookup-mcp) 🏎️ - Dienst zur Suche von Domainnamen, zuerst über [RDAP](https://en.wikipedia.org/wiki/Registration_Data_Access_Protocol) und dann als Fallback über [WHOIS](https://en.wikipedia.org/wiki/WHOIS).
- [Klavis-AI/YouTube](https://github.com/Klavis-AI/klavis/tree/main/mcp_servers/youtube) 🐍 📇 - Extrahiert und konvertiert YouTube Videoinformationen.
- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) 📇 🏠 🍎 🪟 🐧 - Ermöglicht interaktive LLM-Workflows durch Hinzufügen lokaler Benutzerprompts und Chat-Funktionen direkt in die MCP-Schleife.

## Frameworks

> [!NOTE]
> Weitere Frameworks, Dienstprogramme und andere Entwicklerwerkzeuge sind unter https://github.com/punkpeye/awesome-mcp-devtools verfügbar.

- [FastMCP](https://github.com/jlowin/fastmcp) 🐍 - Ein High-Level-Framework zum Erstellen von MCP Servern in Python.
- [FastMCP](https://github.com/punkpeye/fastmcp) 📇 - Ein High-Level-Framework zum Erstellen von MCP Servern in TypeScript.

## Tipps und Tricks

### Offizieller Prompt, um LLMs über die Verwendung von MCP zu informieren

Möchtest du Claude nach Model Context Protocol fragen?

Erstelle ein Projekt und füge dann diese Datei hinzu:

https://modelcontextprotocol.io/llms-full.txt

Jetzt kann Claude Fragen zum Schreiben von MCP Servern und deren Funktionsweise beantworten.

- https://www.reddit.com/r/ClaudeAI/comments/1h3g01r/want_to_ask_claude_about_model_context_protocol/

## Star History

<a href="https://star-history.com/#punkpeye/awesome-mcp-servers&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date" />
 </picture>
</a>

