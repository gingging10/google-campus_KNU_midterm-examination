# google-campus_KNU_midterm-examination
구글 AI 기반 서비스 개발 — 개인 미니 프로젝트  

##프로젝트 개요
이 프로젝트는 Google Gemini 2.5 Flash 모델을 활용하여  
캐나다 어학연수를 준비하는 학생이 매일 아침 사용할 수 있는  
학교·식당·체육시설(헬스장, 수영장)** 관련 5개의 영어 문장을 자동 생성하는 데모입니다.  

Gemini 모델의 텍스트 생성 기능**과 System Prompt 제어 구조를 통해  
매번 새로운 영어 표현을 JSON 형식으로 생성하고,  
이를 표 형태로 시각화하여 학습자에게 제공합니다.  

##주요 기능
-실행 시 현재 날짜(`date_seed`)를 기반으로 매일 다른 문장 세트 생성
-gym, cafeteria, pool 등 입력 상황에 맞게 문장 생성
-ROLE / MISSION / OUTPUT SCHEMA 명시로 모델 일관성 확보
-`generate_content()`를 통해 Gemini 서버에 직접 요청
-생성된 문장을 표 형태로 정리하여 학습자가 쉽게 확인 가능
