
```
             ███████╗██████╗ ████████╗██╗    ██╗
             ██╔════╝██╔══██╗╚══██╔══╝██║    ██║
             █████╗  ██║  ██║   ██║   ██║ █╗ ██║
             ██╔══╝  ██║  ██║   ██║   ██║███╗██║
             ███████╗██████╔╝   ██║   ╚███╔███╔╝
             ╚══════╝╚═════╝    ╚═╝    ╚══╝╚══╝ 
```


**Felipe "yuee" Lemos, 21** — Software Engineer & Offensive Security Researcher  
Rio de Janeiro, Brazil

I build offensive tools and break security assumptions. Currently preparing for OSCP while researching EDR evasion techniques and building AI-powered automation systems.

---

### What I Work On

**Security Research**
- EDR/AV bypass techniques (syscall unhooking, API obfuscation)
- Process injection methods (RemoteThread, APC, thread hijacking)
- Binary analysis and reverse engineering
- Network pivoting and stealth communications

**Engineering**
- Agentic AI systems (LLM orchestration, workflow automation)
- Computer vision & image analysis (reverse engineering, statistical modeling)
- Low-level systems programming (Rust, C/C++)
- Backend infrastructure (Go, Python, distributed systems)
- Security tooling and automation frameworks

---

### Selected Work

**[New Journey](https://www.roblox.com/games/17011057137/New-Journey)** — Roblox PvP Game  
Head Developer & Audio Lead Design (2 years). Marvel-inspired combat system with custom audio engine. 7.2M+ visits.

**Agentic AI Automator** — Business Process Automation  
Python pipeline integrating GPT-4 for conversational workflow automation. Built end-to-end: API design, PostgreSQL modeling, Redis caching, Docker deployment. Reduced manual processes by 80% in production.

**Project Chameleon** — Network Tunneling & Proxying
Rust/Python hybrid for bypassing enterprise restrictions. Implements custom protocols for stealth networking and API routing. Designed for low-latency, high-concurrency environments.

**EDR Validation Framework** — Security Defense Testing  
Python orchestration layer with C++/Rust payloads. Simulates process injection, syscall manipulation, and evasion techniques for authorized security testing. MongoDB persistence, Redis job queues.

**CAPTCHA Solver V2** — Computer Vision & Reverse Engineering  
Full reverse engineering pipeline for CAPTCHA systems. PyTorch ViT for solving, coupled with statistical analysis suite for synthetic generation calibration.

**Analysis Pipeline:**
- `deep_background_analysis.py`: Extracts noise distribution via HoughLinesP (line detection), HoughCircles (interference patterns), and spatial density mapping in 5x5 grids. Generates comparative histograms for statistical validation.
- `extract_complete_metrics.py`: Core reverse engineering module. Uses median/mode pixel analysis across grouped samples to mathematically separate static backgrounds from dynamic text. Auto-generates C# config snippets for synthetic generator.
- `extract_color_palette.py`: K-Means clustering (sklearn) on extracted text pixels to identify exact RGB palette (16-20 dominant colors) with frequency distribution. Outputs production-ready ColorPalette class.
- `parameter_extractor.py`: Unified orchestrator. Processes batches → detects primitives via Hough + LSD (Line Segment Detector) → aggregates statistics → generates final CaptchaConfig.cs. Includes hallucination filtering to reject false detections.

**Tech:** PyTorch, OpenCV, scikit-learn, scipy, Vision Transformers

**Prisma Tech** — API Gateway & Backend Systems  
Founded company providing Baileys integration and backend infrastructure. Go/Python services with PostgreSQL/MongoDB. Security-focused design with enterprise automation capabilities.

---

### Current Stack

**Languages**: Python, Rust, C/C++, Go, C#, JavaScript  
**Security**: Kali, Metasploit, Burp, Wireshark, custom tooling  
**AI/ML**: PyTorch, Transformers, LangChain, OpenAI API, OpenCV, scikit-learn, scipy  
**Infrastructure**: Docker, PostgreSQL, MongoDB, Redis, Git  
**Research**: Binary exploitation, malware analysis, network protocols, computer vision

---

### Environment

```
AMD Ryzen 7 5700X
NVIDIA RTX 4070 12GB
32GB DDR4

Arch Linux / Windows 10 / Fedora
Kodachi, Ubuntu, Windows Server (VMs)
```

---

### Certifications & Training

- **OSCP** (In Progress)
- **TryHackMe** — [Active Profile](https://tryhackme.com/p/pv_)

---

### Contact

**LinkedIn**: [linkedin.com/in/yuee](https://www.linkedin.com/in/yuee/)  
**Location**: Rio de Janeiro, BR

Open to collaboration on: Red team tooling, offensive security research, AI automation, low-level systems development.

---

<sub>All security research conducted for educational purposes and authorized testing only. Projects follow responsible disclosure practices.</sub>
