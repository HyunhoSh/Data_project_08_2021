# Data_project_08_2021(team project)
## Correlation analysis of non-Seoul region tourism infrastructure and the number of visitors

> Hyphothesis: Areas with a large number of external visitors will also have a lot of tourism infrastructure.
> > The correlation coefficient between the number of external visitors and tourism infrastructure is expected to be high
> Why is Seoul excluded? -> The density of population is very high and all infrastructure is developed so that distortion is likely to occur in the result.

## Contents
1. Collecting and pre-processing the number of visitors to local governments nationwide
2. Extraction of top 15 regions and bottom 15 regions based on the number of external visitors
3. Collection and pre-processing of tourism data in areas other than Seoul
4. Analyse tourism infrastructure ["tourist destinations", "cultural facilities", "festival performance events", "travel course", "leports", "accomodation", "shopping", "restaurants"]
5. After comparing and analysing the commonalities and differences of tourism infrastructure in the top 15 regions, draw conclusions by comparing them with the bottom 15 regions
6. Extract the correlation by calculating the correlation coefficient


## Conclusion
- A quantitative linear relationship was observed between cultural facilities and festival performance events, but no correlation with other infrastructure was observed.
> There will be other factors except the tour infrastructure, so the additional analysis of the increase of the number of tourists is needed.







#### <Data source>
#### 한국관광데이터랩(외부관광객수)-> https://datalab.visitkorea.or.kr/datalab/portal/bda/getLocgoAna.do
#### TourAPI3.0 사이트(관광인프라수집)-> https://api.visitkorea.or.kr/search/galleryList.do
#### DBPia_참고논문 -> https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE01642617
