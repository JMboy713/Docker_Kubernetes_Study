# 기본적으로 사용하고자 하는 앱
FROM node:14  
# 사용 디렉토리
WORKDIR /app
# 패키지.ㅓ내ㅜ
COPY package.json .
# npm install 을 설치해서 모든 필요 dependency를 설치한다. 
RUN npm install
# 나머지 코드 
COPY . .
# 포트
EXPOSE 3000
# 노드 명령으로 app.mjs를 실행
CMD [ "node", "app.mjs" ]