**Introduction:**

The purpose of this research is to advance the use of geographic information system (GIS) mapping to produce a burden of disease map by estimating and validating the use of Bayesian spatiotemporal methods compared to the use of Kriging method and Inverse Distance Weighted (IDW) algorithm.  To achieve this research goal of allowing for more accurate models will increase the effectiveness of combating the spread of the Human Immunodeficiency Virus (HIV).  I will achieve this goal through the following objectives. 

1. Use various methods of estimation to achieve the goal of locating and implementing measures to slow the spread of HIV. 

2. Use survey and census data to estimate a model to predict the burden of HIV and the spatial variability of the disease across Sub-Saharan Africa.

**Human Development Topic:**

Human Immunodeficiency Virus (HIV) is the leading cause of disease burden in Sub-Saharan Africa with 28.5 million people living with HIV as of 2006 (Mboup et. al, 2006).  As a leading cause of morbidity and mortality it has turned into an epidemic. With machine learning techniques epidemiologist has been able to take an technological advanced method to combat this problem. Yet, lack of data in low income and developing countries in Sub-Sahara Africa, can create gaps and problems for the allocation of resources. In terms of Amartya Sens definition of human development: More productive way to allocate resources would enhancement of human capabilities, such as peoples health which in return would allow for the capabilities to be used for opportunities such as a better jobs.  This can be shown as the enhancement of freedoms that are stripped by HIV such as the freedom to have a healthy life.  With this research is on the premise of trying to achieve sustainability development goal 3 of promoting good health and well being.  Reaching this goal is crucial in the development of humans throughout the Sub-Saharan Africa region by allowing those population to have the quality of health allowing enhances their ability to develop in other aspects. 

**Human Development Process:**

Human Immunodeficiency Virus (HIV) has a huge presence in Sub-Saharan Africa.  Sub-Saharan has networks just like that of other countries based on the sexual networks and social networks that people maintain.  With the highest rates of HIV spreading occurring from either sexual intercourse, through childbirth, and through the sharing of needles (such as through the use of drugs).  These social networks allow for transmission of HIV rapidly through areas with poor healthcare system, sexual education, and high rates of drug use.  These factors identify how HIV could be a huge burden in the less developed countries and regions, such as Sub-Saharan Africa. In low developed areas the deficit of social services cause for a higher chance for disease and like HIV.  

Development of the situation started with trying to find a way to cure and/or treat HIV and stopping the spread of disease.  The process got first addressed through the steps of sexual education to stop the spread, in location that had the resources to to hold courses.  Next there was the development of antiretroviral therapy (ART), which is a lifelong treatment has been successful at managing the disease.  The problem that arises from it is that only about 40% of eastern and central Africans (a good portion of Sub-Saharan Africa) actually receive treatment (Dwyer-Lindgren, 2019).  This is due to the poverty that leads to limited access to good healthcare.  Crucial things such as test for HIV, antiretroviral therapy, and knowledge about safe sex practices.   Usually in areas of higher population density there consists of more social networks, which in return allows for an enabler for HIV to strive.  This can be shown to be hot spots for HIV and areas where less density appears can be associated with lower rates of HIV to be cold spots.  Through this you can see how this is a complex system of development due to the different the factors that are at play.  Thinks such as the healthcare on system which not all people are about to obtain.  It a hard problem to solve with the factors of economics that also arises from developing countries.  In *Mapping the spatial variability of HIV infection in Sub-Saharan Africa*, the authors write, 

​		"Under the premise that in a resource-constrained environment such as Sub-Saharan Africa it is not 		possible to do everything, to everyone, everywhere, detailed geographical knowledge about the HIV 		epidemic becomes essential to tailor programmatic responses to specific local needs." (Cuadros et.al, 		2017)

This quote expresses how it isn't possible to collect all the knowledge about the epidemic on the ground in such a "resource-constrained environment." This can be seen by how it is hard for government and researchers to gather information in a uniform fashion.  The quote expresses how the process of data science are key for that of human development in areas like Sub-Saharan Africa, that are challenged by disease burden such as HIV.  Showing how data science is an essential in aiding in developing solutions to this epidemic. 

In another study, researchers wanted to look at the extend that GIS has been used in on the topic of HIV.  Their search found 773 unique articles that spoke to the extent that data science methods have been used in the research of HIV.  The article spoke to the role that GIS plays, *Boyda et al.* wrote 

"Our findings demonstrate the wide array of spatial approaches to HIV-related data. These applications include characterizing geographic distribution of HIV, evaluating HIV epidemiologic risk factors, and assessing and improving implementation of HIV services" (Boyda et al., 2019).

