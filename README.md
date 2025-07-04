# Counting Hours, Counting Losses: The Toll of Unpredictable Work Schedules on Financial Security - Supplementary

**Paper Title:** Counting Hours, Counting Losses: The Toll of Unpredictable Work Schedules on Financial Security

**Publication Link:** [TBA]

**Abstract:**

Financial instability is a pressing concern in the United States, with drivers that include growing employment disparities and insufficient wages. While research typically focuses on financial aspects such as income inequality in precarious work environments, there is a tendency to overlook the time-related aspect of unstable work schedules. The inability to rely on a consistent work schedule not only leads to burnout and conflicts between work and family life but also results in financial shocks that directly impact workers' income and assets. Unforeseen fluctuations in earnings pose challenges in financial planning, affecting decisions regarding savings and spending, and ultimately undermining individuals' long-term financial stability and well-being. 

Our objective in this study is to understand how unforeseen fluctuations in earnings exacerbate financial fragility by investigating the extent to which individuals' financial management depends on their ability to anticipate and plan for future events. To answer this question, we present a computational framework to model real-time consumption decisions under income uncertainty, drawing on advances in online planning and reinforcement learning (RL) with lookahead. We introduce a novel online algorithm that enables utility-maximizing agents to dynamically adapt consumption choices in response to financial shocks, leveraging partial deterministic information about future income. This approach forms the basis of our simulation framework, which models how workers manage consumption in the face of variable work schedules and the imperative to avoid financial ruin.

Through theoretical analysis, we quantify the utility advantage conferred by varying levels of lookahead. Empirical simulations demonstrate how increased lookahead improves financial utility. 
That is, with this framework, we demonstrate both theoretically and empirically how a worker's capacity to anticipate schedule changes enhances their long-term utility. Conversely, the inability to predict future events can worsen workers' financial instability. Moreover, our framework enables us to explore policy interventions aimed at mitigating the problem of schedule uncertainty. By modeling both individual behavior and potential policy interventions (e.g., advance scheduling regulations), our framework draws on ideas from machine learning and reinforcement learning to inform economic questions surrounding information access in financial planning.

**Experiments**:

In the main directory

1. *Section 5.2 (Future Lookahead: An Empirical Inquiry):* Consumption_with_Lookahead.ipynb, Robustness_of_consumption_model.ipynb
2. *Section 5.3 (Dynamics of Asset Appreciation and Depreciation):* Consumption_with_Lookahead.ipynb
3. *Section 5.4 (Interventions):* Consumption_Interventions.ipynb

In the *Additional Experiments* Directory

1. *Appendix B.2 (Unemployment):* Unemployment_Insurance_and_Consumption.ipynb
2. *Appendix B.3 (Real-world Educational-based Patience Factors):* High_School_Diploma_and_Patience_in_Consumption.ipynb, College_Degree_and_Patience_in_Consumption.ipynb
3. *Appendix B.4 (Real-world Return Rates on Liquid Assets):* Consumption_with_Asset_Returns_Following_Cash_Rates.ipynb, Consumption_with_Asset_Returns_Following_Stock_Rates.ipynb
4. *Appendix B.5 (More Real-world Shock Profile Case Studies):* Exploring_Shocks.ipynb

**Supplementary:** Counting Hours, Counting Losses - Appendix.pdf
