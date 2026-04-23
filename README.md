# Awesome CI/CD [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, platforms, frameworks, practices, and learning resources for **Continuous Integration and Continuous Delivery/Deployment (CI/CD)** across modern software development workflows.

## Contents

- [Foundations & Concepts](#foundations--concepts)
- [CI/CD Platforms](#cicd-platforms)
- [Pipeline Configuration & Orchestration](#pipeline-configuration--orchestration)
- [Build & Test Automation](#build--test-automation)
- [Container & Kubernetes CI/CD](#container--kubernetes-cicd)
- [Deployment & Release Management](#deployment--release-management)
- [DevSecOps & Security](#devsecops--security)
- [Infrastructure as Code](#infrastructure-as-code)
- [Observability & Feedback](#observability--feedback)
- [Self-Hosted & Open Source](#self-hosted--open-source)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Foundations & Concepts

- [CI/CD Overview](https://martinfowler.com/articles/continuousIntegration.html) – Foundational concepts and practices for continuous integration.
- [Twelve-Factor App](https://12factor.net/) – Methodology influencing modern deployment pipelines.
- [Trunk-Based Development](https://trunkbaseddevelopment.com/) – Source control strategy optimized for CI/CD.
- [GitOps](https://www.gitops.tech/) – Declarative operations model using Git as the source of truth.
- [DevOps Handbook](https://itrevolution.com/the-devops-handbook/) – Industry reference for DevOps and CI/CD practices.

## CI/CD Platforms

- [GitHub Actions](https://github.com/features/actions) – Native CI/CD automation integrated with GitHub repositories.
- [GitLab CI/CD](https://docs.gitlab.com/ee/ci/) – Built-in CI/CD platform within GitLab.
- [CircleCI](https://circleci.com/) – Cloud-native CI/CD platform with strong container support.
- [Travis CI](https://www.travis-ci.com/) – Hosted CI service popular in open-source projects.
- [Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines) – CI/CD integrated into Bitbucket repositories.
- [Azure Pipelines](https://azure.microsoft.com/en-us/products/devops/pipelines/) – CI/CD service for Azure DevOps.
- [Jenkins](https://www.jenkins.io/) – Widely used open-source automation server.

## Pipeline Configuration & Orchestration

- [YAML Pipelines](https://yaml.org/) – Declarative configuration format for defining CI/CD workflows.
- [YAML Validator](https://yamlvalidator.dev), [(chrome extension)](https://chromewebstore.google.com/detail/yaml-validator/gjgbohnlhijomhfiflapnlnmcpckgigg) – Online YAML validator and formatter with JSON Schema support for CI/CD pipeline configs including GitHub Actions, CircleCI, and Bitbucket Pipelines.
- [Tekton](https://tekton.dev/) – Kubernetes-native framework for building CI/CD systems.
- [Argo Workflows](https://argo-workflows.readthedocs.io/) – Workflow engine for Kubernetes-based pipelines.
- [Argo CD](https://argo-cd.readthedocs.io/) – GitOps continuous delivery tool for Kubernetes.
- [Spinnaker](https://spinnaker.io/) – Multi-cloud continuous delivery platform.

## Build & Test Automation

- [Make](https://www.gnu.org/software/make/) – Classic build automation tool.
- [Bazel](https://bazel.build/) – Fast, scalable build and test system.
- [Gradle](https://gradle.org/) – Build automation tool for JVM-based projects.
- [Maven](https://maven.apache.org/) – Dependency management and build tool for Java.
- [pytest](https://docs.pytest.org/) – Popular Python testing framework.
- [JUnit](https://junit.org/) – Standard testing framework for Java applications.

## Container & Kubernetes CI/CD

- [Docker](https://www.docker.com/) – Containerization platform used in CI/CD pipelines.
- [Kubernetes](https://kubernetes.io/) – Container orchestration platform for production deployments.
- [Helm](https://helm.sh/) – Package manager for Kubernetes applications.
- [Kustomize](https://kustomize.io/) – Kubernetes-native configuration management.
- [Skaffold](https://skaffold.dev/) – Continuous development tool for Kubernetes-native apps.
- [Buildah](https://buildah.io/) – Tool for building OCI container images.

## Deployment & Release Management

- [Octopus Deploy](https://octopus.com/) – Deployment automation and release management platform.
- [Flux](https://fluxcd.io/) – GitOps tool for continuous delivery on Kubernetes.
- [Capistrano](https://capistranorb.com/) – Remote server automation tool for deployments.
- [LaunchDarkly](https://launchdarkly.com/) – Feature flagging and release control platform.
- [Feature Flags](https://martinfowler.com/articles/feature-toggles.html) – Progressive delivery and deployment safety techniques.

## DevSecOps & Security

- [Snyk](https://snyk.io/) – Security scanning for dependencies and containers.
- [OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/) – Identify vulnerable dependencies in builds.
- [Trivy](https://aquasecurity.github.io/trivy/) – Container image and filesystem vulnerability scanner.
- [Checkov](https://www.checkov.io/) – Infrastructure as code security scanner.
- [GitGuardian](https://www.gitguardian.com/) – Detect secrets and credentials in repositories.

## Infrastructure as Code

- [Terraform](https://www.terraform.io/) – Declarative infrastructure provisioning tool.
- [Pulumi](https://www.pulumi.com/) – Infrastructure as code using general-purpose languages.
- [Ansible](https://www.ansible.com/) – Configuration management and automation platform.
- [AWS CloudFormation](https://aws.amazon.com/cloudformation/) – Infrastructure as code service for AWS.
- [Crossplane](https://crossplane.io/) – Kubernetes-based infrastructure orchestration.

## Observability & Feedback

- [Prometheus](https://prometheus.io/) – Metrics collection and monitoring system.
- [Grafana](https://grafana.com/) – Visualization and dashboards for metrics and logs.
- [Sentry](https://sentry.io/) – Error tracking and performance monitoring.
- [Datadog](https://www.datadoghq.com/) – Full-stack observability platform.
- [New Relic](https://newrelic.com/) – Application performance monitoring and telemetry.

## Self-Hosted & Open Source

- [Drone CI](https://www.drone.io/) – Container-native CI/CD platform.
- [Buildkite](https://buildkite.com/) – Hybrid CI/CD platform with self-hosted agents.
- [GoCD](https://www.gocd.org/) – Open-source CI/CD server focused on continuous delivery.
- [Concourse CI](https://concourse-ci.org/) – Pipeline-based CI system with strong reproducibility.
- [Woodpecker CI](https://woodpecker-ci.org/) – Open-source fork of Drone CI.

## Learning Resources

### Tutorials
- [CI/CD with GitHub Actions](https://docs.github.com/en/actions) – Official GitHub Actions documentation and examples.
- [GitLab CI/CD Tutorials](https://docs.gitlab.com/ee/ci/examples/) – Practical GitLab pipeline examples.
- [Jenkins User Documentation](https://www.jenkins.io/doc/) – Guides for Jenkins pipelines and administration.

### Guides
- [CI/CD Best Practices](https://docs.gitlab.com/ee/ci/pipelines/best_practices.html) – Recommended pipeline design patterns.
- [Progressive Delivery](https://www.weave.works/technologies/progressive-delivery/) – Safe deployment strategies for production.
- [DevSecOps Guide](https://owasp.org/www-project-devsecops-guideline/) – Integrating security into CI/CD pipelines.

### Courses
- *CI/CD Fundamentals* – Building and maintaining modern pipelines.
- *Kubernetes CI/CD* – Deploying cloud-native applications.
- *DevSecOps Engineering* – Security-focused delivery pipelines.

## Related Awesome Lists

- [Awesome DevOps](https://github.com/awesomelistsio/awesome-devops)
- [Awesome GitLab](https://github.com/awesomelistsio/awesome-gitlab)
- [Awesome GitHub](https://github.com/awesomelistsio/awesome-github)
- [Awesome Kubernetes](https://github.com/awesomelistsio/awesome-kubernetes)
- [Awesome Docker](https://github.com/awesomelistsio/awesome-docker)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
