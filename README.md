## Black Litterman model을 활용한 주식 포트폴리오 비중 결정
***
#### 1. '24년도 2학기 SWIC: Multi Asset Macro 팀에서 팀장을 맡으며 여러 자산군에 투자하는 펀드 완성


#### 2. 그러나 부족한 요소가 정말 많았음


<details>
  <summary>자가 피드백</summary>
  
a. 모델에 대한 이해가 매우 부족했음
  
b. 데이터를 가공하는 능력이 부족했음
     
c. .cvs 파일을 코드가 직접 읽게 하고 싶었으나 이를 구현하지 못하여 엑셀에서 구한 값을 직접 코드에 대입해줬음.
</details>

#### 3. Input 값들에 대한 경제학적 의미와 그 값에 대한 검토가 반드시 필요


#### 4. 특히 tau값이나 risk_aversion에 대한 이해 없이 임의로 사용


#### 5. 그럼에도 파이썬 프로그램을 통해 결과를 만들었음


#### 6. 펀드의 기대 수익률: 13.8246% / 표준편차: 15.6173%
![SWIC_stock_allocation_result](https://github.com/user-attachments/assets/b6bc64a0-3d92-499d-8827-c439ac9b5ddc)

---
#### 해당 펀드 내 주식의 비중을 정하기 위해 Black Litterman model 활용하였습니다.
[여기에서](https://pleasurehwang.tistory.com/14) 해당 모델에 대한 간략한 한글 소개를 볼 수 있습니다.
