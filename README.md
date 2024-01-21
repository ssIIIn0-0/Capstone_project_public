# Capstone project (공개용)

## 프로젝트 소개
산업체 DNX의 고령자용 앱(순이) 생방송 대본의 AI 자동 제작 프로젝트(Open AI API 활용)

## 개요
- 개발목적 : 2023년 4-1학기 캡스톤설계 및 실습과목 팀프로젝트
- 개발기간 : 2023.03.28 ~ 2023.06.05 (약 2달)
- 프로젝트 팀원 : 송종빈, 김명학, 이도희, 박시은
- 개발도구 : visual studio
- 개발언어 : Python
- 플랫폼 : PC, 모바일


## 개발 내용
1. 대본 생성 과정
   - 각 주제와 카테고리에 맞는 프롬프트를 제작하여 OpenAI API에 전달
   - OpenAI로 부터 생성된 대본을 바탕으로 채점 프롬프트 생성 및 API로 재전달
   - 생성된 대본을 바탕으로 제목과 설명 생성 프롬프트 제작
   - 생성된 제목, 설명, 대본을 추가 가공 후 웹으로 출력

2. 대본 재생성
   - 별점과 피드백을 입력받아 대본 재생성 프롬프트 생성 및 OpenAI API에 전달

3. 이미지 생성
   - 키워드를 입력받아 이미지 생성 프롬프트 자동 생성 후 생성된 이미지를 웹으로 출력


### 정보 유출의 이유로 직접적으로 개발에 참여한 코드만 공개합니다. 
