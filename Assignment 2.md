Improved Prediction of the Categorization of Urbanization throughout India through Various Geospatial Data Science Methods and Models

by Miao Liu

April 4, 2020

Introduction

The purpose of this research is to improve upon the use of the conventional definition and categorization of urbanization to generate a scientific and uniform standard to monitor the progress of urbanization and identify its problems by specifying, estimating, and validating an urban growth model as compared to the previous models. Central to achieving this research goal of classifying urban footprints will be increasing the resolution of India’s urban areas and population distribution from different datasets. I will achieve this goal through meeting the following objectives:

1.	Use remotely sensed data to estimate the stage of urbanization and the effects of urban agglomeration

2.	Use survey data to estimate the population of different settlements for identifying areas of human activity across India
This work will build on previous research by Joshi, Pranati Datta, Rana Hasan, Shahab Fazal, and H. Taubenböck and will incorporate new methods to implement an oriented process of urban planning as well as advances towards inferring the future of urban development. [1, 2, 3, 4, 5]

Human Development Topic

1.	Problem Statement: many of the most significant changes around the world are related to urbanization. In contrast to its big population, India is one of the least urban countries in the world. Although official report maintains a high percentage of urbanization, most Indians have difficulty enjoying high living standards. 

(a)	Because of India’s large economy, urbanization in India is no longer a domestic problem. With the largest population in the world, India has a hard time balancing economic growth and human development, leaving its urban planning messy. Uneven urban growth threatens social stability and people’s living environment.

(b)	Slums now account for about 26 percent of all urban population in cities. In India, this means 100 million people. Statistics show that 44 percent of urban households occupied on room or less in mega cities.  

(c)	The low availability of reliable datasets, the ambiguous classification of urbanization, and the misunderstanding about urban sprawl processes slow down the process of urbanization. The lack of transparent data makes it complex for institutions to direct funding and target underdeveloped areas. Local governments devote little time to figure out the right strategies to improve urban growth.  

(d)	Unlike most other cities in developing countries, many Indian slums are situated near employment centers in the heart of town. India requires better infrastructure, institutions, and resources to equip itself for the increasing urban population.

2.	How does your selected dimension of human development relate to Amartya Sen’s definition?

In his article, Sen introduces five distinct types of freedom: political freedoms, economic facilities, social opportunities, transparency guarantees, and protective security. These distinct types of freedom advance the general capability of the society, and the research covers three of them. As Sen argues, human development is an inclusive project that enlarges people’s freedom.  A careful analysis on urban transition makes economic activities promising, encouraging business investment on social programs and urban development. Once we ensure the accuracy of data-collection, the government can come up with better solutions to reduce poverty and social inequalities. An organized urban planning also promotes equality by averaging the living standards. Urbanizing one area provides more social opportunities in employment and education. The prerequisite of robust urban growth is the access to transparent database. Relying on geospatial techniques for assessment, urbanization enhances the accuracy and transparency of data.  

3.	Which SDG relates to your selected human development topic? 

The five sources relate to several development goals. First, improving urban growth creates sustainable cities and communities. Its application can extend to reducing inequalities and reducing poverty, which relate to another two SDGs. A successful urban development provides people with a decent standard of living as well as a long healthy life. As the number of slums in India decreases, the gap between the wealthy and the poor is reduced. Additionally, urbanization has great impact on the environment and the society. The urban expansion of city is proved to affect air quality, the wildlife, the water cycle, etc. Generally, measuring urban growth is essential for city-planners, economists, and the government at large. 

Human Development Process

