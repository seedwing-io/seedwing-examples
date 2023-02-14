# seedwing-examples

Example projects in different programming languages and how to use them with Seedwing components.

## Checking for vulnerabilities in Java CycloneDX SBOMs in GitHub Actions

This example uses the following:

* A [quarkus](java) Java application with the CycloneDX maven plugin enabled.
* A [GitHub Actions Workflow](.github/workflows/java-ci.yaml) contains an example CI pipeline that builds the SBOM and performs policy checks using `seedwing-policy-cli`.
* A [vulnerabilities.dog](policies/vulnerabilities.dog) policies that are applied to the SBOM.
