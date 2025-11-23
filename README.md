# MMORPG Plugin für Minecraft Paper

Ein vollständiges MMORPG-Plugin für Minecraft Paper Server (1.20.x - 1.21.x) mit Klassen-System, Rassen, Skills, Quests, Parties, Gilden, **Berufen, Economy-System, Shops** und mehr.

## Features

### ✨ Core-Features
- **6 Einzigartige Klassen**: Krieger, Magier, Schurke, Paladin, Waldläufer, Priester
- **6 Spielbare Rassen**: Mensch, Elf, Zwerg, Ork, Halbling, Nachtelf
- **Skill-System**: Über 20+ Skills mit Talent-Bäumen
- **Level-System**: Bis Level 100 mit XP-Gain aus verschiedenen Quellen
- **Attribut-System**: STR, DEX, INT, VIT, LUCK mit Rassenboni
- **Quest-System**: 72+ Quests mit verschiedenen Quest-Typen
- **Party-System**: Gruppiere dich mit bis zu 5 Spielern
- **Gilden-System**: Erstelle und verwalte Gilden mit Rängen

### 💼 Berufe-System
- **10 Berufe**: Bergbau ⛏, Holzfäller 🪓, Farmer 🌾, Fischer 🎣, Schmied 🔨, Alchemist ⚗, Verzauberer ✨, Kräuterkundler 🌿, Koch 🍳, Jäger 🏹
- **Level 1-100**: Levele jeden Beruf bis 100
- **XP-System**: Sammle XP durch relevante Aktionen
- **Fähigkeiten**: Schalte alle 10 Level neue Abilities frei
- **Progression**: Exponentielles XP-Wachstum für Langzeitmotivation

### 🏪 Shop-System
- **Server-Shop**: 6 Kategorien (Waffen, Rüstungen, Tränke, Materialien, Nahrung, Spezial)
- **Spieler-Shops**: Erstelle deinen eigenen Shop für 5000 Gold
- **Shop-Verwaltung**: Füge Items hinzu, setze Preise, verwalte Vorrat
- **Verkaufs-System**: Verkaufe Items an den Server-Shop (50% Kaufpreis)

### 💰 Economy-System
- **Vault-Integration**: Vollständige Vault-API-Unterstützung
- **Balance-Verwaltung**: Deposits, Withdrawals, Transfers
- **Shop-Transaktionen**: Kaufe und verkaufe Items
- **Profession-Belohnungen**: Verdiene Gold durch Berufe

### 🎮 HUD & Effects
- **Mana-Bar**: BossBar zeigt Mana-Status in Echtzeit
- **ActionBar**: Zeigt HP, Mana, Level und XP
- **Scoreboard**: Live-Stats-Anzeige mit Klasse, Rasse, Gold
- **Effect-System**: Buffs & Debuffs mit Partikel-Effekten
- **Skill-Effects**: Visuelle Effekte für Skills (Level-Up, Kreis-Effekte)

### 📖 Guidebook-System
- **Interaktives Guide**: 7 Kapitel mit allen Features
- **Guide-GUI**: Übersicht aller Kapitel
- **Bücher**: Erhalte geschriebene Bücher für jedes Kapitel
- **Commands-Übersicht**: Alle wichtigen Befehle auf einen Blick

### 🏆 Achievement-System
- **30+ Achievements**: Über 30 Erfolge in 8 Kategorien
- **Kategorien**: Kampf, Erkundung, Handwerk, Sozial, Quests, Berufe, Sammlung, Spezial
- **Seltenheitsstufen**: Common, Uncommon, Rare, Epic, Legendary
- **Fortschritts-Tracking**: Automatische Erfassung deines Fortschritts
- **Belohnungen**: XP, Gold, Skillpunkte, Titel
- **Achievement-GUI**: Übersichtliche Anzeige mit Kategorien
- **Fortschrittsbalken**: Visueller Fortschritt für unvollendete Achievements
- **Benachrichtigungen**: Toasts bei Achievement-Freischaltung
- **Broadcast**: Epic/Legendary Achievements werden serveröffentlich angekündigt

### 🏰 Territory-Control
- **Gilden-Territorien**: Beanspruche Land für deine Gilde
- **8 Schutz-Flags**: PVP, Explosionen, Block-Break/Place, Container, Interaktionen, Mob-Spawning, Feuer
- **5 Territory-Typen**: Normal, Festung, Handelsposten, Farm, Mine
- **Level-System**: Upgrade Territorien von Level 1-10
- **Trusted Players**: Vertraue Spielern Zugriff auf dein Territory
- **Kosten-System**: 10 Gold pro Block + Upgrade-Kosten

