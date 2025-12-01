# About Me

Hey, I'm Aja. I'm a programmer and designer who has been building prototypes to improve my skills in game development and project management. This my personal repository and hub for all of my game system and tool creations, as well as pieces of my lean software suite for Mandible.

###
---
# Public Projects

These are currently a few mainline modules from the Mandible ecosystem. They represent the foundation of our projects and will remain publicly available for the time being.

### **Mandible.Generic**
A foundational package containing engine-agnostic utility systems:
- Custom serialization helpers
- Data structures (e.g., Blackboard, SerializedDictionary)
- Math and runtime utilities
- Shared infrastructure for our Mandible modules

### **Mandible.PlayerController**
A modular, kinematic character controller built for flexibility and extensibility:
- Dynamic camera handling
- Event-driven forces and movement channels
- Input abstraction layer (Keyboard/Mouse & Controller)
- Assessed for future physics integration
- Clean interoperability with Mandible.AbilitySystem

### **Mandible.AbilitySystem**
A modular ability framework with emphasis on extensibility and runtime flexibility:
- Base slots, swappable slots, and override profiles
- Weighted input buffering and ability queuing
- Runtime ability data and cooldown tracking
- Extensions: *UltimateAbilitySystem* addon inspired by Overwatch's Ultimates
- Integrates cleanly with Mandible.PlayerController and custom keybinding setups

---

# Private R&D Systems (In Development)

These systems remain private while APIs, documentation, and architecture stabilize.  
They form the backbone of long-term Mandible engine and tooling development.

### **SPKTRE (Flagship Project)**
A high-systems action project built on custom Mandible tooling.  
Includes experimental movement logic, AI prototypes, data interfaces, and world systems.

### **BiteGraph**
A serialized node-graph and blackboard framework designed for designer-friendly logic:
- Serialized editor interface
- Reflection-driven discovery for custom node types
- Condition, action, and hard-coded node support
- Blackboard variable system
- Built to integrate with controllers, abilities, and AI systems

### **HybridController + PhysicsSystem**
An experimental kinematic/physics hybrid movement system:
- Additive movement layers (forces + kinematic intent)
- Omnigravity support and non-standard medium behaviors
- PhysicsSystem proxy with serialized rigidbody parameters
- Custom locomotion models for experimental traversal and planetary environments

---

# Smaller Projects & Prototypes

Compact tools and earlier prototypes exploring engine behavior, gameplay, and software design.

- **OsuProfileScraper** — Python-based osu! API scraper for OBS integration (live data overlays).  
- **NovaRift** — Survival/exploration prototype focusing on systemic crafting and planetary traversal.  
- **Anima** — Frog-themed metroidvania prototypes exploring movement, level readability, and environmental storytelling.  
- **Additional micro-projects** — early gameplay tests, engine experiments, and structural prototypes for pipeline practice.

---

# Tech Stack & Tools
- **Languages:** Bash, C, C#, CSS, HTML, Java, Python  
- **Engines:** Unity, Godot  
- **Version Control:** Git  
