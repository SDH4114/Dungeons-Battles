## Core Development Skills

### 1. Java Programming

- Understanding of Object-Oriented Programming (OOP)
- Working with classes, interfaces, and inheritance
- Knowledge of collections (List, Map, Set)
- Exception handling
- Working with data streams

### 2. Minecraft Forge / Fabric API

- Understanding mod structure
- Registration of blocks, items, entities
- Event handling
- Creating crafting recipes
- Working with configuration files

### 3. Modding Systems

#### Forge

- Using `@Mod` annotation
- FML (Forge Mod Loader)
- Registration via `DeferredRegister`
- Working with Capabilities

#### Fabric

- Using `ModInitializer`
- Fabric API modules
- Mixins for modifying base game

### 4. Creating Game Elements

#### Blocks

- Creating simple and complex blocks
- BlockState and block properties
- TileEntity for data storage
- Block rendering

#### Items

- Basic items
- Tools with durability
- Armor
- Food and potions

#### Entities

- Mobs (friendly/hostile)
- AI and behavior
- Animations
- Entity rendering

### 5. Graphics and Resources

#### Textures

- Creating 16x16, 32x32 textures
- PNG formats
- Animated textures

#### Models

- JSON models for blocks and items
- Cubic models
- OBJ models for complex objects

#### Sounds

- OGG format
- Registering sound events

### 6. Working with Data

#### NBT (Named Binary Tag)

- Saving item data
- Storing information in the world
- Client-server synchronization

#### Datapacks

- Custom recipes
- Loot tables
- Advancements

### 7. Network Communication

- Packets for client-server synchronization
- SimpleChannel (Forge)
- Networking API (Fabric)
- Handling server and client logic

### 8. GUI and Interfaces

- Creating custom menus
- Containers and slots
- Screen classes for display
- Inventory interaction

### 9. World Generation

- Custom WorldGen
- Biomes
- Structures
- Ores and their distribution
- Feature placement

### 10. Optimization and Debugging

- Performance profiling
- Logging (Logger)
- Debugging via IDE (IntelliJ IDEA, Eclipse)
- Testing in different environments

## Development Tools

### IDE

- IntelliJ IDEA (recommended)
- Eclipse
- Visual Studio Code

### Build Systems

- Gradle
- Understanding build.gradle
- Dependencies and repositories

### Graphics Editors

- Aseprite (pixel art)
- GIMP
- Paint.NET
- Blockbench (3D models)

### Version Control

- Git
- GitHub for publishing

## Useful Knowledge

### Documentation

- Reading official Forge/Fabric documentation
- Studying code from other mods
- Community tutorials

### Mathematics

- Vectors and coordinates
- Trigonometry for animations
- Random numbers and probabilities

### Game Design

- Balancing mechanics
- User Experience (UX)
- Game loops and progression

## Mod Complexity Levels

### Beginner Level

- Simple blocks and items
- Basic recipes
- Textures and models

### Intermediate Level

- TileEntities with inventory
- Custom GUIs
- New mobs
- Structure generation

### Advanced Level

- Complex mechanic systems
- Multiblock structures
- Energy systems
- API for other mods
- Cross-platform compatibility

---

## How to Use This Document with Codex

When working with AI coding assistants like Codex, GitHub Copilot, or Claude, follow these guidelines:

### 1. **Reference Specific Skills**

Start your prompts with: "Using skills from Skills.md, help me..."

Example:

```
Using the Forge API skills, create a custom block that emits light
```

### 2. **Specify Your Level**

Mention your experience level:

```
As a beginner, show me how to register a simple item in Forge 1.20
```

### 3. **Combine Multiple Skills**

```
Using NBT data storage and GUI skills, create an item that stores player data and displays it in a custom screen
```

### 4. **Request Step-by-Step Guidance**

```
Following the Beginner Level path, guide me through creating my first block with texture
```

### 5. **Ask for Code Examples**

```
Show me Java code for creating a TileEntity with inventory, following Forge best practices
```

### 6. **Request Explanations**

```
Explain how Event Handling works in Forge with practical examples
```

### 7. **Troubleshooting**

```
My block isn't rendering correctly. Check my code using the Block Rendering skills
```

### 8. **Project Planning**

```
Based on these skills, create a roadmap for building a tech mod with machines and energy system
```

## Best Practices for AI-Assisted Coding

1. **Be Specific**: Reference exact skill categories from this document
2. **Provide Context**: Mention your Minecraft version, mod loader (Forge/Fabric)
3. **Ask for Explanations**: Don't just get code, understand it
4. **Iterate**: Start simple, then add complexity
5. **Request Comments**: Ask for well-commented code
6. **Version Awareness**: Specify Minecraft and Forge/Fabric versions
7. **Error Handling**: Ask for proper error handling in code
8. **Best Practices**: Request code that follows modding conventions

## Example Conversation Flow

```
User: "Using Skills.md Section 4 (Blocks), help me create a glowing ore block for Minecraft 1.20 Forge. I'm at beginner level."

AI: [Provides step-by-step code with explanations]

User: "Now add a custom texture to this block using Section 5 skills"

AI: [Explains texture creation and registration]

User: "How do I make this ore drop a custom item? Reference the Items section"

AI: [Shows loot table creation]
```

---

**Примечание для использования с русским языком:**

Когда вы работаете с AI ассистентом, вы можете просить его отвечать на русском языке, даже если этот документ на английском:

```
Используя навыки из раздела "Forge API", помоги мне создать кастомный блок. Отвечай на русском языке с объяснениями.
```

AI будет использовать английские термины из документа, но давать объяснения на русском языке.