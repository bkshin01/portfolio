# 📖 신보경
> **데이터를 통해 더 나은 결정을 돕고 가치를 만들어가는 데이터 엔지니어, 신보경입니다.**

<br>

# 🖥️ Skill
- 자주 사용하고 자신있음.<br>
  `python`, `Airflow`, `MySQL`, `AWS`, `Docker`
- 사용해본 경험이 있음.<br>
  `JAVA`, `HTML`, `Node.js`, `PostgreSQL`, `PySpark`

<br>

# 🏫 Education
이화여자대학교 사이버보안전공
> 2020.03 - 2025.02
- 사이버 보안 지식과 함께 데이터베이스, 컴퓨터 구조, 네트워크 등의 컴퓨터 과학 기본 지식을 습득 
- 전공 학점: 3.64/4.5

<br>

# ✍️ Projects.
## 1️⃣ 날씨와 농산물 거래의 상관관계 분석 프로젝트
> 2024.11 - 2025.01<br><br>
> 기여
> - 5천만 건의 데이터를 처리하는 클라우드 인프라 설계
> - 동적 도매 데이터 ETL 파이프라인 구축
> - 데이터 시각화, ML 학습 지원을 위한 데이터 마트 설계
> - 기존 데이터를 활용해 추가 데이터를 생성해 날씨 기반 도매 가격 예측 모델의 정확도 74%까지 향상

<table>
  <td>
    <img src="https://github.com/user-attachments/assets/23607582-f594-4328-a929-8fbe22112e92" height="200">
    <img src="https://github.com/user-attachments/assets/0038566d-2733-4aaf-aa7f-0546c69dc9e4" height="190">
  </td>
</table>

Tech Stack
- `Airflow`, `python`, `AWS EC2`, `AWS Redshift`, `Preset`

Description
- 사용 데이터
  - 기온, 강수량, 적설량 데이터의 평균, 최대, 최소 데이터 사용
  - 농산물의 과거 정적 도매 가격
  - 매일 추가되는 동적 도매 가격
  - 소매 가격 데이터
- 데이터 처리
  - 불필요한 컬럼 제거
  - `.csv` > `parquet` 형식 변환
  - 도매 데이터와 소매 데이터의 컬럼 동기화
- 데이터 활용
  - Preset을 사용해 데이터 시각화, 대시보드 생성
  - 날씨 기반 도매 가격 예측 모델의 정확도 74%

관련 링크
1. [GitHub Link](https://github.com/ClimateAndMarketPrediction/CAMP-project)
2. [관련 블로그 포스팅 - 왜 Airflow를 써야 할까?](https://velog.io/@takeon/왜-Airflow를-써야-할까)

<br>

---

## 2️⃣ 정치,경제 뉴스 debiasing 프로젝트
> 2023.09 - 2024.06<br><br>
> 기여
> - 경제 뉴스 기사에 대한 감성 분석 모델 개발
> - 경제 뉴스 기사에 대한 개체명 인식 모델 개발
> - 모델 통합 Docker 컨테이너 패키징 및 공개 배포

<table>
  <td>
    <img height="250" alt="Image" src="https://github.com/user-attachments/assets/c91c543c-98b8-465b-92a6-be20b1d6262e" />
    <img src="https://github.com/user-attachments/assets/b43b51ca-5d13-4b25-80ce-ae575f00551f" height="250">
    <img src="https://github.com/user-attachments/assets/c60d4a38-c62c-4907-b86a-539f0e5dba86" height="250">
  </td>
</table>

Tech Stack
- `python`, `Docker`, `pandas`, `numpy`, `transformers`

Description
- 정치 뉴스 기사의 성향과 경제 뉴스 기사의 감성을 분석
- 각 뉴스 기사에 대한 분석 결과를 제시하여 편향된 뉴스만을 접하는 것을 방지

관련 링크
1. [모델 개발 GitHub Link](https://github.com/bkshin01/NER-SA-with-GPU)
2. [프로젝트 통합 GitHub Link](https://github.com/Bubblow)
3. [최종 발표 자료](https://docs.google.com/presentation/d/1cvIJKLaOebm3xhjvJcm3HqNxu7IrMfey/edit?usp=drive_link&ouid=116858154360033016413&rtpof=true&sd=true)

<br>

---

## 3️⃣ 원자재 가격과 증시지수 상관관계 분석
> 2024.11<br><br>
> 기여
> - sector 별 ETF 가격 데이터 ETL
> - 수집한 데이터 데이터 시각화

<table>
  <td>
    <img src="https://github.com/user-attachments/assets/258c28be-4b3d-463c-be18-b6fc8cf60442" height="250">
    <img src="https://github.com/Dollar-Dalla/Dollar_Dalla/raw/main/basic_charts.gif" height="250">
    <img src="https://github.com/Dollar-Dalla/Dollar_Dalla/blob/main/joined_charts.gif" height="250">
  </td>
</table>

Tech Stack
- `python`, `Docker`, `pandas`, `Airflow`, `Redshift`, `Git`

Description
- ETF, 국제증시지수, 원자재, USD 환율, KRW 환율, 암호화폐 데이터를 ETL
- 추출한 데이터를 기반으로 데이터 시각화, 대시보드 생성

관련 링크
1. [최종 발표 자료](https://www.canva.com/design/DAGXpR1xrI8/3KCINkUUWTaiG-zu58NS2w/edit?utm_content=DAGXpR1xrI8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

<br>

---

## 4️⃣ 식당 배달 시스템 구현
> 2023.05 - 2023.06<br><br>
> 기여
> - ERD 설계, 기능 구현을 위한 SQL 쿼리 작성

<img src="https://github.com/user-attachments/assets/b4ce8501-a77b-4669-b625-e508ef86cdf3" height="250">

Tech Stack
- `java`, `JDBC`, `MySQL`

Description
- 5개의 테이블을 MySQL DB에서 구축
- 6가지 애플리케이션 메뉴를 통해 메뉴와 배달 주문을 관리

관련 링크
1. [GitHub Link](https://github.com/bkshin01/Delivery-Service)

<br>

---

## 5️⃣ 악성 코드 탐지 프로젝트
> 2022.06 - 2022.07<br><br>
> 기여
> - 데이터 전처리
> - 최종 악성 코드 탐지 모델의 정확도 95%까지 향상

Tech Stack
- `python`, `skleran`, `numpy`

Description
- 악성 코드 탐지 모델 학습을 위한 행위 기반 데이터를 사용해 학습, 예측
- LogisticRegression, DecisionTree를 포함한 총 9가지 모델을 시험하고, 각각의 모델에 대한 정확도를 비교

관련 링크
1. [최종 발표 자료](https://drive.google.com/file/d/1kc1R-FF3ZpS2lgvOVIYNgh2tle9BGIO-/view?usp=sharing)

<br>

---

