# Daegu Apartment Price Prediction Project

## Business Background

Daegu, the fourth-largest city in South Korea, boasts a population of approximately 2.5 million residents. The city's real estate market, particularly the apartment sector, is highly active and influenced by various factors including geographic location, property features, accessibility to facilities, and broader economic conditions.

## Problem Statement

The Daegu real estate market faces significant challenges:

1. **Market Efficiency**: There's a need for accurate pricing to mitigate risks of property mispricing and enhance market efficiency.
2. **Affordability Crisis**: With a price-to-income ratio of 17.58 and mortgages consuming 140.01% of average income, there's a clear affordability issue.
3. **Investment Decisions**: Investors need reliable data to make informed decisions in a complex market.
4. **Urban Planning**: City planners require data-driven insights for sustainable urban development.
5. **Financial Risk Assessment**: Banks and financial institutions need precise property appraisals for mortgage lending and risk assessments.

## Project Goals

1. Develop a machine learning model to accurately predict apartment prices in Daegu.
2. Identify key factors influencing apartment prices.
3. Provide interpretable insights into property valuation for various stakeholders.
4. Enhance decision-making processes in real estate transactions, urban planning, and financial risk assessment.

## Methodology

- Data Collection and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Selection and Training (XGBoost chosen as the final model)
- Hyperparameter Tuning
- Model Evaluation and Interpretation (using SHAP values)

## Key Findings

1. **Model Performance**: Achieved 84.35% accuracy (R² score) in predicting apartment prices.
2. **Critical Price Drivers**:
   - Apartment size (sqft) is the most influential factor
   - Building age (YearBuilt) is the second most important, with newer not always meaning more valuable
   - Number of facilities in the apartment complex is the third most impactful
3. **Market Insights**:
   - Proximity to subway and universities has less impact than traditionally assumed
   - Complex relationship between building age and price, challenging conventional wisdom

## Conclusion

The developed XGBoost model provides highly accurate apartment price predictions for the Daegu market. It offers valuable insights into the complex interplay of factors affecting property values, challenging some traditional assumptions about real estate pricing. The model's interpretability through SHAP analysis allows for transparent and justifiable valuations, which can significantly improve decision-making processes for various stakeholders in the real estate ecosystem.

## Recommendations

1. **For Real Estate Agencies**: 
   - Utilize the model for initial property valuations to enhance efficiency and accuracy.
   - Use SHAP analysis to provide data-driven explanations to clients about property pricing.

2. **For Investors**:
   - Leverage the model to identify potentially undervalued properties.
   - Use insights on feature importance to guide investment strategies.

3. **For Urban Planners**:
   - Consider the revealed impact of urban features (e.g., facilities, transportation) on housing prices when planning developments.
   - Use the model to simulate how urban development decisions might affect property values.

4. **For Financial Institutions**:
   - Incorporate the model into risk assessment processes for mortgage lending.
   - Use the model's uncertainty metrics to inform lending policies.

5. **For Property Developers**:
   - Focus on optimizing the most impactful features (size, facilities) when designing new projects.
   - Consider the nuanced relationship between building age and value in renovation decisions.

6. **Continuous Improvement**:
   - Regularly update the model with new data to ensure it remains accurate and relevant.
   - Explore integration with additional data sources (e.g., economic indicators, social trends) for more comprehensive analysis.

## Future Work

- Expand the model to cover other types of real estate in Daegu.
- Develop a user-friendly interface for non-technical stakeholders to access the model's insights.
- Investigate the potential for adapting the model to other South Korean cities.

---

This project demonstrates the power of machine learning in revolutionizing real estate valuation and decision-making processes. By providing accurate, data-driven insights, it has the potential to significantly improve market efficiency, inform urban development, and enhance investment strategies in Daegu's dynamic real estate market.
