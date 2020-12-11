# spring-security-oauth2-sample

1. GitHubのDeveloper settingsから新しいOAuth Appを作成し、Client IDとClient Secretを取得する。
2. 以下のコマンドのClient IDとClient Secretを置き換えて起動する。

```text
gradle bootRun --args='--spring.security.oauth2.client.registration.github.clientId={Client ID} --spring.security.oauth2.client.registration.github.clientSecret={Client Secret}'
```

3. localhost:8080にアクセスすると、以下の画面が表示される。
![authorize_page](https://github.com/fujihiraryo/spring-security-oauth2-sample/blob/resources/images/authorize_page.png)

## 参考
[Spring Boot と OAuth2](https://spring.pleiades.io/guides/tutorials/spring-boot-oauth2)
