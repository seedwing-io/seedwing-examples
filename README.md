# seedwing-examples

Example projects in different programming languages and how to use them with Seedwing components.

Each example has an entry in this README explaining where the project code, policies and the CI jobs are located.

## Checking for vulnerabilities in Java CycloneDX SBOMs in GitHub Actions

This example uses the following:

* A [quarkus](java) Java application with the CycloneDX maven plugin enabled.
* A [GitHub Actions Workflow](.github/workflows/java-ci.yaml#L15) contains an example CI pipeline that builds the SBOM and performs policy checks using `seedwing-policy-cli`.
* A [vulnerabilities.dog](policies/vulnerabilities.dog) policies that are applied to the SBOM.
