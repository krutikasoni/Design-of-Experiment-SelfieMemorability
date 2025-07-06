# 🧪 Design of Experiment (DOE): Factors Impacting Selfie Memorability

This project applies a 2² full factorial Design of Experiment (DOE) to analyze how **lighting** and **background clutter** influence the **memorability of selfies**. Conducted as part of a behavioral statistics course, the study provides insights into visual factors that enhance recall in digital images.


## 🎯 Objective
Leverage DOE methodology to:
- Quantify the effects of lighting and background on image memorability
- Identify the most effective selfie conditions using ANOVA and interaction analysis
- Understand factor relationships using predictive modeling


## 🔬 Experimental Design

- **Design**: 2x2 full factorial (2 factors, 2 levels each)
  - **Factor A (Lighting)**: Indoor (–1) vs. Outdoor (+1)
  - **Factor B (Background)**: Cluttered (–1) vs. Plain (+1)

- **Treatments**:
  1. Indoor + Cluttered
  2. Indoor + Plain
  3. Outdoor + Cluttered
  4. Outdoor + Plain

- **Response Variable**: Memorability score (scale of 1–10), rated by independent judges


## 📈 Key Results

| Factor                | Effect  |
|------------------------|---------|
| Lighting (A)           | +1.75   |
| Background (B)         | Insignificant |
| Interaction (A*B)      | +1.5    |
| Best Combination       | Outdoor + Plain (score = 10) |

- Predictive Equation:  
  `Y = 7.25 + 0.875A + 0.75(A*B)`

- Lighting had the strongest main effect on recall
- Interaction was statistically significant; background alone was not


## 🛠 Tools & Techniques
- DOE methodology (2² factorial design)
- ANOVA for main and interaction effects
- Python for statistical analysis & visualization
- Manual data collection and memorability scoring


## 💡 Insights & Recommendations
- Use **outdoor lighting** for improved image memorability
- Keep **backgrounds minimal**, especially when paired with good lighting
- Consider interaction effects — combined factors impact recall more than isolated ones


## 🔄 Future Improvements
- Add more factors (filters, camera angles, facial expressions)
- Use a larger, more diverse rater pool
- Include time-based recall tests for deeper insight


## ✅ Outcome
Demonstrated how a structured DOE framework can uncover critical insights into visual content design and user perception, with practical implications for digital marketing, photography, and UI/UX image testing.
