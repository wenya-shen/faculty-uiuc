# 

```
title: The Societal Impact of Sharing Economy Platform Self-Regulations—An Empirical Investigation
authors: Wencui Han, Xunyi Wang, Mehmet Eren Ahsen, Sunil Wattal
journal: Information Systems Research
published: 2022
```
 

 # Executive Summary
 

 -   This research examines the **impact of platform self-regulations** in the context of the **home-sharing market** on **crime rates**.
 -   Using policy changes ("one host, one home" (OHOH) and "primary residency" (PR) regulations) that reduce the number of Airbnb listings in San Francisco, New York City, and Denver, **difference-in-difference approach** is deployed to empirically test the impact of platform self-regulations on crime rate.
 -   Key **theoretical** / **conceptual framework** discussions
     -   **Crime Pattern Theory**: Offenders follow a "**crime template**" where paths of offenders and targets intersect [Brantingham and Brantingham, 1993]. Targets in unsafe environments are more likely to be attacked [Seigel, 2006].
     -   **Routine Activity Theory**: Crime events occur due to the joint influence of a motivated offender, a suitable target, and the absence of capable guardians [Cohen and Felson, 1979].
 -   Key **findings** / arguments including
     -   Reduction in Airbnb listings resulting from platform self-regulations leads to a reduction in overall crime in the affected zip codes, specifically in **assault**, **robbery**, and **burglary**.
     -   Regulations may lead to an **increase in theft incidents**, likely due to more guests sharing homes with hosts.
     -   **Income**, **housing price**, and **population** moderate the impact of the regulations on different types of neighborhoods.
     -   Number of listings and the total Airbnb occupancy **mediate** the impact of the regulations.
     -   Higher median incomes, higher housing prices, and lower unemployment rates are likely to have increased crime with increased Airbnb occupancy, while low-income and low-population areas may have decreased crime as Airbnb occupancy increases.
 

 #sharing_economy #home_sharing #platform_self_regulation #crime_rate #societal_impact #airbnb #difference_in_differences #geographically_weighted_regression #crime_pattern_theory #routine_activity_theory
 