1.	The studies on urbanization in India focus on different aspects of urban growth. Joshi’s articles assess urbanization patterns. Most of the studies focus on urbanization in relation to land use, transportation, etc. Nonetheless, it is important to have studies that address the urban sprawl problem since they can offer a level of stratification of the area for analyzing urban footprints [1]. Pranati Datta’s article aims to trace pattern of urbanization by using Indian Census data. It interprets the degree of urbanization in with the help of different tables and concludes India at an accelerating process of urbanization. Meanwhile, it resolves urban growth into three components and highlights the basic features of India’s urbanization. Lastly, it points out that faulty urban planning with poor economic base results in problems in the field of social infrastructure and leaves policy recommendations [2]. For Rana Hasan, the accelerating process of urbanization has no substantial impact on improving people’s income. The third source adds another factor that defines whether urbanization in India is successful or not. Without appropriate planning and infrastructure investment, Indian people can hardly enjoy agglomeration benefits [3]. Shahab Fazal measures the loss of farming land to urbanization to suggest the drawbacks of unplanned urbanization. Land transformation, one of the essential parts of urbanization, can impose serious loss of fertile soil [4]. According to H. Taubenböck, we can formulate an effective growth pattern by comparing existing mega cities, Mumbai, Delhi, and Kolkata. He adopts a time series of Landsat data that detects the urban footprints in the three cities [5].

a.	Joshi’s night-time satellite data exhibits information in different cities of India. They include mega cities, incipient mega cities, and urban agglomeration [1]. In Census of India that Datta relies on, two types of town are identified: statutory towns and census towns [2]. Hasan’s paper combines establishment-level data from India’s Economic census, town-level data from the Town Directory of the Population Census to explore agglomeration effects across cities in India [3]. Different from other sources which analyze India as a whole, Fazal narrows his focus on Saharanpur city, the district headquarters Meerut division [4]. The last article constructs tables based on the Landsat program which offers a series of earth observation satellites [5]. 

b.	The five sources endeavor to identify disadvantages of the current urban planning and how messy urbanization could stagnate human development. Most of the data in these sources come from census conducted by the local governments. Mega cities such as Delhi are still the hotspots in the research because they are more relevant to the topic. Metropolis in India are models that tell what are accomplished and what can be improved.

2.	Using temporal DMSP-OLS night-time satellite data, Joshi groups Indian cities according to their population sizes. After comparing the urban sprawl timeline, the study suggests distinct features for each city based on the measurement. Datta divides the analysis of urbanization into different sections. Each section has a table of numbers from census reports to support the findings. In the end, Datta devises five policies for a sustainable urban development. In Hasan’s paper, urban agglomeration effects are measured by town-level data. It is also the only source that focuses heavily on calculation. To obtain a finer geographic unit, it suggests an alternative approach which assessing urban agglomeration effects at the city level and compares the results. Thanks to the rapid development in remote sensing technology, Fazal has collected successive changes in land transformation. The vast conversion of agricultural land to non-agricultural areas is encroachment of messy urbanization. Lastly, Taubenhöck quantifies the structure of urbanization using spatial metrics. The result conforms that analysis on current urban development promotes future planning. 

a.	My human development process behaves as both a complex adaptive social and economic system. Urbanization always brings socio-economic impacts on the society. Measuring urbanization depends on economic performance of a region, but the success of urban planning is measured by social development. For instance, while urban growth increases wages for suburban workers, it can take up agricultural area and lead to environmental consequences. 

b.	The first three sources are on a national scale, but each one is conducted at a different level. The first source has a special focus on 12 large Indian cities. The second one includes all million-plus cities in India. The third one chooses the town-level. The last two are relevant case studies that are within the region. The study area of the fourth one is Saharanpur City. The fifth work picks three most representative cities for measurement.

Geospatial Data Science Methods

1.	Geospatial data science methods

a.	Joshi adopts multi-temporal remote sensing, one of the most important data-gathering tools for analyzing land-use changes. It operates in sum-synchronous riod orbits with night-time overpasses covering the Indian region. Hasan tests the relationship between wages and urban development with the help of agglomeration regressions. Fazal also chooses remote sensing for its accurate data at a high resolution. The study is done in a GIS environment because it couples well with remote sensing. Taubenhöck uses an object-oriented hierarchical approach, which combines spectral features with shape, neighborhood and texture features [5].

b.	The first system is mainly used to detect urban footprints and their changes. The difference of light intensity helps to distinguish between urbanized areas and non-urbanized areas. The third source centers on formulas for calculation. Satellite imagery is the better option because it is more economical and updated. Although mixed spectral information limits the level of accuracy, the Landsat images offer enough data for assessing urban change. 

2.	Geospatial data sets used

