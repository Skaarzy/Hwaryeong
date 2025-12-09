# Map Discovery System

## Overview
The world of the Joseon-era murim is vast and filled with hidden secrets, sacred sites, and forgotten locations. Rather than revealing the entire map at game start, players gradually uncover the realm through exploration and discovery. The map system uses a two-stage revelation mechanic that encourages curiosity while maintaining a sense of mystery and exploration. Players must physically travel to locations, discover what they contain, and use knowledge gained to unlock further secrets.

## Stage One: Lifting the Fog

### Initial Map State (From Game Start)
The map begins partially revealed with **major roads and pathways always visible**, connecting all main provincial capitals and major cities. This allows the player to navigate between settlements without visiting one first, enabling natural exploration and wandering. Players can follow roads, discover locations by traveling, and unlock small portions of the map through their own journeys.

### What's Initially Visible
- **Major trade routes and roads** - main pathways connecting all significant cities
- **Primary cities and capitals** - marked as destination points
- **Coastlines and major geographic boundaries** - basic world shape
- **General direction and scale** - sense of the world's layout
The initial revealed portion is **minimal but functional**, allowing travel and basic navigation without requiring city visits.

### Provincial Capital Discovery
When the player enters a major city or provincial capital for the first time, the fog of war obscuring that entire province lifts from the map. This represents the MC gaining detailed geographical knowledge through visiting the capital and gain knowledge of a map of that Capitals province  local exploration, speaking with merchants, guards, and citizens about the terrain and secrets.

### What Gets Fully Revealed
- **Detailed physical geography** - mountains, rivers, forests, plains, coastlines become clearly visible
- **Secondary roads and paths** - smaller routes, shortcuts, and local trails appear
- **All cities and towns** - populated centers beyond just the capitals
- **Natural landmarks** - distinctive geographical features (peaks, waterfalls, hidden caves)
- **Complete province layout** - the full shape and scale become clear

### The Benefit of City Visits
While players can explore on their own by following roads and wandering, visiting a provincial capital provides **significant map advantages**:
- Reveals entire province at once (vs. gradual discovery through walking)
- Unlocks many question marks simultaneously (vs. finding them individually)
- Provides NPCs who share information about nearby locations and activities
- Accelerates content discovery substantially
However, city visits are **not mandatory** - thorough explorers can discover most content through dedicated wandering and following roads, just more slowly and laboriously.

## Stage Two: Question Mark Discovery

### Question Mark Placement
Once a province's fog is lifted, **question marks (?)** appear scattered across the map at specific locations. These marks indicate points of interest—places where something notable exists—but their nature remains unknown. Question marks appear at:
- **Isolated caves and mountain shrines**
- **Abandoned temples and training grounds**
- **Festival grounds and tournament venues**
- **Warrior meeting places and dueling arenas**
- **Hidden meditation spots and sacred sites**

### Distribution Logic
Question marks are placed intentionally across the province, reflecting the various activities and systems available in that region. A province in the demon war era might have more question marks related to meditation and technique discovery, while a political era region might concentrate them near dueling locations and weapon scroll sites.

The density of question marks varies by province size and activity potential, preventing either overwhelming saturation or barren emptiness.

## Discovery Through Exploration

### Approaching a Question Mark
When the player travels to and approaches a question mark on the map, they physically encounter whatever location it represents. The environment itself provides contextual clues—a peaceful glade suggests meditation, an ancient stone monument suggests a stele, a fighting arena suggests tournaments or duels.

### Identification Moment

As the player draws near, an interaction prompt or environmental trigger reveals what the location is:
- **"Ancient Stele"** - reveals as a Stele Riddle location
- **"Bamboo Grove"** - reveals as a Flute Meditation location
- **"Training Ground"** - reveals as a technique fragment site
- **"Tournament Arena"** - reveals as a Ssireum or Duel location
- **"Abandoned Warrior's Camp"** - reveals as a Wandering Warrior encounter
The question mark transforms into its actual location type icon on the map.

### No Information Before Discovery

Critically, the player cannot determine what a question mark is without physically traveling there. This creates:
- **Genuine exploration** - the thrill of discovering what lies ahead
- **Intentional mysteries** - some locations reveal secrets through experience rather than prior knowledge
- **Player agency** - the choice to investigate or bypass unknown locations
- **Natural pacing** - discovery feels earned rather than handed to the player

## Revealed Location Persistence

### Map Memory
Once a question mark is revealed as a specific location type, it remains permanently marked on the map with its proper icon. Players can see at a glance that a location is a flute meditation site, a duel arena, or a weapon scroll location.

### Revisit Access
Revealed locations remain accessible for revisit and repeat activities (duels can be challenged again, flute melodies can be replayed for rewards, etc.). The map shows the location type, allowing players to plan which activities to pursue.

### Progressive Mapping
As players explore more provinces and discover more locations, their map fills with icons representing the various systems. This creates a visual sense of progress and growing familiarity with the realm.

### Player Choice
- **Use statues for guidance** - bow to learn what activities exist, then seek them out
- **Ignore statues** - explore organically, discovering question marks through wandering
This adds optional depth for players seeking guidance while maintaining mystery for those preferring pure exploration.

## Map System Benefits

### Encourages Exploration
The question mark system rewards thorough exploration. Players who investigate every location uncover all available content and systems, while those rushing through the story may miss significant optional activities.

### Preserves Mystery
Without pre-revealed information, even the map becomes a tool of discovery rather than spoiler. Players genuinely wonder what lies at each question mark, creating moments of pleasant surprise.

### Natural Pacing
Location discovery happens organically through story progression and natural exploration. The game doesn't frontload all available activities at once, but rather reveals them as the player journeys through the world.

### Multiple Playstyles
- **Completionists** can methodically explore each province, discovering every question mark
- **Story-focused players** can follow main quests while occasionally investigating nearby question marks
- **Explorers** can wander freely, discovering activities based on curiosity and wanderlust

## Technical Implementation

### Question Mark Visibility
Question marks appear only after a province's fog is lifted. They are visible on the zoomed-out map but become clearer as the player approaches them in the world.

### Interaction Radius
Question marks can be interacted with when the player is within a certain distance, triggering the discovery moment and converting the question mark to its proper location type icon.

### Data Persistence
The game tracks which question marks have been discovered and converted to known location types. This data persists across saves, allowing players to reference their knowledge of the world.

## Design Philosophy
- **Organic Discovery** - exploration feels natural and rewarding, not mechanically enforced
- **Minimal Hand-Holding** - players determine their own pace and depth of exploration
- **Meaningful Exploration** - discovering a location provides actual information and access to activities
- **World Coherence** - the map system reinforces the living, breathing nature of the Joseon-era world
- **Player Agency** - choice about what to explore, when to explore, and how thoroughly to map the realm