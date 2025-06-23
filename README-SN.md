# SolarNetwork External Publishing

To publish to Maven Central, for example `micrometer-commons`:

```
cd micrometer-commons
../gradlew -PMAVEN_CENTRAL_USER="USERNAME" \
  -PMAVEN_CENTRAL_PASSWORD="PASSWORD" \
  -Prelease.version=1.15.2-SN01 \
  -Pversion=1.15.2 \
  publishToMavenCentral
```
