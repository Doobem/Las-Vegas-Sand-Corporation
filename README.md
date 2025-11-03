# Business Process and Data Analysis - Las Vegas Sand Corporation
## Table of Content
- [ Project Overview](#project-overview)
- [Business Process](#business-process)
- [Data Analysis](#data-analysis)
- [Conclusion](#conclusion)

## Project Overview
The scope of this paper examines how the pandemic (Omicron) is affecting  Las Vegas Sands and to analyse its reaction. In the tourist industry, the last several months have been unparalleled. Travel restrictions, airline cancellations, dwindling customer trust, and a barrage of unfavourable news ae just a few of the difficulties that hotel owners are dealing with.

## Business Process
### Introduction
Las Vegas Sands Corporation (LVS) is a large multinational corporation and the world’s premier operator of destination properties (incorporated Resorts) with premium hotels, world-class gaming and entertainment, conference and exposition spaces, mater chef restaurants,  and  a variety of other attractions. The company has a founding chairman and CEO Sheldon G. Adelson, it is geographically classified in three areas: Macau, Singapore and United States. LVS has witnessed a significant drop in revenue and, as a result, profitability because of resort closures. In mid- April 2020 release, Las Vegas Sands reported net sales of $.78 billion(USD)  and a 51.1 percent reduction from the same time  in 2021.

### Jusification of Tools and Technique
Las Vegas Sands Corporation's strategic analysis is divided into two parts: external analysis and internal analysis. Michael Porter's Five Force Framework is utilised in the External Analysis to assess the profitability and attractiveness of the sector. The amount of competition for Las Vegas Sands Corporation's products and services, as well as the company's strengths and weaknesses, will be determined using Porter's five force analysis. Resource Audit, on the other hand, is utilised in internal analysis to identify main rivals. Auditing each area of LVS to determine how many resources it has, both material and intangible.

Quantitative study was carried out utilising Rich picture and UML (Unified Modelling Language) Context diagram for the investigation technique. Rich picture is a diagrammatical depiction of Las Vegas Sands Corporation's issue domain. It captures the most important aspect of an LVS issue and allows for agreement on the interpretation to be used. The UML diagram aids in visualising, specifying, building, and documenting the LVS system's artefacts, as well as facilitating communication and reducing misunderstanding among project stakeholders. A stakeholder analysis is performed utilising CATWOE and the Power/Interest grid for the considered perspective. The CATWOE is a sub-system methodology technique that is completed for each actor in the rich picture diagram to guarantee that root definition is well-informed and complete. The Power/Interest grid is a matrix that is used to manage the LVS stakeholder category in a different way, taking into consideration their amount of power and interest.

### Application of Analysis on Las Vegas Sands Corporation
#### Strategy Analysis
This refers to the process of investigating an organisation and its working environment, as well as the business's objective or mission, timeframe, and resources (Expert Commentator, 2021). It is made up of two parts: external analysis and internal analysis. I would use Michael Porter's five force model for the external analysis, and the resource audit for the internal analysis.
##### Porters five force Analysis of LVS

Table 1: Porters five force Analysis

<img width="452" height="127" alt="Screenshot 2025-11-03 105758" src="https://github.com/user-attachments/assets/0ffb95f8-64c7-4e4f-85b8-683d821f79d3" />


#### Investigation Situation
Rich Picture of Las Vegas Sands Corporation

<img width="940" height="670" alt="image" src="https://github.com/user-attachments/assets/a760d8b4-337c-4bb3-a9b6-768b6a0de203" />


Several findings about LVS were obtained based on several investigations performed using tools. Strategy analysis was performed with the support of  Michael Porter's five force analysis to verify what LVS should incorporate in its imminent strategy. There is no question that the LVS could benefit from enhancements and new features. One top long-term advice for Las Vegas Sands is to start creating destination resorts in popular tourist areas across the world. This might help them hedge some of the risks associated with their casino operations, but it would also make them less reliant on favourable government regulations.
They could grow into every country on the planet without relying on licenced casino gaming. Another suggestion for Las Vegas Sands is to diversify into internet gaming. Las Vegas Sands might also expand into nations where gambling is now allowed. For example, while both Russia and India have allowed casino gaming, no corporation has made a significant attempt to join their markets. Bringing more commonly played games closer together within the casino may assist with this. They might also try to persuade guests to stay for extended periods of time, albeit this may not be feasible for all guests. They must provide a better, more personalised, and personalised experience to everyone to keep clients from departing after only one day.



#### Evaluation 
Diagram.net was used to create numerous diagrams such as DFD and UML since it is exceptionally easy to use and has numerous tools for cooperating and designing various structures required for creating UML and DFD illustrations. Michael Porter helped us comprehend how various aspects of the LVS business, such as customers, competitors, owners, partners, and employees, interact. This, paired with a resource audit, enabled LVS identify its market position and design a plan that would help the company to grow. As indicated by a DFD context diagram, a Rich picture was used to gain a global view of LVS and its decent share of shareholders, as well as various issues faced by different bodies participating in a process. This, along with the use of CATWOE analysis to develop each stakeholder's opinion on LVS, aided in solving conflicting issues in advance, and able to decide which stakeholders are of highest importance based on their influence / interest using the Power/Interest grid. Structured English was used in a better understanding of the situations described by the UML Use case diagram and be able to understand LVS more efficiently as a firm as a result. The sequence diagram depicted the communication of customers and employees in the LVS hotel and resort system.

## Data Analysis

### Introduction 
The purpose of this part is to perform market basket analysis on transactional data. In transaction databases, association rules are constructed by identifying common patterns and relationships among groups of entries. Finding associations and correlations between the various things that customers add in their shopping cart to gain a better understanding of their purchasing habits.

When it comes to data analysis, there are several sorts of association rules:
•	Actionable Rules: these contain high-level and actionable data 
•	Trivial Rules: these are data already well known by those acquainted with the business
•	Inexplainable Rules: these have no clarification and don’t indicate action of any sort.

The Apriori algorithm, a data mining approach for identifying common itemset from datasets, is used to construct association rules. The Apriori method finds the optimum association rules from a dataset using three matrices, resulting in a successful approach on datasets (Section, 2021). The following are the three types of matrices:

•	Support: It calculates how many times a certain item or combination of items appears in a dataset. Support indicates the frequency of the rule inside the transaction. A large value implies that the rule impacts a large proportion of the database.
	Support  A	    B[S,C] = frq(A,B)/N 
		=Frequency of (A,B) over total number of transactions.
    
•	Confidence: It determines how likely an individual is to purchase a product after having purchased another. It represents the proportion of transactions having A and B  compared to transactions containing only A. It’s a conditioned to estimate probability	Confidence (A      B[S,C]) = Support(A,B)/Support(A)  

•	Lift: This is a statistic that determines the degree to which the best rules are related. It is made by taking confidence and dividing it by support. 	
	  Lift (A       B[S,C]) = Support(A,B)/Support (A) Support (B)
A weak connection exists when the lift is less than one, whereas a strong association exists when the lift is more than or equal to one. 


### Application

The dataset in discussion contains data from an online retail store’s transaction. It comprises over 500,000 transactions from thirty-seven nations, as well as one unknown country. It has around eight columns. The apriori algorithm is used to generate multiple rules, Germany is said to be considered to see what the most popular items are and what products may be purchased together. Examining Germany with a generated frequent itemset with support 7%  below:

Apriori() function is used to supply a list of parameters, with the support level, confidence level, and minimum length of each item specified being the parameters. This will assist us in comprehending the dataset's transaction patterns.
frequent_itemsets = apriori(basket_sets, min_support=0.07, use_colnames=True)
 
<img width="887" height="373" alt="image" src="https://github.com/user-attachments/assets/66c9cc0a-a738-4a11-82e2-b10ac3a30eeb" />


The model support is statistically summarised in the summary result (figure 11). The collection is only turned into frequent items, not related rules, the analysis of the dataset is restricted in scope and functionality, looking at 11 baskets and only using the support property. With a support of 0.1, the highest itemset is "6 Ribbons Rustic Charm."
The Apriori algorithm may produce goods that might be purchased together, demonstrating that the popularity of these items is not dependent on their purchase together. This is examined with the diagram :

 <img width="1039" height="327" alt="image" src="https://github.com/user-attachments/assets/64e4808c-d22c-4775-be11-0076f7b3c134" />


"""filter the data frame using standard panda’s code. In this case, look for a large lift (7) and high confidence (.6)"""
aa=rules[ (rules['lift'] >= 7) &
       (rules['confidence'] >= 0.6) ]
       
Overall, we observe a lot of powerful resultant pairings with 'Round Snack Boxes set of 4 Woodland,' which might mean that Round Snack Boxes set of 4 Woodland is a core product category. A manager could decide to keep the price and margins low on Round Snack Boxes set of 4 Woodland to drive sale volume. The exceptions are Plasters in Tin Woodland Animals and Spaceboy Lunch Box, although we may infer that these would be considered alternatives. The rule with Round Snack Boxes set of 4 Fruits shows considerable lift with a confidence of 0.8, which is a more intriguing finding. This might lead to a push for the Round Snack Boxes set of 4 Fruit to be promoted even more, with the condition that buyers will buy other things at the same time.

### Conclusion

Market basket analysis is a form of unsupervised machine learning technique for spotting developments in transactional data. It helps merchants better understand and serve their customers by forecasting their purchase habits in the business realm. An increasing number of companies is using market basket analysis to acquire helpful insight on association and hidden links. As business groups continue to study the technology's potential, a predictive type of market basket analysis is making headway across numerous sectors to uncover consecutive purchases. worth. Market basket analysis is the most common type of artificial intelligence that consumers encounter. It is used to provide recommendations to customers.


