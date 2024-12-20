# note

## 목차

### EEG, Electroencephalography와 우울증

[리뷰: Technical and clinical considerations for electroencephalography-based biomarkers for major depressive disorder](https://www.nature.com/articles/s44184-023-00038-7)

주요우울장애(MDD)는 삶의 질을 크게 떨어뜨리는 만연하고 쇠약해지는 정신 질환입니다. 
질병의 이질성과 치료에 대한 개인의 반응에 대한 이해가 부족하여 새로운 MDD 치료제 개발에 거의 진전이 없었습니다. 
뇌파검사(EEG)는 대규모 데이터 수집의 용이성과 인공물을 해결하기 위한 계산 방법의 발전으로 인해 이를 개선할 준비가 되어 있습니다. 
본 연구는 MDD에서 뇌 기반 바이오마커를 개발하기 위한 EEG의 실행 가능성을 요약한다. 
우리는 잘 정립된 EEG 전처리 파이프라인의 특성을 조사하고 민감하고 신뢰할 수 있는 바이오마커의 발견으로 이어지는 요인을 고려합니다.

**EEG는 MDD 환자와 건강한 대조군 환자 간의 유의미한 차이를 감지할 수 있습니다.**

**정신 질환의 진단은 보다 효율적이고 정확하기 위해 노력하기 때문에 이러한 고려 사항을 염두에 두는 것이 점점 더 중요해지고 있으며, 특히 MDD 연구에서 EEG 분야는 전처리 단계에 대한 "황금 표준"이 없기 때문입니다.**

**MDD에 대한 강력한 바이오마커의 개발은 전 세계 환자들의 치료 결과를 개선할 것입니다.**


[연구: Electroencephalography-based endogenous phenotype of diagnostic transition from major depressive disorder to bipolar disorder](https://www.nature.com/articles/s41598-024-71287-5)

주요우울장애(MDD)에서 양극성 장애(BD)로의 진단적 전환을 포함한 기분 장애의 신경병리학은 잘 이해되지 않고 있습니다. 
이 연구는 MDD 환자와 MDD에서 BD로 진단이 변경된 환자의 휴식 상태 뇌파(EEG) 활동을 조사했습니다. 
MDD로 등록된 68명의 환자 중 연구 기간 동안 BD로 전환된 17명의 환자 진단이 이루어졌습니다. 
우리는 기계 학습 기술을 적용하여 센서 및 소스 수준 EEG 기능을 사용하여 두 그룹을 구별했습니다. 
센서 수준에서, BD 환자는 MDD 환자에 비해 AF3 채널에서 더 높은 세타 대역 전력을, FC5 채널에서 낮은 알파 대역 전력을 보였다. 
근원 수준에서, BD 환자는 우측 전대상(prerior cingulate)에서 더 높은 세타 밴드 활성을 보였고, 좌측 해마회(left parahippocampal gyrus)에서 낮은 알파 밴드 활성을 보였다. 
BD와 MDD를 구별하기 위해 이 4가지 EEG 특징을 선정하였으며, 80.88%의 정확도, 76.47%의 민감도, 82.35%의 특이도를 보인 최상의 분류 성능을 보였다. 
우리의 발견은 BD 및 MDD 환자에서 뚜렷한 세타 및 낮은 알파 밴드 활동을 보여주었습니다. 

**이러한 차이는 두 가지 별개의 기분 장애 사이의 진단 및 진단 전환을 위한 후보 신경표지자로 작용할 수 있습니다.**

[연구: MDD brain network analysis based on EEG functional connectivity and graph theory](https://www.cell.com/heliyon/fulltext/S2405-8440(24)13022-8)

기존 연구에 따르면 주요 우울증 장애(MDD)의 뇌 네트워크는 비정상적인 토폴로지를 가지고 있습니다. 
그러나 신뢰할 수 있는 MDD 브레인 네트워크를 구축하는 것은 여전히 미해결 과제입니다.
본 논문은 신뢰할 수 있는 MDD 뇌네트워크 구축 방법을 제시하였다. 
먼저, 7가지 연결 방법을 사용하여 채널 간의 상관 관계를 계산하고 기능적 연결 매트릭스를 얻습니다. 
그런 다음 4가지 이진화 방법을 사용하여 매트릭스를 이진화하여 EEG 뇌 네트워크를 얻습니다. 
또한, 집단 간 차이를 최대화한다는 기준에 따라 개선된 이진화 방법인 적응 임계값(AT) 방법을 제안했습니다. 
AT는 최적의 이진화 임계값을 자동으로 설정하고 기존 방법의 인위적인 영향을 극복할 수 있습니다. 
그 후, 집단 간 차이를 분석하기 위해 뇌 네트워크에서 여러 네트워크 메트릭을 추출합니다. 
마지막으로, 통계적 분석과 Fscore 값을 사용하여 다양한 방법의 성능을 비교하고 뇌 네트워크 구축을 위한 가장 신뢰할 수 있는 방법을 설정했습니다.
세타, 알파 및 총 주파수 대역에서 MDD 뇌 네트워크의 클러스터링 계수, 전역 효율성, 국소 효율성 및 정도는 감소하고 MDD 뇌 네트워크의 경로 길이는 증가합니다.
결과는 AT가 기존 이진화 방법보다 성능이 우수하다는 것을 보여줍니다. 
다른 방법에 비해 PLV(Phase-Locked Value) 및 AT를 기반으로 하는 뇌 네트워크 구축 방법은 신뢰성이 더 우수합니다.
MDD는 특히 전두엽과 측두엽에서 뇌 기능 장애를 일으킵니다.

[NeuroPharm study: EEG wakefulness regulation as a biomarker in MDD](https://www.sciencedirect.com/science/article/pii/S0022395621003952?via%3Dihub)

MDD는 건강한 대조군에 비해 휴식 중 더 엄격한 경계 조절을 보여줍니다.
과안정 경계 조절을 가진 환자는 에스시탈로프람과 둘록세틴으로 인한 이익이 적습니다.
반응자와 송금자의 각성 조절은 치료 후 건강한 대조군으로 정상화됩니다.

여러 뇌파(EEG) 기반 바이오마커가 주요 우울장애(MDD)의 진단 또는 예측 도구로 제안되었지만, 이 분야에 대한 복제 연구는 분명히 부족합니다. 
MDD의 각성 조절 장애와 같은 임상적 특징을 신경 생리학적 패턴과 연결하는 마커는 예를 들어 EEG 정보에 입각한 항우울 치료 선택에 특히 유망한 후보입니다. 
우리는 독립적인 MDD 샘플에서 휴식 중 EEG 경계 조절의 비정상적인 소견을 재현할 수 있는지, 그리고 항우울 치료 반응에 대한 예측 변수로 사용할 수 있는지 조사합니다. 
EEG 휴식 상태는 NeuroPharm 시험에서 91명의 환자와 35명의 건강한 대조군에서 기록되었습니다. 
EEG-경계는 VIGALL(Vigilance Algorithm Leipzig)을 사용하여 평가되었습니다. 
우리는 두 가지 다른 반응 기준(NeuroPharm 및 iSPOT-D)을 사용하여 SSRI/SNRI 치료 8주 후 환자와 건강한 대조군 사이, 그리고 송금자/반응자와 비송금자/무반응자 간의 휴식 중 경계 조절을 비교했다. 
우리는 건강한 피험자에 비해 환자에서 과안정된 EEG-각성 조절을 보여주는 이전 결과를 재현했습니다. 
iSPOT-D 기준에 의해 정의된 반응자는 치료 전 반응이 없는 환자에 비해 낮은 경계 단계에 대한 더 높은 경향을 보였지만, 이는 NeuroPharm 기준을 사용할 때 적용되지 않았습니다. 
EEG-각성 조절 패턴은 치료 8주 후 건강한 대조군 패턴으로 정규화되었습니다. 
이 복제 연구는 EEG-vigilance regulation의 진단적 가치와 MDD에서 치료법 선택을 위한 바이오마커로서의 유용성을 뒷받침합니다.

[EEG biomarker informed prescription of antidepressants in MDD: a feasibility trial](https://www.sciencedirect.com/science/article/abs/pii/S0924977X2030986X?via%3Dihub)

우리는 발작성 활동, 알파 피크 빈도 및 전두엽 알파 비대칭을 연구했습니다.
**항우울제 치료에서 EEG 바이오마커의 구현은 임상적으로 실현 가능합니다.**
뇌파 측정 정보에 입각한 항우울제 처방은 TAU보다 증상 완화에 우수했다.

치료 전 바이오마커를 사용하여 환자에게 선호하는 항우울제 약물 치료를 안내하는 것은 현재의 완만한 반응과 관해율을 향상시키는 유망한 접근 방식이 될 수 있습니다. 
이 공개 라벨 전향적 연구는 이전에 확인된 EEG 특징(발작성 활성, 알파 피크 빈도, 전두엽 알파 비대칭)을 사용하여 임상의가 TAU(Treatment As Usual)와 비교하여 세 가지 다른 항우울제(AD, 에스시탈로프람, 세르트랄린, 벤라팍신) 중에서 선택하는 데 정보를 제공함으로써 이러한 치료 전 바이오마커 사용의 타당성을 평가했습니다. 
EEG 데이터는 알츠하이머병 치료 8주 전에 주요 우울 장애가 있는 195명의 외래 환자로부터 얻었습니다. 
1차 결과 측정은 Beck Depression Inventory-II(BDI-II)에 대한 치료 전과 후 간의 백분율 변화였습니다. 
AN(C)OVA를 통한 TAU와 EEG 정보 처방을 비교했다. 모집은 기준선 효과를 확립하기 위해 TAU를 받는 환자부터 시작되었으며, 그 후 EEG 정보 처방을 받는 환자를 모집했습니다. 
108명의 환자가 EEG 정보 처방을 받았고 87명의 환자가 TAU를 받았습니다. 임상의와 환자는 프로토콜에 만족했습니다. 
전체적으로, EEG 정보에 입각한 임상의의 70명(65%)이 권고 사항을 따랐고(TAU 그룹에서는 52명(60%)가 처방을 따랐으며, 이는 타당성을 확립했다. 
여기서 우리는 상관 관계 연구에서 이전에 보고된 EEG 변수에 의해 정보에 입각한 치료 할당이 실현 가능했음을 확인합니다.