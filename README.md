# spring boot https
--------------------------

## Build & Run
```
./gradlew bootRun
```

```
Access the application at https://localhost:8443/env
```

jks key creation
----------------------
keytool -genkey -keyalg RSA -alias tomcat -keystore keystore.jks -validity 360 -keysize 2048

pkcs12 key creation
----------------------
keytool -genkey -alias tomcat -storetype PKCS12 -keyalg RSA -keysize 2048 -keystore keystore.p12 -validity 3650