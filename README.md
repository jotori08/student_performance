# 👨‍🎓 고등학생 학업 정보 데이터
## 📃 데이터셋 소개
- 고등학생의 학업 성공 요인을 분석하기 위한 학생 정보 데이터셋
- 데이터 출처: https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset

## 📊 속성 정보
| 속성명 | 설명 |
| :--- | :--- |
| `StudentID` | **학생 고유 식별번호** |
| `Age` | **연령** |
| `Gender` | **성별** |
| `Ethnicity` | **민족성(0:백인 / 1:아프리카계 미국인/ 2: 아시아계 / 3: 기타** |
| `ParentalEducation` | **부모 교육(0: 없음 / 1: 고등학교 / 2: 대학 / 3: 학사 / 4. 그 이상** |
| `StudyTimeWeekly` | **주당 학습 시간(0 ~ 20)** |
| `Absences` | **학기 중 결석 횟수(0 ~ 30)** |
| `ParentalSupport` | **학부모 지원(0: 없음 / 1: 낮음 / 2: 중간 / 3: 높음 / 4: 매우 높음** |
| `Extracurricular` | **과외 활동(0: 아니오 / 1: 예)** |
| `Sports` | **스포츠 참여(0: 아니오 / 1: 예)** |
| `Music` | **음악 활동 참여(0: 아니오 / 1: 예)** |
| `Volunteering` | **자원봉사 참여(0: 아니오 / 1: 예)** |
| `GPA` | **학점 평균(2.0 ~ 4.0)** |

## ✅ 구글 코랩에서 데이터 업로드 및 불러오기
```python
!git clone https://github.com/jotori08/student_performance.git

import pandas as pd
df = pd.read_csv('/content/student_performance/student performance.csv')
```
