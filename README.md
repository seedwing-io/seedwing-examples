# seedwing-java-example

Example Java project integrating with Seedwing.

This example consists the following:

* A [quarkus](java) Java application with the CycloneDX maven plugin enabled.
* A [GitHub Actions Workflow](.github/workflows/ci.yaml#L15) contains an example CI pipeline that builds the SBOM and performs policy checks using `seedwing-policy-cli`.
* A [set of policies](policies/) that are applied at different stages in the CI pipeline.
