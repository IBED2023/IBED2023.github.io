<script type="text/javascript" src="2html/jquery-3.3.1.min.js"></script>
<script type="text/javascript" src="2html/2html.js"></script>
<link rel="stylesheet" type="text/css" href="2html/style.css">

# IBED

International Building Emission Dataset (IBED)

A multi-regional dataset aims to monitor energy trends, emissions mitigation, and building stock on a global scale.

IBED was initially proposed by [Dr. Minda Ma](http://chongjian.cqu.edu.cn/info/1556/6706.htm) in 2021, and now it is a project led by [Lawrence Berkeley National Laboratory<img src='./image/logo-LBNL.png' style='width: 4em;'>](https://buildings.lbl.gov/)(LBNL, operated by UC Berkeley for U.S. DOE), [Tsinghua University<img src='./image/logo-THQ.png' style='width: 4em;'>](https://www.tsinghua.edu.cn), and [Chongqing University<img src='./image/logo_CQU.png' style='width: 4em;'>](https://www.cqu.edu.cn).

<div align=left><img  src="IBED_logo1.png" width=30%/> </div> 
## About IBED                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   

We are pleased to announce the release of a public version of our dataset, which is accessible at [http://ibed.world](http://ibed.world/). Our dataset is established based on the IEA database, which has clear distinctions between the end uses relevant to residential and commercial energy activities in its energy balance sheet.

To ensure the reliability of our database, we used the [IEA dataset](https://www.iea.org/data-and-statistics) as the primary reference to compile comprehensive and trustworthy data tables for each carbon-emitting country. For major emitters such as [China](https://doi.org/10.1016/j.enconman.2019.111915), [the United States](https://www.sciencedirect.com/science/article/pii/S2542435119303575), and [India](https://doi.org/10.1016/j.apenergy.2019.01.065), we accounted for and calibrated the building energy consumption data and the corresponding carbon emissions data based on the baseline dataset. For other carbon-emitting countries, we collected, cleaned, and validated survey reports and statistical results from regional governments and research institutions, which were then integrated with the baseline dataset to build a unified and standardized database.

<img src="About%20IBED.png" alt="About IBED" style="zoom:120%;" />



## Publications of IBED

In 2023, some of IBED's noteworthy applications have been featured in international journals like *Advances in Applied Energy*, *Applied Energy*, and *Sustainable Cities and Society*.
[1] Xiang X, Zhou N, Ma M\*, Feng W, Yan R. Global transition of operational carbon in residential buildings since the millennium. *Advances in Applied Energy* 2023;11:100145.
[2] Yan R, Chen M, Xiang X, Feng W, Ma M\*. Heterogeneity or illusion? Track the carbon Kuznets curve of global residential building operations. *Applied Energy* 2023;347:121441.
[3] Zhang S, Zhou N, Feng W, Ma M\*, Xiang X, You K. Pathway for decarbonizing residential building operations in the US and China beyond the mid-century. *Applied Energy* 2023;342:121164.
[4] Chen L, Ma M\*, Xiang X. Decarbonizing or illusion? How carbon emissions of commercial building operations change worldwide. *Sustainable Cities and Society* 2023;96:104654.
[5] Xiang X, Ma M\*, Ma X, Chen L, Cai W, Feng W, et al. Historical decarbonization of global commercial building operations in the 21st century. *Applied Energy* 2022;322:119401.
[6] Zhang S, Ma M*, Xiang X, Cai W, Feng W, Ma Z. Potential to decarbonize the commercial building operation of the top two emitters by 2060. *Resources, Conservation and Recycling* 2022;185:106481.



<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="image\GA-1.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Source: https://doi.org/10.1016/j.adapen.2023.100145</div>
</center>





<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="image\GA-2.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Source: https://doi.org/10.1016/j.apenergy.2023.121164</div>
</center>





<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="image\GA-3.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Source: https://doi.org/10.1016/j.apenergy.2023.121441</div>
</center>







## Carbon emissions of residential building operations 

| Regions                                                     | Name                                | Abbreviations | Unit            | 2000   | 2010   | 2020  |
| ----------------------------------------------------------- | ----------------------------------- | ------------- | --------------- | ------ | ------ | ----- |
| Europe & New Zealand                                        | Carbon  emissions                   | $C$           | $\text{MtCO}_2$ | 1089.5 | 1086.1 | 802.2 |
| Europe & New Zealand                                        | Share  of residential space heating | $C_{RSH}$     | $\%$            | 50.3%  | 50.8%  | 49.8% |
| Europe & New Zealand                                        | Share  of residential space cooling | $C_{RSC}$     | $\%$            | 2.3%   | 2.1%   | 2.3%  |
| Europe & New Zealand                                        | Share  of other end uses            | $C_{RA}$      | $\%$            | 47.4%  | 47.1%  | 47.9% |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Carbon  emissions                   | $C$           | $\text{MtCO}_2$ | 63.2   | 82.5   | 102.4 |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share  of residential space heating | $C_{RSH}$     | $\%$            | 17.2%  | 18.3%  | 17.8% |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share  of residential space cooling | $C_{RSC}$     | $\%$            | 3.2%   | 6.7%   | 9.8%  |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share  of other end uses            | $C_{RA}$      | $\%$            | 79.6%  | 75.0%  | 72.4% |
| China                                                       | Carbon  emissions                   | $C$           | $\text{MtCO}_2$ | 412.9  | 690.7  | 803.4 |
| China                                                       | Share  of residential space heating | $C_{RSH}$     | $\%$            | 43.0%  | 43.4%  | 36.1% |
| China                                                       | Share  of residential space cooling | $C_{RSC}$     | $\%$            | 6.2%   | 6.1%   | 11.3% |
| China                                                       | Share  of other end uses            | $C_{RA}$      | $\%$            | 50.9%  | 50.5%  | 52.5% |
| India                                                       | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 157.5  | 248.2  | 375   |
| India                                                       | Share of residential space  heating | $C_{RSH}$     | $\%$            | 0.0%   | 0.0%   | 0.0%  |
| India                                                       | Share of residential space  cooling | $C_{RSC}$     | $\%$            | 22.5%  | 29.7%  | 36.4% |
| India                                                       | Share of other end uses             | $C_{RA}$      | $\%$            | 77.5%  | 70.3%  | 63.6% |
| Northeast Asia (Japan, Korea)                               | Carbon  emissions                   | $C$           | $\text{MtCO}_2$ | 239.9  | 285.5  | 281.6 |
| Northeast Asia (Japan, Korea)                               | Share  of residential space heating | $C_{RSH}$     | $\%$            | 29.2%  | 29.6%  | 26.7% |
| Northeast Asia (Japan, Korea)                               | Share  of residential space cooling | $C_{RSC}$     | $\%$            | 3.4%   | 4.0%   | 3.2%  |
| Northeast Asia (Japan, Korea)                               | Share  of other end uses            | $C_{RA}$      | $\%$            | 67.4%  | 66.4%  | 70.0% |
| Africa (South Africa, Morocco)                              | Carbon  emissions                   | $C$           | $\text{MtCO}_2$ | 41     | 66.1   | 88.2  |
| Africa (South Africa, Morocco)                              | Share  of residential space heating | $C_{RSH}$     | $\%$            | 14.4%  | 14.2%  | 13.8% |
| Africa (South Africa, Morocco)                              | Share  of residential space cooling | $C_{RSC}$     | $\%$            | 14.3%  | 14.2%  | 13.7% |
| Africa (South Africa, Morocco)                              | Share  of other end uses            | $C_{RA}$      | $\%$            | 71.3%  | 71.7%  | 72.5% |
| North America                                               | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 1289   | 1267.8 | 969.2 |
| North America                                               | Share of  residential space heating | $C_{RSH}$     | $\%$            | 37.9%  | 31.0%  | 36.1% |
| North America                                               | Share of  residential space cooling | $C_{RSC}$     | $\%$            | 7.9%   | 10.4%  | 9.6%  |
| North America                                               | Share of other end  uses            | $C_{RA}$      | $\%$            | 54.3%  | 58.6%  | 54.3% |
| Australia                                                   | Carbon  emissions                   | $C$           | $\text{MtCO}_2$ | 54.9   | 67.8   | 54.8  |
| Australia                                                   | Share  of residential space heating | $C_{RSH}$     | $\%$            | 14.5%  | 14.8%  | 17.3% |
| Australia                                                   | Share  of residential space cooling | $C_{RSC}$     | $\%$            | 5.2%   | 7.3%   | 8.2%  |
| Australia                                                   | Share  of other end uses            | $C_{RA}$      | $\%$            | 80.3%  | 77.9%  | 74.6% |







## Energy consumption of residential building operations 

| Regions                                                     | Name                                | Abbreviations | Unit                     | 2000     | 2010     | 2020     |
| ----------------------------------------------------------- | ----------------------------------- | ------------- | ------------------------ | -------- | -------- | -------- |
| Europe & New Zealand                                        | Energy  consumption                 | $E$           | Peta joule $(\text{PJ})$ | 15047.47 | 16564.21 | 14579.32 |
| Europe & New Zealand                                        | Share  of residential space heating | $E_{RSH}$     | $\%$                     | 62.3%    | 61.6%    | 57.2%    |
| Europe & New Zealand                                        | Share  of residential space cooling | $E_{RSC}$     | $\%$                     | 1.9%     | 1.9%     | 2.0%     |
| Europe & New Zealand                                        | Share  of other end uses            | $E_{RA}$      | $\%$                     | 35.8%    | 36.4%    | 40.8%    |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Energy  consumption                 | $E$           | Peta joule $(\text{PJ})$ | 1668.4   | 2001.8   | 2326.2   |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share  of residential space heating | $E_{RSH}$     | $\%$                     | 13.4%    | 14.7%    | 14.9%    |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share  of residential space cooling | $E_{RSC}$     | $\%$                     | 5.5%     | 7.5%     | 9.7%     |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share  of other end uses            | $E_{RA}$      | $\%$                     | 81.2%    | 77.9%    | 75.3%    |
| China                                                       | Energy  consumption                 | $E$           | Peta joule $(\text{PJ})$ | 5157.2   | 11614.6  | 19192.9  |
| China                                                       | Share  of residential space heating | $E_{RSH}$     | $\%$                     | 50.4%    | 50.4%    | 44.3%    |
| China                                                       | Share  of residential space cooling | $E_{RSC}$     | $\%$                     | 4.8%     | 4.8%     | 9.9%     |
| China                                                       | Share  of other end uses            | $E_{RA}$      | $\%$                     | 44.8%    | 44.8%    | 45.8%    |
| India                                                       | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 1142.2   | 1672.9   | 2598     |
| India                                                       | Share of residential space  heating | $E_{RSH}$     | $\%$                     | 0.0%     | 0.0%     | 0.0%     |
| India                                                       | Share of residential space  cooling | $E_{RSC}$     | $\%$                     | 9.0%     | 14.6%    | 22.0%    |
| India                                                       | Share of other end uses             | $E_{RA}$      | $\%$                     | 91.0%    | 85.4%    | 78.0%    |
| Northeast Asia (Japan, Korea)                               | Energy  consumption                 | $E$           | Peta joule $(\text{PJ})$ | 2766.1   | 2982.9   | 2829.8   |
| Northeast Asia (Japan, Korea)                               | Share  of residential space heating | $E_{RSH}$     | $\%$                     | 34.8%    | 35.9%    | 33.6%    |
| Northeast Asia (Japan, Korea)                               | Share  of residential space cooling | $E_{RSC}$     | $\%$                     | 2.3%     | 2.7%     | 2.2%     |
| Northeast Asia (Japan, Korea)                               | Share  of other end uses            | $E_{RA}$      | $\%$                     | 62.9%    | 61.3%    | 64.2%    |
| Africa (South Africa, Morocco)                              | Energy  consumption                 | $E$           | Peta joule $(\text{PJ})$ | 569.5    | 574.2    | 681.7    |
| Africa (South Africa, Morocco)                              | Share  of residential space heating | $E_{RSH}$     | $\%$                     | 14.8%    | 13.6%    | 12.8%    |
| Africa (South Africa, Morocco)                              | Share  of residential space cooling | $E_{RSC}$     | $\%$                     | 13.1%    | 12.7%    | 12.5%    |
| Africa (South Africa, Morocco)                              | Share  of other end uses            | $E_{RA}$      | $\%$                     | 72.1%    | 73.8%    | 74.6%    |
| North America                                               | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 12250.9  | 12894.7  | 12941.2  |
| North America                                               | Share of  residential space heating | $E_{RSH}$     | $\%$                     | 56.4%    | 48.8%    | 46.9%    |
| North America                                               | Share of  residential space cooling | $E_{RSC}$     | $\%$                     | 4.3%     | 6.3%     | 7.3%     |
| North America                                               | Share of other end  uses            | $E_{RA}$      | $\%$                     | 39.3%    | 44.8%    | 45.8%    |
| Australia                                                   | Energy  consumption                 | $E$           | Peta joule $(\text{PJ})$ | 378.4    | 428.8    | 455.2    |
| Australia                                                   | Share  of residential space heating | $E_{RSH}$     | $\%$                     | 44.2%    | 37.2%    | 35.7%    |
| Australia                                                   | Share  of residential space cooling | $E_{RSC}$     | $\%$                     | 2.7%     | 4.2%     | 4.7%     |
| Australia                                                   | Share  of other end uses            | $E_{RA}$      | $\%$                     | 53.1%    | 58.5%    | 59.5%    |



## Socio-economic indicators of residential buildings

| Regions                                                     | Name                    | Abbreviations | Unit                   | 2000   | 2010   | 2020   |
| ----------------------------------------------------------- | ----------------------- | ------------- | ---------------------- | ------ | ------ | ------ |
| Europe & New Zealand                                        | Population  size        | $P$           | Million persons        | 659.3  | 682.5  | 704.8  |
| Europe & New Zealand                                        | Average  household size | $p$           | persons per  household | 2.7    | 2.6    | 2.4    |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Population  size        | $P$           | Million persons        | 270    | 302.1  | 331.4  |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Average  household size | $p$           | persons per  household | 4.5    | 4      | 3.6    |
| China                                                       | Population  size        | $P$           | Million persons        | 1262.6 | 1337.7 | 1411.1 |
| China                                                       | Average  household size | $p$           | persons per  household | 3.4    | 3.1    | 2.6    |
| India                                                       | Population size         | $P$           | Million persons        | 1012.6 | 1180.9 | 1347.1 |
| India                                                       | Average household size  | $p$           | persons per household  | 5.4    | 5.1    | 4.8    |
| Northeast Asia (Japan, Korea)                               | Population  size        | $P$           | Million persons        | 173.9  | 177.6  | 178.1  |
| Northeast Asia (Japan, Korea)                               | Average  household size | $p$           | persons per  household | 2.8    | 2.6    | 2.4    |
| Africa (South Africa, Morocco)                              | Population  size        | $P$           | Million persons        | 73.8   | 83.6   | 96.2   |
| Africa (South Africa, Morocco)                              | Average  household size | $p$           | persons per  household | 6.1    | 5.5    | 5.7    |
| North America                                               | Population size         | $P$           | Million persons        | 312.9  | 343.3  | 368.2  |
| North America                                               | Average household  size | $p$           | persons per  household | 2.6    | 2.6    | 2.5    |
| Australia                                                   | Population  size        | $P$           | Million persons        | 19.2   | 22     | 25.7   |
| Australia                                                   | Average  household size | $p$           | persons per  household | 2.6    | 2.6    | 2.5    |





## Data availability

For additional information, including **detailed energy activities of residential buildings' end uses, commercial building stocks, and energy and emissions of commercial buildings' end uses**, you can contact the project leader, [Dr. Minda Ma](https://buildings.lbl.gov/people/minda-ma), at <maminda@lbl.gov>. We will provide the requested information upon reasonable request.



## ArchTracking

ArchTracking is an upcoming software program for tracking the nation-regional energy and emission impacts of building decarbonization measures.



## PyLMDI

**Python-LMDI: a tool for index decomposition analysis of building carbon emissions**

A timely analysis for carbon emission reduction in buildings is an effective global response to the crisis of climate change. The logarithmic mean Divisia index (LMDI) decomposition analysis approach has been extensively used to assess the carbon emission reduction potential of the buildings sector. In order to simplify the calculation process and to expand its application scope, a new open-source Python tool (PyLMDI) developed in this article is used to compute the results of LMDI decomposition analysis, including multiplicative and additive decomposition. Users can quickly obtain the decomposition result by initializing the input data through a simple class data structure. In addition, the carbon emissions from commercial buildings are used as a numerical example to demonstrate the function of PyLMDI. In summary, PyLMDI is a potential calculation tool for index decomposition analysis that can provide calculation guidance for carbon emission reduction in the buildings sector. The data and codes for the numerical example are also included.

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="PyLMDI_FrameWork.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Research flow chart and conceptual diagram illustrating the architecture of PyLMDI</div>
</center>



**Source codes**

```python
import numpy as np
from operation import Lfun

class PyLMDI():
    def __init__(self,Vt,V0,Xt,X0):
        self.V0 = V0
        self.Vt = Vt
        self.X0 = X0
        self.Xt = Xt
        
    def Add(self):
        Delta_V = [sum(self.Vt)-np.sum(self.V0)]
        for start, end in zip(self.X0, self.Xt):
            temp = sum([ Lfun(self.Vt[i], self.V0[i]) * np.log(end[i]/start[i]) 
                        for i in range(len(start))])
            Delta_V.append(temp)       
        return Delta_V

    def Mul(self):
        D_V = [sum(self.Vt) / np.sum(self.V0)]
        for start, end in zip(self.X0,self.Xt):
            temp = sum([Lfun(self.Vt[i], self.V0[i])/Lfun(sum(self.Vt),sum(self.V0))*np.log(end[i]/start[i])
                        for i in range(len(start))])
            D_V.append(np.exp(temp))            
        return 
```



## Robustness of DSD method

Let carbon emissions of residential building operations in China and India be an example, here we present the robustness analysis of the DSD method. 

**China:**

|      | C        | C_RSC    | C_RSH    | C_RWH    | C_RC     | C_RL     | C_RA     | E        | E_RSC    | E_RSH    | E_RWH    | E_RC     | E_RL     | E_RA     | P        | GDP      | HCE     | nHouseholds |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | ------- | ----------- |
| 2000 | 412.938  | 25.54544 | 177.408  | 74.76198 | 29.40054 | 41.35025 | 64.47183 | 176.0856 | 8.515147 | 88.70398 | 14.19191 | 29.40054 | 13.78342 | 21.49061 | 1262.645 | 3683440  | 1264850 | 367.0479651 |
| 2001 | 429.7979 | 26.08845 | 193.357  | 75.07706 | 29.0252  | 40.40786 | 65.84228 | 188.3755 | 8.934401 | 99.15744 | 14.4593  | 29.43732 | 13.83831 | 22.54873 | 1271.85  | 4080390  | 1390550 | 373.4145625 |
| 2002 | 443.751  | 27.8495  | 214.1834 | 58.90245 | 30.52722 | 42.00162 | 70.28682 | 209.0731 | 9.806161 | 112.7281 | 15.59403 | 31.4066  | 14.7893  | 24.74888 | 1280.4   | 4522480  | 1541520 | 379.7153025 |
| 2003 | 494.7233 | 33.18322 | 260.3678 | 31.76612 | 36.32753 | 49.33056 | 83.74812 | 257.8393 | 12.02291 | 140.7393 | 18.93996 | 37.92018 | 17.87339 | 30.34352 | 1288.4   | 5074660  | 1673660 | 385.9796285 |
| 2004 | 521.4411 | 32.47041 | 256.9412 | 66.18924 | 35.8724  | 48.01872 | 81.94912 | 260.3781 | 12.11582 | 142.7451 | 19.02126 | 38.00043 | 17.91743 | 30.57803 | 1296.075 | 5737890  | 1853560 | 392.2745157 |
| 2005 | 572.104  | 34.62103 | 273.8725 | 86.0087  | 38.92333 | 51.3015  | 87.37688 | 285.9376 | 13.31578 | 156.4986 | 20.93236 | 41.85304 | 19.73135 | 33.60649 | 1303.72  | 6592140  | 2124480 | 398.6911315 |
| 2006 | 584.2721 | 36.1716  | 283.9519 | 77.14842 | 41.6801  | 54.02988 | 91.29021 | 307.2357 | 14.35381 | 167.0306 | 22.68235 | 45.50229 | 21.44043 | 36.22627 | 1311.02  | 7660000  | 2410220 | 405.1359703 |
| 2007 | 602.3258 | 38.15625 | 295.2476 | 69.52077 | 45.34893 | 57.75315 | 96.29911 | 332.9143 | 15.63781 | 178.9379 | 24.92642 | 50.27597 | 23.66932 | 39.46685 | 1317.885 | 8986560  | 2804390 | 411.5818239 |
| 2008 | 614.9546 | 38.29501 | 290.1351 | 83.64176 | 47.22009 | 59.01339 | 96.6493  | 342.8685 | 16.2267  | 181.3344 | 26.17285 | 53.17577 | 25.00567 | 40.95309 | 1324.655 | 10042800 | 3152820 | 418.136048  |
| 2009 | 642.408  | 38.85461 | 286.1795 | 108.0933 | 49.98601 | 61.23292 | 98.06163 | 356.6304 | 17.0415  | 184.6319 | 27.89873 | 57.19223 | 26.85654 | 43.00949 | 1331.26  | 11057100 | 3458700 | 424.7798341 |
| 2010 | 690.7296 | 42.18972 | 299.6582 | 117.167  | 56.94367 | 68.29223 | 106.4788 | 396.5661 | 19.17714 | 199.7721 | 31.9619  | 66.21358 | 31.04192 | 48.39945 | 1337.705 | 12380200 | 3914860 | 431.5177419 |
| 2011 | 705.6291 | 45.94059 | 307.8855 | 121.5317 | 57.67705 | 68.76261 | 103.8317 | 417.8341 | 21.67009 | 212.3348 | 34.2406  | 68.17618 | 32.43519 | 48.9772  | 1345.035 | 13844400 | 4608250 | 439.5539216 |
| 2012 | 720.3104 | 49.89067 | 315.037  | 122.8489 | 59.34989 | 70.15875 | 103.0253 | 442.6478 | 24.45621 | 225.0264 | 36.93706 | 71.334   | 34.39155 | 50.50258 | 1354.19  | 15124500 | 5199440 | 448.4072848 |
| 2013 | 732.0165 | 54.84024 | 325.1409 | 110.9724 | 62.69164 | 73.30664 | 105.0646 | 477.0814 | 27.97972 | 240.8451 | 40.61066 | 76.64015 | 37.40135 | 53.60439 | 1363.24  | 16185100 | 5536640 | 459.003367  |
| 2014 | 723.8046 | 54.82843 | 303.5699 | 135.5719 | 60.90936 | 70.28924 | 98.63571 | 469.1134 | 29.16406 | 233.5153 | 40.82242 | 75.75791 | 37.38789 | 52.4658  | 1371.86  | 17121300 | 5988630 | 469.8150685 |
| 2015 | 737.7605 | 61.1485  | 313.8122 | 116.1577 | 66.62469 | 75.70532 | 104.3121 | 515.3272 | 33.97139 | 251.0498 | 45.96129 | 84.33505 | 42.05851 | 57.95119 | 1379.86  | 17796700 | 6461180 | 480.7874564 |
| 2016 | 744.7835 | 69.26889 | 318.6044 | 92.67514 | 67.10563 | 86.49813 | 110.6313 | 552.5774 | 40.27261 | 265.5037 | 45.71467 | 86.47633 | 50.28961 | 64.3205  | 1387.79  | 18712100 | 7035350 | 492.1241135 |
| 2017 | 775.5455 | 76.086   | 317.0713 | 104.3906 | 66.8022  | 95.84316 | 115.3522 | 583.1795 | 46.3939  | 275.7142 | 44.62683 | 87.66693 | 58.44095 | 70.33671 | 1396.215 | 19887000 | 7733720 | 504.0487365 |
| 2018 | 767.3278 | 81.36178 | 309.2549 | 89.34894 | 65.6903  | 103.4014 | 118.2705 | 605.8926 | 52.15499 | 281.1409 | 42.67814 | 87.82126 | 66.28293 | 75.81443 | 1402.76  | 21736500 | 8570800 | 515.7205882 |
| 2019 | 781.2282 | 85.04376 | 295.9428 | 107.8811 | 63.87335 | 109.0589 | 119.4283 | 620.6643 | 57.462   | 281.8503 | 39.9479  | 87.02091 | 73.68842 | 80.69479 | 1407.745 | 23441900 | 9272040 | 523.3252788 |
| 2020 | 803.4236 | 90.98227 | 290.2873 | 116.0863 | 64.16568 | 117.7478 | 124.1542 | 655.3169 | 64.98734 | 290.2873 | 38.13612 | 89.119   | 84.1056  | 88.68154 | 1411.1   | 24255800 | 9164630 | 538.5877863 |



|      | c=C/H    | c-rsc    | c-rsh    | c-rwh    | c-rc     | c-rl     | c-ra     | p=P/HCE | g=GDP/P  | s=HCE/GDP | e=E/HCE  | w-rsc    | w-rsh    | w-rwh    | w-rc        | w-rl        | w-ra        | k-rsc | k-rsh | k-rwh    | k-rc  | k-rl | k-ra |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | ------- | -------- | --------- | -------- | -------- | -------- | -------- | ----------- | ----------- | ----------- | ----- | ----- | -------- | ----- | ---- | ---- |
| 2000 | 1125.025 | 69.59701 | 483.3373 | 203.6845 | 80.09999 | 112.6563 | 175.6496 | 3.44    | 2917.241 | 0.343388  | 0.139215 | 0.048358 | 0.503755 | 0.080597 | 0.166967311 | 0.078276796 | 0.122046372 | 3     | 2     | 5.26793  | 1     | 3    | 3    |
| 2001 | 1150.994 | 69.86458 | 517.8079 | 201.0555 | 77.72916 | 108.2118 | 176.3249 | 3.406   | 3208.232 | 0.340789  | 0.135468 | 0.047429 | 0.526382 | 0.076758 | 0.156269391 | 0.073461287 | 0.119700947 | 2.92  | 1.95  | 5.192303 | 0.986 | 2.92 | 2.92 |
| 2002 | 1168.641 | 73.3431  | 564.0632 | 155.1227 | 80.39502 | 110.6135 | 185.104  | 3.372   | 3532.084 | 0.340857  | 0.135628 | 0.046903 | 0.53918  | 0.074587 | 0.150218293 | 0.070737476 | 0.118374297 | 2.84  | 1.9   | 3.777243 | 0.972 | 2.84 | 2.84 |
| 2003 | 1281.734 | 85.97143 | 674.5636 | 82.29998 | 94.11774 | 127.8061 | 216.9755 | 3.338   | 3938.73  | 0.329807  | 0.154057 | 0.046629 | 0.545841 | 0.073456 | 0.147069037 | 0.069319885 | 0.11768385  | 2.76  | 1.85  | 1.677201 | 0.958 | 2.76 | 2.76 |
| 2004 | 1329.276 | 82.77471 | 655.0036 | 168.7319 | 91.44719 | 122.411  | 208.9076 | 3.304   | 4427.128 | 0.323039  | 0.140475 | 0.046532 | 0.548222 | 0.073052 | 0.145943247 | 0.068813127 | 0.117437031 | 2.68  | 1.8   | 3.47975  | 0.944 | 2.68 | 2.68 |
| 2005 | 1434.955 | 86.83672 | 686.929  | 215.7277 | 97.62777 | 128.6748 | 219.1593 | 3.27    | 5056.408 | 0.322275  | 0.134592 | 0.046569 | 0.547317 | 0.073206 | 0.146371233 | 0.069005779 | 0.117530863 | 2.6   | 1.75  | 4.108887 | 0.93  | 2.6  | 2.6  |
| 2006 | 1442.163 | 89.28261 | 700.8806 | 190.426  | 102.8793 | 133.3623 | 225.3323 | 3.236   | 5842.779 | 0.31465   | 0.127472 | 0.046719 | 0.543656 | 0.073827 | 0.148102216 | 0.069784955 | 0.117910366 | 2.52  | 1.7   | 3.401254 | 0.916 | 2.52 | 2.52 |
| 2007 | 1463.441 | 92.70636 | 717.3484 | 168.9112 | 110.182  | 140.32   | 233.9732 | 3.202   | 6818.926 | 0.312065  | 0.118712 | 0.046972 | 0.537489 | 0.074873 | 0.151017758 | 0.071097343 | 0.118549573 | 2.44  | 1.65  | 2.789039 | 0.902 | 2.44 | 2.44 |
| 2008 | 1470.705 | 91.58505 | 693.8772 | 200.0348 | 112.93   | 141.1344 | 231.1432 | 3.168   | 7581.446 | 0.313938  | 0.10875  | 0.047326 | 0.528875 | 0.076335 | 0.155090871 | 0.072930794 | 0.119442567 | 2.36  | 1.6   | 3.195745 | 0.888 | 2.36 | 2.36 |
| 2009 | 1512.332 | 91.47    | 673.7124 | 254.4691 | 117.6751 | 144.1521 | 230.8528 | 3.134   | 8305.74  | 0.312804  | 0.103111 | 0.047785 | 0.517712 | 0.078229 | 0.160368354 | 0.075306374 | 0.120599609 | 2.28  | 1.55  | 3.874489 | 0.874 | 2.28 | 2.28 |
| 2010 | 1600.698 | 97.77052 | 694.4284 | 271.5231 | 131.9614 | 158.2605 | 246.7542 | 3.1     | 9254.806 | 0.316219  | 0.101298 | 0.048358 | 0.503755 | 0.080597 | 0.166967311 | 0.078276796 | 0.122046372 | 2.2   | 1.5   | 3.665834 | 0.86  | 2.2  | 2.2  |
| 2011 | 1605.33  | 104.5164 | 700.4499 | 276.4886 | 131.2172 | 156.4373 | 236.2205 | 3.06    | 10292.97 | 0.33286   | 0.090671 | 0.051863 | 0.50818  | 0.081948 | 0.16316566  | 0.077626963 | 0.117216861 | 2.12  | 1.45  | 3.549344 | 0.846 | 2.12 | 2.12 |
| 2012 | 1606.375 | 111.262  | 702.5688 | 273.9672 | 132.3571 | 156.4621 | 229.7582 | 3.02    | 11168.67 | 0.343776  | 0.085134 | 0.05525  | 0.508364 | 0.083446 | 0.16115296  | 0.077695056 | 0.114092012 | 2.04  | 1.4   | 3.325898 | 0.832 | 2.04 | 2.04 |
| 2013 | 1594.795 | 119.4768 | 708.3629 | 241.7682 | 136.5821 | 159.7083 | 228.8972 | 2.97    | 11872.52 | 0.342083  | 0.086168 | 0.058648 | 0.50483  | 0.085123 | 0.160643765 | 0.078396155 | 0.112358993 | 1.96  | 1.35  | 2.732593 | 0.818 | 1.96 | 1.96 |
| 2014 | 1540.616 | 116.7022 | 646.1477 | 288.5644 | 129.6454 | 149.6104 | 209.9458 | 2.92    | 12480.36 | 0.349777  | 0.078334 | 0.062168 | 0.49778  | 0.08702  | 0.161491677 | 0.079699052 | 0.111840343 | 1.88  | 1.3   | 3.321016 | 0.804 | 1.88 | 1.88 |
| 2015 | 1534.484 | 127.1841 | 652.7047 | 241.5988 | 138.5741 | 157.4611 | 216.961  | 2.87    | 12897.47 | 0.363055  | 0.079757 | 0.065922 | 0.487166 | 0.089189 | 0.163653397 | 0.081615153 | 0.112455141 | 1.8   | 1.25  | 2.527294 | 0.79  | 1.8  | 1.8  |
| 2016 | 1513.406 | 140.7549 | 647.4067 | 188.3166 | 136.3592 | 175.7649 | 224.8036 | 2.82    | 13483.38 | 0.375979  | 0.078543 | 0.072881 | 0.480482 | 0.08273  | 0.156496319 | 0.09100917  | 0.11640088  | 1.72  | 1.2   | 2.027252 | 0.776 | 1.72 | 1.72 |
| 2017 | 1538.632 | 150.9497 | 629.0489 | 207.1043 | 132.5312 | 190.1466 | 228.8513 | 2.77    | 14243.51 | 0.388883  | 0.075407 | 0.079553 | 0.472778 | 0.076523 | 0.150325806 | 0.100210919 | 0.120609017 | 1.64  | 1.15  | 2.33919  | 0.762 | 1.64 | 1.64 |
| 2018 | 1487.875 | 157.7633 | 599.656  | 173.2507 | 127.3758 | 200.4988 | 229.3306 | 2.72    | 15495.52 | 0.394305  | 0.070693 | 0.08608  | 0.464011 | 0.070438 | 0.144945251 | 0.109397165 | 0.1251285   | 1.56  | 1.1   | 2.093553 | 0.748 | 1.56 | 1.56 |
| 2019 | 1492.816 | 162.5065 | 565.5045 | 206.1454 | 122.0529 | 208.3959 | 228.2104 | 2.69    | 16652.09 | 0.395533  | 0.066939 | 0.092581 | 0.454111 | 0.064363 | 0.140206084 | 0.118725088 | 0.130013577 | 1.48  | 1.05  | 2.700546 | 0.734 | 1.48 | 1.48 |
| 2020 | 1491.723 | 168.9275 | 538.9786 | 215.5383 | 119.1369 | 218.6233 | 230.518  | 2.62    | 17189.28 | 0.377833  | 0.071505 | 0.099169 | 0.442972 | 0.058195 | 0.135993743 | 0.128343406 | 0.135326199 | 1.4   | 1     | 3.043999 | 0.72  | 1.4  | 1.4  |



|      | Δc\|p    | Δc\|g    | Δc\|s    | Δc\|e    | Δc\|w-rsc | Δc\|w-rsh | Δc\|w-rwh | Δc\|w-rc | Δc\|w-rl | Δc\|w-ra | Δc\|k-rsc | Δc\|k-rsh | Δc\|k-rwh | Δc\|k-rc | Δc\|k-rl     | Δc\|k-ra     | sum          | Δc           |
| ---- | -------- | -------- | -------- | -------- | --------- | --------- | --------- | -------- | -------- | -------- | --------- | --------- | --------- | -------- | ------------ | ------------ | ------------ | ------------ |
| 2001 | -11.3032 | 108.1991 | -8.64811 | -31.0421 | -1.35309  | 21.985    | -9.87577  | -5.22507 | -7.0108  | -3.41495 | -1.88473  | -12.6684  | -2.92626  | -1.11253 | -2.984482011 | -4.75669558  | 25.97790135  | 25.9692308   |
| 2002 | -11.6357 | 111.5351 | 0.233869 | 1.365137 | -0.79786  | 12.98715  | -5.082    | -3.12201 | -4.13378 | -2.01365 | -1.98873  | -14.0425  | -56.3494  | -1.13052 | -3.039312806 | -5.019181004 | 17.76665356  | 17.64758401  |
| 2003 | -12.4075 | 133.4144 | -40.3475 | 155.9887 | -0.465    | 7.583789  | -1.75403  | -1.84492 | -2.40906 | -1.17358 | -2.2713   | -16.4721  | -93.2758  | -1.2633  | -3.400313298 | -5.732332321 | 114.170095   | 113.0928874  |
| 2004 | -13.3642 | 152.5871 | -27.0689 | -120.481 | -0.17712  | 2.893484  | -0.6639   | -0.71292 | -0.91781 | -0.44702 | -2.48144  | -18.2131  | 87.86382  | -1.36581 | -3.679358455 | -6.262688674 | 47.50923563  | 47.54171909  |
| 2005 | -14.2895 | 183.6009 | -3.27061 | -59.0983 | 0.06772   | -1.10861  | 0.401677  | 0.276732 | 0.35091  | 0.170912 | -2.56958  | -18.8981  | 31.78724  | -1.41204 | -3.803832081 | -6.485118514 | 105.7203883  | 105.679271   |
| 2006 | -15.0358 | 207.9436 | -34.4433 | -78.1846 | 0.283865  | -4.65717  | 1.713571  | 1.178371 | 1.470944 | 0.716421 | -2.75191  | -20.1139  | -38.3334  | -1.52032 | -4.094226792 | -6.945300061 | 7.226773586  | 7.207788859  |
| 2007 | -15.3448 | 224.4473 | -11.9856 | -103.435 | 0.491902  | -8.08898  | 2.525172  | 2.075975 | 2.54901  | 1.241468 | -2.93521  | -21.1682  | -35.612   | -1.64013 | -4.413662366 | -7.407920896 | 21.29934141  | 21.27807119  |
| 2008 | -15.6612 | 155.5123 | 8.781018 | -128.588 | 0.691493  | -11.4002  | 3.557855  | 2.968776 | 3.583045 | 1.745196 | -3.07177  | -21.7109  | 25.05134  | -1.74496 | -4.691327574 | -7.752561816 | 7.270383376  | 7.263408019  |
| 2009 | -16.0929 | 136.0817 | -5.40087 | -79.4071 | 0.882361  | -14.5854  | 5.542222  | 3.857728 | 4.572091 | 2.226912 | -3.15643  | -21.708   | 43.55721  | -1.83206 | -4.919037442 | -7.966237167 | 41.65216819  | 41.62704304  |
| 2010 | -16.974  | 168.3635 | 16.90093 | -27.6114 | 1.127933  | -18.694   | 7.839879  | 5.027754 | 5.845387 | 2.846687 | -3.37841  | -22.4288  | -14.5538  | -2.01336 | -5.396879827 | -8.526450553 | 88.37506503  | 88.36641404  |
| 2011 | -20.8186 | 170.4288 | 82.21246 | -177.657 | 7.074598  | 6.099405  | 4.555462  | -3.03076 | -1.31171 | -9.74859 | -3.74509  | -23.6441  | -8.84827  | -2.15977 | -5.828338033 | -8.943580187 | 4.634961647  | 4.631966959  |
| 2012 | -21.1299 | 131.1206 | 51.81705 | -101.189 | 6.822986  | 0.25487   | 4.985268  | -1.63574 | 0.137175 | -6.29508 | -4.14874  | -24.6169  | -17.896   | -2.19911 | -6.018037464 | -8.961660417 | 1.047423044  | 1.045410434  |
| 2013 | -26.7215 | 97.81838 | -7.90402 | 19.32829 | 6.882661  | -4.92151  | 5.125544  | -0.42552 | 1.420071 | -3.51013 | -4.61344  | -25.656   | -50.6022  | -2.28178 | -6.32402916  | -9.17432143  | -11.55947386 | -11.57999512 |
| 2014 | -26.6144 | 78.26614 | 34.8664  | -149.415 | 6.884287  | -9.51816  | 5.830007  | 0.700596 | 2.548314 | -1.01456 | -4.92088  | -25.5419  | 51.57815  | -2.29743 | -6.442782487 | -9.138199397 | -54.22918013 | -54.17954117 |
| 2015 | -26.5559 | 50.54716 | 57.28833 | 27.68849 | 7.144408  | -13.9976  | 6.506689  | 1.782619 | 3.646794 | 1.170056 | -5.29944  | -25.4707  | -72.2097  | -2.35494 | -6.67506495  | -9.281210821 | -6.070054033 | -6.132116427 |
| 2016 | -26.7831 | 67.70294 | 53.30392 | -23.383  | 13.43386  | -8.97978  | -16.0757  | -6.14714 | 18.13343 | 7.61648  | -6.08536  | -26.5364  | -47.1476  | -2.45791 | -7.566997336 | -10.04077873 | -21.0132305  | -21.07798385 |
| 2017 | -27.2992 | 83.6902  | 51.49688 | -62.1702 | 12.77071  | -10.3165  | -15.407   | -5.40803 | 17.61265 | 8.055326 | -6.94383  | -27.1609  | 28.27576  | -2.44754 | -8.709336303 | -10.80306074 | 25.23602767  | 25.22623471  |
| 2018 | -27.562  | 127.4795 | 20.94822 | -97.6916 | 12.16812  | -11.4964  | -15.7157  | -4.73604 | 17.12732 | 8.427602 | -7.71818  | -27.3038  | -21.0429  | -2.40949 | -9.765884616 | -11.45693019 | -50.74817429 | -50.75685069 |
| 2019 | -16.5289 | 107.282  | 4.635266 | -81.3053 | 11.65959  | -12.5611  | -17.0675  | -4.14521 | 16.72696 | 8.761361 | -8.42948  | -27.0939  | 48.1742   | -2.35599 | -10.76153549 | -12.04330988 | 4.94711429   | 4.940515394  |
| 2020 | -39.3465 | 47.38004 | -68.32   | 98.46063 | 11.38997  | -13.7114  | -21.2373  | -3.67851 | 16.62898 | 9.185791 | -9.20772  | -26.9388  | 25.23743  | -2.32228 | -11.86242918 | -12.7456267  | -1.087728372 | -1.093110115 |





**India:**

|      | C        | C_RSC    | C_RSH | C_RWH    | C_RC     | C_RL     | C_RA     | E        | E_RSC    | E_RSH | E_RWH    | E_RC     | E_RL     | E_RA     | P           | GDP         | HCE         | nHouseholds |
| ---- | -------- | -------- | ----- | -------- | -------- | -------- | -------- | -------- | -------- | ----- | -------- | -------- | -------- | -------- | ----------- | ----------- | ----------- | ----------- |
| 2000 | 157.5464 | 35.49227 | 0     | 17.35762 | 43.13753 | 46.35953 | 15.19951 | 38.99836 | 3.49161  | 0     | 2.339476 | 20.09076 | 11.58124 | 1.495276 | 1012.6356   | 2211693.66  | 1369389.105 | 211.742701  |
| 2001 | 161.9421 | 38.18027 | 0     | 18.38302 | 41.87394 | 47.33482 | 16.17004 | 39.15201 | 3.711367 | 0     | 2.4313   | 20.08255 | 11.35497 | 1.571832 | 1028.610328 | 2370617.126 | 1477393.18  | 215.5989878 |
| 2002 | 166.9365 | 39.39628 | 0     | 18.50031 | 44.55811 | 47.98184 | 16.5     | 41.10389 | 4.017321 | 0     | 2.571056 | 21.19095 | 11.64202 | 1.682539 | 1045.7512   | 2499147.076 | 1522248.463 | 219.676574  |
| 2003 | 174.208  | 42.3832  | 0     | 19.15684 | 45.48696 | 49.63352 | 17.54752 | 42.85488 | 4.391405 | 0     | 2.707635 | 22.08172 | 11.85599 | 1.818133 | 1062.4476   | 2748789.707 | 1639502.151 | 223.6742261 |
| 2004 | 187.5822 | 46.42808 | 0     | 20.68747 | 48.56305 | 52.93922 | 18.96436 | 45.89833 | 4.687228 | 0     | 2.892117 | 24.01304 | 12.39136 | 1.91458  | 1079.222    | 3046209.54  | 1756182.823 | 227.7121718 |
| 2005 | 190.7547 | 47.78447 | 0     | 20.83539 | 49.91922 | 52.97116 | 19.24446 | 46.99239 | 5.043033 | 0     | 3.02377  | 24.49955 | 12.39503 | 2.031004 | 1096.0636   | 3390666.371 | 1952393.027 | 231.9987523 |
| 2006 | 199.8443 | 52.17458 | 0     | 20.95815 | 51.15148 | 54.79897 | 20.76117 | 49.03307 | 5.76778  | 0     | 3.167499 | 25.14553 | 12.65717 | 2.2951   | 1112.9616   | 3777034.028 | 2182099.645 | 235.9444436 |
| 2007 | 209.0912 | 56.38164 | 0     | 22.29562 | 51.76168 | 56.59221 | 22.06004 | 49.67696 | 6.128294 | 0     | 3.296474 | 25.31062 | 12.5438  | 2.397774 | 1129.9052   | 4176280.771 | 2414137.051 | 240.1594964 |
| 2008 | 218.2264 | 60.48833 | 0     | 23.08601 | 53.0081  | 58.37216 | 23.2718  | 51.31683 | 6.670267 | 0     | 3.451291 | 25.94603 | 12.68297 | 2.566266 | 1146.8836   | 4387760.606 | 2647139.585 | 244.45548   |
| 2009 | 239.1338 | 68.98929 | 0     | 24.9875  | 55.66177 | 63.40594 | 26.08928 | 54.40154 | 7.374253 | 0     | 3.649929 | 27.43301 | 13.15566 | 2.788679 | 1163.886    | 4763056.07  | 2711780.542 | 248.8440634 |
| 2010 | 248.2155 | 73.80094 | 0     | 24.98952 | 56.76848 | 65.22794 | 27.42862 | 57.11973 | 8.319552 | 0     | 3.829615 | 28.3243  | 13.55424 | 3.092018 | 1180.9016   | 5229906.991 | 2886256.667 | 253         |
| 2011 | 259.6173 | 79.07416 | 0     | 25.45904 | 58.93364 | 67.34149 | 28.80895 | 59.61631 | 9.209725 | 0     | 4.013625 | 29.15237 | 13.88523 | 3.355363 | 1197.9196   | 5618380.735 | 3213035.2   | 257.9552652 |
| 2012 | 289.025  | 94.05701 | 0     | 28.74471 | 57.71817 | 74.99113 | 33.51395 | 60.79157 | 10.0794  | 0     | 4.161015 | 29.02318 | 13.93653 | 3.591445 | 1216        | 6153155.416 | 3635273.287 | 262.9384275 |
| 2013 | 303.5449 | 101.1821 | 0     | 29.38416 | 59.81191 | 77.94333 | 35.22337 | 63.7514  | 11.16156 | 0     | 4.364943 | 29.96676 | 14.3726  | 3.885544 | 1234.4336   | 6477517.562 | 3823023.247 | 268.1637495 |
| 2014 | 332.1787 | 114.3452 | 0     | 30.96057 | 63.33451 | 84.67338 | 38.86505 | 68.62594 | 12.59847 | 0     | 4.62444  | 31.91202 | 15.20889 | 4.282123 | 1249.7075   | 6781021.983 | 4074006.492 | 272.8832572 |
| 2015 | 338.3611 | 118.1902 | 0     | 30.40434 | 65.30143 | 85.36102 | 39.1041  | 72.51276 | 14.01971 | 0     | 4.860556 | 33.16386 | 15.83011 | 4.638524 | 1265.1634   | 7159798.324 | 4411093.253 | 278         |
| 2016 | 340.1003 | 119.6929 | 0     | 29.89931 | 67.36993 | 84.74004 | 38.39811 | 75.82273 | 15.26082 | 0     | 5.098944 | 34.27044 | 16.29677 | 4.895753 | 1280.7761   | 7735001.687 | 4832567.543 | 283.0638065 |
| 2017 | 356.4234 | 129.0879 | 0     | 31.21762 | 67.73344 | 88.3557  | 40.02868 | 78.45761 | 16.52748 | 0     | 5.320735 | 34.84582 | 16.63859 | 5.12498  | 1294        | 8276934.253 | 5154929.57  | 288.0043932 |
| 2018 | 377.0113 | 139.0114 | 0     | 33.25787 | 70.59018 | 92.68792 | 41.46388 | 81.79863 | 17.52891 | 0     | 5.60098  | 36.40861 | 17.03166 | 5.228468 | 1309.7446   | 9021613.79  | 5672591.728 | 293.7810928 |
| 2019 | 374.417  | 139.3879 | 0     | 32.27544 | 71.77063 | 91.0302  | 39.95287 | 85.45577 | 19.16239 | 0     | 5.861279 | 37.35909 | 17.58048 | 5.492531 | 1328.824    | 9526237.284 | 6080434.683 | 300.622439  |
| 2020 | 375.0321 | 136.4052 | 0     | 32.7247  | 77.94463 | 88.97626 | 38.9813  | 88.70476 | 19.51315 | 0     | 6.16529  | 39.80381 | 17.64612 | 5.576385 | 1347.1286   | 9005119.326 | 5676661.689 | 308.3273855 |



|      | c=C/H    | c-rsc    | c-rsh | c-rwh    | c-rc     | c-rl     | c-ra     | p=P/HCE  | g=GDP/P  | s=HCE/GDP | e=E/HCE  | w-rsc    | w-rsh | w-rwh    | w-rc        | w-rl        | w-ra        | k-rsc       | k-rsh   | k-rwh    | k-rc     | k-rl     | k-ra     |
| ---- | -------- | -------- | ----- | -------- | -------- | -------- | -------- | -------- | -------- | --------- | -------- | -------- | ----- | -------- | ----------- | ----------- | ----------- | ----------- | ------- | -------- | -------- | -------- | -------- |
| 2000 | 744.0466 | 167.6198 | 0     | 81.97505 | 203.7262 | 218.9427 | 71.78291 | 4.782387 | 2184.096 | 0.6191586 | 0.028479 | 0.089532 | 0     | 0.059989 | 0.515169404 | 0.296967266 | 0.03834203  | 10.16501603 | #DIV/0! | 7.419446 | 2.147132 | 4.002986 | 10.16502 |
| 2001 | 751.1264 | 177.0893 | 0     | 85.26488 | 194.2214 | 219.5503 | 75.00055 | 4.770942 | 2304.679 | 0.6232104 | 0.026501 | 0.094794 | 0     | 0.062099 | 0.512937832 | 0.290022532 | 0.040146897 | 10.28738707 | #DIV/0! | 7.560986 | 2.085091 | 4.168645 | 10.28739 |
| 2002 | 759.9196 | 179.3376 | 0     | 84.21613 | 202.8351 | 218.4204 | 75.1104  | 4.760413 | 2389.81  | 0.6091072 | 0.027002 | 0.097736 | 0     | 0.06255  | 0.515546107 | 0.283234106 | 0.040933819 | 9.806603586 | #DIV/0! | 7.195609 | 2.102695 | 4.121435 | 9.806604 |
| 2003 | 778.8472 | 189.4863 | 0     | 85.64615 | 203.3626 | 221.901  | 78.45126 | 4.749978 | 2587.224 | 0.5964451 | 0.026139 | 0.102472 | 0     | 0.063181 | 0.515267395 | 0.276654269 | 0.042425337 | 9.651398896 | #DIV/0! | 7.075118 | 2.059937 | 4.186368 | 9.651399 |
| 2004 | 823.7688 | 203.8893 | 0     | 90.8492  | 213.2651 | 232.483  | 83.28214 | 4.739413 | 2822.598 | 0.5765141 | 0.026135 | 0.102122 | 0     | 0.063011 | 0.523179057 | 0.269974075 | 0.041713504 | 9.905230254 | #DIV/0! | 7.153054 | 2.022361 | 4.272269 | 9.90523  |
| 2005 | 822.2229 | 205.9687 | 0     | 89.80819 | 215.1702 | 228.3252 | 82.9507  | 4.724437 | 3093.494 | 0.575814  | 0.024069 | 0.107316 | 0     | 0.064346 | 0.521351552 | 0.263766699 | 0.043219843 | 9.47534442  | #DIV/0! | 6.890533 | 2.037556 | 4.273581 | 9.475344 |
| 2006 | 846.9975 | 221.1308 | 0     | 88.82665 | 216.7946 | 232.2537 | 87.99177 | 4.717049 | 3393.679 | 0.5777284 | 0.022471 | 0.11763  | 0     | 0.064599 | 0.512827864 | 0.258135333 | 0.046807174 | 9.045868416 | #DIV/0! | 6.616626 | 2.034218 | 4.329481 | 9.045868 |
| 2007 | 870.6346 | 234.7675 | 0     | 92.83671 | 215.5304 | 235.6443 | 91.85578 | 4.704812 | 3696.134 | 0.5780591 | 0.020578 | 0.123363 | 0     | 0.066358 | 0.509504151 | 0.252507434 | 0.048267315 | 9.200217    | #DIV/0! | 6.763474 | 2.045058 | 4.511567 | 9.200217 |
| 2008 | 892.704  | 247.4411 | 0     | 94.43852 | 216.8415 | 238.7844 | 95.19853 | 4.691585 | 3825.812 | 0.6033008 | 0.019386 | 0.129982 | 0     | 0.067255 | 0.505604742 | 0.247150345 | 0.050008275 | 9.068351471 | #DIV/0! | 6.689095 | 2.043014 | 4.602404 | 9.068351 |
| 2009 | 960.9784 | 277.239  | 0     | 100.4143 | 223.6813 | 254.8019 | 104.8419 | 4.67717  | 4092.373 | 0.5693363 | 0.020061 | 0.135552 | 0     | 0.067092 | 0.5042691   | 0.241825174 | 0.051261034 | 9.355426947 | #DIV/0! | 6.846024 | 2.029007 | 4.819669 | 9.355427 |
| 2010 | 981.089  | 291.7033 | 0     | 98.77281 | 224.3813 | 257.818  | 108.4135 | 4.667595 | 4428.741 | 0.5518753 | 0.01979  | 0.145651 | 0     | 0.067045 | 0.495875984 | 0.237295279 | 0.054132222 | 8.870783129 | #DIV/0! | 6.525336 | 2.004232 | 4.812364 | 8.870783 |
| 2011 | 1006.443 | 306.5422 | 0     | 98.69555 | 228.4646 | 261.0588 | 111.682  | 4.643904 | 4690.115 | 0.5718792 | 0.018555 | 0.154483 | 0     | 0.067324 | 0.488999949 | 0.232909838 | 0.056282628 | 8.585941456 | #DIV/0! | 6.343152 | 2.021572 | 4.849866 | 8.585941 |
| 2012 | 1099.212 | 357.715  | 0     | 109.3211 | 219.5121 | 285.2042 | 127.4593 | 4.624657 | 5060.161 | 0.5907982 | 0.016723 | 0.165803 | 0     | 0.068447 | 0.477421169 | 0.229250967 | 0.059078008 | 9.331606354 | #DIV/0! | 6.9081   | 1.988692 | 5.380906 | 9.331606 |
| 2013 | 1131.939 | 377.3147 | 0     | 109.5754 | 223.0425 | 290.6557 | 131.3502 | 4.603283 | 5247.36  | 0.5901988 | 0.016676 | 0.175079 | 0     | 0.068468 | 0.47005644  | 0.225447598 | 0.06094838  | 9.065234629 | #DIV/0! | 6.731852 | 1.995942 | 5.42305  | 9.065235 |
| 2014 | 1217.292 | 419.0261 | 0     | 113.4572 | 232.0938 | 310.2916 | 142.4237 | 4.579642 | 5426.087 | 0.6007954 | 0.016845 | 0.183582 | 0     | 0.067386 | 0.465013906 | 0.221620143 | 0.06239802  | 9.07611824  | #DIV/0! | 6.694986 | 1.98466  | 5.567361 | 9.076118 |
| 2015 | 1217.126 | 425.1447 | 0     | 109.3681 | 234.8972 | 307.054  | 140.6622 | 4.550947 | 5659.189 | 0.6160918 | 0.016439 | 0.193341 | 0     | 0.06703  | 0.457352048 | 0.218307924 | 0.063968381 | 8.430289773 | #DIV/0! | 6.255321 | 1.969054 | 5.392319 | 8.43029  |
| 2016 | 1201.497 | 422.8477 | 0     | 105.6275 | 238.0026 | 299.3673 | 135.6518 | 4.52469  | 6039.308 | 0.6247662 | 0.01569  | 0.20127  | 0     | 0.067248 | 0.451981021 | 0.21493255  | 0.064568413 | 7.843146366 | #DIV/0! | 5.863824 | 1.965832 | 5.199805 | 7.843146 |
| 2017 | 1237.562 | 448.2151 | 0     | 108.3929 | 235.182  | 306.786  | 138.9863 | 4.492987 | 6396.394 | 0.6228066 | 0.01522  | 0.210655 | 0     | 0.067817 | 0.444135687 | 0.212071134 | 0.065321645 | 7.81050376  | #DIV/0! | 5.867164 | 1.943804 | 5.310287 | 7.810504 |
| 2018 | 1283.307 | 473.1803 | 0     | 113.2063 | 240.2816 | 315.5    | 141.1387 | 4.458233 | 6888.071 | 0.6287779 | 0.01442  | 0.214293 | 0     | 0.068473 | 0.44510048  | 0.208214494 | 0.063918767 | 7.93040725  | #DIV/0! | 5.937866 | 1.938832 | 5.442095 | 7.930407 |
| 2019 | 1245.473 | 463.6643 | 0     | 107.362  | 238.7401 | 302.8057 | 132.9005 | 4.420242 | 7168.923 | 0.6382829 | 0.014054 | 0.224238 | 0     | 0.068588 | 0.437174576 | 0.205726083 | 0.064273377 | 7.274035813 | #DIV/0! | 5.506553 | 1.921102 | 5.177913 | 7.274036 |
| 2020 | 1216.344 | 442.4037 | 0     | 106.1362 | 252.7983 | 288.5772 | 126.4283 | 4.36915  | 6684.677 | 0.6303816 | 0.015626 | 0.219979 | 0     | 0.069503 | 0.44872239  | 0.198930986 | 0.062864554 | 6.990424565 | #DIV/0! | 5.307894 | 1.95822  | 5.042255 | 6.990425 |



|      | Δc\|p    | Δc\|g    | Δc\|s    | Δc\|e    | Δc\|w-rsc | Δc\|w-rsh | Δc\|w-rwh | Δc\|w-rc | Δc\|w-rl | Δc\|w-ra  | Δc\|k-rsc | Δc\|k-rsh | Δc\|k-rwh | Δc\|k-rc | Δc\|k-rl     | Δc\|k-ra     | sum          | Δc           |
| ---- | -------- | -------- | -------- | -------- | --------- | --------- | --------- | -------- | -------- | --------- | --------- | --------- | --------- | -------- | ------------ | ------------ | ------------ | ------------ |
| 2001 | -1.79122 | 40.1746  | 4.876253 | -53.8125 | 9.839866  | 0         | 2.890094  | -0.86361 | -5.18809 | 3.3753662 | 2.061973  | 0         | 1.579972  | -5.83294 | 8.890531417  | 0.878106195  | 7.078363173  | 7.079750832  |
| 2002 | -1.66925 | 27.40433 | -17.2936 | 14.15955 | 5.446874  | 0         | 0.613482  | 1.006795 | -5.18662 | 1.4569347 | -8.52965  | 0         | -4.19719  | 1.668872 | -2.494144221 | -3.592349089 | 8.794020818  | 8.793226167  |
| 2003 | -1.68831 | 61.06394 | -16.1617 | -24.994  | 8.723633  | 0         | 0.852871  | -0.10983 | -5.17481 | 2.747488  | -2.9412   | 0         | -1.43419  | -4.17254 | 3.441542114  | -1.224700946 | 18.92823406  | 18.92760485  |
| 2004 | -1.78378 | 69.75339 | -27.2272 | -0.11282 | -0.67176  | 0         | -0.23783  | 3.173645 | -5.55217 | -1.367925 | 5.103744  | 0         | 0.966495  | -3.83428 | 4.613760158  | 2.098679695  | 44.9219347   | 44.92153107  |
| 2005 | -2.60458 | 75.4223  | -1.00012 | -67.7788 | 10.16629  | 0         | 1.893156  | -0.74958 | -5.35927 | 2.9485355 | -9.09259  | 0         | -3.37744  | 1.603464 | 0.07075661   | -3.687856175 | -1.545765687 | -1.545816189 |
| 2006 | -1.30609 | 77.29027 | 2.77     | -57.3522 | 19.58926  | 0         | 0.350876  | -3.56031 | -4.96976 | 6.8132228 | -9.90134  | 0         | -3.62294  | -0.35415 | 2.992672185  | -3.963431607 | 24.77609978  | 24.77454219  |
| 2007 | -2.23084 | 73.31496 | 0.491479 | -75.578  | 10.84325  | 0         | 2.439782  | -1.40554 | -5.15692 | 2.7618654 | 3.855508  | 0         | 1.993538  | 1.148839 | 9.637783381  | 1.521181296  | 23.63693779  | 23.63715725  |
| 2008 | -2.48205 | 30.40127 | 37.68046 | -52.598  | 12.59867  | 0         | 1.256365  | -1.6609  | -5.08672 | 3.3136763 | -3.47992  | 0         | -1.03543  | -0.2162  | 4.728605945  | -1.3500684   | 22.06978431  | 22.06940301  |
| 2009 | -2.85077 | 62.39865 | -53.6813 | 31.72801 | 10.99622  | 0         | -0.23514  | -0.58258 | -5.37371 | 2.4728216 | 8.16732   | 0         | 2.258559  | -1.51519 | 11.3797311   | 3.11482416   | 68.2774728   | 68.27441031  |
| 2010 | -1.9898  | 76.6994  | -30.2457 | -13.2034 | 20.43674  | 0         | -0.06979  | -3.76018 | -4.84671 | 5.8105294 | -15.1288  | 0         | -4.77796  | -2.75229 | -0.388796417 | -5.671371895 | 20.11186269  | 20.11051201  |
| 2011 | -5.05652 | 56.98127 | 35.38176 | -64.0705 | 17.6063   | 0         | 0.409845  | -3.16157 | -4.83946 | 4.2867391 | -9.76045  | 0         | -2.79581  | 1.950476 | 2.013925114  | -3.591356256 | 25.35464944  | 25.35406367  |
| 2012 | -4.36989 | 79.90114 | 34.2439  | -109.367 | 23.43895  | 0         | 1.719026  | -5.36679 | -4.32197 | 5.7875072 | 27.6052   | 0         | 8.866147  | -3.6726  | 28.36138149  | 9.943499263  | 92.76874275  | 92.76856864  |
| 2013 | -5.16748 | 40.52243 | -1.13231 | -3.14262 | 20.00329  | 0         | 0.03352   | -3.43997 | -4.8168  | 4.0330527 | -10.6409  | 0         | -2.82862  | 0.805248 | 2.24628467   | -3.747337314 | 32.72783093  | 32.72698938  |
| 2014 | -6.04542 | 39.32431 | 20.89296 | 11.85143 | 18.86417  | 0         | -1.7762   | -2.4541  | -5.14315 | 3.2159461 | 0.477315  | 0         | -0.61232  | -1.2898  | 7.888448418  | 0.164156662  | 85.35774402  | 85.3537924   |
| 2015 | -7.6505  | 51.19854 | 30.60267 | -29.7043 | 21.86236  | 0         | -0.58982  | -3.87922 | -4.64804 | 3.5180589 | -31.1559  | 0         | -7.56702  | -1.84332 | -9.860631313 | -10.44792417 | -0.16504327  | -0.166042279 |
| 2016 | -6.99732 | 78.61498 | 16.9077  | -56.3771 | 17.04005  | 0         | 0.348809  | -2.7932  | -4.72447 | 1.2897503 | -30.6087  | 0         | -6.94693  | -0.38716 | -11.02248138 | -9.972609192 | -15.62867617 | -15.62946928 |
| 2017 | -8.5744  | 70.05073 | -3.83074 | -37.0895 | 19.84363  | 0         | 0.900719  | -4.1427  | -4.06178 | 1.592564  | -1.81592  | 0         | 0.060923  | -2.66613 | 6.371772419  | -0.572676431 | 36.06648324  | 36.06538909  |
| 2018 | -9.78647 | 93.33329 | 12.02583 | -68.0441 | 7.887738  | 0         | 1.066609  | 0.515843 | -5.71003 | -3.040759 | 7.016978  | 0         | 1.327014  | -0.60882 | 7.628212162  | 2.133800114  | 45.74509364  | 45.74456858  |
| 2019 | -10.8199 | 50.5268  | 18.96885 | -32.4819 | 21.24659  | 0         | 0.186107  | -4.30338 | -3.71648 | 0.7578324 | -40.4671  | 0         | -8.31471  | -2.20027 | -15.38192974 | -11.83398259 | -37.8334532  | -37.83413961 |
| 2020 | -14.3099 | -86.0828 | -15.3318 | 130.504  | -8.68561  | 0         | 1.414702  | 6.4059   | -9.92966 | -2.873159 | -18.0138  | 0         | -3.92231  | 4.701981 | -7.848696957 | -5.155678325 | -29.12684277 | -29.12897894 |



<script type="text/javascript" src="//rf.revolvermaps.com/0/0/7.js?i=5vnbozco0jv&amp;m=0&amp;h=256&amp;c=ff0000&amp;r=0" async="async"></script>
[TOC]





