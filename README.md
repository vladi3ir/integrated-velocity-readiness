# Integrated Velocity Readiness (IVR) Score

*A first-principles metric for rapid, capital-efficient hardware scaling.*

---

## ✨ Overview

Traditional maturity metrics — **TRL** (Technology Readiness Level), **MRL** (Manufacturing Readiness Level), and **CRL/IRL** (Commercial/Investment Readiness Levels) — assess progress in silos.  
They fail to reward **speed**, **capital efficiency**, and **parallel maturity** across technology, production, and business.

**Integrated Velocity Readiness (IVR)** combines these into one actionable score:

$$
\mathrm{IVR\_Maturity} = \min(\mathrm{TC},\mathrm{PS},\mathrm{CV})
$$

- **TC** — *Technical Certainty*  
- **PS** — *Production Scalability*  
- **CV** — *Capital Viability*

We then add a **Velocity Factor**:

$$
V_f = \frac{\Delta \text{Maturity Levels}}{\text{Capital Expenditure}~(\$) \times \text{Time}~(\text{months})}
$$

And define the **final IVR Score**:

$$
\boxed{\mathrm{IVR} = \mathrm{IVR\_Maturity} \times (1 + V_f)}
$$

This forces teams to raise their **weakest link** while rewarding rapid, capital-efficient risk retirement.

---

## 📈 Why It Matters

- **Holistic:** Technology cannot scale faster than its least mature axis.  
- **Velocity-driven:** Encourages quick, high-impact experiments instead of slow burn.  
- **Investor-friendly:** Simple number communicates both *where you are* and *how fast you’re getting there*.  
- **Hardware-aware:** Explicitly integrates manufacturing and market readiness, not just prototypes.

---

## 🛠️ How to Use

1. **Score each axis (1–9):**

| Level | TC — Technical Certainty | PS — Production Scalability | CV — Capital Viability |
|-------|-------------------------|----------------------------|------------------------|
|1|Basic research, no proof of concept.|No production process.|Market unknown.|
|3|Analytical proof-of-concept.|Lab-only process.|Early customer validation.|
|5|Validated in relevant environment.|Low-rate production proven.|Early sales, viability shown.|
|7|System proven in operational setting.|Pilot line, early QMS.|Contracts & market route validated.|
|9|Full maturity & integration.|Full-rate stable production.|Business model scaled & efficient.|

2. **Compute static readiness:**

\[
\mathrm{IVR\_Maturity} = \min(TC, PS, CV)
\]

3. **Compute velocity factor:**

\[
V_f = \frac{\Delta \text{levels advanced}}{\$\,\text{spent} \times \text{months}}
\]

4. **Calculate final score:**

\[
\mathrm{IVR} = \mathrm{IVR\_Maturity} \times (1+V_f)
\]

5. **Interpret:**  
   - Low IVR\_Maturity → find the bottleneck axis.  
   - Low \(V_f\) → you’re advancing slowly or burning too much capital.

---

## 🚀 Example

> **Rocket Pump Alpha**  
> TC = 7, PS = 4 → improved to 5 after \$1.5M and 1 month, CV = 8  
>
> Static: \( \min(7,4,8) = 4 \)  
> Velocity: \( V_f = \frac{1}{1.5 \times 1} = 0.67 \)  
> Final: \( IVR = 4 \times (1 + 0.67) = 6.68 \)

---

## 🤝 Contribute

- **Feedback / case studies:** open an [issue](../../issues).  
- **Pull requests:** welcome for typos, clarifications, or tools (e.g. spreadsheets, calculators).

You **may not change the metric’s core definition without attribution** — please cite:

> *V. Stefanovski, Integrated Velocity Readiness Score (IVR), 2025.*

---

## 📜 License

Creative Commons **Attribution 4.0 International (CC BY 4.0)**  
You can share and adapt with proper credit.

---
