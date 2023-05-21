<script type="text/javascript" src="2html/jquery-3.3.1.min.js"></script>
<script type="text/javascript" src="2html/2html.js"></script>
<link rel="stylesheet" type="text/css" href="2html/style.css">

# IBED

International Building Emission Dataset (IBED)

A multi-regional dataset aims to monitor energy trends, emissions mitigation, and building stock on a global scale.

IBED is a project led by [Lawrence Berkeley National Laboratory<img src='./image/logo-LBNL.png' style='width: 4em;'>](https://www.lbl.gov/) (LBNL, operated by UC Berkeley for U.S. DOE), [Tsinghua University<img src='./image/logo-THQ.png' style='width: 4em;'>](https://www.tsinghua.edu.cn), and [Chongqing University<img src='./image/logo_CQU.png' style='width: 4em;'>](https://www.cqu.edu.cn).

<div align=left><img  src="IBED_logo1.png" width=30%/> </div> 



## About IBED                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   

We are pleased to announce the release of a public version of our dataset, which is accessible at [http://ibed.world](http://ibed.world/). Our dataset is established based on the IEA database, which has clear distinctions between the end uses relevant to residential and commercial energy activities in its energy balance sheet.

To ensure the reliability of our database, we used the [IEA dataset](https://www.iea.org/data-and-statistics) as the primary reference to compile comprehensive and trustworthy data tables for each carbon-emitting country. For major emitters such as [China](https://doi.org/10.1016/j.enconman.2019.111915), [the United States](https://www.sciencedirect.com/science/article/pii/S2542435119303575), and [India](https://doi.org/10.1016/j.apenergy.2019.01.065), we accounted for and calibrated the building energy consumption data and the corresponding carbon emissions data based on the baseline dataset. For other carbon-emitting countries, we collected, cleaned, and validated survey reports and statistical results from regional governments and research institutions, which were then integrated with the baseline dataset to build a unified and standardized database.

<img src="About%20IBED.png" alt="About IBED" style="zoom:120%;" />





## Carbon emissions of residential building operations 

| Regions                                                     | Name                                | Abbreviations | Unit            | 2000   | 2010   | 2020  |
| :---------------------------------------------------------- | :---------------------------------- | :------------ | :-------------- | :----- | :----- | :---- |
| Europe & New Zealand                                        | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 1089.5 | 1086.1 | 802.2 |
| Europe & New Zealand                                        | Share of residential space heating  | $C_{RSH}$     | $\%$            | 50.3%  | 50.8%  | 49.8% |
| Europe & New Zealand                                        | Share of residential space cooling  | $C_{RSC}$     | $\%$            | 2.3%   | 2.1%   | 2.3%  |
| Europe & New Zealand                                        | Share of other end uses             | $C_{RA}$      | $\%$            | 47.4%  | 47.1%  | 47.9% |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 63.2   | 82.5   | 102.4 |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share of residential space heating  | $C_{RSH}$     | $\%$            | 17.2%  | 18.3%  | 17.8% |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share  of residential space cooling | $C_{RSC}$     | $\%$            | 3.2%   | 6.7%   | 9.8%  |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share of other end uses             | $C_{RA}$      | $\%$            | 79.6%  | 75.0%  | 72.4% |
| China                                                       | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 412.9  | 690.7  | 803.4 |
| China                                                       | Share of residential space heating  | $C_{RSH}$     | $\%$            | 43.0%  | 43.4%  | 36.1% |
| China                                                       | Share of residential space cooling  | $C_{RSC}$     | $\%$            | 6.2%   | 6.1%   | 11.3% |
| China                                                       | Share of other end uses             | $C_{RA}$      | $\%$            | 50.9%  | 50.5%  | 52.5% |
| India                                                       | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 157.5  | 248.2  | 375.0 |
| India                                                       | Share of residential space heating  | $C_{RSH}$     | $\%$            | 22.5%  | 29.7%  | 36.4% |
| India                                                       | Share of residential space cooling  | $C_{RSC}$     | $\%$            | 0.0%   | 0.0%   | 0.0%  |
| India                                                       | Share of other end uses             | $C_{RA}$      | $\%$            | 77.5%  | 70.3%  | 63.6% |
| Northeast Asia (Japan, South Korea)                         | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 239.9  | 285.5  | 281.6 |
| Northeast Asia (Japan, South Korea)                         | Share of residential space heating  | $C_{RSH}$     | $\%$            | 29.2%  | 29.6%  | 26.7% |
| Northeast Asia (Japan, South Korea)                         | Share of residential space cooling  | $C_{RSC}$     | $\%$            | 3.4%   | 4.0%   | 3.2%  |
| Northeast  Asia (Japan, South Korea)                        | Share of other end uses             | $C_{RA}$      | $\%$            | 67.4%  | 66.4%  | 70.0% |
| Africa (South Africa, Morocco)                              | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 41.0   | 66.1   | 88.2  |
| Africa (South Africa, Morocco)                              | Share of residential space heating  | $C_{RSH}$     | $\%$            | 14.4%  | 14.2%  | 13.8% |
| Africa (South Africa, Morocco)                              | Share of residential space cooling  | $C_{RSC}$     | $\%$            | 14.3%  | 14.2%  | 13.7% |
| Africa (South Africa, Morocco)                              | Share of other end uses             | $C_{RA}$      | $\%$            | 71.3%  | 71.7%  | 72.5% |
| United States                                               | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 1209.3 | 1193.9 | 902.0 |
| United States                                               | Share of residential space heating  | $C_{RSH}$     | $\%$            | 36.5%  | 29.3%  | 34.2% |
| United States                                               | Share of residential space cooling  | $C_{RSC}$     | $\%$            | 8.3%   | 10.9%  | 10.1% |
| United States                                               | Share of other end uses             | $C_{RA}$      | $\%$            | 55.2%  | 59.8%  | 55.7% |
| Canada                                                      | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 79.7   | 73.9   | 67.2  |
| Canada                                                      | Share of residential space heating  | $C_{RSH}$     | $\%$            | 58.9%  | 58.0%  | 62.1% |
| Canada                                                      | Share of residential space cooling  | $C_{RSC}$     | $\%$            | 1.2%   | 2.6%   | 2.2%  |
| Canada                                                      | Share of other end uses             | $C_{RA}$      | $\%$            | 39.9%  | 39.4%  | 35.7% |
| Australia                                                   | Carbon emissions                    | $C$           | $\text{MtCO}_2$ | 54.9   | 67.8   | 54.8  |
| Australia                                                   | Share of residential space heating  | $C_{RSH}$     | $\%$            | 14.5%  | 14.8%  | 17.3% |
| Australia                                                   | Share of residential space cooling  | $C_{RSC}$     | $\%$            | 5.2%   | 7.3%   | 8.2%  |
| Australia                                                   | Share of other end uses             | $C_{RA}$      | $\%$            | 80.3%  | 77.9%  | 74.6% |









## Energy consumption of residential building operations 

| Regions                                                     | Name                                | Abbreviations | Unit                     | 2000     | 2010     | 2020     |
| ----------------------------------------------------------- | ----------------------------------- | ------------- | ------------------------ | -------- | -------- | -------- |
| Europe & New Zealand                                        | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 440710.3 | 485132.6 | 426999.2 |
| Europe & New Zealand                                        | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 62.3%    | 61.6%    | 57.2%    |
| Europe & New Zealand                                        | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 1.9%     | 1.9%     | 2.0%     |
| Europe & New Zealand                                        | Share of other end uses             | $E_{RA}$      | $\%$                     | 35.8%    | 36.4%    | 40.8%    |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 1668.4   | 2001.8   | 2326.2   |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 13.4%    | 14.7%    | 14.9%    |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 5.5%     | 7.5%     | 9.7%     |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Share of other end uses             | $E_{RA}$      | $\%$                     | 81.2%    | 77.9%    | 75.3%    |
| China                                                       | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 5157.2   | 11614.6  | 19192.9  |
| China                                                       | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 50.4%    | 50.4%    | 44.3%    |
| China                                                       | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 4.8%     | 4.8%     | 9.9%     |
| China                                                       | Share of other end uses             | $E_{RA}$      | $\%$                     | 44.8%    | 44.8%    | 45.8%    |
| India                                                       | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 1142.2   | 1672.9   | 2598.0   |
| India                                                       | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 9.0%     | 14.6%    | 22.0%    |
| India                                                       | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 0.0%     | 0.0%     | 0.0%     |
| India                                                       | Share of other end uses             | $E_{RA}$      | $\%$                     | 91.0%    | 85.4%    | 78.0%    |
| Northeast Asia (Japan, South Korea)                         | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 2766.1   | 2982.9   | 2829.8   |
| Northeast Asia (Japan, South Korea)                         | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 34.8%    | 35.9%    | 33.6%    |
| Northeast Asia (Japan, South Korea)                         | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 2.3%     | 2.7%     | 2.2%     |
| Northeast Asia (Japan, South Korea)                         | Share of other end uses             | $E_{RA}$      | $\%$                     | 62.9%    | 61.3%    | 64.2%    |
| Africa (South Africa, Morocco)                              | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 569.5    | 574.2    | 681.7    |
| Africa (South Africa, Morocco)                              | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 14.8%    | 13.6%    | 12.8%    |
| Africa (South Africa, Morocco)                              | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 13.1%    | 12.7%    | 12.5%    |
| Africa (South Africa, Morocco)                              | Share of other end uses             | $E_{RA}$      | $\%$                     | 72.1%    | 73.8%    | 74.6%    |
| United States                                               | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 10942.2  | 11560.3  | 11499.0  |
| United States                                               | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 55.6%    | 47.5%    | 45.0%    |
| United States                                               | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 4.7%     | 6.8%     | 7.9%     |
| United States                                               | Share of other end uses             | $E_{RA}$      | $\%$                     | 39.7%    | 45.7%    | 47.1%    |
| Canada                                                      | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 1308.7   | 1334.4   | 1442.2   |
| Canada                                                      | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 63.0%    | 60.3%    | 62.0%    |
| Canada                                                      | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 1.0%     | 2.4%     | 2.3%     |
| Canada                                                      | Share of other end uses             | $E_{RA}$      | $\%$                     | 36.0%    | 37.3%    | 35.7%    |
| Australia                                                   | Energy consumption                  | $E$           | Peta joule $(\text{PJ})$ | 378.4    | 428.8    | 455.2    |
| Australia                                                   | Share of residential  space heating | $E_{RSH}$     | $\%$                     | 44.2%    | 37.2%    | 35.7%    |
| Australia                                                   | Share of residential space cooling  | $E_{RSC}$     | $\%$                     | 2.7%     | 4.2%     | 4.7%     |
| Australia                                                   | Share of other end uses             | $E_{RA}$      | $\%$                     | 53.1%    | 58.5%    | 59.5%    |







## Socio-economic indicators of residential buildings

| Regions                                                     |          Name           | Abbreviations |          Unit          | 2000   | 2010   | 2020   |
| ----------------------------------------------------------- | :---------------------: | :-----------: | :--------------------: | ------ | ------ | ------ |
| Europe & New Zealand                                        |    Population  size     |      $P$      |    Million  persons    | 659.3  | 682.5  | 704.8  |
| Europe & New Zealand                                        | Average  household size |      $p$      | persons per  household | 2.7    | 2.6    | 2.4    |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) |    Population  size     |      $P$      |    Million  persons    | 270.0  | 302.1  | 331.4  |
| South America (Brazil, Colombia, Argentina, Chile, Uruguay) | Average  household size |      $p$      | persons per  household | 4.5    | 4.0    | 3.6    |
| China                                                       |    Population  size     |      $P$      |    Million  persons    | 1262.6 | 1337.7 | 1411.1 |
| China                                                       | Average  household size |      $p$      | persons per  household | 3.4    | 3.1    | 2.6    |
| India                                                       |    Population  size     |      $P$      |    Million  persons    | 1012.6 | 1180.9 | 1347.1 |
| India                                                       | Average  household size |      $p$      | persons per  household | 5.4    | 5.1    | 4.8    |
| Northeast Asia (Japan, South Korea)                         |    Population  size     |      $P$      |    Million  persons    | 173.9  | 177.6  | 178.1  |
| Northeast Asia (Japan, South Korea)                         | Average  household size |      $p$      | persons per  household | 2.8    | 2.6    | 2.4    |
| Africa (South Africa, Morocco)                              |    Population  size     |      $P$      |    Million  persons    | 73.8   | 83.6   | 96.2   |
| Africa (South Africa, Morocco)                              | Average  household size |      $p$      | persons per  household | 6.1    | 5.5    | 5.7    |
| United States                                               |    Population  size     |      $P$      |    Million  persons    | 282.2  | 309.3  | 331.5  |
| United States                                               | Average  household size |      $p$      | persons per  household | 2.6    | 2.6    | 2.5    |
| Canada                                                      |    Population  size     |      $P$      |    Million  persons    | 30.7   | 34.0   | 36.7   |
| Canada                                                      | Average  household size |      $p$      | persons per  household | 3.0    | 2.9    | 2.8    |
| Australia                                                   |    Population  size     |      $P$      |    Million  persons    | 19.2   | 22.0   | 25.7   |
| Australia                                                   | Average  household size |      $p$      | persons per  household | 2.6    | 2.6    | 2.5    |



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











[TOC]





