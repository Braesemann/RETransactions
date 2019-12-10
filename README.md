# Can Digital Technologies Speed up Real Estate Transactions?

Process maps accompanying the paper 'Can Digital Technologies Speed Up Real Estate Transactions?' (**link to paper will follow**). 

## Description
**Last modified:** December 2019 <br>
**Authors:** Andrew Saull, Andrew Baum, Fabian Braesemann <br>
**Licence:** CC-BY (4.0)

**Abstract:** 
Purpose. This study presents a structured investigation of the most important causes for delay in commercial real estate transactions. It assesses the potential of digital technologies such as ’Blockchain’, ’Property Passports’ or ’Automated Valuation Models’ to make transactions faster and cheaper. <br>
Methodology. We conduct a focus group interview to identify the individual steps and the parties in- volved in real estate transactions. Subsequently, we discuss the prospects of digital technologies based on semi-structured interviews with real estate professionals and PropTech executives, and a comprehensive screening of technological solutions offered by PropTech firms.<br>
Findings. The lack of a an up-to-date, single pool of standardised property information turns out to be the most critical cause for delay in real estate transactions. However, the most promising technologies to mitigate this problem, in particular digital property passports summarising all relevant building in- formation, face substantial barriers to adoption. The real estate industry has so far not been willing to more openly share data, which is a pre-requiste for the successful introduction of property passports. In addition, the principle of caveat emptor makes a lengthy due diligence process essential for buyers.<br>
Implications. We conclude that industry-wide collaborations are necessary to help major efficiency gain- ing technologies to break through. Insurance products should accompany property data log books to guarantee the quality of data provided.<br>
Originality. This study considers the potential impact of technologies in the wider context of the com- plete real estate transaction process. It identifies the major phases of that process and the associated bottlenecks. We gather evidence both from industry experts and PropTech executives and contrasts their views regarding the potential of digital technologies to remove those bottlenecks. <br>
**Keywords:** Commercial Real Estate • Real Estate Transactions • PropTech • Property Passport •
Blockchain • Automated Valuation Models


## Folder Structure and Disclaimer
Since some data has been crawled with the help of commercial tools, neither all data nor all code to reproduce the entire work is included. The provided code allows crawling textual components from web pages, analysing sentiment and tagging the following keywords:

**E-mobility & environment:** e-mobility, battery, environment, biological, eco, ecological, electric, hybrid, environment, environmental-friendly;<br> 
**Connectivity & shared mobility:** connectivity, shared, mobility, sharing, interconnectedness, cloud, cloud computing, wifi, 5G;<br> 
**Autonomous driving & artificial intelligence:** autonomous, self-driving, ai, machine learning, artificial intelligence, intelligent, neural network, algorithm.
<br> <br> 

```
.
+-- code
|   +-- Crawling
    |   +-- 1_Crawler.ipynb (code for crawling web pages)
    |   +-- 2_CleanUpEdges.ipynb (cleaning the crawled network data)
    +-- Analysis
    |   +-- 3_ContentAnalysis.ipynb (code for analysing web page content after cleaned up)
    |   +-- 4_NetworkAnalysisPlots.ipynb (visualizing and analysing networks)
    |   +-- 5_AutomotiveFigures.R (code for reproducing figures)
+-- data
|   +-- car_sales.csv (data of global car sales)
|   +-- node_data.csv (tagged web page data including the features "sentiment", "digital trend"...)
+-- readme.md
```

## Reference
Please cite as follows 

```
@article{
stoehr2019mining,
title={Mining Automotive the Industry – A Network Analysis of Corporate Positioning and Technological Trends},
author={Niklas Stoehr, Fabian Braesemann and Shi Zhou},
booktitle={under review at Complex Networks 2019},
year={2019},
url={www.github.com/Braesemann/MiningAutomotiveIndustry},
}
```




