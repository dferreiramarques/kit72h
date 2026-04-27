# KIT72H 🛡️

> **Available in / Disponível em / Disponible en / Disponibile in / Disponible en / Verfügbar auf:**
> 🇵🇹 [Português](#-português) · 🇬🇧 [English](#-english) · 🇪🇸 [Español](#-español) · 🇮🇹 [Italiano](#-italiano) · 🇫🇷 [Français](#-français) · 🇩🇪 [Deutsch](#-deutsch)

---

## 🇵🇹 Português

### O que é o KIT72H?

O **KIT72H** é uma aplicação web progressiva (PWA) que te ajuda a preparar e gerir um kit de emergência para 72 horas, de acordo com as recomendações da União Europeia e do BCE. Foi criado a pensar na experiência mobile, com um design moderno inspirado no sistema Vibe da monday.com.

O apagão de abril de 2025 na Península Ibérica mostrou como qualquer família pode ser apanhada desprevenida. O KIT72H existe para isso não voltar a acontecer.

### Funcionalidades

- **Lista pré-configurada** com 25 artigos essenciais divididos por categorias: Água, Alimentação, Saúde, Energia e Outros
- **Cálculo dinâmico** — define o número de pessoas e as horas de autonomia, e as quantidades recalculam-se automaticamente
- **Gestão de validades** — regista a data de validade de cada unidade individual; a validade mais próxima prevalece sempre
- **Sistema de alertas** por níveis: ✅ OK (>90 dias) · 🕐 Atenção (31–90 dias) · ⚠️ Alerta (<30 dias) · 🔴 URGENTE (≤7 dias) · 🚫 Expirado
- **Campo para dinheiro em espécie** com recomendação oficial BCE/DECO: 70–100 € por adulto, em notas de 5, 10 e 20 €
- **Checklist interativa** com visual verde ao marcar itens como concluídos
- **Filtros por categoria** e painel de alerta dedicado
- **6 idiomas** — Português, Inglês, Espanhol, Italiano, Francês e Alemão
- **PWA instalável** — funciona offline e pode ser instalada no ecrã principal do telemóvel
- **Dados persistentes** em localStorage — nada é guardado em servidores

### Tecnologia

- HTML5 + CSS3 + JavaScript vanilla (sem dependências externas)
- Design System **Vibe** da monday.com (tokens oficiais extraídos do `@vibe/core`)
- Fontes: **Poppins** (títulos) e **Figtree** (corpo)
- Service Worker para funcionamento offline
- PWA com `manifest.json`

### Instalação / Deployment

```bash
# Clona o repositório
git clone https://github.com/teu-utilizador/kit72h.git
cd kit72h

# Não há dependências — apenas serve os ficheiros estáticos
# Exemplos:

# Netlify / Vercel: arrasta a pasta para o dashboard
# GitHub Pages: activa nas settings do repositório
# Railway: usa um servidor estático simples
# Localmente:
npx serve .
```

### Estrutura do projeto

```
kit72h/
├── index.html      # Aplicação completa (single-file)
├── manifest.json   # PWA manifest
├── sw.js           # Service Worker (cache offline)
└── README.md       # Este ficheiro
```

---

## 🇬🇧 English

### What is KIT72H?

**KIT72H** is a Progressive Web App (PWA) designed to help you build and manage a 72-hour emergency kit, following European Union and ECB recommendations. Built mobile-first, with a modern design based on monday.com's Vibe Design System.

The April 2025 Iberian blackout demonstrated how any family can be caught unprepared. KIT72H exists to prevent that from happening again.

### Features

- **Pre-configured list** of 25 essential items across five categories: Water, Food, Health, Energy and Others
- **Dynamic calculation** — set the number of people and hours of autonomy, and quantities recalculate automatically
- **Expiry tracking** — log an expiry date for each individual unit; the nearest date always takes priority
- **Tiered alert system**: ✅ OK (>90 days) · 🕐 Attention (31–90 days) · ⚠️ Alert (<30 days) · 🔴 URGENT (≤7 days) · 🚫 Expired
- **Cash field** with official ECB/DECO guidance: 70–100 € per adult, in 5, 10 and 20 € notes
- **Interactive checklist** with a green highlight when items are marked as ready
- **Category filters** and a dedicated alert panel
- **6 languages** — Portuguese, English, Spanish, Italian, French and German
- **Installable PWA** — works offline and can be added to your phone's home screen
- **Persistent data** via localStorage — nothing is sent to any server

### Technology

- HTML5 + CSS3 + Vanilla JavaScript (zero external dependencies)
- **Vibe** Design System by monday.com (official tokens from `@vibe/core`)
- Fonts: **Poppins** (headings) and **Figtree** (body)
- Service Worker for offline support
- PWA with `manifest.json`

### Installation / Deployment

```bash
# Clone the repository
git clone https://github.com/your-username/kit72h.git
cd kit72h

# No dependencies — just serve the static files
# Examples:

# Netlify / Vercel: drag the folder into the dashboard
# GitHub Pages: enable in repository settings
# Railway: use a simple static server
# Locally:
npx serve .
```

### Project structure

```
kit72h/
├── index.html      # Complete app (single-file)
├── manifest.json   # PWA manifest
├── sw.js           # Service Worker (offline cache)
└── README.md       # This file
```

---

## 🇪🇸 Español

### ¿Qué es KIT72H?

**KIT72H** es una aplicación web progresiva (PWA) que te ayuda a preparar y gestionar un kit de emergencia para 72 horas, siguiendo las recomendaciones de la Unión Europea y del BCE. Diseñada pensando en el móvil, con un diseño moderno basado en el sistema Vibe de monday.com.

El apagón de abril de 2025 en la Península Ibérica demostró cómo cualquier familia puede quedar desprotegida. KIT72H existe para que eso no vuelva a ocurrir.

### Funcionalidades

- **Lista preconfigurada** con 25 artículos esenciales divididos en cinco categorías: Agua, Alimentos, Salud, Energía y Otros
- **Cálculo dinámico** — define el número de personas y las horas de autonomía, y las cantidades se recalculan automáticamente
- **Gestión de caducidades** — registra la fecha de caducidad de cada unidad individual; siempre prevalece la más próxima
- **Sistema de alertas** por niveles: ✅ OK (>90 días) · 🕐 Atención (31–90 días) · ⚠️ Alerta (<30 días) · 🔴 URGENTE (≤7 días) · 🚫 Caducado
- **Campo para efectivo** con recomendación oficial BCE/DECO: 70–100 € por adulto, en billetes de 5, 10 y 20 €
- **Lista de verificación interactiva** con efecto verde al marcar artículos como preparados
- **Filtros por categoría** y panel de alertas dedicado
- **6 idiomas** — Portugués, Inglés, Español, Italiano, Francés y Alemán
- **PWA instalable** — funciona sin conexión y se puede añadir a la pantalla de inicio del móvil
- **Datos persistentes** en localStorage — nada se envía a ningún servidor

### Tecnología

- HTML5 + CSS3 + JavaScript vanilla (sin dependencias externas)
- Sistema de diseño **Vibe** de monday.com (tokens oficiales de `@vibe/core`)
- Fuentes: **Poppins** (títulos) y **Figtree** (cuerpo)
- Service Worker para soporte offline
- PWA con `manifest.json`

---

## 🇮🇹 Italiano

### Cos'è KIT72H?

**KIT72H** è una Progressive Web App (PWA) pensata per aiutarti a costruire e gestire un kit di emergenza per 72 ore, in linea con le raccomandazioni dell'Unione Europea e della BCE. Progettata per il mobile, con un design moderno ispirato al sistema Vibe di monday.com.

Il blackout dell'aprile 2025 nella Penisola Iberica ha dimostrato quanto facilmente qualsiasi famiglia possa trovarsi impreparata. KIT72H nasce per evitare che ciò accada di nuovo.

### Funzionalità

- **Lista preconfigurata** con 25 articoli essenziali suddivisi in cinque categorie: Acqua, Alimenti, Salute, Energia e Altro
- **Calcolo dinamico** — imposta il numero di persone e le ore di autonomia, e le quantità si aggiornano automaticamente
- **Gestione delle scadenze** — registra la data di scadenza di ogni singola unità; prevale sempre quella più vicina
- **Sistema di allerta** a livelli: ✅ OK (>90 giorni) · 🕐 Attenzione (31–90 giorni) · ⚠️ Allerta (<30 giorni) · 🔴 URGENTE (≤7 giorni) · 🚫 Scaduto
- **Campo per il contante** con raccomandazione ufficiale BCE/DECO: 70–100 € per adulto, in banconote da 5, 10 e 20 €
- **Checklist interattiva** con evidenziazione verde quando si contrassegnano gli articoli come pronti
- **Filtri per categoria** e pannello di allerta dedicato
- **6 lingue** — Portoghese, Inglese, Spagnolo, Italiano, Francese e Tedesco
- **PWA installabile** — funziona offline e può essere aggiunta alla schermata principale del telefono
- **Dati persistenti** in localStorage — nessun dato viene inviato a server esterni

### Tecnologia

- HTML5 + CSS3 + JavaScript vanilla (nessuna dipendenza esterna)
- Design System **Vibe** di monday.com (token ufficiali da `@vibe/core`)
- Font: **Poppins** (titoli) e **Figtree** (corpo)
- Service Worker per il supporto offline
- PWA con `manifest.json`

---

## 🇫🇷 Français

### Qu'est-ce que KIT72H ?

**KIT72H** est une application web progressive (PWA) conçue pour vous aider à préparer et gérer un kit d'urgence pour 72 heures, conformément aux recommandations de l'Union européenne et de la BCE. Pensée pour le mobile, avec un design moderne basé sur le système Vibe de monday.com.

La panne d'électricité d'avril 2025 dans la péninsule Ibérique a montré à quel point n'importe quelle famille peut être prise au dépourvu. KIT72H existe pour que cela ne se reproduise pas.

### Fonctionnalités

- **Liste préconfigurée** de 25 articles essentiels répartis en cinq catégories : Eau, Aliments, Santé, Énergie et Autres
- **Calcul dynamique** — définissez le nombre de personnes et les heures d'autonomie, et les quantités se recalculent automatiquement
- **Gestion des dates d'expiration** — enregistrez la date de péremption de chaque unité individuelle ; la date la plus proche prévaut toujours
- **Système d'alerte** par niveaux : ✅ OK (>90 jours) · 🕐 Attention (31–90 jours) · ⚠️ Alerte (<30 jours) · 🔴 URGENT (≤7 jours) · 🚫 Expiré
- **Champ pour les espèces** avec recommandation officielle BCE/DECO : 70–100 € par adulte, en billets de 5, 10 et 20 €
- **Liste de contrôle interactive** avec mise en évidence verte lors du marquage des articles comme prêts
- **Filtres par catégorie** et panneau d'alerte dédié
- **6 langues** — Portugais, Anglais, Espagnol, Italien, Français et Allemand
- **PWA installable** — fonctionne hors ligne et peut être ajoutée à l'écran d'accueil du téléphone
- **Données persistantes** en localStorage — rien n'est envoyé à aucun serveur

### Technologie

- HTML5 + CSS3 + JavaScript vanilla (aucune dépendance externe)
- Système de design **Vibe** de monday.com (tokens officiels depuis `@vibe/core`)
- Polices : **Poppins** (titres) et **Figtree** (corps)
- Service Worker pour le support hors ligne
- PWA avec `manifest.json`

---

## 🇩🇪 Deutsch

### Was ist KIT72H?

**KIT72H** ist eine Progressive Web App (PWA), die dir hilft, ein 72-Stunden-Notfallkit aufzubauen und zu verwalten – entsprechend den Empfehlungen der Europäischen Union und der EZB. Für Mobilgeräte optimiert, mit einem modernen Design basierend auf dem Vibe-Designsystem von monday.com.

Der Stromausfall im April 2025 auf der Iberischen Halbinsel hat gezeigt, wie schnell jede Familie unvorbereitet getroffen werden kann. KIT72H soll verhindern, dass das erneut passiert.

### Funktionen

- **Vorkonfigurierte Liste** mit 25 wesentlichen Artikeln in fünf Kategorien: Wasser, Lebensmittel, Gesundheit, Energie und Sonstiges
- **Dynamische Berechnung** — lege die Personenzahl und die Stunden der Autonomie fest, und die Mengen werden automatisch neu berechnet
- **Ablaufdatumverwaltung** — erfasse das Ablaufdatum jeder einzelnen Einheit; das nächste Datum hat immer Vorrang
- **Mehrstufiges Alarmsystem**: ✅ OK (>90 Tage) · 🕐 Achtung (31–90 Tage) · ⚠️ Alarm (<30 Tage) · 🔴 DRINGEND (≤7 Tage) · 🚫 Abgelaufen
- **Bargeldfeld** mit offizieller EZB/DECO-Empfehlung: 70–100 € pro Erwachsenem, in 5-, 10- und 20-€-Scheinen
- **Interaktive Checkliste** mit grüner Hervorhebung beim Abhaken von Artikeln
- **Kategoriefilter** und dediziertes Alarmfenster
- **6 Sprachen** — Portugiesisch, Englisch, Spanisch, Italienisch, Französisch und Deutsch
- **Installierbare PWA** — funktioniert offline und kann dem Startbildschirm des Mobilgeräts hinzugefügt werden
- **Persistente Daten** in localStorage — nichts wird an Server übertragen

### Technologie

- HTML5 + CSS3 + Vanilla JavaScript (keine externen Abhängigkeiten)
- **Vibe** Design System von monday.com (offizielle Tokens aus `@vibe/core`)
- Schriften: **Poppins** (Überschriften) und **Figtree** (Fließtext)
- Service Worker für Offline-Unterstützung
- PWA mit `manifest.json`

---

## License / Licença / Licencia / Licenza / Licence / Lizenz

MIT — free to use, fork, and adapt. / Livre de usar, copiar e adaptar.