<details>
  <summary>Click to expand sections</summary>
	
 # 1. Introduction
 

 -   The sharing economy has disrupted traditional industries and had unforeseen societal impacts [Greenwood and Wattal 2017, Zervas et al. 2017, Burtch et al. 2018, Babar and Burtch 2020], sparking debates on the need for regulation.
 -   Home-sharing platforms like Airbnb facilitate social harmony [Walker 2016] and generate revenue for local businesses but face opposition due to unfair competition with hotels, increased rents, and house prices [Horn and Merante 2017, Chen et al. 2021b].
 -   Major stakeholders contend to impose regulations on the sharing economy [Rauch and Schleicher 2015], while others propose self-regulation by the platforms themselves [Cohen and Sundararajan 2015].
     -   Airbnb has worked with municipalities to create self-regulations addressing the housing price crisis by removing short-term listings from professional hosts [Chen et al. 2021a], effectively reducing property sales prices [Kim et al. 2017].
 -   The rapid expansion of home-sharing economies raises concerns for public safety, with media highlighting criminal activities targeting Airbnb guests [Fox News 2018].
     -   Complaints emerged from cities stating that Airbnb has not adequately addressed issues related to safety [Grind and Shifflett 2019].
     -   Despite anecdotal evidence, the understanding of how home-sharing and platform self-regulations impact crime incidents is limited.
 -   I am interested in studying the societal impact (crime rate) of home-sharing platforms’ self-regulations.
     -   I will examine the impact of platform self-regulation on crime using policy changes that reduce the number of Airbnb listings.
     -   Previous studies on sharing economy regulations exist [e.g., Chen et al. 2021a], but I am among the first to study the societal impact of home-sharing self-regulations on crime rates.
     -   Xu et al. [2019] show the association between Airbnb and crime in an exploratory study, but this research lacks causal identification mechanisms and discussion of regulations.
 -   I seek to address the following research questions:
     -   *RQ1*: Do home-sharing platforms’ self-regulations impact crime rate?
     -   *RQ2*: How do economic and demographic factors moderate the relation between home-sharing platforms’ self-regulations and crime?
     -   *RQ3*: What factors mediate the effect of home-sharing platforms’ self-regulations on crime rate?
 -   To answer these questions, I leverage classic criminology theories, such as crime pattern theory and routine activity theory [Eck and Weisburd 2015], to conceptualize how the reduced presence of Airbnb listings impacts criminal acts.
     -   By rationalizing the relationship between the number of Airbnb listings and crime rates, I understand how home-sharing platforms' self-regulations impact local crime rates via reducing Airbnb listings.
 -   To identify the causal mechanisms, I use two policy changes implemented in 2016 and 2017 as a natural experimental design:
     -   the “one host, one home” regulation (OHOH)
     -   the “primary residency” regulation (PR)
     -   These regulations limited the number of Airbnb listings by a single host and prohibited commercial host listings in San Francisco, New York City, and Denver.
     -   I also construct a comparison group of zip codes from Los Angeles, Boston, and Seattle based on the size of the Airbnb market and economic and demographic characteristics.
     -   Using the difference-in-difference (DID) approach, comparing changes in crime incidents before and after implementing the policies, I can provide evidence of the impact of the regulations on crime.
 -   To construct the data set on crime rate, I collected incident-level detailed crime reports from January 2015 to December 2018 from each of these six cities' police departments.
     -   I also obtained a proprietary data set of detailed information of all active Airbnb listings during these four years from the six cities.
     -   The final data set includes more than 5 million crime incidents and listing information for over 400,000 Airbnb listings.
     -   Finally, I collected a number of economic and demographic measures from the U.S. Census Bureau, the Bureau of Labor Statistics, the Bureau of Transportation Statistics, the Federal Judicial Center, and Zillow Research to construct a set of control variables.
 -   The results show that the policies reduced overall crime in the affected zip codes.
     -   Specifically, I see reductions in assault, robbery, and burglary.
     -   Surprisingly, both policies increase theft incidents, as the policies led to more guests sharing homes with the hosts, increasing theft opportunities.
     -   Several robustness checks are carried out to validate the main results, including a relative time model, multiple falsification tests, and a DID estimation using the propensity score-matching method.
     -   Findings from all specifications are consistent with no detection of a heterogeneous pretreatment trend, which indicates that the primary assumption of the DID model is not violated [Angrist and Pischke 2008].
 -   To shed further light on the mechanism, I also examine how the policies impacted the supply, occupancy, and quality of Airbnb listings using mediation analysis.
     -   The number of listings and the total Airbnb occupancy was significantly reduced after implementing the policies, and they mediate the impact of the regulations.
 -   Finally, I explore the heterogeneous impact of Airbnb occupancy on crime in different neighborhoods.
     -   To incorporate confounding effects as a result of the spatial proximity between different neighborhoods, I apply geographically weighted regression (GWR).
     -   Our results suggest that with increased Airbnb occupancy, neighborhoods with higher median incomes, higher housing prices, and lower unemployment rates are likely to have increased crime.
     -   By contrast, low-income and low-population areas may have decreased crime as Airbnb occupancy increases.
     -   A potential explanation of these heterogeneous effects could be that in high-income neighborhoods, increased Airbnb occupancy boosts tourists' volume, which provides more suitable targets for offenders [Schwartz and Pitts 1995, Brunt et al. 2000].
     -   In lower-income neighborhoods, local businesses can benefit from the positive economic spillover effect of Airbnb, and financially struggling families might gain additional income through Airbnb. Thus, with improved economic circumstances, individuals in these communities will be less likely to pursue criminal acts that bear huge risks [Becker 1968, Freeman 1999, Raphael and Winter-Ebmer 2001].
 -   This research contributes to a growing stream of literature focusing on the societal and economic impact of platforms [Chan and Ghose 2014, Greenwood and Agarwal 2015, Bapna et al. 2016, Sundararajan 2016, Greenwood and Wattal 2017] by offering an understanding of the nuanced impact of self-regulations of the home-sharing industry on crime.
 -   This work also contributes to the public policy debate on the regulations of sharing economy platforms.
     -   The results of this study suggest that home-sharing platforms’ self-regulation can have societal benefits, but such policies should consider the mechanism and heterogeneity of the platform’s impacts on different types of crime and the geospatial location of the neighborhoods.
 

 # 2. Related Literature
 

 ## 2.1. Societal and Economic Impact of the Sharing Economy
 -   Academic research on the sharing economy has mainly focused on studying its impact as a disruptive technology on traditional industries, the economic environment, and society.
 -   A few studies highlight the effects of the sharing economy on the businesses they directly compete with.
     -   Wallsten [2015] finds that increased Uber use is associated with a decrease in complaints about taxi services.
     -   Zervas et al. [2017] show that space-sharing services impact the hotel industry unevenly, with lower-end hotels and hotels not catering to business travelers being the most affected.
     -   Li and Srinivasan [2019] study the impact of Airbnb on revenue and market size for the hotel industry.
 -   Another dimension of the sharing economy’s impact lies in its spillover effect on the economic environment.
     -   Burtch et al. [2018] show that the entry of ride-sharing platforms reduces entrepreneurial activity and lowers its quality.
     -   Research reveals that participation in online sharing economy markets is driven by local economic downturns and can help unemployed and financially struggling individuals generate temporary employment [Dillahunt and Malone 2015].
     -   Recent research also finds a positive association between local (offline) unemployment rates and the online labor supply in the gig economy [Huang et al. 2020].
 -   Furthermore, a growing body of literature sheds light on the societal impact of the sharing economy.
     -   Extensive evidence shows that the sharing economy can increase social welfare.
         -   For example, Babar and Burtch [2020] study the impact of ride-hailing services on public transit and find that ride-hailing services significantly reduced road-based, short-haul public transit services and increased the use of rail-based and long-haul transit services.
         -   Also, compared with traditional taxis, Uber shows a higher capacity utilization rate in terms of time and fuel efficiency [Cramer and Krueger 2016].
         -   Research on ride sharing also shows that Uber's entry is associated with a significant decline in drunk driving fatality rates [Greenwood and Wattal 2017].
         -   The number of Uber pickups is negatively associated with occurrences of rape in New York City (NYC) [Park et al. 2021].
 -   With the positive impacts of the sharing economy well documented, research has also focused on its negative effects.
     -   Anecdotal evidence has shown that guests of home sharing have been the target of various criminal activities [Fox News 2018, Xu et al. 2019].
     -   Home-sharing platforms such as Airbnb have been criticized for paying no attention to addressing safety issues [Grind and Shifflett 2019].
     -   Mejia and Parker [2021] provide evidence of bias in ride-sharing services by showing that ride cancellation rates are higher for African Americans and the LGBTQ community.
     -   Furthermore, prior literature has uncovered negative consequences of peer-to-peer platforms (which is a broader concept that includes the sharing economy), such as gender and racial discrimination on these platforms [Ge et al. 2020, Edelman et al. 2017].
     -   Racial hate crimes are found to be positively related to the availability of the internet [Chan et al. 2016].
     -   Chan and Ghose [2014] show how the entry of Craigslist increases the prevalence of HIV by providing a platform for people seeking casual sex partners, and Chan et al. [2019] also find Craigslist leads to a 17.58% increase in prostitution cases.
     -   Greenwood and Agarwal [2015] further identify granular effects across subpopulations (i.e., race, gender, and socioeconomic status) in the process where matching platforms increase HIV incidence.
 -   My work adds to this budding literature on the societal impact of sharing economy platforms.
     -   Airbnb's economic, societal, and spillover effect has attracted much attention from scholars [Zervas et al. 2017, Zhang et al. 2017, Benjaafar et al. 2019, Chen et al. 2021b, Mayya et al. 2021].
     -   This space-sharing platform can drastically change local communities [Sundararajan 2016], which may be related to change in criminal patterns.
     -   Because of both the economic implications and the externalities that the sharing economy generates, it is imperative to advance this stream of literature [Koopman et al. 2015].
 

 ## 2.2. Regulations on Home Sharing and Crime
 -   The direct and spillover effects of the sharing economy have led to a debate on the need to craft necessary regulations.
     -   There is a small but growing stream of research investigating sharing economy regulation across many disciplines [Katz 2015, Koopman et al. 2015, Hong and Lee 2018].
     -   Some researchers argue that platform self-regulation is the right approach to resolve the challenges brought by the sharing economy [Cohen and Sundararajan 2015, Sundararajan 2016].
     -   Others are concerned with market failure and advocate for some regulations to account for the negative externalities that platforms impose [Interian 2016].
     -   Studies in the field of law have investigated specific policy choices to regulate the sharing economy [Katz 2015, He 2017].
     -   Chen et al. [2021a] find that regulatory interventions have less impact on long-term growth in the home-sharing economy, but short-term regulations can create a deterrent for new entrants.
 -   Despite the diverse opinions, the consensus is that there should be a particular government intervention level that is best suited to regulate and collaborate with sharing-economy platforms [Interian 2016].
     -   Cohen and Sundararajan [2015] note that although platform self-regulation is ideal, government involvement or oversight is essential to correct for any suboptimal outcome.
 -   My central research question is to study whether and how the home-sharing platforms’ self-regulations impact crime rates.
     -   The purpose of the regulations (i.e., the “OHOH” and the “PR”) investigated in this study was to reduce the number of short-term rental listings to lower the local housing price and rent and to protect affordable housing.
     -   Parallel with this rationale, I argue that the regulations reduce the number of short-term home sharing listings, which lessen the volume of home-sharing guests; this can eventually reduce crime incidents.
     -   The implied logic here is that the guests tend to become the targets of criminals. Therefore, to assess our research question, it is critical to understand how home-sharing prevalence may induce crime activities.
 -   Prior work in sociology and criminology literature has discussed the generation of illegal acts as a result of environment and space features [Eck and Weisburd 2015].
     -   Rather than focusing on offenders' characteristics, theorists of space criminology concentrate more on the circumstances or environmental settings where criminal acts occur [Cohen and Felson 1979].
     -   These criminologists believe that crime may not always take place randomly and that crime rates depend on factors such as time, space, and society.
     -   Several theoretical perspectives, such as rational choice theory, crime pattern theory, and routine activity theory [Cohen and Felson 1979], have improved our understanding of the importance of environment in crime prevention efforts.
         -   The rational choice theory suggests that offenders will select targets and choose means to achieve their goals in a specific manner [Cornish and Clarke 2014].
         -   *Crime pattern theory* suggests that criminals usually follow a "**crime template**" to commit crimes, which consists of places where the paths of both offenders and targets intersect [Brantingham and Brantingham 1993].
         -   Targets are more likely to be attacked as a result of being exposed to an unsafe environment [Seigel 2006].
         -   In addition, offenders will feel most comfortable committing criminal events within the areas they know, and in most ways, offenders behave similar to the nonoffender population [Brantingham et al. 2017].
         -   *Routine activity theory* also supports the arguments that crime pattern theory provides.
             -   Specifically, routine activity theory seeks to understand the occurrence of crime events as the joint influence of several factors:
                 -   the presence of a motivated offender,
                 -   a suitable target,
                 -   the absence of capable guardians against a violation [Cohen and Felson 1979].
             -   While engaging in their illegal activities, rational offenders will note places where the handlers, guardians, or managers are unlikely to show up [Eck and Weisburd 2015].
 -   In the case of home sharing, guests have a higher chance of becoming targets of criminal activity compared with residents who regularly stay in the community.
     -   Although one may assume that tourists and travelers would experience the same level of crime as the residents of the community they are staying in, the fact that their behavior is different suggests otherwise [Brunt et al. 2000].
     -   Criminology literature has documented lifestyle as a pertinent risk of victimization [Schwartz and Pitts 1995].
     -   As noted in Ryan [1993, p. 177], tourists are obvious in their dress, and they carry items of wealth that are easily disposable such as currency, passports and cameras. They are relaxed, and off guard. They are also less likely to press charges should the criminal be caught.
     -   Furthermore, travelers may be unaware of risky locations, display signs of carelessness, and act differently than locals.
     -   Chesney-Lind and Lind [1986] find that tourists in Hawaii were more likely to become victims of crime such as robbery and rape than were locals.
 -   From the perspectives of both crime pattern theory and routine activity theory, the potential targets become actual victims when the potential offender is willing to commit a crime and when the potential target fits the offender’s crime template [Brantingham et al. 2017].
     -   Consider the following example: Potential offenders conduct routine activities, such as work, school, and shopping, like everyone else.
     -   They have normal spatiotemporal movement patterns [Brantingham et al. 2017].
     -   They also build awareness of the locations around their normal activities.
     -   However, when a house becomes a home-sharing property, one could readily observe and perceive certain changes regarding this property’s features.
     -   For example, the flow of the people to the house may spike, and the noise level around the house may increase [Ozer et al. 2021].
     -   These evident changes may trigger potential offenders to commit crimes on home-sharing guests, who are mostly tourists and travelers.
     -   Taken together, the penetration of home sharing in a community may induce criminal activities.
     -   When implementations of the regulations remove partial home-sharing listings, those home-sharing properties will be restored as normal residences, and we may expect a reduction in the crime rate.
 

 # 3. Research Methodology
 

 ## 3.1. Background
 -   Airbnb is an online marketplace and hospitality service for people to lease or rent short-term lodging.
     -   As the leading home-sharing platform, Airbnb has more than 7 million lodging listings in over 100,000 cities in 220 countries and has facilitated more than 750 million check-ins as of 2020.
 -   With rapid growth, home-sharing platforms have been associated with numerous social and economic issues, such as increasing prices for long-term rental housing.
 -   To work with the local government to promote responsible sharing, Airbnb has launched many self-regulation policies in many cities.
 -   Using such policies as a natural experiment, I examine the impact of home-sharing platforms’ self-regulations on crime incidents.
 

 ## 3.2. Econometric Identification
 -   In many cities with high housing demands, Airbnb has been criticized for squeezing the meagre supply of long term rental accommodations when property owners list their housing units on short-term rental platforms because it is more lucrative.
     -   Research reveals a rapidly growing portion of Airbnb’s listings belong to commercial operators who rent out more than one residential property to short-term visitors.
 -   To limit the impact of home sharing on long-term rental and housing markets, Airbnb is working with many cities worldwide to enact policies that self-regulate certain types of listings.
 -   My econometric identification hinges on policy changes that would directly reduce Airbnb listings and the number of guests hosted through Airbnb but are not related to crime statistics in the area.
     -   The usual empirical strategy utilizing the entry of home-sharing platforms may suffer from endogeneity challenges, such as simultaneity and omitted-variable biases.
 -   Therefore, I use policy changes that can serve as natural experiments to estimate the impact of Airbnb regulations on criminal activities.
     -   By searching the Airbnb site, I found that San Francisco, New York City, and Denver have enacted policies that explicitly require short-term rentals to be the sole primary residence of the host and/or require removing multiple listings belonging to the same host.
     -   Two types of policies have been adopted in these markets: **OHOH** and **PR**, intending to significantly reduce the number of listings.
     -   These are city-level policies that are implemented across all zip codes in the three cities.
 -   To determine whether the policies are effective, I observe the number of removed listings as a result of these policies.
     -   I define removed listings as listings that were active (that had at least one booked night) six months before the policy implementation but do not exist in the data set after the policy implementations (listings not observed).
     -   I found OHOH removed 29% and 26% listings from New York and San Francisco, respectively.
     -   PR removed 55% and 20% listings from San Francisco and Denver, respectively.
 -   Note here that all the sources, such as news articles, consistently state that the policies' implementations are mainly aimed at increasing the long-term rental housing supply and protecting affordable housing.
     -   Thus, the policies are not aimed at reducing crime.
     -   Because the policies are implemented at the city level, their implementations are not likely to be driven by zip code–level characteristics.
 -   I estimate these policies’ impact on crime by comparing changes in crime incidents before and after enacting the policies in a specific zip code with a baseline of changes in crime incidents in zip codes with no such policy over the same time.
     -   I construct the control group with zip codes from three cities similar to the affected cities (detailed in Section 3.3).
 

 ## 3.3. Data
 -   I combine several sources of data to form a rich data set.
     -   First, I collect incident-level crime reports from the police departments of the six cities in our sample.
         -   The reports include the details of each incident, such as time of reporting, location (in the form of geo-coordinates), crime types, suspects and victims (race and gender), and the resolutions.
         -   I collect the reports from January 2015 to December 2018 (48 months total, 22 months before the implementation of the first policy and 11 months after the implementation of the last policy).
         -   The crime incident reports from these cities do not follow the same reporting standard.
         -   Therefore, following the definitions in the National Incident-Based Reporting System, I first recode these crime reports and keep the four most common crime incident types in the United States:
             -   theft (the taking of another person's property or services without that person's permission or consent, with the intent to deprive the rightful owner of it),
             -   burglary (the illegal entry into a building or other area to do something illegal there),
             -   assault (an intentional act that puts another individual in danger of immediate harm),
             -   robbery (the taking of or attempt to take anything of value by force or threat of force, or by putting the victim in fear).
     -   Second, I obtained property-level Airbnb data from a third-party business intelligence company.
         -   The data set contains listing-level information such as zip code–level location, property characteristics, host descriptions, reviews, and prices of the listings.
         -   More important, it also includes property performance information (e.g., numbers of days booked by guests and available days of the listings for booking); thus, it provides an accurate measure of Airbnb occupancy.
         -   I am also able to identify listings that are removed after the policy implementations by using listing IDs.
         -   This data set spans the same time period as our crime reports (i.e., from January 2015 to December 2018).
     -   Last, I construct a vector of time-variant control variables that could impact crime rates across zip codes and cities from the U.S. Census Bureau, Bureau of Transportation Statistics, the Bureau of Labor Statistics, the Federal Judicial Center, and Zillow Research.
         -   The control variables include population, number of arrival passengers, unemployment rate, average monthly earning, law enforcement employee number, bankruptcy cases, and housing price index.
 -   I now discuss the process of choosing policy-unaffected cities.
     -   Because the policy was announced and implemented at the city level in New York City, San Francisco, and Denver, I choose cities comparable to these three affected cities.
     -   I first rank the major U.S. cities by Airbnb market size (in terms of the number of Airbnb listings) and economic and demographic characteristics (population, median household income, and unemployment rate).
     -   Then I use a Euclidean distance algorithm to find the nearest “neighbors” to the affected cities.
     -   Among the top 10 cities, I then select the cities that are not affected by policies that regulate Airbnb activities from 2015 to 2018.
     -   Among the remaining 7 cities, I further investigate the availability of crime incidence reports.
     -   Finally, I select 3 cities—Los Angeles, Seattle, and Boston—to form our control groups.
 -   Note that in our model, I include zip code–specific trends to relax the parallel trend assumption.
     -   I also test the comparability of the control group with the affected zip codes using a relative time model.
     -   I conduct a propensity score-matching analysis to ensure the comparability of the two groups.
 -   I merge these sources of data at the zip code level by year-month.
     -   Our sample consists of 421,869 Airbnb properties and 5,052,571 crime incidents from 581 zip codes, including 268 zip codes from treated cities and 213 zip codes from untreated cities.
 

 # 4. Analyses and Findings
 

 ## 4.1. The Policy Impact on Crime Incidents
 

 ### 4.1.1. Results from Difference-in-Difference Estimation
 -   I use a two-treatment DID estimation [Huang et al. 2017] to establish the effects of the two policies restricting home sharing on the crime rate.
     -   I also run separate DID estimations for each policy, and the results are consistent.
 -   I estimate the DID models as reflected in Equation (1):
     -   ln Crime cit( )  β1Onehomect + β2Primary Residencect + γ′Zit + μt + v i + εcit: (1)
     -   The dependent variable ln Crimeit( ) is an aggregated measure of the log transformation of the number of incidents of the different types of crime in zip code i in city c in month t; ln Total Crimeit( ) is the average of ln Crimeit( ) of different types of crimes.
     -   Our primary independent variables are treatment indicators Onehomect and Primary_Residencect, which are equal to 1 if that policy was announced in city c by time t.
     -   We also incorporate zip code (v i) and time (year-month) (μt) fixed effects to account for the unobserved characteristics pertaining to the zip codes and certain months.
     -   The error term is indicated byε.
     -   To reduce heteroskedasticity concerns, I use robust standard error clustered at the zip code level.
 -   I include Zit, a vector of covariates including zip code–level and city-level economic and demographic characteristics and zip code–specific time trends.
     -   I use three types of controls to account for variations in tourist/traveler volume across different zip codes and months.
         -   First, I include zip code–specific trends as a control in Zit to relax the parallel trending assumption.
         -   Second, I include city-county-month fixed effects to control for differences in seasonal demands across different cities and zip codes.
         -   Third, I collect passenger arrival data for all airports in the six cities from the Bureau of Transportation Statistics to control for changes in tourism over time in a given city.
     -   I also include a few relevant zip code–level controls, including the rent index at zip code-month level collected from Zillow Research, to control for the economic status of the zip code, as well as the location desirability of the zip code.
     -   I also include the personal bankruptcy claims at zip code-month level collected from the Federal Judicial Center to control for the economic hardship in a zip code that might impact crime activity.
     -   Finally, to control for any variations in law enforcement and government efforts in reducing crime during our observation window, I include county-year-level numbers of law enforcement workers as control variables in the model.
 -   The results (Table 4) show that after implementing the OHOH, overall crime was reduced by 4.9%: assaults were reduced by 6.8%, robbery by 6.8%, and burglary by 7.7% in affected zip codes compared with unaffected zip codes.
     -   After implementing the PR, overall crime shows a reduction of 5.8%; assaults were further reduced by 15.6% in affected zip codes and robbery by another 4.9% compared with unaffected zip codes.
     -   Surprisingly, theft increased after the implementation of both policies—by 7.3% and 5.1%, respectively—compared with that in control zip codes.
     -   A probable explanation for the increase in thefts is that as a result of the policies, because multiple listings and nonprimary residences are removed, more guests are likely to share homes with the hosts.
 

 ### 4.1.2. Results from Relative Time Model
 -   I check the parallel trend assumption by replicating our results in the main specification using a relative time model, which allows us to measure the treatment's effect over time, both before and after the treatment.
 -   Specifically, I model Crimeicit by Equation (2):
     -   ln Crimeict( ) ∑nτ−TλτDcτ + γ′Zit + μt + vi + εit: (2)
     -   Here, D ct is a dummy variable indicating whether month t is the τ month before (for negative τ’s) or after (for positive τ’s) the OHOH implementation.
     -   Standard errors are robust and clustered at the zip code level.
 -   As shown in Table 5, there is no evidence of the violation of the parallel trending assumption, and the results are consistent with the main specification.
 

 ### 4.1.3. Falsification Test
 -   Next, I perform a falsification test by running a random implementation model to determine whether the observed effect occurs purely by chance.
 -   To execute this model, I randomly apply the policy change treatment to 23,088 zip code-months, then regress the log of crime incidents on this “pseudo”-treatment, store the coefficient, and replicate the analysis 1,000 times before comparing the outcome of the actual treatment against the pseudotreatments.
 -   The results show that it is unlikely that the coefficients and effect sizes generated from our actual treatment are similar to the ones generated by the pseudotreatments (p < 0.001).
     -   Thus, the observed effect is unlikely to occur purely by chance.
     -   In addition, the estimated placebo coefficient is insignificantly different from 0 in all models, suggesting correlation within the zip code-month has been accounted for.
 

 ### 4.1.4. DID with Propensity Score Matching
 -   To ensure the comparability of the treatment zip codes and the control zip codes, I use propensity score matching (PSM) to construct a matching group of control zip codes, based on observable measures before the implementation of the policies.
 -   After matching, the covariates are quite balanced, with no significant differences between the controlled and treated groups.
 -   I then estimate the same model in Equation (1) on the PSM sample and report the results in Appendix D.
     -   The results are consistent with our main model results.
 

 ## 4.2. Mediating Effects of Airbnb Supply and Occupancy
 

 ### 4.2.1. Policy Impact on Airbnb Supply and Occupancy
 -   To further understand how the policies impact crime incidents, I investigate the impacts of the policies on Airbnb supply and occupancy.
     -   OHOH is expected to reduce the total number of listings.
     -   Similarly, in the case of PR, the total number of listings should also reduce significantly.
 -   With these policies in place, the price and quality of the listings might be impacted as well.
 -   To estimate these impacts, I use the estimation specification in Equation (1) to estimate the impact of the policies on Airbnb supply (Total number of listings, Total number of multilistings, and Total number of single listings), Airbnb total occupancy, and listing quality (Average price per night and Average listing rating).
 -   The DID results (Table 6) show that the total number of listings, total number of multilistings, and total number of single listings significantly reduced after OHOH was put in place (6.8%, 3.9%, and 8.6%, respectively).
     -   And they further reduced by 12.2%, 10.4%, and 13.9% after enacting PR.
     -   The total occupancy of Airbnb listings reduced 12.2% and 21.3% after OHOH and PR, respectively.
 -   Considering these results, I know that the number of guests hosted through Airbnb significantly reduced after the two policies were enacted.
     -   In addition, I see that the quality of listings is higher after the policy implementations (the average rating is 2% after OHOH and another 7.3% higher after PR).
     -   I also find that the average price reduced by 6.8% after OHOH.
 

 ### 4.2.2. Mediating Effects of Airbnb Supply and Occupancy
 -   In order to investigate whether the impacts of the policies are mediated through Airbnb listings and occupancy, I carry out mediation analyses following the procedure suggested by Baron and Kenny [1986].
     -   First, the main results of the study (Table 4) show that the implementations of policy impact crime incidents.
     -   Second, I demonstrated that the implementations of the policies impact the mediators—Airbnb supply and occupancy (Table 6).
     -   Next, I demonstrate that the mediators impact the dependent variables without controlling for the policies (Table 7).
     -   Finally, I regress total crime on both policy implementations and Airbnb supply/occupancy (Table 8).
         -   The results show that when including Airbnb supply or occupancy in the model, the impacts of policy implementations were reduced.
         -   And the impact of Airbnb supply and occupancy on crime is significant in all the models.
         -   Thus, the reduction of crime is mediated through the reduction of Airbnb supply and occupancy.
         -   I also carried out the Sobel test [Sobel 1982, Baron and Kenny 1986], and the test results support the significant mediation effects.
 -   These results suggest that the impact of policy implementations on crime is mediated through Airbnb supply and occupancy through reducing the number of tourists entering residential neighborhoods that may become victims of crimes and attract offenders.
 

 ## 4.3. Heterogeneity Effects
 -   The impact of Airbnb’s self-regulations on criminal activities might be heterogeneous across locations, influenced by the characteristics of zip codes and the surrounding areas.
     -   An extensive body of literature on economics of crime shows an association between crime rate and societal issues such as poverty, social exclusion, limited education, poor employment record, and low legitimate earnings [Becker 1968, Freeman 1999, Raphael and Winter-Ebmer 2001].
     -   Meanwhile, the sharing economy offers significant employment opportunities for the unemployed and underemployed populations [Huang et al. 2020].
 -   Therefore, it is useful to explore the heterogeneous effects of reduction of Airbnb occupancy (resulted from the self-regulations) on crime rates.
 -   To understand the heterogeneous impact of Airbnb occupancy on crime across geolocations, I adapt the concept of spatial heterogeneity and the GWR model.
     -   Spatial heterogeneity refers to the impact of geographical distance on the relationships between predicted and explanatory variables [Mennis and Jordan 2005, Wheeler 2019].
     -   GWR is a widely used spatial regression model that can identify how locally weighted regression coefficients may vary across the study area [Wheeler 2019].
 -   The basic idea of GWR is that when researching variables such as crime rate, we should consider the geographical relationships.
     -   To address this concern, GWR uses a matrix to give weights to the values from other locations in the data set to account for their influences on the focal location and to weight the influences based on geographical distance.
     -   Specifically, the GWR model extends the traditional regression framework by incorporating local parameters so that the model can be expressed as in Equation (3):
         -   Y i  β0 lati, loni( ) +∑nk0βk(lati, loni) × Xik + εi ,i  1, : : : , n; (3)
         -   where (lati, loni) denotes the coordinates of the point i, β0(lati, loni) denotes the intercept value, and βk(lati, loni) is a set of coefficients at point i.
         -   Unlike in the global model, where the coefficient estimates are fixed, this model captures local effects by allowing the coefficents to vary across space.
 -   In addition, to utilize the panel data to provide a better understanding of the impact of Airbnb on crime, I adopt the geographically and temporally weighted regression (GTWR) to account for spatial-temporal nonstationary.
     -   Thus, the GTWR model can be expressed as Equation (5):
         -   ln Crimeit( )  β0 lati, loni, ti( ) +∑nk0βk(lati, loni, t i)× Occupancy itk + εi, (5)
         -   where Crimeit is the number of crime incidents in zip code-month i, β0 is the intercept for zip code-month i (with geo-coordinates (lati, loni), time t i), and βk is the coefficient for Airbnb occupancy of zip code-month i.
 -   I use data from New York City to demonstrate the heterogeneous impact of Airbnb on crime (the distance between each pair of zip codes is calculated using the geo-coordinates of zip codes; therefore, I run this regression in one city, not across multiple cities that are not adjacent).
 -   The results (Table 9) show that Airbnb occupancy in general is positively related to crime incidents.
     -   When we allow the coefficient to vary across zip codes, we observe the variations in coefficients.
 -   To better explore and understand what characteristics of zip codes contribute to such patterns, I use a second-stage regression and regress the coefficients of each zip code on zip code characteristics.
     -   I regress the coefficients on the population density, income level, housing value, unemployment rate, race, and education level of a zip code.
 -   The results (Table 10) show that in populated, higher-earning areas with higher housing values and lower unemployment rates, Airbnb has a higher positive impact on crime, whereas in areas with less population, lower income, and higher unemployment rates, Airbnb might reduce crime activity.
 

 ## 4.4. Moderating Effects of Population, Income, and Housing Value
 -   Following prior IS research, I included additional moderation analyses using the factors identified from the GWR analysis using the following specifications, (6)–(8) in the DID model:
     -   ln Crimecit( )  β1Onehomect × log(Population i) + β2Primary Residencect × log(Population i) + γ′Zit + μt + v i + εcit, (6)
     -   ln Crimecit( )  β1Onehomect × log(Median Housing Value i) + β2Primary Residencect × log(Median Housing Valuei) + γ′Zit + μt + vi + εcit, (7)
     -   ln Crime cit( )  β1Onehomect × log(Median Household Incomei) + β2Primary Residencect × log(Median Household Incomei) + γ′Z it + μt + v i + εcit: (8)
 -   The results (Table 11) show that population, median household income, and median housing value moderate the impact of policy implementation, such that in areas with higher population, household income, and housing value, the total crime reduces more after the implementations of policies.
     -   These results are consistent and complement the findings of GWR models.
 

 # 5. Discussion and Conclusions
 

 -   Home sharing has contributed to the local economy and helped millions gain additional income, yet little is known about the societal spillover effects of home sharing.
 -   I attempt to address this gap by empirically investigating the impact of regulations that reduce home-sharing activity on crime incidents.
 -   Using two policy changes that restrict the number of listings in three major cities in the United States as a natural experiment, my DID estimation provides evidence that, in general, reduced home-sharing activities reduce criminal activities.
 -   I use a multitude of additional specifications and robustness tests to cross-validate the results, including a time relative model, a falsification test with random implementation models, and a DID with a propensity score-matching method.
     -   All models support the findings of the main DID specification.
 -   To demonstrate the mechanisms of the policy impacts, I analyze the impact of the new regulations on Airbnb supply and occupancy.
     -   The total number of Airbnb listings and total guest occupancies mediate the policy impact.
     -   Interestingly, I also find that the ratings of the listings improved after the implementation of the two policies.
     -   This result suggests that when home sharing is truly “sharing” of homes, rather than commercial listings that are unofficial hotels operating without proper security and management on site, the quality of service will be higher and will induce fewer safety risks.
 -   It is likely that the impact of home-sharing’s regulations will be heterogeneous, depending on neighborhood characteristics.
     -   Therefore, I examine the heterogeneous impacts of the reduction of Airbnb occupancy on crime.
     -   To better understand how the effects vary across neighborhoods, I use the GWR model.
     -   The ability to visualize how the relationships change on a map when using geo-coordinates enhances the comprehension of research findings.
     -   The results of this analysis indicate that in populated, higher-income areas with higher property values, Airbnb has a higher positive impact on crime.
     -   By contrast, in areas with less population, lower average income, and lower housing values, Airbnb activities negatively impact crime incidents.
 -   In most cities worldwide, regulations have yet to catch up with the sharing economy; thus, the industry largely relies on platform self-regulation.
     -   Our study provides unique insights into the effect that the sharing-economy platform's self-regulation can improve social welfare by reducing crime.
 -   To this end, my study contributes to the budding literature in the area of regulations in the sharing economy and provides empirical evidence to inform ongoing policy debates.
     -   Our results in this study show that well-thought-out regulations can reduce negative spillover effects of the sharing economy, ensure the safety of those who use the economy, and increase consumers' welfare.
     -   In addition, our results regarding the heterogeneous impacts of Airbnb on crime provide nuanced insights for policy makers.
     -   For example, regulations restricting home sharing in some areas of a city, taking into consideration neighborhood characteristics, might be beneficial.
 -   This research makes a valuable contribution to methodology in IS research on geographic IS.
     -   I am among the first in the IS area to explore the heterogeneity effects leveraging GWR, and I hope this work can pave the way for future work, not only in the sharing economy but also in areas such as mobile commerce, location-based advertising, and ubiquitous computing, to better account for dependency characteristics when considering spatial analysis.
 -   Our work has several limitations, some of which can serve as fruitful areas for future research.
     -   First, although our empirical testing demonstrates an absence of unaccounted-for heterogeneity before implementing the policies, it is important to acknowledge that our findings are not based on a completely randomized trial.
     -   Second, to the degree that limited information is available about the Airbnb hosts and guests involved in criminal acts, we are unable to tell what populations are influenced to the greatest extent based on various demographics—age, gender, race, and socioeconomic status.
     -   Finally, the results of this work are based on the analyses of six large and representative cities in the United States, and this work, to a large degree, resolves the data limitation noted by Greenwood and Wattal [2017] and Park et al. [2021].
     -   However, future research could use similar measures based on our study to test such relationships in other cities and states.
 

 # Executive summary of 1. Introduction
 -   The sharing economy has disrupted industries, sparking debates on regulation versus self-regulation.
 -   Home-sharing platforms like Airbnb face scrutiny regarding competition, housing prices, and safety.
 -   This research examines the societal impact, particularly crime rates, of home-sharing platform self-regulations (OHOH and PR) using a difference-in-difference approach.
 -   It seeks to answer:
     -   Do self-regulations impact crime rates?
     -   How do economic factors moderate this relationship?
     -   What factors mediate the effect?
 -   It leverages crime pattern theory and routine activity theory to understand how reduced Airbnb listings impact crime.
 

 # Executive summary of 2. Related Literature
 -   Research on the sharing economy focuses on its impact on traditional industries, the economy, and society.
 -   Studies highlight the effects on competing businesses (e.g., hotels) and the economic environment (e.g., entrepreneurship, employment).
 -   There's growing literature on the sharing economy's societal impact, including both positive (e.g., reduced drunk driving) and negative effects (e.g., discrimination, crime).
 -   The debate on regulations involves whether to promote self-regulation or government intervention to address negative externalities.
 -   Prior research in criminology links crime to environmental factors and space features, using theories like rational choice, crime pattern, and routine activity theory.
 

 # Executive summary of 3. Research Methodology
 -   The study investigates the impact of Airbnb's self-regulation policies on crime incidents.
 -   It uses a natural experiment based on "one host, one home" (OHOH) and "primary residency" (PR) policies in select cities.
 -   The identification strategy hinges on policy changes that reduce Airbnb listings and guest numbers but are unrelated to crime.
 -   Data from multiple sources is combined:
     -   Incident-level crime reports from police departments in six cities
     -   Property-level Airbnb data from a third-party business intelligence company
     -   Economic and demographic variables from various government agencies.
 -   Control cities (Los Angeles, Seattle, and Boston) are selected based on their similarity to treatment cities.
 

 # Executive summary of 4. Analyses and Findings
 -   A two-treatment DID estimation shows that OHOH and PR policies reduced overall crime, assault, robbery, and burglary in affected zip codes.
 -   However, theft incidents increased, potentially due to more shared homes.
 -   A relative time model confirms the parallel trend assumption.
 -   Falsification tests indicate the observed effects aren't purely by chance.
 -   Propensity score matching (PSM) ensures comparability between treatment and control groups.
 -   Airbnb supply and occupancy mediate the policy impact on crime.
 -   Geographically weighted regression (GWR) reveals that the impact of Airbnb occupancy on crime varies geographically.
 -   Population, income, and housing value moderate the policy impacts.
 

 # Executive summary of 5. Discussion and Conclusions
 -   The study empirically investigates the impact of regulations reducing home-sharing activity on crime.
 -   Using a difference-in-difference (DID) estimation, the results suggest that reduced home-sharing activities generally reduce criminal activities.
 -   The total number of Airbnb listings and total guest occupancies mediate the policy impact.
 -   The GWR model reveals that the impact of Airbnb occupancy on crime varies depending on neighborhood characteristics.
 -   This research contributes to the literature on regulations in the sharing economy and provides empirical evidence to inform policy debates.
