# ⚙️ CMOS Inverter Design using Electric VLSI Design Free Tool (Layout, Schematic, DRC, Simulation)

This project demonstrates the complete design, layout, simulation, and verification of a **CMOS Inverter** using the **Electric VLSI Design Tool**.

> 🎓 Designed as part of personal learning in VLSI physical design and layout techniques using open-source tools.

---

## 📂 Project Contents

| File / Folder | Description |
|---------------|-------------|
| `/schematic/` | CMOS Inverter schematic (.jlib or exported images) |
| `/layout/` | Layout view with GDS export |
| `/waveforms/` | Output waveforms captured from simulation |
| `/videos/` | Complete working video (MP4 / YouTube link) |
| `README.md` | This documentation file |
| `LICENSE` | (Optional) MIT or other license |

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

### ✅ Step 2: Layout Design
- Drawn layout using Electric VLSI

- PMOS and NMOS sized for balance

- Used proper VDD, GND, and polysilicon routing

📸 Check /layout folder for GDS and screenshots

### ✅ Step 3: DRC Check
- Layout passed all DRC rules

- Used built-in DRC engine with MOSIS 100nm rules

📄 Results and snapshots in /drc/ folder

### ✅ Step 4: Simulation & Output Waveform
- Applied pulse input to simulate inverter behavior

- Captured waveform using internal simulation tools

📊 Waveform screenshots in /waveforms folder

## 🎥 Working Video
Full demo video of CMOS Inverter design, layout, and simulation:

## 📌 Output Highlights

- Clock High --> Vin High --> Vout Low
- Clock Low --> Vin Low --> Vout High

Output correctly inverts the input signal with expected propagation delay.

## 💡 Learnings
- Hands-on experience with Electric VLSI
- Understanding transistor sizing, layout constraints
- Importance of DRC/LVS in custom digital design
- Delay observed due to rise/fall asymmetry, next step: size adjustment

## 🧠 Author
- Maintained by: Dutt Panchal
- 🔗 Email: dattpanchal2904@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/dattpanchal04/) 
- 💻 [GitHub](https://github.com/DuttPanchal04)

## 📜 License
Feel free to use, share, and modify!