### 🗡️ Custom Items & Equipment-Sets
- **6 Raritäten**: Common, Uncommon, Rare, Epic, Legendary, Mythic
- **18 Stat-Typen**: Damage, Defense, Health, Mana, STR, DEX, INT, VIT, Luck, Crit, Dodge, Lifesteal, etc.
- **7 Item-Typen**: Weapon, Helmet, Chestplate, Leggings, Boots, Accessory, Tool
- **Equipment-Sets**: 2/4-Piece Boni (Dragon Knight, Shadow Assassin, Mystic Mage)
- **10+ Vordefinierte Items**: Excalibur, Staff of Elements, legendäre Set-Items
- **Random Loot Generator**: Level-basierte Item-Generierung

### 🎭 Quest-NPC-System (Citizens Premium)
- **Citizens-Integration**: Vollständige Integration mit Citizens Premium
- **Quest-Geber NPCs**: NPCs bieten Quests an und nehmen sie entgegen
- **Dialog-System**: Mehrstufige Dialoge mit Antwortoptionen
- **Quest-Marker**: Visuelle Marker über NPCs (! für neue Quests, ? für Abgaben)
- **Quest-Chains**: Automatische Folge-Quests nach Abschluss
- **Level-Anforderungen**: NPCs prüfen Spieler-Level und abgeschlossene Quests
- **Dynamische Dialoge**: 6 Dialog-Typen (Begrüßung, Angebot, Annahme, Fortschritt, Abschluss, Keine Quest)
- **NPC-Verwaltung**: Admin-Commands zum Erstellen und Konfigurieren von Quest-NPCs

### ⚔️ Kampf-System
- Custom Damage-Berechnung basierend auf Attributen
- Kritische Treffer basierend auf Glück
- Combat-Status mit Regenerations-Pause
- XP-Gewinn durch Mob-Kills

### 💾 Datenbank
- MySQL und SQLite Support
- HikariCP Connection-Pooling
- Async-Operationen für Performance
- Auto-Save-System
- Profession-Daten persistent gespeichert

### 🎨 GUI-System
- Interaktive Klassen-Auswahl
- Interaktive Rassen-Auswahl
- Server-Shop mit Kategorien
- Guidebook-Übersicht
- **Skills-Übersicht mit Details** (Cooldown, Mana, Schaden)

## Installation

1. **Server-Anforderungen**:
   - Paper/Spigot 1.20.6 oder höher
   - Java 17 oder höher
   - Optional: MySQL-Datenbank
   - **Empfohlen**: Vault + Economy-Plugin (z.B. EssentialsX)
   - **Optional**: Citizens Premium (für Quest-NPCs)

2. **Plugin kompilieren**:
   ```bash
   mvn clean package
   ```

3. **JAR-Datei kopieren**:
   - Die generierte JAR-Datei aus `target/` in den `plugins/` Ordner kopieren
   - **Vault installieren** (für Economy-Features)
   - Server starten

4. **Konfiguration anpassen**:
   - `plugins/MMORPGPlugin/config.yml` nach Bedarf bearbeiten
   - `plugins/MMORPGPlugin/shop-items.yml` für Shop-Items anpassen
   - Optional: Datenbank auf MySQL umstellen
   - Server neu laden: `/mmorpg reload`

## Commands

### Spieler-Commands
| Command | Beschreibung | Aliases |
|---------|--------------|---------|
| `/class [choose\|info\|list]` | Klassen-System verwalten | `/klasse`, `/c` |
| `/race [choose\|info\|list]` | Rassen-System verwalten | `/rasse`, `/r` |
| `/skills [list\|info\|use]` | Skills verwalten | `/skill`, `/s` |
| `/stats [player]` | Zeigt Statistiken | `/status`, `/char` |
| `/party [create\|invite\|leave]` | Party-System | `/p`, `/gruppe` |
| `/guild [create\|invite\|info]` | Gilden-System | `/g`, `/gilde` |
| `/quest [list\|accept\|track]` | Quest-System | `/q`, `/aufgabe` |
| `/profession [list\|info\|stats]` | **Berufe-System** | `/prof`, `/beruf` |
| `/shop [create\|add\|manage]` | **Shop-System** | `/store`, `/laden` |
| `/guide [get]` | **Interaktives Guidebook** | `/help`, `/hilfe` |
| `/achievements [stats\|list]` | **Achievement-System** | `/achievement`, `/ach`, `/erfolge` |
| `/questnpc <sub>` | **Quest-NPC-Verwaltung (Admin)** | `/npcquest`, `/qnpc` |

