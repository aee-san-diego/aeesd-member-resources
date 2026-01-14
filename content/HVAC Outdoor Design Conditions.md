> [!summary]
> To perform HVAC load calculations in compliance with Title 24, generally, you should:
> - Use a calculation methodology from the ASHRAE Fundamentals Handbook (Heat Balance (HB method or Radiant Time Series (RTS) method). These are "the most current and scientifically derived means for estimating cooling load for a defined building space".
> 	- The HB method is suited to iterative software calculations
> 	- The RTS method is a simplified version of the HB method and can be performed with a spreadsheet
> - Use 68F and 75F for indoor design conditions
> - Use outdoor design conditions no more extreme than the 1st percentile for cooling (commercial buildings can use 0.5%) and 99th percentile for heating (in the Joint Appendix the 99th percent is not published and, so, you would need to use the Heating Winter Median of Extremes)
> - In certain scenarios, there are other approaches - particularly for healthcare facilities. See Title 24 requirements for [[HVAC Load Calculations]] and read the code directly for exact information.

Example:

![[JA_Design_Conditions.jpeg]]

From this example, the design conditions for a commercial building in the City of San Diego would be 83F for cooling (the 0.5% value is allowable) and 38F for heating.

---

As recently at 2025, the [[Title 24]] Reference Appendices provide [[HVAC Outdoor Design Conditions|design data]] for California which is based on:

```
"ASHRAE Climatic Data for Region X, Arizona, California, Hawaii and Nevada," Publication SPCDX, 1982 and “Supplement,” 1994
```

This is interesting because the data is, at minimum, over 30 years old and at this point, in relation to [[Climate Change]], its validity is debatable. 

See: [[Suggestions for Improving Title 24]]

---
# See Also
- [[Title 24]]
- [[San Diego Weather Data]]
- [[HVAC Load Calculations]]