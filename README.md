## Personal projects in graduate school

### 범죄 예상 지역 경관 분석
#### | 로드뷰 이미지를 활용하여 범죄 우려 지역의 경관을 분석한 프로젝트

- 범죄 발생 환경은 실제 발생 장소와 거리 수준의 시점에서 분석될 필요가 있지만, 현재 제공되는 데이터는 보안 문제로 인해 수집이 어렵다는 한계가 존재함
- 따라서 범죄 방지 CCTV가 설치된 장소를 범죄 다발 지역 또는 발생 우려 지역으로 가정하고 해당 장소의 로드뷰 이미지를 크롤링하여 수집함
- 사회물리적인 환경이 인간 행태에 영향을 미친다는 범죄 방지 이론 CPTED에서 착안하여 로드뷰 이미지를 분석함
- 경관 분석에는 VGG16 모델을 활용한 이미지 벡터화와 PCA 차원축소, DBSCAN 클러스터링이 사용됨
- 유사한 특성을 가지는 경관들을 군집할 수 있으며, 범죄 방지나 추가적인 CCTV 설치 장소 선정에 활용될 수 있을 것으로 기대됨

|<img width="933" height="524" alt="image" src="https://github.com/user-attachments/assets/45e8ca23-75d4-4af0-8c48-39b1116e214e" />|
|:--:|
|분석 흐름|
|<img width="932" height="522" alt="image" src="https://github.com/user-attachments/assets/9b8703c0-2dbd-4fd1-824f-d22cd7e9aefe" />|
|군집 결과|

---

### 무차별 범죄 상황 모델링
#### | Anylogic 프로그램을 활용해 무차별 범죄 상황을 모델링한 프로젝트

- 무차별 범죄는 시공간적으로 무작위로 발생한다는 특성 상, 피해지역과 희생자가 계속해서 확대될 수 있음
- 행위자 기반 모델링을 지원하는 Anylogic을 활용해 실제 지도를 기반으로 무차별 범죄 상황을 구성하고, 행인, 범죄자, 경찰의 행동을 모델링함

<table align="center">
  <tr>
    <td><img width="427" height="332" alt="image" src="https://github.com/user-attachments/assets/4eda0406-1209-481f-9e27-ad392dc28d2b" /></td>
    <td><img width="351" height="341" alt="image" src="https://github.com/user-attachments/assets/68476283-4377-429a-aa57-ac8d23ed587e" /></td>
    <td><img width="353" height="340" alt="image" src="https://github.com/user-attachments/assets/018f70cc-87ae-4c56-a9b9-22a01070788f" />
  </tr>
  <tr>
    <td>행인 행동 규칙 모델링</td>
    <td>범죄자 행동 규칙 모델링</td>
    <td>경찰 행동 규칙 모델링</td>
  <tr>
  <tr>
    <td colspan="3" align="center"><img width="383" height="264" alt="image" src="https://github.com/user-attachments/assets/579a8588-92d4-4a74-89b1-43075501accc" /></td>
  </tr>
  <tr><td colspan="3" align="center">모델링 실행 화면</td></tr>
</table>

---

### 지리가중회귀분석을 이용한 불법주정차 유발요인의 영향력 분석
#### | 불법주정차를 유발하는 환경적 요인의 영향력을 분석한 프로젝트

- 지역별로 회귀계수를 산출할 수 있는 지리가중회귀분석을 적용하여 공간 자기상관성을 고려하는 동시에, 지역 간 상이한 불법주정차 유발 요인의 영향력을 확인하고 시각화함
- 하지만 도로 위에서만 발생하는 불법주정차의 특성 상, 작은 공간단위로 집계해도 영과잉이 발생하기 때문에 결과가 왜곡될 우려가 있음
- 이는 추구 연구에서 보완함

<table align="center">
  <tr>
    <td><img width="746" height="366" alt="image" src="https://github.com/user-attachments/assets/5606e62b-d3e4-4f3e-a259-f6ec71d9718b" /></td>
  </tr>
  <tr>
    <td align="center">독립변수별 회귀계수의 공간적 분포</td>
  </tr>
</table>

