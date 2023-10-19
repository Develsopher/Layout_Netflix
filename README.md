# Netflix Layout 만들기 Project

<p align='center'><img  src="https://github.com/study-from-goorm/Project_Netflix_Develsopher/assets/78126381/e54e077e-a177-4b4a-99c0-8279b29ef08e" alt="netflix_logo" style="width: 200px; height: 100px"></p>

*해당 레포지토리는 개인 학습용으로 제작되었습니다.*

---
## 준비단계 🛠️
- `general.css` 전체 적용알 css파일 세팅
- `Netflix Sans`폰트 다운 및 적용
- `사용자 지정 속성` (Primary, Secondary, Background 색상) 세팅

## 1️⃣ 전체적인 골격짜기
![layout](https://github.com/study-from-goorm/Project_Netflix_Develsopher/assets/78126381/e888451b-7efd-4560-804d-a1eb96bacc97)

작업을 시작하기전, 전체적인 html 구조를 어떻게 구성할지 고려해보았습니다.

## 2️⃣ 작업 내용

### ✨ 반응형 UI 제작
- **View Width**값이 줄어들거나 늘어남에 따라 반응형으로 layout을 구성하였습니다.
  - Font, Width, Margin 값 등등 `vw`값으로 설정하여 layout이 깨지는 경우를 방지하였습니다.
  - 영화 리스트일 경우 `Media Query`을 사용하여 대표적인 분기점 기준으로 보여지는 카드수를 조절하였습니다.
 
### ✨ 사용성 고려 측면 업그레이드
- 텍스트 정보를 쉽게 파악할 수 있도록 **dimmer영역**을 추가하여 **Main Cover**를 업그레이드하였습니다.
<p align="center">
  <img src="https://github.com/study-from-goorm/Project_Netflix_Develsopher/assets/78126381/0ea5b529-9c5f-445d-ab9b-fa7fa930e48a" align="center" width="45%">
  <img src="https://github.com/study-from-goorm/Project_Netflix_Develsopher/assets/78126381/760bb787-5137-4c54-ad60-daec1dd600ce" align="center" width="45%">
</p>

- 한 화면에 정보표시가 힘들때  **flex box** 를 적절히 활용하여 **영역별 가로스크롤** 을 추가하였습니다. 
- **scroll event**을 활용하여 세로 스크롤이 생길때 **header**영역에 배경을 동적으로 부여하였습니다.

## 📸 최종 결과물
[확인하기](https://astonishing-tanuki-1f8ad4.netlify.app/)


https://github.com/study-from-goorm/Project_Netflix_Develsopher/assets/78126381/c3e1868f-0f9d-4139-8d92-314af33899b5

