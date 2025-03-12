# Whitepaper: Feasibility Study of VASIMR Technology for Interplanetary Cargo Transport

## Abstract
The Variable Specific Impulse Magnetoplasma Rocket (VASIMR) offers high efficiency and adaptability for deep-space missions, thanks to its ability to vary specific impulse and thrust. This study evaluates the practicality of using VASIMR technology to transport a 100-ton (100,000 kg) payload and achieve a delta-v of 10 km/s. Two configurations are analyzed: the existing 5.7 N VASIMR VX-200 engine and a scaled-up 1,000 N system. The analysis reveals substantial challenges regarding power requirements, propellant demands, and mission durations, limiting VASIMR's feasibility for such missions under current technological constraints.

## 1. Introduction

### 1.1 Background
The VASIMR engine, developed by Ad Astra Rocket Company, represents a significant advancement in electric propulsion. Utilizing radio frequency energy to ionize and accelerate plasma, it achieves high specific impulse (ISP) while maintaining the flexibility to vary thrust and efficiency. This makes it an attractive option for interplanetary missions, where fuel efficiency is paramount.

### 1.2 Objectives
This whitepaper explores the practicality of employing VASIMR for heavy payload missions by analyzing:
1. Time required to achieve a delta-v of 10 km/s.
2. Propellant mass required for the mission.
3. Feasibility of scaling VASIMR engines to higher thrust levels.

## 2. Analysis

### 2.1 System 1: VASIMR VX-200 (5.7 N)

#### Parameters
- **Thrust (F)**: 5.7 N  
- **Specific Impulse (ISP)**: 5,000 s  
- **Exhaust Velocity (\(v_e\))**: 49,050 m/s  
- **Payload**: 100,000 kg  
- **Dry Mass**: 50,000 kg  
- **Final Mass (\(m_f\))**: \(m_{\text{payload}} + m_{\text{dry}} = 150,000 \, \text{kg}\)  

#### Propellant Mass Calculation
Using the Tsiolkovsky Rocket Equation:


\[
m_i = m_f \cdot e^{\Delta v / v_e},
\]


Substituting values:


\[
m_i = 150,000 \cdot e^{10,000 / 49,050} \approx 150,000 \cdot 1.226 \approx 183,900 \, \text{kg}.
\]




\[
m_{\text{propellant}} = m_i - m_f = 183,900 - 150,000 = 33,900 \, \text{kg}.
\]



#### Mission Duration Calculation
Average mass:


\[
m_{avg} = \frac{m_i + m_f}{2} = \frac{183,900 + 150,000}{2} = 166,950 \, \text{kg}.
\]


Acceleration:


\[
a = \frac{F}{m_{avg}} = \frac{5.7}{166,950} \approx 3.41 \times 10^{-5} \, \text{m/s}^2.
\]


Time to achieve \( \Delta v = 10,000 \, \text{m/s} \):


\[
t = \frac{\Delta v}{a} = \frac{10,000}{3.41 \times 10^{-5}} \approx 293,256,000 \, \text{s}.
\]


Convert to days:


\[
t \approx \frac{293,256,000}{86,400} \approx 3,395 \, \text{days} \, (\sim 9.3 \, \text{years}).
\]



### 2.2 System 2: Scaled VASIMR (1,000 N)

#### Parameters
- **Thrust (F)**: 1,000 N  
- **Specific Impulse (ISP)**: 5,000 s  
- **Exhaust Velocity (\(v_e\))**: 49,050 m/s  
- **Payload**: 100,000 kg  
- **Dry Mass**: 8,619,550 kg  
- **Final Mass (\(m_f\))**: \(m_{\text{payload}} + m_{\text{dry}} = 8,719,550 \, \text{kg}\)  

#### Propellant Mass Calculation
Using the Tsiolkovsky Rocket Equation:


\[
m_i = m_f \cdot e^{\Delta v / v_e},
\]


Substituting values:


\[
m_i = 8,719,550 \cdot e^{10,000 / 49,050} \approx 8,719,550 \cdot 1.226 \approx 10,687,797 \, \text{kg}.
\]




\[
m_{\text{propellant}} = m_i - m_f = 10,687,797 - 8,719,550 = 1,968,247 \, \text{kg}.
\]



#### Mission Duration Calculation
Average mass:


\[
m_{avg} = \frac{m_i + m_f}{2} = \frac{10,687,797 + 8,719,550}{2} = 9,703,674 \, \text{kg}.
\]


Acceleration:


\[
a = \frac{F}{m_{avg}} = \frac{1,000}{9,703,674} \approx 0.000103 \, \text{m/s}^2.
\]


Time to achieve \( \Delta v = 10,000 \, \text{m/s} \):


\[
t = \frac{\Delta v}{a} = \frac{10,000}{0.000103} \approx 97,087,379 \, \text{s}.
\]


Convert to days:


\[
t \approx \frac{97,087,379}{86,400} \approx 1,124 \, \text{days} \, (\sim 3.1 \, \text{years}).
\]



## 3. Comparison of Systems

| **Metric**              | **VASIMR VX-200 (5.7 N)** | **Scaled VASIMR (1 kN)** |
|--------------------------|---------------------------|--------------------------|
| Thrust                  | 5.7 N                    | 1,000 N                 |
| Propellant Mass         | 33,900 kg                | 1,968,247 kg            |
| Total Initial Mass      | 183,900 kg               | 10,687,797 kg           |
| Time to Δv (10 km/s)    | ~3,395 days (~9.3 years) | ~1,124 days (~3.1 years)|

## 4. Key Insights
1. **Propellant Efficiency**: The VASIMR systems excel at minimizing propellant mass relative to delta-v, but scaling comes at a significant cost to system complexity and power requirements.
2. **Time-Limiting Factor**: The low thrust-to-mass ratio results in long mission durations, especially for the 5.7 N system.
3. **Reactor Scalability**: The scaled VASIMR system introduces prohibitive dry mass due to the need for a 35 MW power source and associated shielding.

## 5. Conclusion
While VASIMR technology demonstrates impressive efficiency, its practical application for heavy payload interplanetary missions is hindered by extended mission durations (especially in low-thrust configurations) and the immense power demands of scaled systems. Significant advancements in lightweight reactor technologies, structural optimization, and mission planning are necessary to unlock its potential.

# Background
- [Table of motor technologies and their fuel/energy use](./table.mht)
- [excel file](./table.xlsx)
- 
