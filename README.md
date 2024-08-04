# Persion AI Docent

## 1.Overview
Gemini API를 활용하여 미술 작품에 대해 궁금한 점을 질의 응답할 수 있는 대화형 AI 구현

### Usage
가상환경 생성 후 dependency를 설치합니다
```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

.env 파일을 생성하여 GOOGLE_API_KEY의 환경변수에 API키를 설정합니다.
```
GOOGLE_API_KEY=
```
run.py 파이썬 파일을 실행해 gradio demo 챗봇을 실행할 수 있습니다.
```
python run.py
```
이후 검색을 통해서 설명을 듣고싶은 작품을 검색한 뒤 해당 작품에 대해서 질문할 수 있습니다.
