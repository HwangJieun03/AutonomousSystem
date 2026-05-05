# Autonomous Driving Systems - Mid-term report
2026 자율이동체시스템 중간고사 대체 과제

## 과제 개요
KITTI Odometry Dataset (Sequence 09)를 이용하여
Projection Matrix 해석, 차량 궤적 시각화, Bayesian 기반 차선 검출 및
딥러닝 모델(Segformer) 비교 분석을 수행하였다.

---

## 데이터셋
- KITTI Odometry Dataset Sequence 09
- 이미지: `gray_09_image_0/`
- Calibration: `calib_09/calib.txt`
- Poses: `poses_09.txt`

---

## 문제 구성
| 문제 | 내용 |
|---|---|
| 문제 1 | Projection Matrix 해석 |
| 문제 2 | Projection Matrix를 이용한 3D → 2D 투영 |
| 문제 3 | Pose를 이용한 차량 궤적 시각화 |
| 문제 4 | Projection Matrix를 활용한 차선 해석 |
| 문제 5 | 실패 구간 분석 |
| 문제 6 | 딥러닝 기반 차선 검출 모델 비교 (Segformer) |

---

## 실행 환경
- Google Colab
- Python 3.10+
- 주요 라이브러리: `numpy`, `matplotlib`, `opencv-python`, `Pillow`, `transformers`

---

## 실행 방법
1. Google Drive에 데이터셋 업로드
2. `BASE` 경로를 본인 환경에 맞게 수정
3. 셀 순서대로 실행
