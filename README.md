# Free Developers Resources (XaaS)

There are plenty of interesting services (XaaS) out there and some offer even free tiers for developers and small teams. I collect the

- [Source Control/Development Platforms](#source-controldevelopment-platforms)
- [Security](#security)
- [Kubernetes](#kubernetes)
- [Observability](#observability)
- [Serverless Platform](#serverless-platform)
- [Container Registry](#container-registry)
- [Networking and Security](#networking-and-security)
- [Collaboration](#collaboration)
- [Enterprise Linux](#enterprise-linux)
- [Additional Info](#additional-info)
  - [Author Information](#author-information)
  - [Maintainer](#maintainer)
  - [Issues, more resources?](#issues-more-resources)

## Source Control/Development Platforms

- **[gitlab]** is a complete open-source DevOps platform, delivered as a single application, fundamentally changing the way Development, Security, and Ops teams collaborate and build software

  - Features:
    - Free-forever features
    - Spans the DevOps lifecycle
    - Bring your own GitLab CI runners
    - Deploy to any production environment
    - Features free static websites
    - Get 400 CI/CD minutes per month
  - [Pricing](https://about.gitlab.com/pricing/)

- **[github]** is development platform which allows to build, ship, and maintain your software.

  - Features:
    - Unlimited public/private repositories
    - Info 2,000 automation minutes/month
    - Free for public repositories
    - Info 500MB of Packages storage
    - Free for public repositories
    - Info Community support
  - [Pricing](https://github.com/pricing#feature-comparison)

- **[bitbucket]** is the development platform from [atlassian]

  - Features:
    - Up to 5 users
    - 50 min / mo build minutes
    - Git LFS 1GB
    - Unlimited private repositories
    - Jira Software integration
    - Trello integration
    - CI/CD
    - Unlimited pull request reviewers
    - Code Insights
    - 3 integrations
    - Merge checks
  - [Pricing](https://www.atlassian.com/software/bitbucket/pricing)

- **[travis-ci]** is a continuous integration platform.

  - Features:
    - 10000 Credits
    - Unlimited unique users
    - Private & Open-Source Repos
    - Windows, Linux, MacOS, FreeBSD 
  - [Pricing](https://www.travis-ci.com/plans)

- **[octopus deploy]** is a continuous delivery platform to enable your developers, release managers, and operations folks to bring all automation into a single place

  - Features:
    - Deployments as-a-service for 10 targets
    - Octopus on your infrastructure for 10 targets
  - [Pricing](https://octopus.com/pricing/overview)

## Security

- **[snyk]** offers different products under it's name:

  [Snyk Open Source Security Management](https://snyk.io/product/open-source-security-management/) - Automatically find, prioritize and fix vulnerabilities in the open source dependencies used to build your cloud native applications

  [Snyk Code](https://snyk.io/product/snyk-code/) - Static Application Security Testing re-imagined for the developer

  [Snyk Container](https://snyk.io/product/container-vulnerability-management/) - Container and Kubernetes security designed to help developers find and fix vulnerabilities in cloud native applications

  [Snyk infrastructure as code](https://snyk.io/product/infrastructure-as-code-security/) - Put cloud native configuration security in the hands of developers

   - Features:
     - 200 Open Source Tests per month
     - 100 Container Tests per month
     - 300 IaC tests per month
     - 100 Synk Code tests per month
     - Unlimited Developers
   - [Pricing](https://snyk.io/plans/)

- **[anchore]** is a continuous security and compliance for cloud-native software development

  - Features:
    - Software Bill of Materials for Linux Containers
    - Security Scanning for NPM, Python, Node, Java
      - CVE Scanning
      - Dockerfile Checks
      - Credential Scanning
      - Allowlist & Denylist
      - Malware Scanning
    - CI/CD Integration
    - Kubernetes Admission Controller
  - [Pricing](https://anchore.com/pricing/)

## Kubernetes

Please see [List of free Trials/Credit for Managed Kubernetes Services](https://github.com/learnk8s/free-kubernetes) for free trials

- **[Openshift]** s a Kubernetes distribution focused on developer experience and application security that's platform agnostic. OpenShift helps you develop and deploy applications to one or more hosts. These can be public facing web applications, or backend applications, including micro services or databases<sup>[redhat-openshift]</sup>

  - Features:
    - TBD

## Observability

- **[logz.io]** is based on cloud-native technologies, so its easy to integrate with your distributed apps, servers, K8s clusters, serverless functions, and the rest of your environment. Based on G2Crowd reviews 1700+ teams already trust Logz.io<sup>[logzio]</sup>

  - Features:
    - A fully managed and auto scaling ELK Stack
    - Index up to 1 GB of log data
    - 10 alertsa
    - Kibana’s powerful search and visualization capabilities
    - ML-powered analytics: Cognitive Insights
    - 3 days of log retention
  - [Pricing](https://logz.io/pricing/)
  - [Community](https://logz.io/blog/logzio-community/)

- **[Grafana Cloud]** is a composable observability platform, integrating metrics and logs with Grafana. Leverage the best open source observability software - including Prometheus, Loki, and Tempo - without the overhead of installing, maintaining, and scaling your observability stack.<sup>[grafana]</sup>

  - Features:
    - 10,000 series for Prometheus or Graphite metrics
    - 50 GB of logs
    - 14-day retention for metrics and logs
    - Access for up to 3 team members
    - 3 Users
    - 10 Alerts
  - [Pricing](https://grafana.com/products/cloud/pricing/)
  - [Community](https://community.grafana.com)
  - [Slack](https://slack.grafana.com)

- **[loggly]** is a log management to explore the full capabilities of Log Management and Analytics powered by SolarWinds Loggly

  - Features:
    - Centralized log management
    - Automated log summaries
    - Search & filters
    - Single user
    - 200 MB/day
    - 7 days retention
  - [Pricing](https://www.loggly.com/plans-and-pricing/)

## Serverless Platform

- **[heroku]** uns your app in lightweight, isolated Linux containers called "dynos." The platform offers different dyno types to help you get the best results for your type of app.

  - Features:
    - 550-1,000 dyno hours per month
    - Deploy with Git and Docker
    - Custom domains
    - Container orchestration
    - Automatic OS patching
  - [Pricing](https://www.heroku.com/pricing)
- **[Netfly]** is an intuitive Git-based workflow and powerful serverless platform to build, deploy, and collaborate on web apps

  - Features:
    - Automated builds from Git
    - Deploy to global Edge network
    - Site previews for every push
    - Instant rollbacks to any version
    - Deploy static assets & dynamic serverless functions
  - [Pricing](https://www.netlify.com/pricing/)
  - [Community](https://www.netlify.com/community/)

- **[cloudflare workers]** allows to deploy serverless code instantly across the globe to give it exceptional performance, reliability, and scale.

  - Features:
    - first 100,000 requests each day are free
    - code runs within milliseconds of your users worldwide

## Container Registry

- **[docker]** or Docker Hub is the world’s leading service for finding and sharing container images with your team and the Docker community.
  - Features:
    - Unlimited public repositories
    - Docker Desktop continuously updated
    - Docker Desktop includes Docker Engine and Kubernetes
    - Limited container image requests
    - Two-factor authentication
  - [Pricing](https://www.docker.com/pricing)
  - [Community](https://www.docker.com/docker-community)
  - [Slack](https://dockercommunity.slack.com/)

- **[quay.io]** is RedHat's container registry which builds, analyzes and distributes your container images

  - Features:
    - Unlimited public repos
  - [Pricing](https://quay.io/plans/)

- **[gitlab]** also offers docker image hosting as part of their platform

## Networking and Security

- **[cloudflare]** is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable.

  - Features:
    - Fast, easy-to-use DNS
    - Free automated SSL certificates
    - Global content delivery network (CDN)
    - Unmetered mitigation of DDoS attacks with up to 67 Tbps capacity
    - Up to 100k Workers requests and 30 scripts
    - 3 Page Rules
  - [Pricing](https://www.cloudflare.com/plans/)
  - [Community](https://community.cloudflare.com/)

- **[cloudflare for teams](https://www.cloudflare.com/teams/)** helps you to stop data loss, malware and phishing with the most performant Zero Trust application access and Internet browsing solution.

- **[jumpcloud]** Cloud Directory Platform as all in one directory, SSO, MDM, MFA, PAM, and more

  - Features:
    - full platform for 10 users and 10 devices
    - Features full platform functionality
    - 10 days of Premium 24x7 in-app live chat supporFast, easy-to-use DNS
  - [Pricing](https://jumpcloud.com/pricing)
  - [Community](https://jumpcloud.com/resources)

## Collaboration

- **[jira] and [confluence]**: [atlassian] offers with [jira] a free issue tracking platform and with [confluence] a free wiki

  - Features:
    - 1 site
    - Supports up to 10 users or 3 agents
    - Features 2 GB of storaga
    - Offers Community support
  - [Pricing](https://www.atlassian.com/software/jira/pricing)

- **[trello]**: [atlassian] offers with [trello] a project management/kanban board

  - Features:
    - Unlimited cards
    - Unlimited members
    - Up to 10 boards
    - 1 Power-Up per board
    - Unlimited storage (10MB/file)
    - 50 automated command runs per month
    - Unlimited activity log
    - Assignee and due dates
    - iOS and Android mobile apps
    - 2-factor authentication
  - [Pricing](https://trello.com/pricing)

- **[stackoverflow for teams]** is a knowledge management & collaboration solution that technologists already trust.

  - Features:
    - 50 teammates
    - ChatOps integrations - Slack & Microsoft Teams
    - Your own private space hosted on stackoverflow.com
    - Structured and searchable knowledge base
  - [Pricing](https://stackoverflow.com/teams/pricing)

## Enterprise Linux

> Well Linux is generally free but it may be interesting to mention specific enterprise linux offers

- **[RedHat Linux]**, while CentOS Linux provided a no-cost Linux distribution, no-cost RHEL also exists today through the [Red Hat Developer program](https://developers.redhat.com/rhel8). You need a [Individual Developer subscription](https://developers.redhat.com/rhel8)<sup>[redhat-linux]</sup>

  - Features:
    -  RHEL can be used in production for up to 16 systems
## Additional Info

### Author Information

Written by [Papanito](https://wyssmann.com) - [Gitlab](https://gitlab.com/papanito) / [Github](https://github.com/papanito)

### Maintainer

- [Papanito](https://github.com/papanito)

### Issues, more resources?

Please create an [issue](https://github.com/papanito/free-dev-resources/issues) in this repository or send a PR with your changes/additions.

[RedHat Linux]: https://www.redhat.com/en/blog/new-year-new-red-hat-enterprise-linux-programs-easier-ways-access-rhel
[Openshift]: https://developers.redhat.com/developer-sandbox/get-started
[Grafana Cloud]: https://grafana.com/products/cloud/
[logz.io]: https://logz.io/
[Loggly]: https://www.loggly.com/
[grafana]: https://wyssmann.com/blog/2021/05/introduction-to-grafana-cloud/
[logzio]: https://wyssmann.com/blog/2021/05/introduction-to-logz.io/
[redhat-openshift]: https://containerjournal.com/features/red-hat-woos-developers-with-free-openshift-instances/
[redhat-linux]: https://www.redhat.com/en/blog/new-year-new-red-hat-enterprise-linux-programs-easier-ways-access-rhel
[netfly]: https://www.netlify.com/
[heroku]: https://www.heroku.com
[cloudflare]: https://www.cloudflare.com/
[cloudflare workers]: https://workers.cloudflare.com/
[jumpcloud]: https://jumpcloud.com/
[atlassian]: https://www.atlassian.com
[confluence]: https://www.atlassian.com/software/confluence/free
[jira]: https://www.atlassian.com/software/jira/free
[bitbucket]: https://bitbucket.org/
[github]: https://github.com
[gitlab]: https://gitlab.com
[trello]: https://trello.com/home
[docker]: https://hub.docker.com/
[quay.io]: https://quay.io/
[travis-ci]: https://www.travis-ci.com
[octopus deploy]: https://octopus.com
[snyk]: https://snyk.io/
[anchore]: https://anchore.com/
[stackoverflow for teams]: https://stackoverflow.com/teams