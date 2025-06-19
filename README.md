# Bank_of_England
This final six-week project for the LSE data-analytics course gave our team (comprised of six students) the opportunity to work directly with the Bank of England on a project analysing the sentiment of BoE speeches and exploring how that sentiment might be incorporated into models predicting macroeconomic shifts. 

As a team, we tested multiple sentiment models (including transformer-based ML models and LLMs) and ran several types of predictive modelling and forecasting (including gradient boosting and SARIMAX) to meet these objectives. We ultimately recommended that BoE incoporate the specialised CentralBankRoBERTa sentiment model alongside long lags to capture effects of communications. 

My personal contributions included running multiple sentiment models for comparison, setting up a rigorous testing process to add weight to our final choice of model, and conducting exploratory and comparative analysis of sentiment over time. I also conducted LDA topic modelling on the speech data set. (We did not end up using this in the final analysis, but you can find the notebook here anyway.)

I was lucky to be on a team of five other incredible anlaysts, who all brought unique skills and ideas to the project. The repo here includes everyone's work, with initials indicating the analyst responsible for each notebook. Those teammates (and just a few of their specific contributions) are: 
- **Chris Buck (CB)**: team lead, spearheading all aspects of the project and instrumental in collating, cleaning, and merging economic-indicator data
- **Germán de la Fuente (GF)**: conducted web scraping to update the data set with the most recent BoE speeches, ran predictive models including scenario analysis using external volatility data
- **Harshdeep Kohli (HK)**: Implemented several sentiment models, applied an advanced Gradient Boosting regression that demonstrated the predictive power of speech sentiment
- **Kelvin Dhondee (KD)**: Compiled economic-research primers for the team to enhance our collective domain knowledge, ran an advanced time-series forecasting model (SARIMAX) that demonstrated how sentiment could enhance economic predictions
- **Victoria Pogonyaylova (VP)**: Played a large part in initial cleaning and EDA, used advanced techniques to customise a highly specialised sentiment model (CentralBankRoBERTa) to suit our needs.