</details>

```
title: When Algorithmic Predictions Use Human-Generated Data: A Bias-Aware Classification Algorithm for Breast Cancer Diagnosis
authors: Mehmet Eren Ahsen, Mehmet Ulvi Saygi Ayvaci, Srinivasan Raghunathan
journal: Information Systems Research
published: 2019
```

# Executive Summary

*   This research investigates the design and value of a **bias-aware linear classification algorithm** for breast cancer diagnosis, where the algorithm utilizes human-generated data.
*   The core **theoretical** framework revolves around how **algorithms** that use data generated by humans inherit **biases**, thereby affecting their performance. The study proposes a **linear classifier** that accounts for **bias** in the input data, specifically focusing on the context of **breast cancer diagnosis**.
*   The study's main **finding** is that a **bias-aware algorithm** can eliminate the adverse impact of **bias** if the error in the mammogram assessment due to radiologist's **bias** has no variance. However, in the presence of error variance, the adverse impact of **bias** can be mitigated, but not eliminated, by the **bias-aware algorithm**.
*   The study argues that the **optimal bias-aware algorithm** assigns less (more) weight to the clinical-risk information (radiologist’s mammogram assessment) when the ==mean error== increases (decreases), but the reverse happens when the ==error variance== increases.
*   The study reveals scenarios where it might be better not to use clinical-risk information if it biases the radiologist's assessment.
*   Using data and point estimates obtained from mammography practice and medical literature, the **bias-aware algorithm** can significantly improve the expected patient life years or the accuracy of decisions based on mammography.
- The algorithm adjusts the weights assigned to **clinical-risk information** and **mammogram assessment** based on the **mean error** and **error variance** due to bias.
- Using data from **mammography practice** and the **medical literature**, we demonstrate that the bias-aware algorithm can significantly improve the **expected patient life years** or the **accuracy of decisions** based on mammography.

