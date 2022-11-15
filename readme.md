1. docker build -t haha .
2. docker run --rm -d  -p 9001:9000/tcp haha
3. 開啟 localhost:9001
4. 登入 sonar
5. 以下步驟為 sonar scanner
5. sonar-project.properties 將這個檔案放在專案底下
6. npm install sonar-scanner --save-dev
7. npx sonar-scanner
8. 看 localhost:9001 就會有報告了