## 1. Project Kickstart Checklist
  * [ ] Select Source Control Management (SCM) for
	  * [ ] Code
	  * [ ] Build Scripts (Read Gradle, NPM, MVN)
	  * [ ] CI/CD piepline (Usually a YAML or a Groovy file)
	  * [ ] Database migration scripts
	  * [ ] Wiki or ADR
	  * [ ] Infrastrcuture related code (Ex: dockerfile, docker compose, terraform)
  * [ ] Select a Build Automation framework like Gradle, NPM, Maven
  * [ ] Select database versioning framework like Liquibase, Flyway or Sequelize)
  * [ ] Start with a test case
	  * [ ] Prefer TDD; Select a unit testing framework like JUnit, XUnit, Mocha, Chai, Jest
	  * [ ] Run tests on every push or PR
	  * [ ] Configure CI/CD pipeline to fail on unit test failure
  * [ ] Choose a logging framework
  * [ ] Configure static code analysis like linting, PMD, Sonar in IDE and build pipline
  * [ ] Create quality gates in build pipeline
  * [ ] Fully automate build, release and deployment process
  * [ ] Deploy a walking skeleton