### Admin-Commands
| Command | Beschreibung | Permission |
|---------|--------------|------------|
| `/mmorpg reload` | Lädt Konfiguration neu | `mmorpg.admin` |
| `/mmorpg debug` | Debug-Informationen | `mmorpg.admin` |

## Profession Commands (Detailliert)
- `/profession` - Zeigt Übersicht aller deiner Berufe
- `/profession list` - Liste aller 10 Berufe mit Beschreibungen
- `/profession info <beruf>` - Detaillierte Infos zu einem Beruf
- `/profession stats` - Zeigt deine Berufe-Statistiken

## Shop Commands (Detailliert)
- `/shop` - Öffnet Server-Shop GUI
- `/shop create <name>` - Erstellt Spieler-Shop (Kosten: 5000 Gold)
- `/shop add <preis>` - Fügt Item zum eigenen Shop hinzu
- `/shop manage` - Verwalte deinen Shop
- `/shop toggle` - Öffne/Schließe deinen Shop
- `/shop list` - Liste aller Spieler-Shops
- `/shop sell` - Verkaufe Item an Server-Shop

## Achievement Commands (Detailliert)
- `/achievements` - Öffnet Achievement-GUI mit allen Kategorien
- `/achievements stats` - Zeigt deine Achievement-Statistik
- `/achievements list` - Liste aller Achievements
- `/achievements list <kategorie>` - Liste einer spezifischen Kategorie
  - Kategorien: `COMBAT`, `EXPLORATION`, `CRAFTING`, `SOCIAL`, `QUESTS`, `PROFESSIONS`, `COLLECTION`, `SPECIAL`

## Quest-NPC Commands (Admin)
- `/questnpc create <name> [typ]` - Erstellt einen Quest-NPC
- `/questnpc remove <id>` - Entfernt einen Quest-NPC
- `/questnpc assignquest <id> <quest-id>` - Ordnet Quest zu NPC zu
- `/questnpc assigncompletion <id> <quest-id>` - Ordnet Quest-Abgabe zu
- `/questnpc setdialog <id> <typ> <text>` - Setzt NPC-Dialog
  - Typen: `greeting`, `offer`, `accept`, `progress`, `complete`, `noquest`
- `/questnpc list` - Liste aller Quest-NPCs
- `/questnpc info <id>` - Zeigt NPC-Details

## Permissions

### Basis-Permissions
- `mmorpg.*` - Alle Permissions (OP)
- `mmorpg.class.use` - Klassen-System nutzen (Standard: true)
- `mmorpg.race.use` - Rassen-System nutzen (Standard: true)
- `mmorpg.skills.use` - Skills nutzen (Standard: true)
- `mmorpg.stats.use` - Eigene Stats anzeigen (Standard: true)
- `mmorpg.stats.others` - Fremde Stats anzeigen (OP)
- `mmorpg.party.use` - Party-System nutzen (Standard: true)
- `mmorpg.guild.use` - Gilden-System nutzen (Standard: true)
- `mmorpg.quest.use` - Quest-System nutzen (Standard: true)
- `mmorpg.admin` - Admin-Commands (OP)

### Neue Permissions
- `mmorpg.profession.*` - Alle Berufe-Permissions (Standard: true)
- `mmorpg.profession.use` - Berufe-System nutzen (Standard: true)
- `mmorpg.shop.*` - Alle Shop-Permissions (Standard: true)
- `mmorpg.shop.use` - Shop-System nutzen (Standard: true)
- `mmorpg.shop.create` - Spieler-Shops erstellen (Standard: true)
- `mmorpg.shop.sell` - Items verkaufen (Standard: true)
- `mmorpg.guide.*` - Alle Guide-Permissions (Standard: true)
- `mmorpg.guide.use` - Guidebook nutzen (Standard: true)
- `mmorpg.achievements.*` - Alle Achievement-Permissions (Standard: true)
- `mmorpg.achievements.use` - Achievement-System nutzen (Standard: true)

## Konfiguration

### config.yml
Hauptkonfiguration für Datenbank, Level-System, Combat und mehr.

```yaml
database:
  type: sqlite  # oder mysql
  
leveling:
  max-level: 100
  xp-multiplier: 1.0
  
combat:
  custom-damage: true
  death-xp-loss: 5
```

### classes.yml
Definition aller Klassen und deren Skills.

### races.yml
Definition aller Rassen und deren Boni/Mali.

