This is a workaround for the following issues:

* https://github.com/eclipse-elk/elk/issues/859

It contains changes submitted in this PR: 

* https://github.com/eclipse-elk/elk/pull/1109

Hopefully this will not be necessary for long until the issue is resolved and a new version of ELK is released.

Use the following command to create a full ELK package with a patched class run: 

```sh
mvn clean package
```

This will create a file `target/elk-full-patched-0.1-SNAPSHOT.jar` that you can the use at your discretion. 