Their results of the range of different ways that GIS were that of many.  With implication of data science methods researchers could look at different players in the development field such as:  distribution of HIV over geographic regions, evaluating epidemiology risk associated, and that of improving the allocation of HIV services.  All these different dimensions of the human development problem all being attacked collectively with machine learning techniques.   



**Geospatial Data Science Methods**

The first big approach was that of a more classical method called the Estimation and Projection Package (EPP).  This is an approach forces on estimating and projecting HIV prevalence in countries with epidemic outbreak.  It uses indicators to be able to define and model a national epidemic in terms of focusing in on local sub-epidemics and also of four key epidemiology parameters used to create a curve to produce the trends.  The limitations that this methods faces is that it is limited to the quality of data supplied, such as that of sex workers, or injecting drug users are not in data sets.  With the use of data sets such of that of local community surveys to be used for entry in this program (Ghys, 2004).

There are many different geospatial data science methods that are used in the overcoming of these challenges for human development.  The machine learning methods that are used 

Two key interpolation techniques methods are: 

1) The Inverse Distance Weighted (IDW) Algorithm 

2) Kriging Function 

The Inverse Distance weighted Algorithm can be applied through the assumption that each measured point in a data set had local influence on unmeasured locations. Doing this by assigning more weight to locations around the prediction location then those further away.  It uses cross-validation to be able to select an optimal power calculate the lowest mean prediction error. Similarly, the Kriging Function uses mathematical models based on distance decay to predict unmeasured areas.  It does this through using probabilistic statistical techniques and autocorrelation to be able to quantify points around the the given point based on a mathematical function called semivariogram.  In a study conducted to compare and contrast the two different methods, it was found that Kriging was best year to year compared to within a year. With the hypothesis of the Kriging methods being superior to that of the IDW, they actually found that the IDW performed robustly in small sample sizes in that of located measured points year to year.    (Kalipeni, E., 2008). 

In a study done by *Dwyer-Lindgren, L. et al*., they looked at how HIV spatial variation had been looked at individual countries but no high spatial resolution across the continent had been investigated. To look across the 5-km x 5-km resolution of Sub-Saharan Africa, They used the data sets such as geolocated database surveys in 41 countries along with 9,9794 sites of antenatal care clinics across the continent.  With this data they used adapted Bayesian spatiotemporal methods to analyze the data to produce gridded estimated of HIV, thus being able to make raster maps for ease of viewing and breaking down data.  They are able to do this through the same idea of of that of the kriging function that uses mathematical methods  while using weights to determine values from that of the overall spatial configuration.  (Dwyer-Lindgren et al., 2019). Bayesian methods is a version of Kriging but differs by accounting for the error introduced by estimating the underlying semivariogram.  These Bayesians methods are also that of a bottom up approach  (Esri). 

 Another study done by *Alegana et al*., they use Bayesian methods to be able be able to map the proportion of under 5 years in Nigeria.  Through using this bottom up approach they used  3 sets of data, with the biggest one being from the DHS.  They used these known stratified data points and were able to use the Bayesian method with covariates to be able to model that proportion of the population.  In the process of doing this they were able to take that raw data and estimate approximately  the proportion throughout the whole country.  This shows the power that Bayesian methods hold in that of such raw data sets.  It shows how the same is applicable for looking at that of quantifying population that could be at HIV or that of mapping interventions to such problems (Alegana, 2015)  

**Discussion/Analyze **

As seen above data science has been very promising and has led to many success in human development, but things still stay in the way of development.  How one author put it is: 

​		"Demographic data come from different sources: censuses, civil registration systems, governmental or 		non-governmental administrative data or sample surveys. Civil registration systems provide the most 		reliable and useful demographic data as they continuously record information on the population of a 		country, including their spatial distribution. However, up-to-date registration systems only exist in a 		small number of countries. Instead, censuses are conducted approximately every 10 years by national 		statistical offices in order to provide consistent and geo-referenced population data. The accuracy and 		amount of data supplied by national censuses vary considerably from one country to the other. From a 		temporal point of view, (at the time of writing) the most recent census is more than 25 years old in 		     	    some sub-Saharan countries such as Angola, Eritrea and the Demographic Republic of Congo" (Linard 		et al., 2012)

This quote talks about how data in low income parts of the world are out of date.  As a focus of Sub-Saharan Africa and the HIV epidemic at hand, it can be see how old data sets can stand in the way of obtaining better estimations of burden of disease.  Countries such as the Democratic Republic of Congo are  those "resource constraint environments" that can't obtain up to date accurate survey and census data. Thus focusing on how these old data sets at hand combined have been able to be turned into productive models with the methods from about, one may ask themselves "How much approximate can these estimation be made with new up to date datasets?"  The pairing of the data science methods remotely and that of new up to date data would allow for that of better approximations.  Methods such as Bayesian spatiotemporal methods and that of algorithms like that of Inverse Distance Weighted (IDW) algorithm could be enhanced through the use of having more accurate data points. 

