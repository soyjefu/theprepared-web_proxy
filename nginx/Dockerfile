# nginx/Dockerfile
FROM nginx:latest

# Nginx 설정 파일 복사
COPY nginx.conf /etc/nginx/nginx.conf

# 필요한 경우 정적 파일 디렉토리 생성 (예: WordPress 정적 파일)
RUN mkdir -p /var/www/html/wordpress
RUN mkdir -p /var/www/html/django
RUN mkdir -p /var/www/html/account