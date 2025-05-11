This project focuses on the design, analysis, and implementation of a Braun Array Multiplier using various optimized Full Adder architectures. All designs were developed and simulated using Cadence Virtuoso with the GPDK 180nm CMOS process.

📌 Project Overview

🧮 Full Adder Exploration
Implemented six different Full Adder architectures, each using different logic styles (e.g., static CMOS, transmission gate, etc.).

Evaluated each design based on:

Propagation delay

Power consumption



🔍 Transistor Sizing Analysis

Measured pre- and post-sizing performance to understand the impact of transistor width on speed and power.

Demonstrated how optimized PMOS/NMOS sizing can significantly reduce delay and energy.

🧰 Braun Array Multiplier Design

Selected the best-performing Full Adder based on worst-case delay after sizing.

Used it to build a Braun Array Multiplier, evaluated for performance and correctness.

Simulations verified in Cadence ADE with waveform and measurement data.

✨ Key Takeaways

⚙️ Transistor sizing plays a critical role in optimizing digital circuits and must be carefully tuned.

🔗 Full Adder choice affects not only the individual cell but also the scalability and efficiency of higher-level arithmetic blocks.

🧮 Logic style trade-offs must be balanced for area, power, and delay — no single design is optimal for all scenarios.

🔍 Early design decisions (logic family, sizing, adder type) have a compound effect on system-level performance.

🛠 Tools & Technologies

Cadence Virtuoso 

GPDK 180nm Process Design Kit

Waveform & Parametric Analysis

Custom Delay & Power Measurement Setups
