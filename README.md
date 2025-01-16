# Premium Relativity Calculation for Motor Vehicle Insurance  

## Objective  
Accurately calculating premiums is vital for maintaining financial stability in the insurance industry while providing competitive pricing to policyholders. Underpricing can lead to financial losses, whereas overpricing may drive customers to competitors.  

This project focuses on developing a reliable method to compute premium relativities based on various rating factors. The goal is to enable insurance companies to establish fair and optimal pricing strategies.  

---

## Data  
The analysis uses a dataset containing key rating factors relevant to determining motor vehicle insurance premiums:  
- **Age**  
- **Gender**  
- **Geographic zone**  
- **Vehicle age**  
- **Number of policy years**  
- **Number of claims**  
- **Claim cost (severity)**  

---

## Methods  
1. **Statistical Analysis**  
   - Conducted statistical tests to assess model fit and determine the significance of rating factors in predicting claim frequency and severity. The analysis was performed with a 95% confidence level.  

2. **Premium Calculation**  
   - Premiums were calculated by multiplying claim frequency and expected claim severity.  

3. **Claim Frequency Modeling**  
   - Modeled using a **Poisson distribution**.  

4. **Claim Severity Modeling**  
   - Modeled using a **log-transformed Gaussian distribution**.  

---

## Results  
- **Best Model Selection**:  
  - Both claim frequency and claim severity models achieved the best performance when all rating factors were included without reduction or level merging.  

- **Claim Frequency Model**:  
  - Residual deviance: **900.58**  
  - Chi-square value: **1942.96**  
  - Conclusion: The model showed a good fit.  

- **Claim Severity Model**:  
  - Residual deviance: **314.99**  
  - Chi-square value: **35.39**  
  - Conclusion: The model showed a good fit.  

- **Premium Calculation**:  
  - The best-performing models for claim frequency and severity were used to calculate motor vehicle insurance premiums.  

The calculated premiums provide valuable insights for insurance companies, enabling better reserve fund management and ensuring fair pricing strategies for motor vehicle insurance policies.  