#Algorithms #Bias #BreastCancerDiagnosis #Classification #DecisionSupportSystems #Mammography #MedicalDecisionMaking #CognitiveBiases #LinearClassifier #ClinicalRiskInformation

<details>
  <summary>Click to expand sections</summary>
	
# 1. Introduction

*   **Algorithms** are increasingly used in decision-making across various domains, but they can be susceptible to human **biases** when the input data is human-generated [Agarwal and Dhar 2014].
*   Algorithms using human-generated decisions as inputs can inherit and even exacerbate **biases** [Coiera 2015, Barocas and Selbst 2016].
    *   This situation is seen in areas like loan approvals, job hiring, and law enforcement [Pasquale 2015].
	*   **Algorithms** that ignore **bias** may provide predictions that suffer from limitations akin to those provided by human beings, potentially worsening the errors [Coiera 2015, Barocas and Selbst 2016].
*   The study aims to design an **algorithm** that accounts for **bias** in input data, particularly in the context of a **clinical decision support system (CDSS)** for **breast cancer diagnosis**.
	*   The **CDSS** is a tool to help referring physicians make informed decisions based on **mammography**.
	*   This approach aligns with integrating **information systems (IS)** research methods and **behavioral economics** to address issues and inform **design science research** [Goes, 2013].