### skills.yml
Definition aller Skills mit Schaden, Manakosten, Cooldowns.

### quests.yml
Definition aller Quests mit Zielen und Belohnungen.

### messages.yml
Alle Spielernachrichten (mehrsprachig erweiterbar).

## Klassen-Übersicht

### 🗡️ Krieger
- **Rolle**: Tank/DPS
- **Stärken**: Hohe Health, hohe Stärke
- **Schwächen**: Wenig Mana, geringe Intelligenz
- **Skills**: Mächtiger Hieb, Angriff, Schildschlag, Berserker-Wut

### 🔮 Magier
- **Rolle**: Ranged DPS
- **Stärken**: Hohe Intelligenz, hohes Mana
- **Schwächen**: Geringe Health, niedrige Rüstung
- **Skills**: Feuerball, Eisblitz, Blitz, Teleport

### 🗡️ Schurke
- **Rolle**: Melee DPS
- **Stärken**: Hohe Geschicklichkeit, hoher Kritschaden
- **Schwächen**: Mittlere Health
- **Skills**: Meucheln, Verstohlenheit, Gift, Schattensprung

### ⚔️ Paladin
- **Rolle**: Tank/Healer
- **Stärken**: Heilfähigkeiten, gute Balance
- **Schwächen**: Keine extremen Stärken
- **Skills**: Heiliger Schlag, Heilung, Göttlicher Schild, Segen

### 🏹 Waldläufer
- **Rolle**: Ranged DPS
- **Stärken**: Hohe Geschicklichkeit, Fernkampf
- **Schwächen**: Mittlere Health
- **Skills**: Mehrfachschuss, Falle, Adlerauge, Begleiter beschwören

### ✨ Priester
- **Rolle**: Healer/Support
- **Stärken**: Mächtige Heilung, Gruppenheilung
- **Schwächen**: Geringe Kampfkraft
- **Skills**: Heilung, Gruppenheilung, Wiederbelebung, Heilige Nova

## Rassen-Übersicht

| Rasse | STR | DEX | INT | VIT | LUCK | Spezialfähigkeit |
|-------|-----|-----|-----|-----|------|------------------|
| Mensch | 0% | 0% | 0% | 0% | +5% | +5% XP-Gewinn |
| Elf | -5% | +10% | +15% | -10% | +5% | Nachtsicht |
| Zwerg | +15% | -15% | -10% | +20% | 0% | +20% Gift-Resistenz |
| Ork | +20% | -10% | -25% | +10% | -5% | +10% Schaden bei niedriger HP |
| Halbling | -15% | +15% | +5% | -15% | +20% | +20% besserer Loot |
| Nachtelf | -10% | +5% | +20% | -5% | +5% | Weniger Mob-Aggro |

## Entwicklung & Erweiterung

### Geplante Features
- [ ] Erweiterte Skill-Effekte mit Partikeln
- [x] **Quest-NPCs mit Citizens Premium Integration**
  - [x] NPC-Quest-Geber erstellen
  - [x] Interaktive Dialoge mit Quest-Annahme
  - [x] Quest-Abgabe bei NPCs
  - [x] Quest-Marker über NPCs (Hologramme)
  - [x] Dynamische NPC-Spawns basierend auf Quest-Status
  - [x] Citizens-API Integration für NPCs
  - [x] Quest-Chain-NPCs (mehrstufige Quests)
  - [x] Dialog-System mit Antwortoptionen
- [x] Territory-Control für Gilden
- [x] Custom Items und Equipment-Sets
- [ ] Dungeons mit Instanzen
- [ ] PvP-Arenen und Ranglisten
- [x] Achievement-System
- [ ] PlaceholderAPI-Integration
- [x] Vault-Economy-Integration

### API für Entwickler
Das Plugin bietet Zugriff auf alle Manager-Klassen:

```java
MMORPGPlugin plugin = MMORPGPlugin.getInstance();
StatsManager statsManager = plugin.getStatsManager();
PlayerData data = statsManager.getPlayerData(player);
```

## Support & Contribution

Bei Fragen, Bug-Reports oder Feature-Requests bitte ein GitHub Issue erstellen.

## Lizenz

Dieses Projekt ist für private und kommerzielle Nutzung frei verfügbar.

## Credits

Entwickelt mit ❤️ für die Minecraft-Community

---

**Version**: 1.0.0-SNAPSHOT  
**Minecraft**: Paper 1.20.6+  
**Java**: 17+


🎯 Empfehlung für nächste Schritte:
Deprecation-Warnings beheben (optional)