a.	Remotely sensed data (raster)

i.	Source [1] [4] [5] use remotely sensed data. 

A.	The Indian region is observed in two or three OLS orbital passes on a swath width of 3000km, but no specific resolution is provided for the first source [1]. In the fourth source, IRS 1C with 5.8 meters resolution is used. IRS 1C is a system that craries sensors and cameras [4]. The study starts with the Multi-Spectral-Scanner featuring a geometric resolution of 79 meters [5].  

B.	The chosen DMSP–OLS night-time satellite data are not exhaustive, but provide a specific feature of the urban system [1]. The data in Fazal’s work is spread over a ten-year time span. Details of the aerial photographs are transferred onto a base map and brought to scale [4]. Landsat data displays the urbanization rates and their spatial distribution in mega cities [5].

b.	Survey data

i.	Source [2] [3] use survey data.

A.	Source 2 collects data from Census of India. It contains population of 23 cities in India, index of urbanization, and population of India by residence. Source 3 utilizes two census and one survey data. The economic census is countrywide. The population census has town-level population and land area data. The final survey has a sample size of 2800 Indian cities from 560 districts [3].

B.	Source 2 have 8 variables out of 9 tables. Source 3 sets the town-level characteristics as explanatory variables. 
C.	Both data are secondary sources. 

Discussion

1.	So far, the paper covers the definition of urbanization, different stages of urbanization, India’s current urban growth, the significance of effective urban development, and potential harms of unsuccessful urban planning. It introduces the topic and how is the topic notworthy in the selected region. 

2.	One research gap I aim to fill is to present viable policies that makes urbanization in India more sustainable. Until now, my work only demonstrates my understanding about urbanization and the influence of uneven urban growth. These are objective facts rather than specific advice that can really alleviate the problem. The lack of substantial solutions make it an armchair general. Finish identifying the bias and misconception about urban growth, I will focus on effective urban planning strategies that bring greater efficiency.

3.	My objective is to offer a clear definition of urbanization, including its different stage and classification and assess the progress and patterns of urbanization in different cities of India. Ultimately, I can propose a sustainable urban planning that maximizes resources and minimizes inequality. 

References

New sources:

[1] Joshi, P.K. & Bairwa, Brij & Sharma, Richa & Sinha, Vinay. (2011). Assessing urbanization patterns over India using temporal DMSP-OLS night-time satellite data. Current Science. 100 1479-1482.

[2] Datta, P. (2006). Urbanisation in India Pranati Datta Population Studies Unit.

[3] Hasan, R., Jiang, Y., & Rafols, R.M. (2017). Urban Agglomeration Effects in India: Evidence from Town-Level Data. Asian Development Review, 34, 201-228.

[4] Fazal, S. (2000). Urban expansion and loss of agricultural land - a GIS based study of Saharanpur City, India.

[5] Taubenböck, H., Wegmann, M., Berger, C., Breunig, M., Roth, A., & Mehl, H. (2008). Spatiotemporal analysis of Indian megacities.

Old Sources:

[6] Urbanization in India. (n.d.). Retrieved from https://www.worldbank.org/en/news/feature/2011/09/22/india-urbanization

[7] Balk, D., M. R. Montgomery, H, Engin, N. LIN, E. Major and B. Jones, "Urbanization in India: Population and Urban Classification Grids for 2011" Data 2019, 4(1), 35; https://doi.org/10.3390/data4010035

[8] Elfie Swerts, Denise Pumain, Eric Denis. The future of India's urbanization. Futures, Elsevier, 2014, 56, pp.43-52. 10.1016/j.futures.2013.10.008. halshs-01061210

[9] Eric Denis and Kamala Marius-Gnanou, « Toward a better appraisal of urbanization in India », Cybergeo : European Journal of Geography [Online], Systems, Modelling, Geostatistics, document 569, Online since 28 November 2010, connection on 21 February 2020. URL : http://journals.openedition.org/cybergeo/24798 ; DOI : https://doi.org/10.4000/cybergeo.24798

[10] Computers, Environment and Urban Systems, ISSN: 0198-9715, Vol: 33, Issue: 3, Page: 179-188