## 1.1. Role of Bias in Breast Cancer Diagnosis

*   In **breast cancer diagnosis**, referring physicians use radiologists' assessments, patient clinical-risk information, and patient preferences [Ayvaci et al. 2018].
*   Radiologists provide probabilistic risk assessments based on **mammogram** findings, often considering the patient's clinical-risk information.
*   The impact of clinical-risk information on radiologists’ assessments is debated; some argue it improves accuracy, while others suggest it may bias the radiologist [Loy and Irwig 2004, Elmore et al. 1997].
*   The radiologist’s assessment could be biased by the patient’s clinical-risk information [Carney et al. 2012].
	*   Undue influences resulting from radiologists’ cognitive **biases** may affect the performance of the referring physician.
*   A **CDSS** can be a valuable tool for referring physicians by helping them make recommendations on follow-up actions.
	*   An important component of such a **CDSS** is the **classification algorithm** that uses the **clinical-risk information** and **mammogram** assessment to predict the likelihood of cancer.
*   The study addresses three key research questions:
    *   What is the optimal design of a linear classification algorithm in the presence of radiologist **bias**?
    *   How does the **bias** affect the **algorithm’s** performance and design?
    *   Should the **clinical-risk information** be used at all in the diagnostic process given its potential to **bias** the radiologist?
