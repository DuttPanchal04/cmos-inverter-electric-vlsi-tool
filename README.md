# ⚙️ CMOS Inverter Design using Electric VLSI Design Free Tool (Layout, Schematic, DRC, Simulation)

This project demonstrates the complete design, layout, simulation, and verification of a **CMOS Inverter** using the **Electric VLSI Design Tool**.

> 🎓 Designed as part of personal learning in VLSI physical design and layout techniques using open-source tools.

---

## 📂 Project Contents

| File / Folder | Description |
|---------------|-------------|
| `schematic` | CMOS Inverter schematic (.jlib or exported images) |
| `layout` | Layout view with GDS export |
| `waveform` | Output waveforms captured from simulation |
| `video` | Complete working video (MP4 / YouTube link) |
| `README.md` | This documentation file |

---

## 🛠️ Tools Used

- 🧰 **Electric VLSI Design Free Tool** (v9.08)
- 💻 Ubuntu 22.04 (or specify your OS)
- 🧪 MOSIS 100nm tech library

---

## 🚀 How to Run This Project

### Step 1: Download, Install, and Run Electric VLSI Free Tool 

- [Follow this Repo](https://github.com/DuttPanchal04/electric-vlsi-design-free-tool-installation-guide)

### Step 2: Open Project

Open the .jlib file ( provided in this repo ) in Electric to explore the schematic and layout.

## 🧪 Project Workflow
### ✅ Step 1: Schematic Design
- Built a CMOS inverter using PMOS + NMOS

- Verified input/output waveform behavior

📸 Screenshots available in /schematic folder

![CMOS Inverter Schematic](https://github.com/user-attachments/assets/e0770b2c-3472-4037-9403-a40a050d12e2)

### ✅ Step 2: Layout Design
- Drawn layout using Electric VLSI

- PMOS and NMOS sized for balance

- Used proper VDD, GND, and polysilicon routing

📸 Check /layout folder for GDS and screenshots

![CMOS Inverter Layout](https://github.com/user-attachments/assets/87d04ce8-a673-4124-9465-66e11b4234bc)

### ✅ Step 3: DRC Check
- Layout passed all DRC rules

- Used built-in DRC engine with MOSIS 100nm rules

![CMOS Inverter DRC Check in Electric Tool](https://github.com/user-attachments/assets/d4b19aa9-8bbc-4b9a-bfc6-b5b2c5b61726)

### ✅ Step 4: Simulation & Output Waveform
- Applied pulse input to simulate inverter behavior

- Captured waveform using internal simulation tools

📊 Waveform screenshots in /waveforms folder

![CMOS Inverter Simulation](https://github.com/user-attachments/assets/be13b3ab-c046-4d73-8d67-b3d97a035ec9)

![Inverter Output Waveform](https://github.com/user-attachments/assets/36ab2bb8-a215-4554-9b4e-923d73e60ce4)

## 🎥 Working Video
Full demo video of CMOS Inverter design, layout, and simulation:

[CMOS Inverter in Electric.webm](https://github.com/user-attachments/assets/1e7eaf31-9050-4e7f-9181-584b6f3823f0)

## 📌 Output Highlights

- Clock High --> Vin High --> Vout Low
- Clock Low --> Vin Low --> Vout High

Output correctly inverts the input signal with expected propagation delay.

## 💡 Learnings
- Hands-on experience with Electric VLSI
- Understanding transistor sizing, layout constraints
- Importance of DRC/LVS in custom digital design
- Delay observed due to rise/fall asymmetry, next step: size adjustment

## 🤝 Contribute & Collaborate
This project is open for contributions and collaborative learning! Whether you're a student, hobbyist, or industry professional, you're welcome to:

- 🔧 Improve and Optimize
- 🔄 Delay Optimization: Suggest or implement better transistor sizing or layout improvements to reduce propagation delay.
- 🔍 Performance Analysis: Simulate with different input pulse widths, supply voltages, or load capacitances.
- ⚡ Power vs Speed Trade-off: Explore dynamic/static power improvements.

## 💡 Design Variants: 
- Extend the project to include: NAND, NOR, XOR gates
- Transmission-gate-based inverters
- CMOS level shifters

## 🧰 Toolchain Integration
- 📤 Export GDS and verify with tools like KLayout or Magic
- 🔁 Perform LVS (Layout vs Schematic) if supported
- 📡 Integrate with open PDKs like SkyWater130 (experimental)

## 🛠️ Feature Enhancements
- 📘 Add detailed transistor sizing guide
- 🎥 Add narration to the existing video or new simulation videos
- 📄 Include timing diagrams and truth tables in Markdown/LaTeX

## 📝 How to Contribute

- Fork this repository
- Clone your fork:
```
git clone https://github.com/yourusername/cmos-inverter-electric-vlsi-tool.git
```
- Create a new branch:
```
git checkout -b improve-delay-sizing
```
- Make your changes, commit, and push:
```
git add .
git commit -m "Optimized NMOS/PMOS sizing to reduce delay"
git push origin improve-delay-sizing
```
- Open a Pull Request from your branch to the main branch.

## 💬 Let's Collaborate
- If you have ideas, questions, or need help getting started:
- Open an Issue on [GitHub](https://github.com/DuttPanchal04)
- Connect with me on [LinkedIn](https://www.linkedin.com/in/dattpanchal04/) to collaborate or showcase your forks!

## 🧠 Author
- Maintained by: Dutt Panchal
- 🔗 Email: dattpanchal2904@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/dattpanchal04/) 
- 💻 [GitHub](https://github.com/DuttPanchal04)

## 📜 License
Feel free to use, share, and modify!
