# Web2test

Personal project by **Thevin2002**.

## Tech stack

CSS, Java, JavaScript, Maven

## Versions in this repo

- `latest/`
- `aug-2023/`

## Configuration

Passwords and keys have been replaced with `CHANGE_ME`. Set your own values before running.

## How to run

Two versions are included (`latest/` and `aug-2023/`). In either folder:

Requires **JDK 17** and **Maven**.

```bash
mvn package
```

Deploy the WAR file from `target/` to a servlet container such as Apache Tomcat or GlassFish/Payara.

Set your database password in `latest/src/main/resources/application.properties` (it is `CHANGE_ME` in this repo).

Tested: both versions build successfully on JDK 17.