*   The contributions of this research are:
    *   A new approach to designing a **bias-aware classification algorithm** and analyzing the impact of **bias** on the algorithm and its performance, which is new to the literature.
    *   Quantifying the value of **bias-aware algorithms** in the **breast-cancer-diagnosis** context.

# 2. Related Literature

*   The study is related to literature on cognitive **biases** in medical decision making, the design of **decision support systems (DSS)**, and mathematical modeling of **decision biases**.

## 2.1. Cognitive Biases in Radiological Diagnosis

*   The presence of **clinical-risk information** is critical in **breast-cancer-diagnostic** performance and may reflect features of various types of **biases**.
*   Three common **biases** are **anchoring**, confirmation, and availability, which occur when synthesizing information for medical decisions [Ogdie et al. 2012].
    *   **Anchoring bias**: The human tendency to overvalue a single piece of information.
	    *   In radiology, the radiologist may be anchored by the clinical history when assessing the radiographic image [Lee et al. 2013, Alpert and Hillman 2004].
	    *   To mitigate the **anchoring effect**, it has been suggested that radiologists look at the image first [Griscom 2002].
	*   **Confirmation bias**: The decision maker looks for confirming evidence to bolster an early assessment, rather than trying to disprove it.
	    *   An early judgment based on the patient’s **clinical-risk information** may induce a radiologist to focus on **mammogram** features consistent with the initial impression and ignore the features that conflict with it [Wallsten 1981].
	    *   **Confirmation bias** relates to a radiologist’s interpretation of findings in support of prior conclusions, while **anchoring** relates to overreliance on a single piece of information, the **clinical-risk information**.
	    *   **Confirmation bias** may amplify the **anchoring effect** in diagnostic decisions [Croskerry 2003].
    *   **Availability bias**: A person overestimates the probability of an event that comes immediately to the person’s mind.
	    *   The **clinical-risk information**, when available at the time of imaging interpretation, may nudge the radiologist to be more suspicious of any findings on an image [Eraker and Politser 1982].
	    *   **Availability bias** can occur when a person overestimates the probability of an event that comes immediately to the person’s mind.
	    *   Mamede et al. (2010) found that medical residents were susceptible to **availability bias**.

## 2.2. Related IS Research

*   The existing literature on **classification** under noisy data focuses mainly on the development of expert systems where decision rules are learned from training data [Hong and Tsang 1997, Wu et al. 2003, Saar-Tsechansky and Provost 2007].
    *   Researchers have developed input modification methods to eliminate the negative effects of noise in training data [Mookerjee 2001, Jiang et al. 2005].
*   A substream of the classification literature focuses on discriminating classes under strategically manipulated data [Dalvi et al. 2004].
    *   Researchers proposed methods for optimal classification [Boylu et al. 2010] or for approximate solutions [Boylu et al. 2007].
*   The study’s approach differs from previous studies by:
    *   Explicitly modeling the source of noise as human **biases** rather than strategic agents.
    *   Decomposing the source of noise into systematic and random parts.
    *   Providing theoretical insights into how input **bias** affects **algorithm** design and performance.

## 2.3. Related Decision Analytic Work

*   The **decision analysis** and operations management community is examining problems related to the mathematical modeling of **decision biases**.
    *   An optimization-based approach was proposed to determine the weights for biased quantile judgments [Bansal et al. 2017].
    *   Research has found that **bias** can be beneficial in coordinating the firms’ decisions [Li et al. 2017].
    *   A machine-learning mechanism was developed to alleviate overconfidence **bias** and the overfitting problem while aggregating forecasts [Grushka-Cockayne et al. 2016].
*   The study takes a prescriptive approach and studies how the **algorithm** should be designed to optimally aggregate information and make recommendations in the presence of biased data.

# 3. Model Description

*   The model considers a patient with an unknown true health status and a radiologist assessing the **mammogram** to determine the presence or absence of cancer.
*   The radiologist has access to the patient’s **clinical-risk information**.
*   Presence or absence of cancer is indicated using labels + and −, respectively.
*   The true (unbiased) risk implied by the patient’s **mammogram** (imaging) and the true risk implied by the patient’s **clinical-risk information** are denoted as xi and xc, respectively.
    *   Conditional on the true health status of the patient, xi and xc follow a bivariate-normal distribution.
*   Under **bias**, the radiologist’s estimate, ˆxi, deviates from xi.
    *   The error introduced by **bias** is a random variable that follows a probability distribution.
*   The mean error, β(xc − ¯xc), depends on:
    *   How much xc deviates from its population mean, ¯xc, which serves as the anchor.
    *   The **bias** factor β ≥ 0, which measures the radiologist’s inherent **bias** level.
*   σ0 captures the variability in the error introduced by **bias** [6].
    *   β  0 and σ0  0 correspond to the unbiased assessment of xi.
*   Given a biased assessment from a radiologist, the tasks of the **classification algorithm** (hereafter, **bias-aware algorithm**) are to (i) aggregate ˆxi and xc and (ii) determine a threshold k for the aggregated risk to classify the instance as + or −.
*   The aggregate information, r, is defined as:
    *   r : (1 − α) ˆxi + αxc ,
    *   where α denotes the weight assigned to xc, and 1 − α denotes the weight assigned to ˆxi.
