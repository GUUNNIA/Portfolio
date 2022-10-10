# Portfolio

## [ MUSINSA PROJECT ] 
[- MUSINSA_PROJECT_PPT](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/MUSINSA_PROJECT_PDF.pdf)

<hr>

#### <h3>#1. 상품별 고유 번호 크롤링 후 해당 상품들의 리뷰와 별점 크롤링 </h3> : [ReviewCrawling_from_each_item_number_based](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/ReviewCrawling_from_each_item_number_based.ipynb)
      [ 별점 : 100 / 80 / 60 / 40 / 20 ] == [ 별점 : 5점 / 4점 / 3점 / 2점 / 1점 ]
      
| Need in #1 Files| File Name | LINK |
|-----------------|-----------|------|
|1.|reset_star_train.tsv| [DATA](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/Example_Data_File/reset_star_train.tsv) |
|2.|reset_star_test.tsv| [DATA](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/Example_Data_File/reset_star_test.tsv) |

<hr>

#### #2. 긍정 / 부정 사전 만들기 & 모델 학습 : [Making Dicctionary_Positive,Negative - Model_Training](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/Making_Dicctionary_Positive%2CNegative_Model_Training.ipynb)


| Need in #2 Files| File Name | LINK | NOTES |
|-----------------|-----------|------|-------|
|1.|[Org]_Musinsa_Standard_review_Label.csv| [DATA](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/Example_Data_File/%5BOrg%5D_Musinsa_Standard_review_Label.csv) | Raw Crawling Data |
|2.|Total(Pos+Neg)_Word_Counts.csv| [DATA](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/Example_Data_File/Total(Pos%2BNeg)_Word_Counts.csv) | ipynb file 'df_1' 내용 참조 |
|3.|1000_Total(Pos+Neg)_Word_Counts.csv| [DATA](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/Example_Data_File/1000_Total(Pos%2BNeg)_Word_Counts.csv) | ipynb file 'df_2' 내용 참조 |
|4.|[HandWork]_SCORE_Intersection_3_to_-3.csv| [DATA](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/Example_Data_File/%5BHandWork%5D_SCORE_Intersection_3_to_-3.csv) | df_1,df_2 Intersection Words |
|5.|[Using_For_Training]_Review_Dataset.csv| [DATA](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/Example_Data_File/%5BUsing_For_Training%5D_Review_Dataset.csv) | For Training |


<hr>

[ 참조 ]
- Stopwords List : https://raw.githubusercontent.com/yoonkt200/FastCampusDataset/master/korean_stopwords.txt

<hr>
<br>

#### #3. 큐레이팅 글(전문성) 과 상품 상세 설명(전문단어)을 비교하여 상품 추천 시스템 제작 [ Using only MusinsaStandard Items ]

| NO.| File Name | LINK | NOTE |
|-----------------|-----------|------|------|
|1-1.| TotalPage_Crawling&Refine&Tokenize | [DATA](https://github.com/GUUNNIA/Portfolio/blob/main/MUSINSA/1-1.TotalPage_Crawling%26Refine%26Tokenize.ipynb) | - MusinsaStandard 상품 전체 상세설명 크롤링 + 토큰화. <br> - 큐레이팅 글과의 유사도 비교를 위함. |
|1-2.| - | [DATA](https://) | - |

## [ CAR DAMAGE DETECTION ]



[- CAR_DAMAGE_DETECTION_PPT](https://github.com/GUUNNIA/Portfolio/blob/main/CAR_DAMAGE_DETECTION/car%20damage.pdf)

업로드예정
