# 파썬 가상화 
python -m venv FAST_API_TEST

# 가상화 파이썬 실행
$ cd FAST_API_TEST/Scrpits
$ activate


# 실행
uvicorn main:app --reload

# 필요 라이브러리 갱신
pip freeze > requirements.txt

# 필요 라이브러리 다운로드 
pip install -r requirements.txt

# openAPI url
 http://127.0.0.1:8000/docs