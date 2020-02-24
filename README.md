
 It contains dataset: CONVID-19_data.csv used in our paper: Estimate the incubation period of coronavirus 2019 (COVID-19)
 
 Estimate the incubation period of coronavirus 2019 (COVID-19)
Ke Men1, Xia Wang2, Yihao, Li3, Guangwei Zhang1, Jingjing Hu1, Yanyan Gao1, Henry Han* 4
1. Institute for Research on Health Information and Technology, School of Public Health, Xi’an Medical University, Xi’an, Shaanxi 710021, China
2. The Air Force Military Medical University, Xi’an, Shaanxi 710032, China
3. Business Analytics, Fordham University, Lincoln Center, New York, NY 10023, USA
4. Computer and Information Science, Fordham University, Lincoln Center, New York, NY 10023, USA

*Correspondence author 

Abstract
Motivation: Wuhan pneumonia is an acute infectious disease caused by the 2019 novel coronavirus (COVID-19). It is being treated as a Class A infectious disease though it was classified as Class B according to the Infectious Disease Prevention Act of China. Accurate estimation of the incubation period of the coronavirus is essential to the prevention and control. However, it remains unclear about its exact incubation period though it is believed that symptoms of COVID-19 can appear in as few as 2 days or as long as 14 or even more after exposure. The accurate incubation period calculation requires original chain-of-infection data that may not be fully available in the Wuhan regions. In this study, we aim to accurately calculate the incubation period of COVID-19 by taking advantage of the chain-of-infection data, which is well-documented and epidemiologically informative, outside the Wuhan regions.

Methods:  We acquired and collected officially reported COVID-19 data from 10 regions in China except for Hubei province. To achieve the accurate calculation of the incubation period, we only involved the officially confirmed cases with a clear history of exposure and time of onset. We excluded those without relevant epidemiological descriptions, working or living in Wuhan for a long time, or hard to determine the possible exposure time.  We proposed a Monte Caro simulation approach to estimate the incubation of COVID-19 as well as employed nonparametric ways.  We also employed manifold learning and related statistical analysis to decipher the incubation relationships between different age/gender groups.

Result: The incubation period of COVID-19 did not follow general incubation distributions such as lognormal, Weibull, and Gamma distributions. We estimated that the mean and median of its incubation were 5.84 and 5.0 days via bootstrap and proposed Monte Carlo simulations.  We found that the incubation periods of the groups with age>=40 years and age<40 years demonstrated a statistically significant difference. The former group had a longer incubation period and a larger variance than the latter. It further suggested that different quarantine time should be applied to the groups for their different incubation periods. Our machine learning analysis also showed that the two groups were linearly separable. incubation of COVID-19 along with previous statistical analysis.  Our results further indicated that the incubation difference between males and females did not demonstrate a statistical significance.