In more recent study done by *Bulstra et al.* they looked looked at the mapping area of sub-Saharan Africa with high level of HIV transmission. In their conclusion they talk bout areas of further study. They wrote, 

​		"Localised HIV prevention interventions specifically tailored to the populations at risk will be essential 		 to curb transmission. More fine-scale geospatial mapping of key populations,—such as sex workers 	 		 and migrant populations—could help us further understand the drivers of these areas with high levels 		 of transmission and help us determine how they fuel the generalised epidemics in SSA" (Bulstra et al., 		 2020) 

Their conclusions help allow for better clarification of the next steps of combating the transmission of HIV.  In the quote they mention the groups that are missing data that is crucial for being able to "curb transmission."  With groups such as sex workers and migrants going undocumented creates a gap in the research of the stop of HIV.   This helps identify that research needs to now be tailored to be able to get data to help attack the problem in areas where poverty is prevalent.  Impoverished areas need to be studied in how to best get accurate data to help combat the little epidemics that occur in areas of high transmission. 

As I continue my research on how to modify and add assisting measure to these geospatial methods. I look to see how to add machine learning techniques paired with better data that will allow combating the widespread disease in the sub-Saharan Africa region.  As said by *Joshua Blumenstock*, "New sources of data should complement, not replace, old sources"(2018).  Using his famous quote,  I propose the question: 

How do you included data of high transmission social groups in the study of HIV in sub-Saharan Africa? 



**Work Citied** 

Mboup S, Musonda R, Mhalu F, et al. HIV/AIDS. In: Jamison DT, Feachem RG, Makgoba MW, et al., editors. Disease and Mortality in Sub-Saharan Africa. 2nd edition. Washington (DC): The International Bank for Reconstruction and Development / The World Bank; 2006. Chapter 17. Available from: https://www.ncbi.nlm.nih.gov/books/NBK2289/

Dwyer-Lindgren, L., Cork, M.A., Sligar, A. *et al.* Mapping HIV prevalence in sub-Saharan Africa between 2000 and 2017. *Nature* **570,** 189–193 (2019). https://doi.org/10.1038/s41586-019-1200-9 

Kalipeni, E., & Zulu, L. (2008). Using GIS to Model and Forecast HIV/AIDS Rates in Africa, 1986-2010. *Professional Geographer*, *60*(1), 33–53. https://doi.org/10.1080/00330120701724061

Esri. (2019). What is Empirical Bayesian kriging? Retrieved from https://desktop.arcgis.com/en/arcmap/10.3/guide-books/extensions/geostatistical-analyst/what-is-empirical-bayesian-kriging-.htm

Linard, C., Tatem, A.J. Large-scale spatial population databases in infectious disease research. *Int J Health Geogr* **11,** 7 (2012). https://doi.org/10.1186/1476-072X-11-7

Cuadros, D.F., Li, J., Branscum, A.J. *et al.* Mapping the spatial variability of HIV infection in Sub-Saharan Africa: Effective information for localized HIV prevention and control. *Sci Rep* **7,** 9093 (2017). https://doi.org/10.1038/s41598-017-09464-y

 Bulstra CA, Hontelez JAC, Giardina F, Steen R, Nagelkerke NJD, Bärnighausen T, et al. (2020) Mapping and characterising areas with high levels of HIV transmission in sub-Saharan Africa: A geospatial analysis of national survey data. PLoS Med 17(3): e1003042. https://doi.org/10.1371/journal.pmed.1003042

[Blumenstock, Joshua](https://search-proquest-com.proxy.wm.edu/indexinglinkhandler/sng/au/Blumenstock,+Joshua/$N?accountid=15053).[Nature]**; London**[ Vol. 561, Iss. 7722, ](https://search-proquest-com.proxy.wm.edu/indexingvolumeissuelinkhandler/40569/Nature/02018Y09Y13$23Sep+13,+2018$3b++Vol.+561+$287722$29/561/7722?accountid=15053) (Sep 13, 2018): 170-172. DOI:10.1038/d41586-018-06215-5 

Ghys PD, Brown T, Grassly NC*, et al* The UNAIDS Estimation and Projection Package: a software package to estimate and project national HIV epidemics *Sexually Transmitted Infections* 2004;**80:**i5-i9.

Alegana VA, Atkinson PM, Pezzulo C, Sorichetta A, Weiss D, Bird T, Erbach-Schoenberg E, Tatem AJ. 2015 Fine resolution mapping of population age-structures for health and development applications. J. R. Soc. Interface 12: 20150073. http://dx.doi.org/10.1098/rsif.2015.0073
