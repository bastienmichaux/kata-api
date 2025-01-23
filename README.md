# [kata-api](https://github.com/bastienmichaux/kata-api)

API testing exercise:
- test object: automationintesting.online API: test `bookin` & `message` APIs
- tech: maven project using rest assured + cucumber + gherkin

## Implementation
- ✅ create Maven repo with Cucumber archetype
- ✅ add dependencies: JUnit suite, Rest Assured, Cucumber
- ✅ Cucumber + Rest Assured smoke test
- cucumber design: https://cucumber.io/docs/bdd/example-mapping/
- map gherkin steps

## Later

- JavaDoc: `javadoc -d doc src\*`
- optimize maven cucumber deps? https://github.com/cucumber/cucumber-jvm/blob/main/cucumber-bom/README.md
- dependency injection: try PicoContainer?
