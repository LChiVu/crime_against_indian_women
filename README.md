## Understanding Violence Against Women in India: An Analysis of Crime Data (2001-2014)**

### Author Information
- **Name:** Chi Vu
- **Date:** 12/15/2022

### Introduction
The dataset "Crime Against Women 2001-2014 (India)" provides a comprehensive overview of violence against women in India from 2001 to 2014. This project aims to analyze this data to understand the prevalent types of violence and explore potential correlations between different forms of violence, particularly focusing on cruelty by husbands and dowry deaths.

### Ethical Considerations
Given the sensitive nature of the data, it's essential to recognize the ethical implications of our analysis. We acknowledge that reported cases may only represent a fraction of the actual incidents due to underreporting, stigma, and fear of reprisal. Our analysis seeks to interpret the available data responsibly, considering the broader societal context and the experiences of women and girls in India.

### Data Explanation and Exploration
- The dataset was retrieved from a project from author Greeshma on [kaggle](https://www.kaggle.com/datasets/greeshmagirish/crime-against-women-20012014-india), the data itself was collected from the Indian government’s official website, [Open Government Data](https://data.gov.in/). 
- The dataset comprises data at multiple levels, including state/union territories (UTs), districts, and crime types. Data cleaning was performed to standardize state and UT names. Due to the extensive district-level data, we aggregated the information at the state/UT level for analysis, focusing on cumulative crime totals.

### Statistical Analysis and Interpretation
Initial exploratory analysis revealed an upward trend in reported cases of violence against women from 2012 to 2014. Cruelty by husbands and relatives emerged as the most prevalent form of violence, followed by assault with intent to outrage modesty. A correlation analysis between cruelty by husbands and dowry deaths indicated a moderate positive correlation (r = 0.486), suggesting a potential relationship between these two variables.

Further, a linear regression model was employed to predict dowry deaths based on the number of cruelty cases. The model indicated a positive association (β = 4.259) between the two variables, suggesting that an increase in husband cruelty cases corresponds to a slight increase in dowry deaths. However, the model's predictive power was limited, explaining only 23.5% of the variance in dowry deaths.

### Conclusions 
Our analysis highlights the prevalence of violence against women in India, with cruelty by husbands being a significant concern. While a correlation exists between cruelty by husbands and dowry deaths, predicting dowry deaths based solely on cruelty cases is challenging. Future research could explore regional variations in violence patterns and factors contributing to underreporting.

### Reflection
Throughout the project, emphasis was placed on ethical considerations, data transparency, and clear communication of findings. Organizational strategies, such as file management and variable naming conventions, facilitated reproducibility and collaboration. Reflecting on the analysis process, efforts were made to simplify complex statistical concepts for broader understanding, emphasizing clarity and accessibility.

### Works Cited
- Chaudhary, Surbhi. “Dowry and Dowry Death.” Times of India Blog, 15 Apr. 2022.
- Ford, Clay. “Understanding Q-Q Plots | University of Virginia Library Research Data Services + Sciences.” University of Virginia Library, 26 Aug. 2015.
- Greeshma. “Crime against Women 2001-2014 (India).” Kaggle, 2019.
- “Open Government Data (OGD) Platform India.” Open Government Data (OGD) Platform India, 21 Jan. 2022.
- Pandey, Geeta. “Rising Crimes against Indian Women in Five Charts.” BBC News, 12 Sept. 2022.
- “Vikaspedia.” Vikaspedia.in, 2022.
