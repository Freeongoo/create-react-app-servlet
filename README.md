
# Quickstart

1) Build project using Maven:

```
mvn package
```

The project is configured to build `local` profile by default.

2) Deploy `create-react-app-servlet.war` to your favourite servlet engine

3) Access application at  
[`http://localhost:8080/`](http://localhost:8080/)

*Note*: depending on your environment you would need to change `PUBLIC_URL` and `REACT_APP_ROUTER_BASE` in profiles. For example, Weblogic uses port `7001` instead of `8080`.

# Production Build

To produce a `production` build, run maven with the `-Pprod` switch:

```
mvn package -Pprod
```