*   The study focuses on exploring the role of **bias** in the design and performance of the **bias-aware algorithm** and not the ability of either type of risk information in discriminating the + cases from the − cases.
*   The following definitions are also used:
    *   I(α, β, σ0)  (μc − μn)/σ as the discriminative ability of r.
    *   ∆i  μci − μni and ∆c  μcc − μnc, respectively.
    *   h : I(0, 0, 0) / I(1, 0, 0)  ∆i / ∆c
    *   t : (UTP − UFN)/P(−) / (UTN − UFP)/P(+)  UTP − UFN / UTN − UFP · P(+) / P(−)

# 4. Theoretical Analysis

*   The analysis explores the optimal **bias-aware algorithm** based on the AUC and the expected utility objectives.
*   It examines how **bias** affects **algorithm** performance and quantifies the impact of ignoring **bias**.
*   The analysis identifies conditions under which it is suboptimal to use the **clinical-risk information** given that it can **bias** the radiologist’s assessment.
*   Finally, the study discusses the case when **bias** impacts error mean and error variance proportionally.

## 4.1. Optimal Bias-Aware Algorithm

*   The **optimal weight** and threshold are characterized in Theorem 1:
    *   α∗(β, σ0) : 1 / (1 + σi / σc (h − ρ) / (σ2 / i (1 − hρ) + σ2 / 0 − σi / σc / β(h − ρ)))
    *   k∗(β, σ0) : k(α∗(β, σ0), β, σ0).
*   Key observations from Theorem 1:
    *   Utility parameters only affect the optimal risk threshold and not the optimal aggregation weight.
    *   If t  1, the risk threshold is also independent of the utility parameters.
    *   When the radiologist is unbiased such that β  0 and σ0  0, the optimal weight for the **clinical-risk information** reduces to that shown by Winkler (1981).
    *   The optimal weight for the clinical-risk information can be negative depending on the relative discriminatory ability of the two risks, the correlation between them, and the **bias** parameters.
*   Structural analysis of the optimal weight:
    *   α∗(β, σ0) is decreasing in **bias** factor β.
    *   An increase in the error variance (σ0) increases the weight assigned to the **clinical-risk information**.
    *   An increase in the correlation between the **clinical-risk information** and the **mammogram** risk (ρ) decreases the weight assigned to the **clinical-risk information** when the error variance is not too high.
    *   The threshold level for risk to recommend a follow-up is increasing in both **bias** factor and error variance.

## 4.2. Impact of Bias Under the Optimal Bias-Aware Algorithm

*   Proposition 1 characterizes how the **bias** factor, error variance, and other model parameters affect the expected utility and the discriminative ability under the **optimal bias-aware algorithm**.
    *   U∗(β2 , σ0)  U∗(β1 , σ0) < U∗(β1 , 0)  U∗(0, 0),
    *   AUC∗(β2 , σ0)  AUC∗(β1 , σ0) < AUC∗(β1 , 0)  AUC∗(0, 0),
    *   U∗(β, σ0) is independent of β and decreases in σ0, σi, σc, and ρ.
*   According to Proposition 1, (i) and (ii), the expected utility and discriminative ability are (weakly) smaller in the presence of **bias** than in its absence even under the **bias-aware algorithm**.
*   When error variance is zero (i.e., σ0  0), the **optimal bias-aware algorithm** eliminates the negative impact of **bias**.
*   In the presence of a positive error variance (i.e., σ0 > 0), the negative effect of **bias** cannot be eliminated through the **optimal bias-aware algorithm** alone.
*   The optimal expected utility, U∗(β, σ0), is independent of the **bias** factor (and, therefore, the mean error), yet it decreases in the error variance.

## 4.3. Impact of Ignoring Bias in the Algorithm

*   The value of the **bias-aware algorithm** is defined as the optimal utility when the algorithm adjusts for **bias** less the utility when the algorithm assumes that **bias** does not exist.
*   The utility value of the **bias-aware algorithm** is defined as:
    *   V(β, σ0) : U∗(β, σ0) − U(α∗(0, 0), β, σ0 , k(α∗(0, 0), 0, 0)).
*   Proposition 2 characterizes how the **bias** affects the value of the **bias-aware algorithm**.
    *   The **bias-aware algorithm** has (i) V(β, σ0) ≥ 0, and (ii) V(β, σ0) is decreasing in β when β < σ2 / 0 /(σc σi · (h − ρ)) and increasing otherwise.
*   The value does not necessarily increase in the **bias** factor (β).
*   If there is no error variance (σ0  0), then an increase in mean error always increases the value of the **bias-aware algorithm**.
*   When the error variance is not zero, the value increases in the mean error only when the mean error is larger than a threshold.
    *   An increase in mean error mitigates the adverse impact of a large error variance for fixed values of α and k.
*   The interaction between the mean error and error variance due to **bias** is critical in determining the value of the **bias-aware algorithm**.

## 4.4. Should the Clinical-Risk Information Be Used Under Radiologist Bias?

*   The adverse impact of mean error alone due to **bias** can be eliminated, but an increase in the error variance diminishes the usefulness of the **clinical-risk information**.
*   The social planner can consider two possible alternatives:
    *   Use the **clinical-risk information** but design the algorithm to account for the **bias**.
    *   Not use the **clinical-risk information** at all.
*   Proposition 3 characterizes when the **clinical-risk information** should be available in the system despite the possibility that it may **bias** the radiologist.
    *   If h ≥ 1 and 1 / h − √(h2 − 1)σ2 / 0 / σ2 / i < ρ, then U∗(β, σ0) < U(0, 0, 0, k(α∗(0, 0), 0, 0)); otherwise, U∗(β, σ0) > U(0, 0, 0, k(α∗(0, 0), 0, 0)).
*   Insights from Proposition 3:
    *   Even when the **clinical-risk information** is informative on its own, not using it in the whole process may be better than using it.
    *   A high-enough correlation will cause the **clinical-risk information** to be not useful.
    *   An increase in the error variance (σ0) enlarges the region in the parameter space where not using the **clinical-risk information** is better than using it.
    *   When a diagnostic task is based on data derived from human experts susceptible to cognitive **biases**, the error variance induced by **bias** is a key factor to consider.

## 4.5. Joint Influence of Bias on Both the Mean Error and Error Variance

*   The baseline model assumes the radiologist’s **bias** influences the mean error and error variance in **mammogram** assessment independently.
*   Assuming that a shift in the **bias** factor has a proportional impact on mean error and error variance, the study models error due to **bias** conditional on **clinical-risk information** as ˆxi − xi | xc ∼ N (β(xc − ¯xc), βσ0).
*   Theorem 2 in Online Appendix B provides the optimal weight and risk threshold under the new model.
*   Proposition 4 suggests that when mean error and error variance are proportional, an increase in the **bias** factor always hurts the **optimal** expected utility or discriminative performance unless there is no error variance.
    *   U∗(β2 , σ0) < U∗(β1 , σ0) < U∗(β1 , 0)  U∗(0, 0),
    *   AUC∗(β2 , σ0) < AUC∗(β1 , σ0) < AUC∗(β1 , 0)  AUC∗(0, 0).
*   The main additional insight from the proposition is that when the **bias** factor influences both the mean error and error variance, the **bias-aware algorithm** alone cannot completely eliminate the adverse impact of **bias**.

# 5. Design and Value of the Bias-Aware Algorithm for Breast Cancer Diagnosis: A Computational Experiment

*   The study uses a **breast-cancer-outcomes database** based on **clinical-risk information** and the medical literature.

## 5.1. Parameter Estimation

*   The study uses the **Breast Cancer Surveillance Consortium (BCSC) database** to estimate the parameters of the **clinical-risk distributions**.
*   The parameters for the clinical-risk distributions are μpc  2.4042, μnc  2.1900, σpc  0.3656, and σnc  0.3869, and the indicated AUC of the clinical-risk information (AUCc) is 0.656.
*   The parameters for the **mammography** distributions are imputed using the performance benchmarks reported in the medical literature.
*   Three different AUC values for the **mammography** risk are selected to represent low (AUCi  0.780), moderate (AUCi  0.820), and high (AUCi  0.890) discriminative ability.
*   The correlation between **mammogram** and **clinical-risk information**, ρ, is estimated as 0.0548 using Spearman’s rank correlation.
*   The study estimates the disutility as the life years lost, following the medical literature.

