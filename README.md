
# Decoding Emotions: EDA for Better Hiring

## Introduction

**This project evaluates the communication and emotional qualities of candidates through Exploratory Data Analysis (EDA)**. Using data from interview videos, we aim to extract actionable insights into emotional stability, communication effectiveness, and adaptability. The analysis helps identify key traits that are critical for recruitment decisions.

## Key Analyses and Findings

### Distribution of Emotions

- **Overall Distribution**: Neutral emotions dominate, covering nearly 50% of the spectrum, followed by fear, sadness, and happiness. Neutrality suggests **emotional control** and **calmness**, suitable for **high-pressure roles**(e.g. HFT roles,Data Analysis Roles etc..).
![Overall Emotion Distribution](images/bargraph.png)

- **Individual Distribution**: Candidates with varied emotions (e.g., fear, sadness, surprise) indicate **adaptability** and **creativity** but may require further evaluation for **leadership roles.** (e.g. Product Manager ,Director etc)
![Individual Emotion Distribution](images/Bar_graph_profile_diff_candids.png)


### Emotional Profiles of Candidates

![Spider Plot: Emotional Profiles](images/emotion_profile_1_&_2.png)

- Candidates exhibiting a high percentage of neutral emotions demonstrate emotional stability, crucial for **leadership or management roles**.
- Positive emotions like happiness suggest enthusiasm and a positive outlook, ideal for collaborative roles such as **sales or public relations**.

### Gaze and Blink Analysis
![Gaze and Blink Analysis](images/gaze_And_blink_data.png)


- **Gaze Stability**: Indicates focus and attentiveness. Candidates with steady gazes are better suited for detail-oriented roles.
- **Blink Frequency**: Excessive blinking may indicate stress, while too little suggests unnatural behavior. A moderate rate reflects calmness and engagement.

### Heatmaps and Correlation Matrices

![Emotion Correlation Heatmap](images/heatmap_emotiono_data.png)

- **Emotion Relationships**:
  - Positive correlations: Anger and disgust show a slight positive relationship.
  - Negative correlations: Neutral emotions negatively correlate with fear and anger, highlighting the ability to handle stress.

![Emotion Correlation Heatmap](images/correlation_plot.png)
- **Emotion and Communication Overlap**:
  - Confidence positively correlates with conciseness (0.72) and enthusiasm (0.62), indicating strong communication skills.

### Visualizations

Key visualizations include:
- Bar charts illustrating dominant emotion distributions.
- Spider plots highlighting individual emotional strengths and weaknesses.
- Heatmaps showing relationships between emotions and communication traits.


## Conclusion

From the emotional profiles analyzed, we found that candidates with dominant neutral emotions show **strong emotional stability** and **resilience**, making them suitable for high-pressure roles like leadership, business analysis, or data-driven jobs. Positive emotions, like **happiness** and **enthusiasm**, indicate adaptability and teamwork skills, which are ideal for creative and team-based roles like **marketing** or **public relations**.

Candidates with more varied emotions, such as **fear** or **sadness**, showed adaptability but might need further evaluation for roles requiring steady emotional control, like **leadership** or **client-facing positions**. There is also a clear link between **confidence**, **conciseness**, and **enthusiasm**, which highlights the importance of strong communication skills in **leadership** and **high-pressure environment**s.

**While emotions and transcripts alone don’t fully determine a candidate’s suitability, they provide useful insights into how well someone handles tough situations like an interview. This can help guide better decisions in matching candidates to the right roles.**

---

### Repository Structure
```plaintext
Emotion-Led-Candidate-Analysis/
├── README.md               # Overview and instructions
├── notebooks/
│   └── EDA.ipynb  # Jupyter Notebook
├── docs/
│   ├── EDA_Report.md       # Report in markdown
│   └── EDA_Report.pdf      # Original report in PDF
├── images/
│   └── visualizations.png  # Saved visualizations
│   └──Bar_graph_profile_diff_candids.png
│   └──bargraph.png
│   └──barplot.png
|    .....
```

## Contact

For questions or contributions, feel free to reach out!
