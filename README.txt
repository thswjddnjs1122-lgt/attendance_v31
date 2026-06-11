출석인정원 V31 실행 방법

이번 버전은 사용자가 올린 원본 PDF 양식(form_template.pdf)을 기준으로 출력 화면을 최대한 동일하게 맞춘 버전입니다.

1. 압축 풀기
2. CMD에서 폴더 이동
   cd Desktop\attendance_v31
3. 가상환경 만들기
   python -m venv venv
4. 가상환경 활성화
   venv\Scripts\activate
5. 설치
   pip install flask pillow
6. 실행
   python app.py
7. 접속
   http://127.0.0.1:5000

관리자 계정
아이디: admin
비밀번호: 1234

주의: 실제 운영 전 app.py의 secret_key와 관리자 비밀번호는 바꾸세요.
