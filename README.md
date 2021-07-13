# Free Developers Resources (XaaS)

There are plenty of interesting services (XaaS) out there and some offer even free tiers for developers and small teams. I collect them in this list.

> Students may also checkout [GitHub Student Developer Pack](https://education.github.com/pack) which may even offer better deals.

- [Build](#build)
- [Code](#code)
- [Cloud Computing](#cloud-computing)
- [Collaboration](#collaboration)
- [Communication](#communication)
- [Container Registry](#container-registry)
- [Data](#data)
- [Design](#design)
- [Development Platforms](#development-platforms)
- [Event Streaming](#event-streaming)
- [Kubernetes](#kubernetes)
- [Networking](#networking)
- [Observability](#observability)
- [IAM](#iam)
- [Search](#search)
- [Security](#security)
- [Serverless Platform](#serverless-platform)
- [Secret Management](#secret-management)
- [Storage (Cloud Native)](#storage-cloud-native)
- [Testing](#testing)
- [Enterprise Linux](#enterprise-linux)
- [Additional Info](#additional-info)
  - [Author Information](#author-information)
  - [Maintainer](#maintainer)
  - [Issues, more resources?](#issues-more-resources)

## Build

see [Development Platforms](#development-platforms)

## Code

- **[codecov]** is a tool to see absolute coverage and coverage changes overlayed with your source code

  - Features
    - Unlimited Public / Private Repositories
    - SAML Ready
    - Community Support
    - Integrates with [github], [gitlab] and [bitbucket]
  - [Pricing](https://about.codecov.io/pricing/)

- **[bettercodehub]** checks your GitHub codebase against 10 engineering guidelines devised by the authority in software quality, Software Improvement Group (SIG)

  - Features:
    - Unlimited public repos
    - 100'000 Lines of code per repo
    - Add issues to GitHub
    - Prioritized list of refactoring candidates
    - 1 User
  - [Pricing](https://www.bettercodehub.com/pricing)

- **[sourcehut]** is the hosted instance of sourcehut and provides paid services to its users. Sourcehut is itself an [open-source project](https://sr.ht/~sircmpwn/sourcehut). Users who contribute patches to the upstream project are eligible for free service.

  - Features
    - Source code hosting
  - [Pricing](https://sourcehut.org/pricing/)
    - There is no difference between any of the plans: they all have access to the same level of service, and the same service limits. You should choose whichever plan best represents your financial ability and your level of investment in sr.ht. It's an honor system: pay what you think the service is worth to you.

## Cloud Computing

- **[google cloud]** offers select Google Cloud products—like Compute Engine, Cloud Storage, and BigQuery—free of charge, within specified monthly usage limits. There are some additional restrictions, checkout the link.
  - Features:
    - App Engine
      - 28 hours per day of "F" instances
      - 9 hours per day of "B" instances
      - 1 GB of egress per day
    - Artifact Registry
      - 0.5 GB storage per month
    - AutoML Natural Language
      - 5000 units of prediction per month
    - AutoML Tables
      - 6 node hours for training and prediction
    - AutoML Translation
      - 500,000 translated characters per month
    - AutoML Video Intelligence
      - 40 node hours for training
      - 5 node hours for prediction
    - AutoML Vision
      - 40 node hours for training and online prediction
      - 1 node hour for batch classification prediction
      - 15 node hours for Edge training
    - BigQuery
      - 1 TB of querying per month
      - 10 GB of storage each month
    - Cloud Build
      - 120 build-minutes per day
    - Cloud Functions
      - 2 million invocations per month (includes both background and HTTP invocations)
      - 400,000 GB-seconds, 200,000 GHz-seconds of compute time
      - 5 GB network egress per month
    - Cloud Logging and Cloud Monitoring
      - Free monthly logging allotment
      - Free monthly metrics allotment
    - Cloud Natural Language API
      - 5,000 units per month
    - Cloud Run
      - 2 million requests per month
      - 360,000 GB-seconds of memory, 180,000 vCPU-seconds of compute time
      - 1 GB network egress from North America per month
    - Cloud Shell
      - Free access to Cloud Shell, including 5 GB of persistent disk storage
    - Cloud Source Repositories
      - Up to 5 users
      - 50 GB of storage
      - 50 GB egress
    - Cloud Storage
      - 5 GB-months of regional storage (US regions only)
      - 5,000 Class A Operations per month
      - 50,000 Class B Operations per month
      - 1 GB network egress from North America to all region destinations (excluding China and Australia) per month
    - Cloud Vision
      - 1,000 units per month
    - Compute Engine
      - 1 non-preemptible f1-micro VM instance per month in some US regions
      - 30 GB-months HDD
      - 5 GB-month snapshot storage in some regions
      - 1 GB network egress from North America to all region destinations (excluding China and Australia) per month
    - Firestore
      - 1 GB storage
      - 50,000 reads, 20,000 writes, 20,000 deletes per day
    - Google Kubernetes Engine
      - No cluster management fee for one Autopilot or Zonal cluster per billing account. For clusters created in Autopilot mode, pods are billed per second for vCPU, memory and disk resource requests. For clusters created in Standard mode, each user node is charged at standard Compute Engine pricing.
    - Pub/Sub
      - 10 GB of messages per month
    - Speech-to-Text
      - 60 minutes per month
    - Video Intelligence API
      - 1,000 units per month
    - Workflows
      - 5,000 internal steps per month
    - 2,000 external HTTP calls per month
  - [Pricing](https://cloud.google.com/products/calculator)

- **[oracle cloud]** offers a always free tier for developers

  - Features:
    - Infrastructure
      - 2 AMD based Compute VMs with 1/8 OCPU** and 1 GB memory each
      - 4 Arm-based Ampere A1 cores and 24 GB of memory usable as one VM or up to 4 VMs
      - 2 Block Volumes Storage, 200 GB total
      - 10 GB Object Storage
      - 10 GB Archive Storage
      - Resource Manager: managed Terraform
      - 5 OCI Bastions
    - Databases
      - Your choice of Oracle Autonomous Transaction Processing, Autonomous Data Warehouse, Autonomous JSON Database, or APEX Application Development. Two databases total, each with 1 OCPU** and 20 GB storage.
      - NoSQL Database with 133 million reads per month, 133 million writes per month, 25 GB storage per table, up to 3 tables
    - Observability and Management
      - Monitoring: 500 million ingestion datapoints, 1 billion retrieval datapoints
      - Application Performance Monitoring: 1000 tracing events per hour
      - Logging: 10 GB per month
      - Notifications: 1 million sent through https per month, 1000 sent through email per month
      - Service Connector Hub: 2 service connectors
    - Additional services
      - Flexible Load Balancer: 1 instance, 10 Mbps
      - Flexible Network Load Balancer
      - Outbound Data Transfer: 10 TB per month

  - [Pricing]: https://www.oracle.com/cloud/free/

## Collaboration

- **[jira] and [confluence]**:[jira] an issue tracking platform and [confluence] wiki/collaboration platfor, both offered by [atlassian]

  - Features:
    - 1 site
    - Supports up to 10 users or 3 agents
    - Features 2 GB of storage
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

## Communication

- **[slack]** is a proprietary business communication platform which offers many IRC-style features, including persistent chat rooms (channels) organized by topic, private groups, and direct messaging

  - Features:
    - Access to 10,000 of your team’s most recent messages
    - 10 integrations with other apps like Google Drive, Office 365 and many more
    - 1:1 voice and video calls between teammates
  - [Pricing](https://slack.com/intl/en-ch/pricing)

- **[zulip]** is an open-source real-time chat with an email threading model

  - Features:
    - 10,000 messages of search history
    - File storage up to 5 GB total
    - Convenient web service
    - No sysadmin work required
  - [Pricing](https://zulip.com/plans/)

## Container Registry

- **[docker]** or Docker Hub is the world’s leading service for finding and sharing container images with your team and the Docker community.

  - Features:
    - Unlimited public repositories
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

## Data

- **[flatline]** is a drop-in data importer, means you define your unique schema, and return the imported data in this format

  - Features:
    - Embeddable import widget
    - Smart column matching
    - Pattern based validation
    - Custom theming
  - [Pricing](https://flatfile.io/product/portal/)

## Design

- **[awesomefonts]** offers vector icons and social logos for your website

  - Features:
    - 1,609 Icons
    - 1 Style + Brands
    - 1 Seat
    - 1 Free Kit
    - 10K Pageviews/Month
  - [Pricing](https://fontawesome.com/plans)

- **[feathericons]**  is a collection of simply beautiful open source icons. Each icon is designed on a 24x24 grid with an emphasis on simplicity, consistency, and flexibility.

- **[iconfinder]** is a large marketplace for icons

  - Features:
    - Access to 321,002 free icons
    - With ads
  - [Pricing](https://www.iconfinder.com/pricing)

## Development Platforms

- **[gitlab]** is a complete open-source DevOps platform to build, ship, and maintain your software.to host and build code

  - Features:
    - Spans the DevOps lifecycle
    - Bring your own GitLab CI runners
    - Deploy to any production environment
    - Free static websites
    - Get 400 CI/CD minutes per month
  - [Pricing](https://about.gitlab.com/pricing/)

- **[github]** is development platform to build, ship, and maintain your software.

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

- **[circleci]** continuous integration in the cloud or on your own infrastructure.

  - Features (cloud):
    - 2,500 free credits/week
    - Run 1 job at a time
    - Build on Linux, Windows, and Arm
  - [Pricing](https://circleci.com/pricing/)

- **[codefresh]** is a GitOps automation platform for Kubernetes apps

  - Features:
    - 1 small runner (1 GB RAM 1 CPU)
    - Up to 3 users
    - SaaS deployment
    - Unlimited builds
    - Unlimited repositories
    - Pipeline metrics
    - Private Helm repository
    - 1-month data retention
  - [Pricing](https://codefresh.io/pricing/)

- **[octopus deploy]** is a continuous delivery platform to enable your developers, release managers, and operations folks to bring all automation into a single place

  - Features:
    - Deployments as-a-service for 10 targets
    - Octopus on your infrastructure for 10 targets
  - [Pricing](https://octopus.com/pricing/overview)

## Event Streaming

- **[confluent]** offers Apache Kafka® as a cloud-native service

  - Features:
    - Single AZ Replication
    - Schema Registry
    - At-rest & in-transit data encryption, Kafka ACLs, SAML/SSO
    - End-to-end Kafka visualizations with Data Flow
    - Available add-ons:
    - Managed Connectors
    - Stream processing with ksqlDB
    - 1 task per Connector
    - First 10 partitions free
    - Up to 100MBps throughput
    - 5TB Storage
    - 99.5% Uptime SLA
  - [Pricing](https://www.confluent.co.uk/confluent-cloud/pricing)

## Kubernetes

> Please see [List of free Trials/Credit for Managed Kubernetes Services](https://github.com/learnk8s/free-kubernetes) for free trials

- **[Openshift]** s a Kubernetes distribution focused on developer experience and application security that's platform agnostic. OpenShift helps you develop and deploy applications to one or more hosts. These can be public facing web applications, or backend applications, including micro services or databases<sup>[redhat-openshift]</sup>

  - Features:
    - TBD

## Networking

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

  - Features:
    - Unlimited custom application and Internet access policies
    - 3 Network-level security for physical locations
    - Email support
    - Zero Trust Network Access
    - Secure Web Gateway
    - Recursive DNS Filters
    - Layer 7 Proxy Filters
    - Antivirus inspection
    - CASB-lite
    - 24h activity log retention
  - [Pricing](https://www.cloudflare.com/teams-pricing/)

## Observability

- **[logz.io]** is based on cloud-native technologies, so its easy to integrate with your distributed apps, servers, K8s clusters, serverless functions, and the rest of your environment. Based on G2Crowd reviews 1700+ teams already trust Logz.io<sup>[logzio]</sup>

  - Features:
    - A fully managed and auto scaling ELK Stack
    - Index up to 1 GB of log data
    - 10 alerts
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

- **[newrelic]** offers an integrated, cost-effective platform to centralize our approach to observability.

  - Features
    - 1 free Full user
    - 100GB free per month for Ingest
    - 8 days+ retention
    - Unlimited querying
    - 100 Synthetics Checks
    - Unlimited free Alerts
    - Free Proactive Detection 
  - [Pricing](https://newrelic.com/pricing)

- **[lightstep]** is a platform which offers infrastructure, application, runtime, cloud, third-party metrics ingestion and tracing

  - Features:
    - 4MB / minute of data tracing
    - max 7'5000 active time series
    - 28 days data retention
  - [Pricing](https://lightstep.com/pricing/)

- **[netdata cloud][netdata]** is an observability platform

  - Features:
    - Unlimited Hosts, Containers
    - Unlimited Metrics
    - Unlimited Custom Metrics
    - 1s Metrics granularity (with 100 ms latency)
    - Unlimited Users
    - Unlimited Admins
    - Unlimited Alarms (with up to per-second granularity)
    - Unlimited Alarm notifications (email, custom webhooks)
    - 200+ Data collection integrations
  - [Pricing](https://www.netdata.cloud/get-netdata/)

- [Sentry's][sentry] application monitoring platform helps every developer diagnose, fix, and optimize the performance of their code.

  - Features:
    - 1 user
    - 5K errors
    - 10K transactions
    - 1GB attachments
    - Support for all languages
    - Release tracking
    - Community forums
  - [Pricing](https://sentry.io/pricing/)

- **[logdna]** provides a scalable, easy to use platform to ingest and take action on all of your data, regardless of structure or use case. It’s trusted by thousands of developers and DevOps teams for SaaS, cloud, and hybrid applications.

  - Features:
    - Live Streaming Tail (no retention)
    - Unlimited Hosts & Source
    - Unlimited Saved Views
    - Single user
  - [Pricing](https://www.logdna.com/pricing)

## IAM

- **[jumpcloud]** Cloud Directory Platform as all in one directory, SSO, MDM, MFA, PAM, and more

  - Features:
    - full platform for 10 users and 10 devices
    - Features full platform functionality
    - 10 days of Premium 24x7 in-app live chat supporFast, easy-to-use DNS
  - [Pricing](https://jumpcloud.com/pricing)
  - [Community](https://jumpcloud.com/resources)

- **[cloudflare]** see under [Newtworking](#networking)

- **[okta]** is the leading platform for identity management

  - Features:
    - Monthly Active User Limit: 15'000
    - Cumulative Rate Limit Per Minute 1'600
    - Community Support
    - 5 OIDC Applications
    - 3 SAML Applications
    - M2M Tokens: 1.5k/month
    - 3 OIN Integrations
    - 3 Inbound Federation
    - Authentication
    - Social Authentication
    - Facebook/Google/Apple
    - MFA Factors
    - SMS/Voice MFA
    - Adaptive MFA Policies
    - User Management
    - Custom Domain
    - Custom Widget
    - ThreatInsight
    - API Access Management
    - Directory Integration
    - AD/LDAP
    - Lifecycle Management (LCM) Engine
    - 99.99% Uptime
  - [Pricing](https://developer.okta.com/pricing/)

## Search

- **[algolia]** is a flexible AI-powered Search & Discovery platform

  - Features:
    - 10 units free
      1 unit = 1,000 search requestsand the capacity to index up to 1,000 records
  - [Pricing](https://www.algolia.com/pricing/)

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

- **[aqua]** is a cloud native security platform available in both, Self-hosted or SaaS offering that secures your public cloud services across multiple accounts and providers.

  - Features:
    - Up to 500 Aqua units (AWS instances, S3 Buckets, ....)
    - CSPM
      - Single cloud account
      - Monthly Scan Reports
      - Compliance Reports CIS Only
    - Platform
      - Up to 5 Users
      - 30 Days Data Retention
      - Community Support
  - [Pricing](https://www.aquasec.com/pricing/)

- **[sonatype oss index]** is a free catalogue of open source components and scanning tools to help developers identify vulnerabilities, understand risk, and keep their software safe.

  - Features:
    - Search known, publicly disclosed vulnerabilities for these package types
      - Maven
      - npm
      - Go
      - PyPI
      - NuGet
      - RubyGems
      - Alpine
      - Bower
      - Cargo
      - Chocolatey
      - Clojars
      - CocoaPods
      - Composer
      - Conan
      - Conda
      - CRAN
      - Debian
      - Drupal
      - RPM
      - Swift

## Serverless Platform

- **[heroku]** uns your app in lightweight, isolated Linux containers called "dynos." The platform offers different dyno types to help you get the best results for your type of app.

  - Features:
    - 550-1,000 dyno hours per month
    - Deploy with Git and Docker
    - Custom domains
    - Container orchestration
    - Automatic OS patching
  - [Pricing](https://www.heroku.com/pricing)

- **[netlify]** is an intuitive Git-based workflow and powerful serverless platform to build, deploy, and collaborate on web apps

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

## Secret Management

- **[doppler]** is a universal secret manager

  - Features:
    - Unlimited Users
    - Unlimited Secrets
    - Secrets Referencing
  - [Pricing](https://www.doppler.com/pricing/)

## Storage (Cloud Native)

- **[robin.io]** Cloud Native Storage for any Kubernetes on‑premises and in any Cloud
  - Features:
    - 5 nodes
    - 5 TB storage
    - Community support
  - [Pricing](https://robin.io/features/)
  - [Slack](https://slack.robin.io/)

- **[portworx]** Kubernetes Storage Platform is the software-defined container storage platform built from the ground up for Kubernetes. By providing scale-out software defined container storage, data availability, data security, backup and disaster recovery for Kubernetes-based applications running on-prem or across clouds Cloud Native Storage

  - Features:
    - 5 nodes
    - 5 TB storage
    - 500 volumes
    - Max 30 Containers per Node
    - Max 50 Volumes
    - Max 1 TB Storage Per Node
    - Max 5 TB Storage Per Cluster
    - 5 Application-Consistent Snapshots per Volume
    - Volume Backup to Cloud:/Day/Volume

  - [Pricing](https://portworx.com/products/features/)
  - [Slack](https://slack.robin.io/)

- **[backblaze b2]** is enterprise-grade, S3 compatible storage that companies around the world use to store and serve data while improving their cloud OpEx vs. Amazon S3 and others.

  - Features:
    - 10GB free
  - [Pricing](https://www.backblaze.com/b2/cloud-storage-pricing.html)

## Testing

- **[testmail.app]** offers e-mail testing via an API

  - Features:
    - 100 emails/month
    - Unlimited inboxes, email addresses, and spam tests
    - Unlimited users
    - 1 day retention
    - One random namespace
  - [Pricing](https://testmail.app/pricing)

- **[lambdatest]** allows you to perform live interactive and automated cross browser testing on 2000+ real browsers and OS online

  - Features:
    - 1 Parallel Test (5 Users)
    - 60 mins/month Realtime Browser Testing
    - 6 Sessions of 10 minutes each
    - 10 Screenshot Tests per month
    - 10 Responsive Tests per month
    - 30 Mins Daily Access To LT Browser
    - 24x7 Support
    - 3rd Party App Integrations
    - Free 100 Automation Minutes for 15 days
  - [Pricing](https://www.lambdatest.com/pricing)

- **[accesslint]** offers automated and continuous web accessibility testing

  - Features:
    - Integrates with [github](https://github.com/marketplace/accesslint)
    - For personal accounts only
  - [Pricing](https://github.com/marketplace/accesslint/plan)

## Enterprise Linux

> Well Linux is generally free but it may be interesting to mention specific enterprise linux offers

- **[RedHat Linux]**, while CentOS Linux provided a no-cost Linux distribution, no-cost RHEL also exists today through the [Red Hat Developer program](https://developers.redhat.com/rhel8). You need a [Individual Developer subscription](https://developers.redhat.com/rhel8)<sup>[redhat-linux]</sup>

  - Features:
    -  RHEL can be used in production for up to 16

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
[netlify]: https://www.netlify.com/
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
[backblaze b2]: https://www.backblaze.com/b2/cloud-storage.html#
[robin.io]: https://robin.io/
[sonatype oss index]: https://ossindex.sonatype.org
[portworx]: https://central.portworx.com/
[circleci]: https://circleci.com/
[codefresh]: https://codefresh.io/
[newrelic]: https://newrelic.com/
[slack]: https://slack.com
[okta]: https://developer.okta.com
[testmail.app]: https://testmail.app
[confluenct]: https://www.confluent.co.uk
[flatline]: https://flatfile.io/product/portal
[algolia]: https://www.algolia.com
[codecov]: https://about.codecov.io
[bettercodehub]: https://www.bettercodehub.com
[awesomefonts]: https://fontawesome.com
[feathericons]: https://feathericons.com
[lightstep]: https://lightstep.com
[netdata]: https://www.netdata.cloud
[lambdatest]: https://www.lambdatest.com
[accesslint]: https://accesslint.com
[iconfinder]: https://www.iconfinder.com
[zulip]: https://zulip.com
[sourcehut]: https://sourcehut.org/
[doppler]: https://www.doppler.com/
[aqua]: https://www.aquasec.com
[oracle cloud]: https://www.oracle.com/cloud/free/
[google cloud]: https://cloud.google.com/free/docs/gcp-free-tier
[sentry]: https://sentry.io/
[logdna]: https://www.logdna.com/
