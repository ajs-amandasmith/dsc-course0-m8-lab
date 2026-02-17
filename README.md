# Aviation Accident Analysis

## Summary of Aircraft Safety Analysis

### Small Aircraft (<20 passengers)

**Findings:**
- The top 15 makes with the lowest Fatal_or_Serious_Rate and lowest Total_Destruction were identified.
- Violin plots show that the safest small aircraft makes have consistently low injury fractions, with relatively narrow distributions, indicating consistent safety across multiple accidents.
- The Total_Destruction Rate for these makes is also low, meaning these aircraft are more robust in the event of an accident.
- Some outliers exist, but overall the combination of low fatal/serious injury fraction and low destruction fraction highlights clear leaders in safety performance.

**Recommendations:**
- Consider aircraft makes such as Luscombe, Grumman Acft Eng Cor-Schweizer, Stinson, and Airbus for operations prioritizing both passenger safety and aircraft robustness.
- These small aircraft consistently show both fewer severe injuries and lower likelihood of total destruction.

---

### Large Aircraft (≥20 passengers)

**Findings:**
- The top 15 makes with the lowest Fatal_or_Serious_Rate and lowest Total_Destruction were identified.
- Strip plots indicate that while large aircraft generally have lower passenger injury fractions due to size and design, some makes exhibit wider variability, highlighting occasional severe events.
- The Total_Destruction Rate is generally low among these large aircraft makes, indicating strong structural integrity.
- The combination of low injury fraction and low destruction rate identifies the most reliable makes for larger passenger operations.

**Recommendations:**
- Large aircraft makes such as Cessna, Grumman, Piper, and Raytheon Aircraft Company are preferred for airline operations where passenger safety and aircraft durability are critical.
- Safety performance should be considered in tandem with operational requirements and passenger capacity.

---

### General Observations

- Both injury fractions and destruction fractions are complementary metrics: a make that performs well on both is clearly safer overall.
- Visualizations (violin and strip plots) provide insights into the distribution and variability of safety outcomes, not just the mean values.
- These analyses can inform fleet acquisition decisions, insurance risk assessments, and maintenance prioritization.

## Discussion of Safety by Specific Airplane Types

### Small Aircraft (<20 passengers)

- After filtering to the 10 Safest Plane Types (Make + Model) with at least 10 accidents each, the mean fatal/serious injury fractions are consistently low.
- Violin plots show that these plane types not only have low average injury fractions, but also relatively narrow distributions, indicating that safety outcomes are consistently good across multiple accidents.
- Outliers are minimal, suggesting that these specific models rarely experience catastrophic events.
- This analysis highlights that within safe makes, certain models stand out as particularly reliable in protecting passengers.

---

### Large Aircraft (≥20 passengers)

- For large aircraft, plane types generally exhibit lower mean fatal/serious injury fractions compared to small planes, likely due to larger structural design and safety features.
- Stripplots reveal more variability among large aircraft models, with some rare accidents resulting in higher fractions of serious/fatal injuries, even among generally safe models.
- The combination of low mean injury fraction and robust distributions identifies the safest large plane types for passenger operations.

**Implications:**  
- While overall safety is high, the visualized variability emphasizes the need for continued monitoring and maintenance to mitigate rare severe events.

---

### General Observations

- Evaluating Plane Types rather than just makes provides a more granular view of safety performance.
- Models with both low mean fatal/serious injury fractions and narrow distributions are the most reliable choices.
- This level of analysis complements destruction-rate metrics and provides actionable guidance for fleet selection and risk management.

### Effect of Weather Condition on Safety

- Mean fatal/serious injury fraction was computed for each weather condition.
- Visualizations indicate that IMC generally correspond to higher injury fractions compared to VMC.
- Most accidents occur under VMC, but serious/fatal injuries are proportionally higher under poor weather conditions.
- This highlights the importance of pilot training,instrumentation, and operational procedures under adverse weather to reduce risk.

### Effect of Number of Engines on Passenger Safety

- Aircraft were grouped by the number of engines (excluding invalid 0 values).
- Analysis shows that single-engine aircraft tend to have higher fatal/serious injury fractions compared to twin-engine and multi-engine aircraft.
- Multi-engine aircraft generally show lower injury fractions, indicating increased redundancy and reliability in case of engine failure or other incidents.
- This aligns with expectations in aviation: more engines provide better performance, especially in critical situations.
- Distributions (via violinplots) highlight that while the mean injury fraction decreases with more engines, variability still exists among individual accidents.