# THE-MATAB-
Speed bump energy harvester that converts the kinetic energy of slow-moving trucks into electricity using a rack-and-pinion gear train and a 12V generator. Reached 246.9 J per 5 min at 50.3% efficiency.

# ⚡ MATAP Electrical Generating Speed Breaker

A low-cost prototype that converts the wasted kinetic energy of slow-moving vehicles into clean electricity, using a rack-and-pinion and gear-train mechanism that drives a 12 V DC generator.

Built for the **Egyptian Grand Challenge: Improve the use of alternative energies**.
6th of October STEM School, Grade 10 (2025–2026), Semester 2.

| Phase 1 (baseline) | Phase 2 (with freewheel) | Improvement |
|:---:|:---:|:---:|
| 175.5 J / 5 min | **246.9 J / 5 min** | **+40.6 %** |
| 35.8 % efficiency | **50.3 % efficiency** | |

---

## 🎬 Demo Video

<!-- HOW TO ADD THE VIDEO:
Option A (best): while editing this README on github.com, drag and drop your .mp4 file here.
GitHub uploads it and inserts a link that plays directly in the page.
Option B: upload the video to YouTube and use:
[![Watch the demo](images/prototype-full.jpg)](https://youtube.com/your-link)
-->

> 📹 **Demo video goes here**

---

## 📌 Table of Contents
1. [The Problem](#-the-problem)
2. [Our Solution](#-our-solution)
3. [Design Requirements](#-design-requirements)
4. [Prior Solutions](#-prior-solutions)
5. [Materials](#-materials)
6. [Methods: How We Built It](#-methods-how-we-built-it)
7. [Safety Precautions](#-safety-precautions)
8. [Test Plan](#-test-plan)
9. [Results](#-results)
10. [Analysis](#-analysis)
11. [Conclusion](#-conclusion)
12. [Recommendations and Real-World Application](#-recommendations-and-real-world-application)
13. [References](#-references)
14. [Team and Acknowledgements](#-team-and-acknowledgements)

---

## 🚨 The Problem

- Egypt gets about **89 % of its energy from fossil fuels** (92 % in 2021). Burning them is a major source of CO₂ and air pollution.
- A large source of energy is wasted every day: the **kinetic energy of vehicles** that brake and slow down.
- At **Alexandria Port**, about **2,880 trucks per day**, each weighing up to **60 tons**, brake at the main gates. All of that kinetic energy is lost as heat.
- If nothing changes, the port keeps depending on dirty energy and on the electrical grid.

## 💡 Our Solution

The **MATAP Speed Bump Power Generator** sits in the road like a normal speed bump:

1. A truck pushes the top layer of the bump **down by 10 cm**.
2. A **rack-and-pinion** turns this linear motion into rotation.
3. A **compound gear train** with chain drives speeds up the rotation.
4. The rotation spins a **12 V, 300 RPM DC generator**.
5. **Springs** push the bump back up, ready for the next vehicle.

Key design choices:
- **Closed shell:** all components are enclosed to avoid the rust problem seen in PAWEC.
- **Ball bearings** reduce friction on every rotating axis.
- **Phase 2 upgrade:** a **freewheel (one-way clutch) and bicycle chain** let the generator keep spinning forward without being dragged backwards when the bump returns up. This is a low-cost change that raised the output by more than 10 %.
- **Recycled parts:** most materials came from broken or old items.

![3D design of the gear train](images/design-3d-gear-train.jpg)
*3D design of the gear train*

## 🔍 Prior Solutions

| Solution | Strength | Weakness |
|---|---|---|
| **Pavegen Systems** (footstep tiles) | Eco-friendly | Produces relatively little power |
| **PAWEC** (Point Absorber Wave Energy Converter, rack-and-pinion) | Produces large amounts of energy | Tends to rust |

Our design takes the rack-and-pinion idea from PAWEC and fixes its rust weakness with an enclosed housing.

---

## 🧰 Materials

| Item | Image | Description | Usage | Cost | Source | Qty |
|---|:---:|---|---|:---:|---|:---:|
| Wood | <img width="263" height="152" alt="image" src="https://github.com/user-attachments/assets/429be9c2-1186-4ff2-a6ff-6960b508072f" /> | Board, 20 in wide and 58 in long | Prototype frame and structural support | 0 | Broken desks | 6 boards |
| Gears | <img src="images/mat-gears.jpg" width="140"> | Metal gears, radius 8.5 cm | Power transmission and adjusting ratios | 495 | Old motorcycle | 6 gears |
| Iron chain | <img src="images/mat-chain.jpg" width="140"> | Chain of 26 joints | Connecting gears for rotational transfer | 75 | Broken motorcycle | 3 chains |
| Freewheel | <img src="images/mat-freewheel.jpg" width="140"> | One-way clutch mechanism | Lets the axle spin freely in one direction | 90 | Broken bicycle | 1 |
| Axes | <img src="images/mat-axes.jpg" width="140"> | Steel rod, 20 cm | Hang the gears and the freewheel | 90 | Broken printer | 3 axes |
| Ball bearings | <img src="images/mat-bearings.jpg" width="140"> | 10 mm inner / 22 mm outer diameter | Reduce friction on the rotating axes | 75 | Old rollerblades | 6 bearings |
| Nails | <img src="images/mat-nails.jpg" width="140"> | 6 cm long | Connecting wooden frame parts | 15 | Old wooden furniture | 10 nails |
| Iron nuts | <img src="images/mat-nuts.jpg" width="140"> | 10 mm diameter | Reinforcing parts on threaded axes | 20 | Old wooden furniture | 12 nuts |
| Epoxy | <img src="images/mat-epoxy.jpg" width="140"> | Two-part adhesive resin and hardener | Permanent bonding of metal or wood parts | 60 | Downtown Cairo | 2 tubes |

Other components: a 12 V, 300 RPM DC generator and 4 high-tension springs.

## 🔨 Methods: How We Built It

**1. Frame.** Wooden panels formed the walls and base. The side panels were nailed to the base so the frame can resist the forces from the mechanical parts.

<p align="center"><img src="images/build-1-frame.jpg" width="260"></p>

**2. Bearings.** Six holes (2.5 cm radius) were drilled in opposite walls with a high-torque drill. Ball bearings were fitted into them to limit friction.

<p align="center"><img src="images/build-2-bearings.jpg" width="260"></p>

**3. Gears and axes.** The gears were fixed firmly onto the steel axes so they stay at a set rotational position.

<p align="center"><img src="images/build-3-gears-axes.jpg" width="260"></p>

**4. Mounting the axes.** The axle and gear assemblies were placed in the ball bearings for smooth, centered rotation.

<p align="center"><img src="images/build-4-axes-mounted.jpg" width="260"></p>

**5. Rack-and-pinion and generator.** A rack was attached to a sliding wooden frame that moves vertically. It is coupled to the freewheel, which drives the final gear through a chain. The final gear is connected to the generator by another chain.

<p align="center"><img src="images/build-5-generator.jpg" width="260"></p>

**6. Return springs.** High-tension springs were wrapped around pens to give predictable spring strength. They pull the moving part back up after the pressure is released, and the lid is fixed on top of them.

<p align="center"><img src="images/build-6-springs.jpg" width="260"></p>

### Final prototype

<p align="center"><img src="images/prototype-full.jpg" width="420"></p>

## 🦺 Safety Precautions

- Work was done under the school Fab Lab safety rules.
- No toxic, explosive or flammable materials were used.
- Extra care was taken around the **pinch points** of the chain-driven gear train, the rack-and-pinion and the spring-loaded shafts.
- The wooden base was built strong enough to handle the downward force during testing.

## 🧪 Test Plan

| Parameter | Value |
|---|---|
| Load | 10 kg mass |
| Stroke | 10 cm compression, then returned by 4 springs |
| Rate | 1 downstroke every 6 seconds (about 50 strokes) |
| Duration | 5 minutes (300 s) |
| Load resistor | 100 Ω across the 12 V generator |
| Measurement | Digital multimeter (peak DC voltage per stroke) |

- **Phase 1:** baseline, with no freewheel.
- **Phase 2:** the freewheel is added so no energy is lost driving the transmission backwards on the upstroke. The same procedure is repeated.

---

## 📊 Results

### Negative result
During assembly, the four 20 cm shafts were not evenly spaced. This jammed the chain-driven transmission and stopped the 15T and 42T gears from rotating freely. We re-measured the spacing and made all shafts parallel before running the electrical tests.

### Phase 1: without freewheel
![Phase 1 voltage](images/results-phase1.png)

### Phase 2: with freewheel
![Phase 2 voltage](images/results-phase2.jpg)

| Metric | Phase 1 | Phase 2 |
|---|:---:|:---:|
| Average peak voltage | 7.65 V | 9.07 V |
| Average current | 0.0765 A | 0.091 A |
| Average power | 0.585 W | 0.823 W |
| Energy per stroke | 3.51 J | 4.938 J |
| **Total energy (5 min)** | **175.5 J** | **246.9 J** |
| **Efficiency** | **35.78 %** | **50.34 %** |

Both phases exceed the **150 J** target.

## 🧮 Analysis

**1. Mechanical work input.** Work per stroke: `E_in = ∫ F(x) dx = m·g·d = 10 × 9.81 × 0.1 ≈ 9.81 J`.
Over 50 strokes in 300 s: `ΣE_in = 9.81 × 50 = 490.5 J`.

**2. Electrical energy output.** Computed from the recorded voltage on the 100 Ω load: `E_out = Σ (Vᵢ² / R) · Δt`.

**3. Efficiency.** `η = E_out / ΣE_in × 100`
- Phase 1: 175.5 / 490.5 = **35.8 %**
- Phase 2: 246.9 / 490.5 = **50.3 %**

**4. Improvement between phases.** `(η₂ − η₁) / η₁ = (50.3 − 35.8) / 35.8 ≈` **40.6 %**

In Phase 1, the upward movement of the spring-loaded shafts forced the chain transmission to run backwards at high speed, causing large friction losses. The freewheel lets the generator keep spinning freely on every upstroke, so that loss is removed.

## ✅ Conclusion

- The rack-and-pinion and compound gear train successfully turned a 10 cm linear input into the fast rotation needed by the 12 V generator.
- The prototype produced **246.9 J in 5 minutes**, above the 150 J requirement.
- The freewheel upgrade raised efficiency from **35.8 % to 50.3 %**, well above the 10 % improvement target.
- The design is mechanically reliable, cheap (built from recycled parts) and scalable as a new source of alternative energy in urban areas.

## 🚛 Recommendations and Real-World Application

**Recommended location: Alexandria Port.**
- It is one of Egypt's most important ports, handling about 10 million tons of cargo per year.
- About 120 trucks per hour pass through main entrances such as Gates 27 and 54, each weighing about 60 tons.
- The full-scale bump would be mainly steel to carry these loads.
- The energy source is wasted mechanical energy, so it does not harm the environment. The project has not been applied before in Egypt.

**Future improvements:**
- **Neodymium-Iron-Boron magnets instead of steel springs.** There is no mechanical wear because the parts never touch, and they act as shock absorbers. They were not used because they are costly and hard to find at large sizes.
- **A flywheel.** It keeps rotating after each press and could increase output by about 10 %. It was not used in the prototype because in a crowded street, a second vehicle could press the bump while the flywheel turns the opposite way, which could damage the mechanism.

## 📚 References

- Aman, A., Kumar, S., & Singh, R. (2018). Design and fabrication of speed breaker power generator using rack and pinion mechanism. *International Journal of Advance Research and Innovation, 6*(1), 48–51.
- Koli, P., Jadhav, A., & Patil, S. (2018). Power generation from speed breaker by using rack and pinion mechanism. *International Journal of Advanced Research in Mechanical Engineering, 6*(2), 24–29.
- Makumi, N., Numbi, E., & Nkurunziza, J. (2018). Design and implementation of a speed breaker energy harvesting system using rack and pinion mechanism. *International Journal of Engineering Research & Technology, 7*(5), 112–118.
- Rokonuzzaman, M., & Hossam-E-Haider, M. (2015). Design and implementation of speed breaker geared generator. *2015 ICEEICT*, 1–5.
- Zebda, M., Saidi, A., & El-Babili, A. (2017). Energy harvesting from vehicle speed bumps: Mathematical modeling and experimental validation. *Journal of Renewable and Sustainable Energy, 9*(4), 044701.

## 👥 Team and Acknowledgements

**Team:** Yassin Esmat · Abdulrahman Ahmed · Sayed Mostafa · Yasin Ahmad Taha

**Thanks to** our Capstone Manager Mr. Bakheet, Capstone Leader Ms. Dalia, Capstone Teacher Mr. Mostafa, and Dr. Shadi Nabil and Dr. Mahmoud Abd Elraazek for their guidance and support.
