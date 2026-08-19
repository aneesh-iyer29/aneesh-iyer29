# Resume Content Bank

Master reference of all resume content, current as of **August 2026**. Every bullet here is true and verified — use this to assemble tailored resumes without digging through git history. When a role or accomplishment changes, update it here first, then propagate to the `.tex` variants.

## Resume variants in this repo

| File | Purpose | Notes |
|---|---|---|
| `main.tex` | General resume | Experience before Projects; trailing periods on bullets |
| `startup.tex` | Startup applications | Projects before Experience (leads with hackathon win); no trailing periods |
| `nvidia.tex` | NVIDIA SWE internship | "Expected Graduation" label (required by JD); skills ordered for JD keywords (Python/C/Java, Linux/Git/Docker, NeMo Gym first); validation/benchmarking bullets prioritized |

## Contact / Header

- Aneesh Iyer
- (513) 399-1607
- aiyer@gatech.edu
- linkedin.com/in/aneesh-iyer
- github.com/aneesh-iyer29
- aneesh-iyer.com

## Education

**Georgia Institute of Technology** — Atlanta, GA
B.S. in Computer Engineering — Cybersecurity & Systems/Architecture — GPA: 4.0
Expected graduation: **May 2028** (some JDs, e.g. NVIDIA, require the month/year explicitly labeled)

- Relevant Coursework: Data Structures & Algorithms, Hardware/Software Systems Programming
- In Progress: Computer Architecture, Cryptographic Hardware for Embedded Systems

## Experience

### Transpira Labs (Backed by Christopher Klaus) — Software Engineer

Atlanta, GA · May 2026 – Aug. 2026 (role has ended; do not use "Present")

Bullet pool (all true; pick per audience):

- Maximized output of 40+ SMEs producing frontier AI training data by building a task authoring platform. *(current headline bullet everywhere)*
- Landed 5 pilot partners by building a custom GTM platform for outreach, lead generation, and analytics. *(business/startup audiences; dropped from nvidia.tex)*
- Built a sandbox replicating a 3PL's full operational stack, enabling end-to-end testing before deployment. *(testing/validation angle)*
- Packaged 288 supply-chain benchmark tasks into a reproducible validation suite with deterministic rewards. *(MLOps/validation audiences; alt phrasing: "reproducible environment with deterministic rewards")*
- Created a benchmark for LLM agents on their ability to RL-train agents, revealing under 1% lift from instruction. *(research/eval audiences)*
- Developed full-stack services for a platform to support 40+ expert contractors building frontier AI training data. *(older phrasing of the platform bullet; superseded by "Maximized output of 40+ SMEs...")*

### Nuntius (YC S'25) — Software Engineer

Remote · Sep. 2025 – Apr. 2026

Bullet pool:

- Delivered a $50K client project evaluating LLM agent tool-use limitations, directing a team of 8 engineers. *(alt phrasing: "Directed a team of 8 engineers to deliver a $50K client project...")*
- Produced 300+ adversarial tasks across 5+ RL environments with automated graders and custom rewards. *(alt phrasing: "Built 5+ RL environments with automated graders and custom rewards; created 300+ adversarial tasks")*
- Designed trajectory-aware validation frameworks crediting intermediate steps to debug agent failure modes. *(MLOps/validation audiences; alt phrasings: "Designed trajectory-aware evaluators assigning partial credit based on intermediate steps instead of binary results", "Moved evals beyond binary pass/fail by designing trajectory-aware evaluators that credit intermediate steps")*

### GT Propulsive Landers — Vice Lead, Guidance, Navigation, and Controls Subteam

Atlanta, GA · Jan. 2026 – Present
Repo: github.com/Avionics-Propulsion-Landers-GT/MonopropUAV
Former title (pre-promotion): "Guidance, Navigation, and Control Team Member | Python, Rust"

Bullet pool:

- Achieved 0.63% average estimated deviation from ground truth via 3 distinct EKFs fusing IMU, GPS, and LIDAR. *(alt split into two: "Engineered sensor fusion pipelines with 3 distinct EKFs spanning IMU, GPS, and LIDAR to filter noisy inputs" + "Achieved a 0.63% average deviation from simulated ground-truth, demonstrating robust estimation accuracy")*
- Automated PID tuning for a 1.8 kN engine simulation via 8 step-response metrics logged to CSV each run.

## Projects

### Build: Scratch for RL Environments — Python, TypeScript, HUD

Jun. 2026 · Live: build.transpiralabs.com

- Won 1st of 70 ($50K+ in prizes/credits) at the HUD × Y Combinator Frontier/RSI RL Environments Hackathon.
- Developed an open-source Scratch-style platform compiling plain-language block trees into RL environments. *(alt phrasings: "Developed open-source tooling: a Scratch-style platform compiling block trees into RL training environments", "Enabled no-code RL: an open-source Scratch-style platform compiling block trees into RL environments")*
- Enabled anyone to evaluate models in custom simulations and launch RL training runs without writing any code.

### MathWorks Math Modeling (M3) Champion — Python, R

Mar. 2025 – May 2025 · Publication: doi.org/10.1137/25S1777554

- Modeled Memphis heat resilience and electricity demand, winning 1st of 794 teams ($20,000 grand prize).
- Quantified vulnerability across 27 zip codes by reducing variables to 4 significant features via backward selection.
- Presented findings to Ph.D. professors and co-authored a publication in SIAM Undergraduate Research Online.

## Volunteering

### Science Olympiad National Team — TypeScript, Web Development

Aug. 2025 – Present

- Open-source maintainer (github.com/toebes/ciphers) for the Codebusters platform (toebes.com/codebusters/) used by 1,000+ coaches/volunteers nationwide.
- Volunteered and supported exam administration for 2,000+ students at state and national level tournaments.
- Member of the GT Alumni Chapter, organizing exam logistics for 40 teams at the GA State Tournament.

### ScioVirtual Foundation Volunteer — HTML, CSS, JS

Summers 2024 – 2026

- Volunteered 100+ hours teaching STEM courses to kids aged 11-14 for the ScioVirtual NonProfit Foundation.
- Created a cryptography training platform for 70+ students with feedback and automated solution verification.
- Achieved the highest-rated course by students among 20+ offerings and was named 2025 Instructor of the Year.

## Technical Skills (full pool — reorder per JD)

- **Languages**: Python, Java, Rust, C, TypeScript/JavaScript, SQL, R, MATLAB, HTML/CSS, Bash, LaTeX
- **AI/ML**: RLVR/GRPO, RL Environment Creation, LLM Evaluation & Benchmarking, HUD SDK, NVIDIA NeMo Gym, NumPy
- **Tools & Systems**: Linux, Docker, Git, Pydantic, Arduino, RISC-V, Control Systems, Sensor Fusion, Embedded Systems
- **Interests**: Machine Learning, Cryptography, Cybersecurity, Aerospace Systems, Optics, GPU & Accelerated Computing, Spanish (Intermediate)

## Tailoring notes

- Keep every variant to **one page** — compile and check before committing.
- Lead skills lines with the JD's named keywords; put the most JD-relevant category first.
- Do **not** add skills/keywords not backed by the pool above (e.g., C++/CUDA/Go/Kubernetes are not currently claimable).
- Big-company/ATS: Experience before Projects, trailing periods. Startups: Projects (hackathon win) first.
