**📘 PCBIY – Semi-Automated Desktop PCB Fabrication Machine**

**A semi-automated 2-layer PCB fabrication machine featuring isolation milling, automated via drilling/riveting, and assisted soldermask application. Designed to bring PCB prototyping into a desktop-friendly workflow.**

This is **V1** of the project. The machine performs all motion and machining steps automatically, while the user manually swaps tools when prompted.

⸻

**🚀 Features (V1)**

**🌀 Fabrication**

	•	High-precision isolation milling
	•	Automated via drilling
	•	Automated via riveting (mechanical micro-rivets)
	•	Assisted soldermask application workflow
	•	Auto-height probing for consistent milling depth

**🔧 User Interaction (Semi-Automatic)**

	•	Manual tool changes (unscrew / screw in new bit)
	•	Machine pauses and guides tool change process
	•	Visual indicators and planned UI prompts
**
⚙️ Electronics & Control**

	•	Closed-loop or high-accuracy stepper motion system
	•	Spindle motor with speed control
	•	Toolpath generation for Gerber inputs
	•	Modular firmware architecture for future ATC upgrades

⸻

**🎯 Project Goals**

	•	Enable affordable, accurate, and fast PCB prototyping at home
	•	Minimize chemical processes
	•	Provide a solid foundation for future versions (V2 with ATC ?, V3 with fully automated soldermask?)
	•	Open-source the entire stack: hardware, firmware, control software

**📁 Repository Structure (Planned)**

  pcbiy/
  
 ├── docs/              # Overview, diagrams, research notes

 ├── mechanics/         # CAD files, STL, STEP, BOM
 
 ├── electronics/       # Schematics, PCB designs
 
 ├── firmware/          # MCU firmware for motion and I/O
 
 ├── ui/                # Web/desktop control interface
 
 ├── toolpath/          # CAM pipeline, Gerber to G-code
 
 └── research/          # Experiments, data, testing results

** 🧩 Roadmap**

**V1 — Semi-Automated (current)**

	•	Manual tool changes
	•	Isolation milling + drilling + vias
	•	Assisted soldermask
	•	Basic UI & firmware

**V2 — Highly Automated**

	•	Automatic tool changer
	•	TBD

**V3 — Fully Integrated Workflow**

	•	“Start → finished PCB” workflow
	•	TBD

⸻

**🧪 Current Status**

	•	Project still being defined

⸻

**🤝 Contributing**

This project is in its early stages.
Feel free to open issues, propose ideas, or share research.

Contributions will be more structured once the core design stabilizes.

⸻

**📜 License**

To be determined.
Hardware and software may use different licenses depending on goals.

⸻

**⭐ Stay Updated**

Watch the repo to follow development.
More documentation and designs will be added as the project evolves.



