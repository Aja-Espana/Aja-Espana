# About Me

Hey, I'm Aja. I'm a programmer and designer who has been building prototypes to improve my skills in game development and project management. This my personal hub for all of my tools and scripts, including systems I've developed for Mandible.

###
---
# Public Projects

There are currently a few mainline systems in the Mandible suite. They're becoming the foundation of our projects and will remain publicly available for the time being.

### **Mandible.Generic**
A foundational package containing Unity and engine-agnostic utils:
- Custom serialization helpers
- Data structures (e.g., Blackboard, SerializedDictionary)
- Math and runtime utilities
- Dependency for other Mandible systems

### **Mandible.PlayerController**
A modular, kinematic character controller that can be easily extensible:
- Dynamic camera handling
- Procedural animations and force response
- Input abstraction layer (PC & Console innately supported)
- Open to use with Physics effectors
- Clean interoperability with Mandible.AbilitySystem

### **Mandible.AbilitySystem**
A modular ability framework that uses ScriptableObject Abilities with a native scripting API & Blackboard:
- Base slots, swappable slots, and override profiles
- Weighted input buffering and ability queuing
- Runtime ability data and cooldown tracking
- Extensions: *UltimateAbilitySystem* addon inspired by Overwatch's Ultimates
- Integrates cleanly with Mandible.PlayerController and its input abstraction layer

---

# Private R&D Systems (In Development)

These systems will be private, since they're in-house Mandible projects or experiments. I might release documentation later on a portfolio site later in my coursework.

### **SPKTRE (Main Project)**
A high-systems action project built on custom Mandible tooling.  
Includes experimental movement controller, AI prototypes, data interfaces, and core systems.

### **BiteGraph**
A simple, experimental node graph to help model decoupled, serialized behavior:
- Serialized editor interface
- Reflection-based querying for custom node types
- Generic condition, action, and hard-coded node support
- Blackboard variable system
- Built to integrate with controllers, abilities, and AI systems

### **HybridController + PhysicsSystem**
An experimental kinematic/physics hybrid movement system:
- Additive movement layers (kinematic + dynamic forces)
- Effector subscription and layering (e.g. bounce pads, grapple spots)
- Omnigravity support and nonstandard physics behaviors
- PhysicsSystem dependency with serialized Rigidbody parameters

---

# Smaller Projects & Prototypes

Earlier personal projects exploring system architecture, object-oriented programming, and software design.

- **OsuProfileScraper** — Python-based osu! API scraper for OBS integration (live data overlays).  
- **NovaRift** — Survival/exploration prototype focusing on systemic crafting and planetary traversal.  
- **Anima** — Frog-themed metroidvania prototype exploring movement, level readability, and musical storytelling.  

---

# Tech Stack & Tools

Languages: C#, C/C++, Python, Java, Bash/Shell, Racket, JavaScript, HTML/CSS, LaTeX 

Technologies: Unity, Unreal Engine, Godot, Shader Graph, Git, Visual Studio, React, Figma
