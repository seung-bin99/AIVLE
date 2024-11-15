## 빅데이터 분석 기반 해양생태 예측 관리 플랫폼, IM OCEAN
|주관|소속|프로젝트 기간|
|:---:|:---:|:---:|
|[KT 에이블스쿨](https://aivle.kt.co.kr/home/main/indexMain)|KT 에이블스쿨 5기 대구/경북 8반 25조|2024-06-17~2024-07-30|
|1|허승빈|수질 & 어업 데이터 전처리 및 데이터 분석|
|2|안성익|ML 모델 & 대시보드 프로토 타입 설계|

### 진행 과정
- 과제 발굴 / 구체화, DX 솔루션 개요서 작성
- 과제 확정, 데이터 분석 방향, 활용 데이터 수집
- 데이터 분석 및 시각화, 제안 전략 수립
- 데이터 분석 기반 기능 정의, 환경분석 기반 고객 니즈 정의
- 제안서 작성 및 품질 업그레이드
- 제안 발표 레이아웃 작성 및 발표 자료 품질 확보, 고객 중심적 제안서 작성 진행
- 프로젝트 마무리
- 과제 정의서, 발표 자료, 사업 1P 설명서, 발표 영상, 개발 코드 통합

### 역할 세부 내용
1. 해양수산빅데이터 거래소, 해양환경정보포털에서 데이터 수집
2. 오입력 데이터 전처리
3. 수산 데이터의 어획량, 어업 좌표 범위 계산한 코드 제작
4. 데이터 분석 및 기술 PM과 의견 공유를 통해 대시보드 기능 도출
 - 수질 및 수온 시계열 그래프
 - 수질 및 수온 현황 지도
 - 수산자원 분포 지도
 - 수산자원 개체수 그래프
5. 프로토타입에 대한 인프라 구성도 설계
6. 제안 전략 및 기획 내용 검토 / 제안서 제출

### 프로젝트 요약(가상 사업)
![사업요약](https://github.com/user-attachments/assets/9c4144ef-9cf1-4230-ba56-a34912ac7922)

### 서비스 시나리오
![서비스시나리오](https://github.com/user-attachments/assets/777f0559-7a51-4c98-a013-a4179b586a08)

### 사용 데이터 및 출처
- 본 저작물은 기상청 기후정보포털에서 공공누리 제1유형으로 개방한 국가 기후변화 표준 시나리오를 이용하였으며, 해당 저작물은 [기상청 기후정보포털](http://www.climate.go.kr/home/bbs/view.php?code=11&bname=notice&vcode=6925&cpage=1&vNum=Notice&skind=&sword=&category1=&category2=)을 참고하여 API 신청을 통해 무료로 이용할 수 있습니다.

#### 국내 해양 생태구 해역 구분(출처: [국가법령정보센터](https://www.law.go.kr/flDownload.do?flSeq=14495017&flNm=%5B%EB%B3%84%ED%91%9C%5D+%EC%83%9D%ED%83%9C%EA%B5%AC%EB%B3%84+%ED%95%B4%EC%97%AD+%EA%B5%AC%EB%B6%84%ED%91%9C))
![생태구 구분](https://github.com/user-attachments/assets/d0582a2c-255c-433f-91b8-72d43b4287c5)

#### 수질/수온 예측 데이터
> [**기상청 기후정보포털**](http://www.climate.go.kr/home/bbs/view.php?code=11&bname=notice&vcode=6925&cpage=1&vNum=Notice&skind=&sword=&category1=&category2=)
> 1. AR6_SSP585_ENSMN_korea_SALNT_gridraw_monthly_2021_2040.nc(표층염도 예측 데이터 2021~2040)
> 2. AR6_SSP585_ENSMN_korea_SALNT_gridraw_monthly_2041_2060.nc(표층염도 예측 데이터 2041~2060)
> 3. AR6_SSP585_ENSMN_korea_SST_gridraw_monthly_2021_2040.nc(표층수온 예측 데이터 2021~2040)
> 4. AR6_SSP585_ENSMN_korea_SST_gridraw_monthly_2041_2060.nc(표층수온 예측 데이터 2041~2060)
#### 어업 관련 데이터
> **[광주과학기술원](https://www.bigdata-sea.kr/)**
> 1. 어업별 어구부이
> 2. 어업별 어선조업
> 3. 어업별 어획량
> 4. 어업별 조업 정보


### 사용 라이브러리
1. `pandas==2.2.2`
2. `scikit-learn=1.4.2`
3. `folium==0.14.0`
4. `streamlit==1.36.0`
5. `streamlit-extras==0.4.0`
6. `streamlit_folium==0.21.0`
7. `altair==5.0.1`