## 5.2. Optimal Bias-Aware Algorithm: Aggregation Weights and Decision Threshold

*   For the prevailing **clinical-risk** model with an approximate AUC of 0.656 and an average-quality **mammogram** with an AUC of about 0.820, the **clinical-risk information** should carry a relative weight of approximately 24% and the **mammogram** risk should carry a relative weight of 76% under no **bias**.
*   Under no **bias**, a follow-up should be recommended if the weighted risk score exceeds a value of 2.62.
*   The **optimal weight** on the **clinical-risk information** (mammogram risk) generally decreases (increases) when either **bias** factor (β) increases or error variance (σ2 / 0 ) decreases.
*   When both **bias** factor and error variance are sufficiently high, it is optimal to use a larger weight for the **clinical-risk information** under **bias** than under no **bias**.
*   An accurate estimation of **bias** parameters is essential for the **optimal design** of a **bias-aware algorithm**.
*   An increase in any **bias** parameter only increases the threshold.

## 5.3. Impact of Radiologists’ Bias on Breast-Cancer-Diagnosis Outcomes

*   The impact of radiologists’ **bias** is quantified as the reduction in expected life years because of the presence of **bias**.
*   When the accuracy of the **mammography** is moderate (i.e., AUCi  0.820), for the prevailing **clinical-risk** models with AUCc  0.656, the presence of various levels of **bias** could result in a reduction in the expected life years for all patients ranging from 8.00 to 119.69.
*   The adverse impact of **bias** increases as the mean error or error variance due to **bias** increases.
*   The negative impact of **bias** is higher if the **mammogram** is more accurate.
*   A reduction in AUC from 0.837 to 0.831 translates into an additional 237,900 misdiagnoses of patients’ health.
*   Appropriate mechanisms to eliminate or mitigate the **bias** should be adopted.

## 5.4. Value of a Bias-Aware Algorithm for Breast Cancer Diagnosis

*   The value of a **bias-aware algorithm** is examined using the percentage of lost expected life years recovered by accounting for **bias**.
*   The no-**bias** case (β  0 and σ0  0) results in the maximal expected life years.
*   When there is no error variance, σ0  0, the **bias-aware algorithm** is able to recover 100% of the loss incurred by a **bias-blind algorithm**.
*   The value of a **bias-aware algorithm** diminishes when either the mean error or error variance increases, but the value can still be substantial.
*   Mitigating the impact of clinical-risk-information-induced **bias** through a **bias-aware algorithm** alone is likely to be challenging when the radiologist’s **bias**-related behavior is highly unpredictable.

## 5.5. Should the Clinical-Risk Information Be Used for Breast Cancer Diagnosis?

*   Not using the **clinical-risk information** for diagnosing **breast cancer** is sometimes better than using it if it will **bias** the radiologist.
*   The thresholds for the mean error or error variance due to **bias** above which using the **clinical-risk information** leads to an inferior expected utility or AUC are shown in Table 2.
*   The critical role played by the relative discriminative ability of the **clinical-risk information** and **mammogram** in decisions concerning the use of **clinical-risk information** for cancer diagnosis is emphasized.

## 5.6. Impact of Bias When the Accuracy of Clinical-Risk Information Improves

*   As the AUC of **clinical-risk information** increases, the percentage of loss that can be recovered by accounting for **bias** decreases.
*   Correcting for the detrimental effects of **bias** is more difficult at higher **clinical-risk information** AUC values.
*   **Bias** becomes less of an issue and a **bias-aware algorithm** becomes less valuable as the discriminative ability of the **clinical-risk information** improves relative to that of the **mammography**.

# 6. Discussion and Conclusion

*   When algorithms use human-generated input data that suffer from human **biases**, the predictions they generate may exacerbate the errors stemming from such **biases**.
*   The **optimal bias-aware algorithm** can eliminate the adverse impact of **bias** if there is no variability associated with the **bias**-induced error in the radiologist’s assessment.
*   The optimal **bias-aware algorithm** assigns a smaller (larger) weight to the **clinical-risk information** (**radiologist’s mammogram** assessment) when the mean error increases, but the reverse happens when the error variance increases.
*   The **bias-aware algorithm** can significantly improve the expected patient life years.
*   The magnitude of improvement depends critically on the relative discriminative abilities of **clinical-risk information** and **mammogram**.

## 6.1. Translating the Findings Into Clinical Practice

*   Realizing the gains indicated by the study depends on:
    *   Finding ways to incorporate proper weighting of **clinical-risk information** and **mammogram** information.
    *   Reducing, eliminating, or properly adjusting for the **bias** due to **clinical-risk information**.
*   The referring physician should use a decision support system (DSS) that accounts for the unintended over- or underassessment of risk because of the available information.
*   One challenge is that the radiologists a physician deals with could be biased to different degrees, both in terms of **bias** factor (i.e., mean error) and error variance.
*   The relative simplicity of the model makes it possible to incorporate the model into a decision-aid tool.
*   The referring physician’s attitude toward its predictions is another issue to consider.

## 6.2. Future Directions

*   The model can be extended to a general scenario with n attributes and m classification outcomes.
*   Nonlinear aggregation models can provide additional insights into the impact of **bias**.
*   Patient-level **mammography** data would provide better estimates.
*   Estimating the **bias** parameters requires extensive well-designed experiments.
*   The model should be validated by implementing it in a **CDSS** in practice and comparing the actual results with the model predictions.

# Executive summary of 1. Introduction

*   **Algorithms** are increasingly used in decision-making and are prone to human **biases** when they use human-generated data.
*   The study focuses on designing a **bias-aware algorithm** for use in a **CDSS** for **breast cancer diagnosis**.
*   The research aims to answer three key questions about the design and impact of a **bias-aware algorithm** in the context of **breast cancer**.

# Executive summary of 2. XXX (Section 2)

*   The study is related to the literature on cognitive **biases** in medical decision making, the design of **DSS**, and mathematical modeling of **decision biases**.
*   The **anchoring**, confirmation, and **availability biases** can affect **radiological diagnosis**.
*   The study’s approach differs from previous studies by explicitly modeling the source of **bias** as human cognitive flaws.
*   The study takes a prescriptive approach and studies how the **algorithm** should be designed to optimally aggregate information in the presence of biased data.

# Executive summary of 3. Model Description

*   The model considers a patient with an unknown health status and a radiologist assessing a **mammogram** and access to **clinical-risk information**.
*   The error introduced by **bias** is a random variable and a function of a **bias** factor and error variance.
*   The study focuses on exploring the role of **bias** in the design and performance of the **bias-aware algorithm**.
*   The study defines aggregate information, r, and the weight assigned to **clinical-risk information** and **mammogram**.

# Executive summary of 4. Theoretical Analysis

*   The analysis explores the optimal **bias-aware algorithm** based on the AUC and the expected utility objectives, focusing on how **bias** affects **algorithm** performance.
*   The **optimal algorithm**'s characteristics are presented, with key observations.
*   It shows how bias affects utility and discriminative ability and the impact of ignoring **bias**.
*   It also identifies the conditions under which it is suboptimal to use the **clinical-risk information** given that it can bias the radiologist’s assessment.
*   It discusses the impact of both the mean error and the error variance.

# Executive summary of 5. Design and Value of the Bias-Aware Algorithm for Breast Cancer Diagnosis: A Computational Experiment

*   The study uses a **breast-cancer-outcomes database** based on **clinical-risk information** and the medical literature to perform a computational experiment.
*   The parameters for the clinical-risk and mammography distributions are estimated.
*   The impact of radiologists’ **bias** on breast-cancer diagnosis outcomes is quantified.
*   The value of a **bias-aware algorithm** for **breast cancer diagnosis** is examined.
*   The study discusses whether **clinical-risk information** should be used and the impact of **bias** on increasing the accuracy of the **clinical-risk information**.

# Executive summary of 6. Discussion and Conclusion

*   The study examines the design and value of a **bias-aware algorithm** for use in a **CDSS** for **breast cancer diagnosis**.
*   The **optimal bias-aware algorithm** can eliminate the adverse impact of **bias** if there is no variability associated with the **bias**-induced error.
*   The **optimal bias-aware algorithm** assigns a smaller (larger) weight to the **clinical-risk information** (**radiologist’s mammogram** assessment) when the mean error increases, but the reverse happens when the error variance increases.
*   The **bias-aware algorithm** can significantly improve the expected patient life years.
*   The findings can be translated into clinical practice, which involves a proper weighting of **clinical-risk information** and **mammogram** information, and reducing, eliminating, or properly adjusting for the **bias** due to **clinical-risk information**.
*   Future research directions are also suggested.
</details>
