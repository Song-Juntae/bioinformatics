# EEG

뇌전도, electroencephalogram, electroencephalography

![MNE 워크플로](https://mne.tools/stable/_images/flow_diagram.svg)

## 목차

뇌파란 무엇인가?

비침습성 측정, EEG, MEG

Event, Epoch, Trial

Artifact removal, EOG

ERP

Fourier Transform

Power spectrum analysis

Time-frequency analysis

Topography

Connectivity

### 뇌파란 무엇인가?

뇌에는 약 1000억개 뉴런이 있고, 각 뉴런은 다른 뉴런과 약 1000번 이상의 시냅스를 이룬다.
뉴런에 임계치 이상 입력이 들어오면 Action potential이 발생, 입력이 커지면 커질수록 Action potential 발생 횟수 증가

### 데이터 분석 과정

전처리
    각 이벤트 별 Channels, Time points, Trials 
    Artifact removal

ERP 분석

Power spectrum 분석

Time-frequency analysis

Topography

### 프로토콜

데이터의 표준화, 실험의 재현성, 데이터의 신뢰성, 효율적인 분석

* EEG 데이터 프로토콜 구성 요소
    * 연구 목표: 뇌파 데이터를 통해 무엇을 밝혀내고자 하는지 명확하게 정의합니다.
    * 대상: 어떤 대상 (예: 건강한 성인, 특정 질환 환자)을 대상으로 연구를 수행할 것인지 결정합니다.
    * 장비: 어떤 종류의 EEG 장비를 사용할 것인지, 전극 배치는 어떻게 할 것인지 등을 설정합니다.
    * 자극: 어떤 종류의 자극 (예: 시각 자극, 청각 자극)을 제공할 것인지, 자극의 강도와 시간 등을 결정합니다.
    * 과제: 피험자가 수행해야 할 과제 (예: 반응 시간 측정, 기억력 테스트)를 설정합니다.
    * 데이터 수집: 샘플링률, 필터링, 노이즈 제거 등 데이터 수집 과정에서 필요한 설정을 합니다.
    * 데이터 분석: 푸리에 변환, 시간-주파수 분석, 공간 분석 등 어떤 분석 방법을 사용할 것인지 결정합니다.
    * 통계 분석: 얻어진 결과를 통계적으로 분석하여 유의성을 검증합니다.

* EEG 데이터 프로토콜 예시
    * 연구 목표: 스트레스 상황에서 뇌파 변화를 측정하여 스트레스와 관련된 뇌 영역을 밝혀낸다.
    * 대상: 건강한 성인 20명
    * 장비: 64채널 EEG 시스템
    * 자극: 스트레스 유발 영상 시청
    * 과제: 스트레스 정도를 자가 평가
    * 데이터 수집: 샘플링률 1000Hz, 밴드패스 필터 0.1-30Hz
    * 데이터 분석: 이벤트 관련 전위(ERP) 분석, 시간-주파수 분석
    * 통계 분석: t-검정, ANOVA

EEG 데이터 프로토콜에 대한 상세 설명
EEG 데이터 프로토콜이란 뇌파(EEG) 데이터를 수집하고 분석하는 과정에서 사용되는 일련의 규칙과 절차를 의미합니다. 뇌파 데이터는 뇌의 전기적 활동을 기록한 것이므로, 이를 정확하게 해석하고 의미 있는 정보를 추출하기 위해서는 체계적인 프로토콜이 필수적입니다.

EEG 데이터 프로토콜의 구성 요소

* 실험 설계:
    * 연구 목적: 어떤 질문에 답하고자 하는가?
    * 참여자: 어떤 특징을 가진 사람들을 대상으로 할 것인가? (나이, 성별, 질병 유무 등)
    * 과제: 참여자에게 어떤 과제를 수행하게 할 것인가? (휴식, 운동, 인지 과제 등)
    * 독립 변수: 실험에서 조작되는 변수는 무엇인가? (예: 자극의 종류, 강도, 시간)
    * 종속 변수: 측정하고자 하는 변수는 무엇인가? (예: 특정 뇌파 성분의 진폭, 주파수)

* EEG 측정:
    * 전극 배치: 어떤 전극을 어디에 부착할 것인가? (국제 10-20 시스템 등)
    * 샘플링률: 얼마나 자주 데이터를 수집할 것인가? (일반적으로 256Hz 이상)
    * 임피던스: 전극과 두피 사이의 저항은 얼마나 되어야 하는가? (일반적으로 5kΩ 이하)
    * 노이즈 제거: 외부 노이즈를 어떻게 제거할 것인가? (차폐실 사용, 필터링 등)

* 데이터 전처리:
    * 아티팩트 제거: 눈 깜빡임, 근육 움직임 등의 아티팩트를 제거하는 방법
    * 필터링: 특정 주파수 대역의 신호를 추출하거나 제거하는 방법
    * 참조 전극 선택: 데이터 분석에 사용할 참조 전극을 선택하는 방법

* 데이터 분석:
    * 시간 영역 분석: 시간에 따른 뇌파 변화를 분석하는 방법 (예: 시각 유발 전위)
    * 주파수 영역 분석: 뇌파의 주파수 성분을 분석하는 방법 (예: 파워 스펙트럼 분석)
    * 시간-주파수 분석: 시간과 주파수 정보를 동시에 분석하는 방법 (예: wavelet 분석)
    * 공간 영역 분석: 뇌의 어느 부위에서 활성이 나타나는지 분석하는 방법 (예: source localization)

* 결과 해석:
    * 통계 분석: 연구 가설을 검증하기 위한 통계 분석
    * 시각화: 뇌파 데이터를 시각적으로 표현하여 이해를 돕는 방법

* EEG 데이터 프로토콜의 중요성
    * 데이터의 신뢰성 확보: 체계적인 프로토콜을 통해 데이터의 품질을 높이고, 연구 결과의 신뢰성을 확보할 수 있습니다.
    * 연구의 재현성 확보: 다른 연구자들이 동일한 연구를 반복할 수 있도록 상세한 프로토콜을 기록해야 합니다.
    * 데이터 분석의 효율성 증대: 체계적인 프로토콜을 따라 데이터를 분석하면 시간과 노력을 절약할 수 있습니다.

* EEG 데이터 분석 도구
    * MATLAB: 신호 처리 및 데이터 분석에 널리 사용되는 도구
    * Python: 다양한 과학 계산 라이브러리를 제공하는 언어 (예: SciPy, NumPy, MNE-Python)
    * EEGLAB: EEG 데이터 분석을 위한 MATLAB toolbox
    * FieldTrip: EEG/MEG 데이터 분석을 위한 MATLAB toolbox

## 참고

[MNE](https://mne.tools/stable/index.html)

[MNE 커뮤니티](https://mne.discourse.group/top)

[유튜브 강의: EEG Analysis using MATLAB](https://www.youtube.com/watch?v=Nq2S_VK_7jI)
