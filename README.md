# 🏢 양지파인리조트 스마트 시설관리 대시보드 - 올인원 패키지

준비된 통합 패키지입니다. 엑셀 작성부터 데이터 업로드, 웹 시각화까지 한 번에 구성할 수 있습니다.

## 📂 파일 구성
1. `past_inspections.csv`: 과거 법정점검 내역을 입력하는 양식 파일입니다.
2. `time_machine_uploader.py`: CSV 파일을 읽어 과거 기록과 내년 일정을 한 번에 계산해 Firebase에 올려주는 파이썬 스크립트입니다.
3. `index.html`: 1년 치 달력을 보여주는 메인 대시보드 화면입니다.

## 🚀 실행 순서
1. **데이터 준비**: `past_inspections.csv` 파일을 열어 그동안 진행했던 점검 내역을 텍스트로 적어줍니다.
2. **타임머신 가동**: 파이썬 환경에서 `python time_machine_uploader.py`를 실행합니다. (실제 적용 시 소스 코드 내 Firebase 인증 부분을 주석 해제하고 세팅해 주세요.)
3. **웹 화면 띄우기**: `index.html`을 브라우저에서 열거나 GitHub Pages에 올려 팀원들과 공유합니다. HTML 소스 안에 이전에 pine-map이나 yustel-manager에서 사용하셨던 Firebase Config를 붙여넣으시면 즉시 데이터가 연동됩니다.
