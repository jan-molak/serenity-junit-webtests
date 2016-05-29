## Automated web tests using Serenity, JBehave and Maven

Copied from https://github.com/serenity-bdd/serenity-demos/tree/master/junit-webtests

A simple example of some BDD-style automated acceptance criteria, running against http://etsy.com.

Run the tests like this:

```
mvn clean verify
```

To run tests on BrowserStack Automate, use:
```
mvn clean verify -Dbrowserstack.url=https://${BROWSERSTACK_USER}:${BROWSERSTACK_ACCESSKEY}@hub.browserstack.com/wd/hub
```


The reports will be generated in `target/site/thucydides`.
