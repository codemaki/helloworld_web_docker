# Hello World Web App

간단한 Flask 기반 웹 애플리케이션입니다.

## 실행 방법

### Docker Compose 사용

```bash
docker-compose up -d
```

### 접속

브라우저에서 http://localhost:5000 으로 접속하세요.

### 종료

```bash
docker-compose down
```

## 기술 스택

- Python 3.11
- Flask 3.0
- Docker & Docker Compose

## 파일 구조

```
.
├── app.py                  # Flask 애플리케이션
├── templates/
│   └── index.html         # HTML 템플릿
├── requirements.txt       # Python 의존성
├── Dockerfile            # Docker 이미지 설정
└── docker-compose.yml    # Docker Compose 설정
```
