---
title: Student Support Code Template
---

<!-- pandoc -s -f markdown -t markdown --columns=94 --reference-links=true README.md -->

## About

This is a template repo for providing student support code (e.g. source code and tests) for
Java based homework assignments.

It comes with batteries included:

-   [Gradle 8.6] preinstalled
-   Basic Gradle configuration:
    -   [JDK 21] based projects
    -   Default [Gradle Java project layout]
    -   [JUnit 5] for software testing
    -   [Checkstyle] to check for valid Javadoc comments for all `public` elements in source
        code
    -   [Spotless] to check formatting of Java code using the [Google Java Style Guide], can
        also format sources if necessary
-   [GitHub workflow] to build and test the project in [GitHub CI], check sources with
    Checkstyle and Spotless
-   [Dependabot] to keep dependencies (GitHub workflow, Gradle configuration) up to date

## Usage

This repo is intended to be used as a template repo. To create new repos for assignments, the
following steps may help:

1.  Fork this repo or use it as a template to create a new repo.
2.  Add the required source code, tests and task descriptions to your new repo.
3.  If needed, adjust the Gradle configuration to your needs.
4.  Make your new repo available to the students.

If desired, activate the GitHub CI in your new repo (under "*Settings \> Actions \> General \>
Allow actions*"). You need to allow at least the following actions: `actions/checkout@v4` and
`actions/setup-java@v4`.

## License

This [work] by [Carsten Gips] and [contributors] is licensed under [MIT].

  [Gradle 8.6]: https://docs.gradle.org/8.6/release-notes.html
  [JDK 21]: https://jdk.java.net/21/
  [Gradle Java project layout]: https://docs.gradle.org/current/userguide/java_plugin.html#sec:java_project_layout
  [JUnit 5]: https://junit.org/junit5/
  [Checkstyle]: https://github.com/checkstyle/checkstyle
  [Spotless]: https://github.com/diffplug/spotless
  [Google Java Style Guide]: https://google.github.io/styleguide/javaguide.html
  [GitHub workflow]: https://docs.github.com/en/get-started/using-github/github-flow
  [GitHub CI]: https://docs.github.com/en/actions/automating-builds-and-tests/about-continuous-integration
  [Dependabot]: https://docs.github.com/en/code-security/dependabot/working-with-dependabot
  [work]: https://github.com/Programmiermethoden-CampusMinden/student-support-code-template
  [Carsten Gips]: https://github.com/cagix
  [contributors]: https://github.com/Programmiermethoden-CampusMinden/student-support-code-template/graphs/contributors
  [MIT]: LICENSE.md
