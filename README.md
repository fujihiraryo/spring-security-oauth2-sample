# spring-security-oauth2-sample

1. GitHubのDeveloper settingsから新しいOAuth Appを作成し、Client IDとClient Secretを取得する。
2. 以下のコマンドのClient IDとClient Secretを置き換えて起動する。

```text
./gradlew bootRun --args='--spring.security.oauth2.client.registration.github.clientId={Client ID} --spring.security.oauth2.client.registration.github.clientSecret={Client Secret}'
```
