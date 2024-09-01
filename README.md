# 2022 Data Youth Campus
This is the private repository from Data Youth Campus, held by Ministry of Science and ICT with Yonsei University in June ~ August, 2022.

Education consists of the 'Big Data Analysis and Processing' course (140H) and the team project (210H). I'm a leader of the team 'Coding in the Trap'. Project code will be released soon in this repository.

Participate in 1 personal project and 2 team projects. Among them, E-commerce Sales Prediction project has been submitted to the competition of 2022 Data Youth Campus.

For more information, visit https://dataonair.or.kr/bigjob/

## Content
- [Thumbnail Complexity Analysis](#thumbnail-complexity-analysis)
- [Webtoon Popularity Forecast](#webtoon-popularity-forecast)
- [E-commerce Sales Prediction](#e-commerce-sales-prediction)

## 🖼️ Thumbnail Complexity Analysis
### Personal Project 
**Date**: July, 2022  
**Advisor**: prof. Hyunho Lee  
To understand the relationship between thumbnail images and webtoon preference, analyze the image complexity of thumbnail images. JPG compression, Shannon entopry, and Canndy edge detection methods are used to analze. These are low level vision approaches from HCI.  
Detect and analyze character faces, and classify draing styles would remain for future works.

Run
```
conda create -n trap python==3.8.0
conda activate trap
pip install -r requirements.txt
demo.ipynb
```

</br>

## 🌟 Webtoon Popularity Forecast
### Team: Coding in the Trap (Team Leader)
**Date**: July ~ August, 2022  
**Advisor**: prof. Hyunho Lee  
**Theme**: Webtoon ranking prediction using webtoon content and author information.  
**Dataset**: Naver Webtoon   
**Part**: Scraping all webtoon information from Naver  


#### Context
(Optional) Basic Information with BeautifulSoup
1. Basic Information: get basic webtoon information from Naver (Without BeautifulSoup)
2. Ranking: get webtoon ranking
3. Previous Work ID
4. Previous Work Information
5. Previous Work Ranking
6. Num Previous Work
7. Num Episodes

</br>

## 📈 E-commerce Sales Prediction
### Team: Coding in the Trap (Team Leader)  
**Date**: August, 2022  
**Advisor**: prof. Hyunho Lee   
**Theme**: Propose sales analysis and marketing strategy using synthetic data from a health supplement shopping mall company.  
**Dataset**: Shopping mall anonymized dataset (5 years)    
**Part**: Data scraping & data analysis through machine learning