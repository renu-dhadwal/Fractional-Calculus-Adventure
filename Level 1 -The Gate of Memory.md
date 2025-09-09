# 🎮 Level 1 – The Gate of Memory

**Characters**:  
- Dr. Fractiona (Guide)  
- Alex (Learner)  

---

**Scene**: Alex stands before a large gate carved with spirals and fading patterns. Above it, the words *“Past and Present Are One.”*

**Dialogue**  
Alex: This place feels mysterious… What lies beyond this gate?  
Dr. Fractiona: This is the Gate of Memory. To enter, you must first understand the idea of a *fractional integral*.  

---

## 🌟 Definition
\[
(I^\alpha f)(t) = \frac{1}{\Gamma(\alpha)} \int_0^t (t-\tau)^{\alpha-1} f(\tau)\, d\tau, \quad \alpha > 0.
\]

This operator remembers the past, but with fading memory: recent values of \(f\) matter more than distant ones.

---

## 🧩 Mini-Quest 1
Evaluate \( (I^{1/2} 1)(t) \).

- Choice A: Proportional to \(t^{1/2}\)  
- Choice B: Proportional to \(t\)  
- Choice C: Constant  

**Solution**:  
\[
(I^{1/2} 1)(t) = \frac{1}{\sqrt{\pi}} \int_0^t (t-\tau)^{-1/2} d\tau = \frac{2}{\sqrt{\pi}} t^{1/2}.
\]  
Correct Answer: **A**

---

## 📊 Visual
See `/figures/memory_kernel_alphaXX.png` for plots of kernel decay for \(\alpha = 0.2, 0.5, 0.9\).

---

## 🧩 Mini-Quest 2
Which \(\alpha\) remembers the distant past most strongly?

- Choice A: \(\alpha = 0.2\)  
- Choice B: \(\alpha = 0.5\)  
- Choice C: \(\alpha = 0.9\)

**Answer**: A, because the kernel decays more slowly.

---

🏆 **Reward**: You have earned the **Key of Memory**.
