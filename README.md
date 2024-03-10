# Awesome DevOps

[![Awesome DevOps](http://awesome-devops.xyz/assets/banner.png)](https://github.com/wmariuss/awesome-devops)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Deploy](https://github.com/wmariuss/awesome-devops/actions/workflows/deploy.yml/badge.svg)](https://github.com/wmariuss/awesome-devops/actions/workflows/deploy.yml)
[![Links validator](https://github.com/wmariuss/awesome-devops/actions/workflows/links-validator.yml/badge.svg)](https://github.com/wmariuss/awesome-devops/actions/workflows/links-validator.yml)

> A curated list of platforms, tools, practices and resources to create, improve DevOps culture and SRE Team in the organization.

DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market.

## Contents

- [Cloud Platforms](#cloud-platforms)
- [Open Source Cloud Platforms](#open-source-cloud-platforms)
- [Operating Systems](#operating-systems)
- [Distributed Filesystems](#distributed-filesystems)
- [Applications Platforms](#applications-platforms)
- [Kubernetes Application Management](#Kubernetes-Application-Management)
- [Internal Developer Platforms](#internal-developer-platforms)
- [Container Image Registry](#container-image-registry)
- [Automation & Orchestration](#automation--orchestration)
- [Continuous Integration & Delivery](#continuous-integration--delivery)
- [Source Code Management](#source-code-management)
- [Web Servers](#web-servers)
- [SSL](#ssl)
- [Databases](#databases)
- [Observability and Monitoring](#observability--monitoring)
- [Service Discovery & Service Mesh](#service-discovery--service-mesh)
- [Chaos Engineering](#chaos-engineering)
- [API Gateway](#api-gateway)
- [Code review](#code-review)
- [Distributed messaging](#distributed-messaging)
- [Programming Languages](#programming-languages)
- [Chat and ChatOps](#chat-and-chatops)
- [Secret Management](#secret-management)
- [Security](#security)
- [Sharing](#sharing)
- [VPN](#vpn)
- [DevSecOps](#DevSecOps)
- [Information](#information)
  - [Guidelines](#guidelines)
  - [Presentations](#presentations)
  - [Initiatives](#initiatives)
  - [Keeping Informed](#keeping-informed)
  - [Wardley Maps for Security](#wardley-maps-for-security)
- [Training](#training)
  - [Labs](#labs)
  - [Vulnerable Test Targets](#vulnerable-test-targets)
  - [Conferences](#conferences)
  - [Podcasts](#podcasts)
  - [Books](#books)
- [Tools](#tools)
  - [Dashboards](#dashboards)
  - [Automation](#automation)
  - [Hunting](#hunting)
  - [Testing](#testing)
  - [Alerting](#alerting)
  - [Threat Intelligence](#threat-intelligence)
  - [Attack Modeling](#attack-modeling)
  - [Secret Management](#secret-management)
  - [Red Team](#red-team)
  - [Visualization](#visualization)
  - [Sharing](#sharing)
  - [ChatOps](#chatops)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
- [Resources](#resources)
  - [Books](#books)
  - [Conferences](#conferences)
  - [DevOps Roadmap](#devops-roadmap)

---

## Cloud Platforms

*Public and Private Cloud Platforms.*

- [Amazon Web Services (AWS)](https://aws.amazon.com/) - Cloud Computing Services.
- [Google Cloud Platform (GCP)](https://cloud.google.com/) - Cloud Computing Services.
- [Azure](https://azure.microsoft.com/) - Cloud Computing Platform & Services.
- [Alibaba Cloud](https://us.alibabacloud.com/) - Integrated suite of cloud products and services.
- [Oracle Cloud](https://www.oracle.com/cloud/) - Comprehensive and fully integrated stack of cloud applications and platform services.
- [DigitalOcean](https://www.digitalocean.com/) - Helping developers easily build, test, manage, and scale applications of any size.
- [Scaleway](https://www.scaleway.com/) - Single way to create, deploy and scale your infrastructure in the cloud.
- [Vultr](https://www.vultr.com/) - Easily deploy cloud servers, bare metal, and storage worldwide.
- [VMware Cloud](https://cloud.vmware.com/) - Run, manage, connect and protect all of your apps on any cloud.
- [IBM Cloud](https://www.ibm.com/cloud) - Tools, data & APIs to make AI real now.
- [Stackpath](https://www.stackpath.com/) - Platform of computing infrastructure and services built at the edge of the cloud.
- [Linode](https://www.linode.com/) - Accelerate innovation in the cloud, virtual computing must be more accessible, affordable, and simple.
- [Kinsta](https://kinsta.com/application-hosting/) - Create and deploy web applications and databases in minutes.

## Open Source Cloud Platforms

*Private, Public and Hybrid open source Cloud Platforms.*

- [Openstack](https://www.openstack.org/) - Open source software for creating private and public clouds.
- [Apache CloudStack](https://cloudstack.apache.org/) - Designed to deploy and manage large networks of virtual machines.
- [OpenNebula](https://opennebula.org/) - Build Private Clouds and manage Data Center virtualization based on KVM, LXD and VMware.
- [Eucalyptus](https://www.eucalyptus.cloud/) - Building AWS-compatible private and hybrid clouds.
- [DC/OS](https://dcos.io/) - Distributed operating system based on the Apache Mesos distributed systems kernel.
- [Apache Mesos](http://mesos.apache.org/) - Program against your datacenter like it’s a single pool of resources.
- [Localstack](https://github.com/localstack/localstack) - Fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline.

## Operating Systems

*Operating Systems - Server Platform.*

- [Ubuntu](https://ubuntu.com/) - Enterprise Open Source and Linux.
- [Rocky Linux](https://rockylinux.org/) - Open-source enterprise operating system designed to be 100% bug-for-bug compatible with Red Hat Enterprise Linux.
- [CoreOS](http://coreos.com/) - The pioneering lightweight container host.
- [OSv](http://osv.io/) - Versatile modular unikernel designed to run unmodified Linux applications securely on micro-VMs in the cloud.
- [Atomic](http://www.projectatomic.io/) - Use immutable infrastructure to deploy and scale your containerized applications.
- [Photon](https://github.com/vmware/photon) - Linux container host optimized for cloud-native applications, cloud platforms, and VMware infrastructure.

## Distributed Filesystems

*Network distributed filesystems.*

- [Ceph](https://ceph.io/en/) - Highly scalable object, block and file-based storage under one whole system.
- [Gluster](https://www.gluster.org/) - Free and open source software scalable network filesystem.
- [LINBIT](https://www.linbit.com/en/) - Create, remove, and replicate block storage devices for datacenter scale environments.
- [XtreemFS](http://www.xtreemfs.org/) - Fault-tolerant distributed file system for all storage needs.
- [min.io](https://min.io/) - High performance, distributed object storage system.

## Applications Platforms

*Applications management platforms, Containers platform and Containers management.*

- [Openshift](https://www.openshift.com/) - The Kubernetes platform for big ideas.
- [Dokku](https://dokku.com/) - Helps you build and manage the lifecycle of applications.
- [Flynn](https://flynn.io/) - Open source platform (PaaS) for running applications in production.
- [Cloud 66](https://www.cloud66.com/) - DevOps as a service that helps to build, deploy and manage any application on any cloud or server.
- [Docker](https://www.docker.com/) - Create, deploy, and run applications by using containers.
- [Docker Compose](https://github.com/docker/compose) - Define and run multi-container applications with Docker.
- [Docker Swarm](https://github.com/docker/swarm) - Docker-native clustering system.
- [Kubernetes](https://kubernetes.io/) - Automating deployment, scaling, and management of containerized applications.
- [LXC](https://linuxcontainers.org/) - Lets Linux users easily create and manage system or application containers.
- [Rancher](https://rancher.com/) - Lets you deliver Kubernetes-as-a-Service.
- [OpenVz](https://openvz.org/) - Container-based virtualization for Linux.
- [Singularity](https://sylabs.io/singularity/) - Run the application from the local environment to the cloud.
- [AppScale](https://github.com/AppScale/appscale) - Easy-to-manage serverless platform for building and running scalable web and mobile applications.
- [Kata Containers](https://katacontainers.io/) - Building lightweight virtual machines that seamlessly plug into the containers ecosystem.
- [K3S](https://k3s.io/) - The certified Kubernetes distribution built for IoT and Edge computing.
- [Podman](https://github.com/containers/podman) - A tool for managing OCI containers and pods.
- [Linx](https://linx.software) - General-purpose low-code platform for building and hosting backend solutions.

## Kubernetes Application Management

- [Helm](https://helm.sh/) - The package manager for k8s. Helm is the best way to find, share, and use software built for Kubernetes.
- [Kustomize](https://kustomize.io/) - Kubernetes native configuration management. Kustomize introduces a template-free way to customize application configuration that simplifies the use of off-the-shelf applications.

## Internal Developer Platforms

*Internal Developer Platforms (or IDP) is a set of tools, services and processes that supports and accelerates your software development, while taking care of managing the underlying infrastructure.*

- [Port](https://www.getport.io/) - A platform for building no-code, holistic, Internal Developer Portals.
- [Backstage](https://backstage.io/) - An open platform for building developer portals.
- [Kratix](https://kratix.io/) - A framework used by platform teams to build the custom platforms tailored to their organisation.

## Container Image Registry

*Container Image registry.*

- [Quay](https://www.projectquay.io/) - Container image registry that enables you to build, organize, distribute, and deploy containers.
- [Dockyard](https://github.com/Huawei/dockyard) - Container & Artifact Repository.
- [Harbor](https://goharbor.io/) - An open source trusted cloud native registry project that stores, signs, and scans content.
- [GitHub Container Registry](https://github.blog/2020-09-01-introducing-github-container-registry/) - Container registry free for public images.

## Automation & Orchestration

*Tools for automation, orchestration, deployment, provisioning and configuration management.*

- [Ansible](https://www.ansible.com/) - Simple IT automation platform that makes your applications and systems easier to deploy.
- [Salt](https://www.saltstack.com/) - Automate the management and configuration of any infrastructure or application at scale.
- [Puppet](https://puppet.com/) - Unparalleled infrastructure automation and delivery.
- [Chef](https://www.chef.io/) - Automate infrastructure and applications.
- [Juju](https://jaas.ai/) - Simplifies how you configure, scale and operate today's complex software.
- [Rundeck](https://www.rundeck.com/) - Runbook Automation For Modernizing Your Operations.
- [StackStorm](https://stackstorm.com/) - Connects all your apps, services, and workflows. Automate DevOps your way.
- [Bosh](https://www.cloudfoundry.org/bosh/) - Release engineering, deployment, and lifecycle management of complex distributed systems.
- [Cloudify](https://cloudify.co/) - Connect, Control, & Automate from core to edge: unlimited locations, clouds and devices.
- [Tsuru](https://tsuru.io/) - An extensible and open source Platform as a Service software.
- [Fabric](http://www.fabfile.org/) - High level Python library designed to execute shell commands remotely over SSH.
- [Capistrano](https://capistranorb.com/) - A remote server automation and deployment tool.
- [Mina](http://nadarei.co/mina/) - Really fast deployer and server automation tool.
- [Terraform](https://www.terraform.io/) - use Infrastructure as Code to provision and manage any cloud, infrastructure, or service.
- [Pulumi](https://www.pulumi.com/) - Modern infrastructure as code platform that allows you to use familiar programming languages and tools to build, deploy, and manage cloud infrastructure.
- [Packer](https://www.packer.io/) - Build Automated Machine Images.
- [Vagrant](https://www.vagrantup.com/) - Development Environments Made Easy.
- [Foreman](https://theforeman.org/) - Complete lifecycle management tool for physical and virtual servers.
- [Nomad](https://learn.hashicorp.com/nomad) - Deploy and Manage Any Containerized, Legacy, or Batch Application.
- [Marathon](https://mesosphere.github.io/marathon/) - A production-grade container orchestration platform for DC/OS and Apache Mesos.
- [OctoDNS](https://github.com/github/octodns) - Managing DNS across multiple providers. DNS as code.
- [ManageIQ](https://www.manageiq.org/) - Manage containers, virtual machines, networks, and storage from a single platform.
- [Ignite](https://github.com/weaveworks/ignite) -  Open Source Virtual Machine (VM) manager with a container UX and built-in GitOps management.
- [Selefra](https://github.com/selefra/selefra) - An open-source policy-as-code software that provides analytics for multi-cloud and SaaS.
- [Spacelift](https://spacelift.io/) - Flexible orchestration solution for IaC development.
- [Atlantis](https://www.runatlantis.io/) - Terraform Pull Request Automation
- [KubeVela](https://kubevela.io/) - Modern application delivery platform that makes deploying and operating applications across today's hybrid, multi-cloud environments easier, faster and more reliable.
- [Stacktape](https://stacktape.com) - Developer-friendly Infrastructure as a Code framework built on top of AWS.
- [Score](https://score.dev) - Open Source developer-centric and platform-agnostic workload specification.
- [Meshery](https://meshery.io/) - An open source, cloud native manager that enables the design and management of all Kubernetes-based infrastructure and applications.
- [Digger](https://digger.dev) - Open Source Infrastructure as Code management tool that runs within your CI/CD system.

## Continuous Integration & Delivery

*Continuous Integration, Continuous Delivery and Continuous Delivery. GitOps.*

- On premises
  - [Jenkins](http://jenkins-ci.org/) - automation server for building, deploying and automating any project.
  - [Github Actions](https://docs.github.com/en/actions) - Build, test, and deploy your code right from GitHub. Make code reviews, branch management, and issue triaging work the way you want.
  - [Argocd](https://argoproj.github.io/cd/) - Declarative continuous delivery with a fully-loaded UI.
  - [Tekton](https://tekton.dev/) - Tekton is a powerful and flexible open-source framework for creating CI/CD systems, allowing developers to build, test, and deploy across cloud providers and on-premise systems.
  - [Buildbot](http://buildbot.net/) - automate all aspects of the software development cycle.
  - [Gitlab CI](https://about.gitlab.com/product/continuous-integration/) - pipelines build, test, deploy, and monitor your code as part of a single, integrated workflow.
  - [Drone](https://github.com/drone/drone) - a Container-Native, Continuous Delivery Platform.
  - [Concourse](https://concourse-ci.org/) - pipeline-based continuous thing-doer.
  - [Spinnaker](https://www.spinnaker.io/) - fast, safe, repeatable deployments for every Enterprise.
  - [goCD](https://www.gocd.org/) - Delivery and Release Automation server.
  - [Teamcity](https://www.jetbrains.com/teamcity/) - enterprise-level CI and CD.
  - [Bamboo](https://www.atlassian.com/software/bamboo) - tie automated builds, tests, and releases together in a single workflow.
  - [Integrity](http://integrity.github.io/) - Continuous Integration server.
  - [Zuul](https://zuul-ci.org/) - drives continuous integration, delivery, and deployment systems with a focus on project gating.
  - [Argo](https://argoproj.github.io/) - Open Source Kubernetes native workflows, events, CI and CD.
  - [Strider](https://strider-cd.github.io/) - Continuous Deployment/Continuous Integration platform.
  - [Evergreen](https://github.com/evergreen-ci/evergreen) - A Distributed Continuous Integration System from MongoDB.
  - [werf](https://werf.io/) - Open Source CI/CD tool for building Docker images & deploying them to Kubernetes using a GitOps approach.
  - [Flux](https://github.com/fluxcd/flux) - automatically ensures that the state of your Kubernetes cluster matches the configuration you’ve supplied in Git.
  - [Flagger](https://github.com/weaveworks/flagger) - progressive delivery Kubernetes operator (Canary, A/B Testing and Blue/Green deployments).
  - [Tekton](https://tekton.dev/) - powerful and flexible open-source framework for creating CI/CD systems.
  - [PipeCD](https://pipecd.dev/) - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications.
  - [Gitploy](https://www.gitploy.io/) - Build the deployment system around GitHub in minutes.
  - [Dagger](https://dagger.io/) - CI/CD as Code that Runs Anywhere.
- Public Services
  - [Travis CI](https://travis-ci.org/) - easily sync your projects, you’ll be testing your code in minutes.
  - [Circle CI](https://circleci.com/) - powerful CI/CD pipelines that keep code moving.
  - [Bitrise](https://www.bitrise.io/) - CI/CD for mobile applications.
  - [Buildkite](https://buildkite.com/) - run fast, secure, and scalable continuous integration pipelines on your own infrastructure.
  - [Cirrus CI](https://cirrus-ci.org/) - continuous integration system built for the era of cloud computing.
  - [Codefresh](https://codefresh.io/) - GitOps automation platform for Kubernetes apps.
  - [Github actions](https://github.com/features/actions) - GitHub Actions makes it easy to automate all your software workflows, now with world-class CI/CD.
  - [Kraken CI](https://kraken.ci/) - Modern CI/CD, open-source, on-premise system that is highly scalable and focused on testing.
  - [Earthly](https://earthly.dev/) - Develop CI/CD pipelines locally and run them anywhere.

## Source Code Management

*Source Code management, Git-repository manager, Version Control. Some of them are included in Code review section.*

- [GitHub](https://github.com/) - Helps developers store and manage their code, as well as track and control changes to their code.
- [Gitlab](https://gitlab.com/) - Entire DevOps lifecycle in one application.
- [Bitbucket](https://bitbucket.org/product/) - Gives teams one place to plan projects, collaborate on code, test, and deploy
- [Phabricator](https://github.com/phacility/phabricator/) - A collection of web applications which help software companies build better software.
- [Gogs](https://gogs.io/) - A painless self-hosted Git service.
- [Gitea](https://gitea.io/) - A painless self-hosted Git service.
- [Gitblit](https://github.com/gitblit/gitblit) - Pure Java Git solution for managing, viewing, and serving Git repositories.
- [RhodeCode](https://rhodecode.com/) - Centralized control for distributed repositories. Mercurial, Git, and Subversion under a single roof.
- [Radicle](https://radicle.xyz/) - Radicle is a sovereign peer-to-peer network for code collaboration, built on top of Git.

## Web Servers

*Web servers and reverse proxy.*

- [Nginx](http://nginx.org/) - High performance load balancer, web server and reverse proxy.
- [Apache](http://httpd.apache.org/) - Web server and reverse proxy.
- [Caddy](https://caddyserver.com/) - Web server with automatic HTTPS.
- [Cherokee](http://cherokee-project.com/) - Highly concurrent secured web applications.
- [Lighttpd](http://www.lighttpd.net/) - Optimized for speed-critical environments while remaining standards-compliant, secure and flexible.
- [Uwsgi](https://github.com/unbit/uwsgi/) - Application server container.

## SSL

*Tools for automating the management of SSL certificates.*

- [Certbot](https://github.com/certbot/certbot) - Automate using Let’s Encrypt certificates on manually-managed websites to enable HTTPS.
- [Let’s Encrypt](https://letsencrypt.org/) - Free, automated, and open Certificate Authority.
- [Cert Manager](https://github.com/jetstack/cert-manager) - K8S add-on to automate the management and issuance of TLS certificates from various issuing sources.

## Databases

*Relational (SQL) and non-relational (NoSQL) databases.*

- Relational (SQL)
  - [PostgreSQL](https://www.postgresql.org/) - Powerful, open source object-relational database system.
  - [MySQL](https://www.mysql.com/) - Open-source relational database management system.
  - [MariaDB](https://mariadb.org/) - Fast, scalable and robust, with a rich ecosystem of storage engines, plugins and many other tools.
  - [SQLite](https://sqlite.org/) - Small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- Non-relational (NoSQL)
  - [Cassandra](http://cassandra.apache.org/) - Manage massive amounts of data, fast, without losing sleep.
  - [ScyllaDB](https://www.scylladb.com/) - NoSQL data store using the seastar framework, compatible with Apache Cassandra
  - [Apache HBase](http://hbase.apache.org/) - Distributed, versioned, non-relational database.
  - [Couchdb](https://couchdb.apache.org/) - Database that completely embraces the web.
  - [Elasticsearch](https://www.elastic.co/products/elasticsearch) - Distributed, RESTful search and analytics engine capable of addressing a growing number of use cases.
  - [MongoDB](https://www.mongodb.com/) - General purpose, document-based, distributed database built for modern applications.
  - [Rethinkdb](https://github.com/rethinkdb/rethinkdb) - Open-source database for the realtime web.
  - Key-Value
    - [Couchbase](https://www.couchbase.com/) - Distributed  multi-model NoSQL document-oriented database that is optimized for interactive applications.
    - [Leveldb](https://github.com/google/leveldb) - Fast key-value storage library.
    - [Redis](https://redis.io/) - In-memory data structure store, used as a database, cache and message broker.
    - [RocksDB](https://rocksdb.org/) - A library that provides an embeddable, persistent key-value store for fast storage.
    - [Etcd](https://github.com/etcd-io/etcd) - Distributed reliable key-value store for the most critical data of a distributed system.

## Observability & Monitoring

*Observability, Monitoring, Metrics/Metrics collection and Alerting tools.*

- [Steampipe](https://steampipe.io/) - The universal SQL interface for any cloud API, & cloud intelligence dashboards extensible w/ HCL+SQL.
- [Sensu](https://sensu.io/) - Simple. Scalable. Multi-cloud monitoring.
- [Alerta](https://github.com/alerta/alerta) - Scalable, minimal configuration and visualization monitoring system.
- [Cabot](https://github.com/arachnys/cabot) - Self-hosted, easily-deployable monitoring and alerts service.
- [Amon](https://github.com/amonapp/amon) - Modern server monitoring platform.
- [Icinga](https://icinga.com/) - Monitors availability and performance, gives you simple access to relevant data and raises alerts.
- [Monit](https://mmonit.com/monit/#home) - Managing and monitoring Unix systems.
- [Naemon](http://www.naemon.org/) - Fast, stable and innovative while giving you a clear view of the state of your network and applications.
- [Nagios](https://www.nagios.org/) - Computer-software application that monitors systems, networks and infrastructure.
- [Sentry](https://sentry.io/welcome/) - Error monitoring that helps all software teams discover, triage, and prioritize errors in real-time.
- [Shinken](https://github.com/shinken-solutions/shinken) - Monitoring framework.
- [Zabbix](https://www.zabbix.com/) - Mature and effortless monitoring solution for network monitoring and application monitoring.
- [Glances](https://github.com/nicolargo/glances) - Monitoring information through a curses or Web based interface.
- [Healthchecks](https://github.com/healthchecks/healthchecks) - Cron monitoring tool.
- [Bolo](http://bolo.niftylogic.com/) - Building distributed, scalable monitoring systems.
- [cAdvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers.
- [ElastiFlow](https://github.com/robcowart/elastiflow) - Network flow monitoring (Netflow, sFlow and IPFIX) with the Elastic Stack.
- [Co-Pilot](https://pcp.io/) - System performance analysis toolkit.
- [Keep](https://github.com/keephq/keep) - Open source alerting CLI for developers.
- [Globalping CLI](https://github.com/jsdelivr/globalping-cli) - Run network commands like ping, traceroute and mtr from hundreds of global locations.
- [Grai](https://github.com/grai-io/grai-core) - Open source observability integrating data impact analysis into CI.
- [Canary Checker](https://canarychecker.io) - Open source health check platform.
- Metrics/Metrics collection
  - [Thundra Foresight](https://www.thundra.io/foresight) - Visibility into CI pipeline by spotting test failures in no time.
  - [Prometheus](https://prometheus.io/) - Power your metrics and alerting with a leading open-source monitoring solution.
  - [Collectd](https://github.com/collectd/collectd) - The system statistics collection daemon.
  - [Facette](https://github.com/facette/facette) - Time series data visualization software.
  - [Grafana](https://grafana.com/) - Analytics & monitoring solution for every database.
  - [Graphite](https://graphite.readthedocs.io/en/latest/) - Store numeric time-series data and render graphs of this data on demand.
  - [Influxdata](https://www.influxdata.com/) - Time series database.
  - [Netdata](https://www.netdata.cloud/) - Instantly diagnose slowdowns and anomalies in your infrastructure.
  - [Freeboard](https://github.com/Freeboard/freeboard) - Real-time dashboard builder for IOT and other web mashups.
  - [Autometrics](https://autometrics.dev/) - An open source micro framework for observability.
- Logs Management
  - [Loki](https://github.com/grafana/loki) - Horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. 
  - [Anthracite](https://github.com/Dieterbe/anthracite) - An event/change logging/management app.
  - [Graylog](https://github.com/Graylog2/graylog2-server) - Free and open source log management.
  - [Logstash](https://www.elastic.co/products/logstash#) - Collect, parse, transform logs.
  - [Fluentd](https://www.fluentd.org/) - Data collector for unified logging layer.
  - [Flume](https://flume.apache.org/) - Distributed, reliable, and available service for efficiently collecting, aggregating, and moving logs.
  - [Heka](https://hekad.readthedocs.io/en/latest/#) - Stream processing software system.
  - [Kibana](https://www.elastic.co/products/kibana) - Explore, visualize, discover data.
 
- Tracing
  - [Jaeger](https://www.jaegertracing.io/) - Jaeger: open source, distributed tracing platform. Monitor and troubleshoot workflows in complex distributed systems
  
- Status
  - [Cachet](https://github.com/CachetHQ/Cachet) - Beautiful and powerful open source status page system.
  - [StatusPal](https://statuspal.io/?utm_source=github.com&utm_medium=referral&utm_campaign=awesome-devops) - Communicate incidents and maintenance effectively with a beautiful hosted status page.
  - [Instatus](https://instatus.com) - Quick and beautiful status page.

## Service Discovery & Service Mesh

*Service Discovery, Service Mesh and Failure detection tools.*

- [Istio](https://istio.io/) - Connect, secure, control, and observe services.
- [Cilium](https://cilium.io/) - Cilium is an open source, cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary Kernel technology eBPF
- [Gateway API](https://gateway-api.sigs.k8s.io/) -  Gateway API is an add-on containing API kinds that provide dynamic infrastructure provisioning and advanced traffic routing.
- [Consul](https://www.hashicorp.com/products/consul/) - Connect and secure any service.
- [Serf](https://www.serf.io/) - Decentralized cluster membership, failure detection, and orchestration.
- [Doozerd](https://github.com/ha/doozerd) - A consistent distributed data store.
- [Zookeeper](http://zookeeper.apache.org/) - Centralized service for configuration, naming, providing distributed synchronization, and more.
- [Etcd](https://etcd.io/) - Distributed, reliable key-value store for the most critical data of a distributed system.
- [Kong](https://konghq.com/) - Deliver performance needed for microservices, service mesh, and cloud native deployments.
- [Linkerd](https://github.com/linkerd/linkerd2) - Service mesh for Kubernetes and beyond.

## Chaos Engineering

*The discipline of experimenting on a distributed system in order to build confidence in the system's capability to withstand turbulent conditions in production.*

- [Chaos Toolkit](https://github.com/chaostoolkit) - The Open Source Platform for Chaos Engineering.
- [Chaos Monkey](https://github.com/Netflix/chaosmonkey) - A resiliency tool that helps applications tolerate random instance failures.
- [Toxiproxy](https://github.com/Shopify/toxiproxy) - Simulate network and system conditions for chaos and resiliency testing.
- [Pumba](https://github.com/alexei-led/pumba) - Chaos testing, network emulation and stress testing tool for containers.
- [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) - A Chaos Engineering Platform for Kubernetes.
- [Litmus](https://github.com/litmuschaos/litmus) - Litmus enables teams to identify weaknesses in infrastructures.

## API Gateway

*API Gateway, Service Proxy and Service Management tools.*

- [API Umbrella](https://github.com/NREL/api-umbrella) - Proxy that sits in front of your APIs, API management platform.
- [Ambassador](https://www.getambassador.io/) - Kubernetes-Native API Gateway built on the Envoy Proxy.
- [Kong](https://konghq.com/) - Connect all your microservices and APIs with the industry’s most performant, scalable and flexible API platform.
- [Tyk](https://tyk.io/) - API and service management platform.
- [Cilium](https://github.com/cilium/cilium) - API aware networking and security using BPF and XDP.
- [Gloo](https://github.com/solo-io/gloo) - Feature-rich, Kubernetes-native ingress controller, and next-generation API gateway.
- [Envoy](https://www.envoyproxy.io/) - Cloud-native high-performance edge/middle/service proxy.
- [Traefik](https://traefik.io/) - Reverse proxy and load balancer for HTTP and TCP-based applications.

## Code review

*Code review. A few of the Source Code Management tools have built-in code review features.*

- [Gerrit](https://www.gerritcodereview.com/) - Web-based team code collaboration tool.
- [Review Board](https://www.reviewboard.org/) - Web-based collaborative code review tool.
- [MeshMap](https://layer5.io/cloud-native-management/meshmap) - World’s only visual designer for Kubernetes and cloud native applications. Design, deploy, and manage your Kubernetes-based, cloud native deployments allowing you to speed up infrastructure configuration.

## Distributed messaging

*Distributed messaging platforms and Queues software.*

- [Rabbitmq](https://www.rabbitmq.com/) - Message broker.
- [Kafka](http://kafka.apache.org/) - Building real-time data pipelines and streaming apps.
- [Activemq](http://activemq.apache.org/) - Multi-Protocol messaging.
- [Beanstalkd](https://beanstalkd.github.io/) - Simple, fast work queue.
- [NSQ](https://nsq.io/) - Realtime distributed messaging platform.
- [Celery](http://www.celeryproject.org/) - Asynchronous task queue/job queue based on distributed message passing.
- [Faktory](https://github.com/contribsys/faktory) - Repository for background jobs within your application.
- [Nats](https://nats.io/) - Simple, secure and high performance open source messaging system.
- [RestMQ](http://restmq.com/) - Message queue which uses HTTP as transport.
- [Dkron](https://github.com/distribworks/dkron) - Distributed, fault tolerant job scheduling system.
- [KubeMQ](https://kubemq.io/) - Kubernetes-native messaging platform.

## Programming Languages

*Programming languages.*

- [Python](https://www.python.org/) - Programming language that lets you work quickly and integrate systems more effectively.
- [Ruby](https://www.ruby-lang.org/) - A dynamic, open source programming language with a focus on simplicity and productivity.
- [Go](https://golang.org/) - An open source programming language that makes it easy to build simple, reliable, and efficient software.

## Chat and ChatOps

*Chat and ChatOps.*

- [Rocket](https://rocket.chat/) - Open source team communication.
- [Mattermost](https://mattermost.com/) - Messaging platform that enables secure team collaboration.
- [Zulip](https://zulipchat.com/) - Real-time chat with an email threading model.
- [Riot](https://about.riot.im/) - A universal secure chat app entirely under your control.
- ChatOps:
  - [CloudBot](https://github.com/CloudBotIRC/CloudBot) - Simple, fast, expandable, open-source Python IRC Bot.
  - [Hubot](https://hubot.github.com/) - A customizable life embetterment robot.

## Secret Management

*Security as code, sensitive credentials and secrets need to be managed, security, maintained and rotated using automation.*

- [Sops](https://github.com/mozilla/sops) - Simple and flexible tool for managing secrets.
- [Vault](https://www.hashicorp.com/products/vault/) - Manage secrets and protect sensitive data.
- [Keybase](https://keybase.io/) - End-to-end encrypted chat and cloud storage system.
- [Vault Secrets Operator](https://github.com/ricoberger/vault-secrets-operator) - Create Kubernetes secrets from Vault for a secure GitOps based workflow.
- [Git Secret](https://github.com/sobolevn/git-secret) - A bash-tool to store your private data inside a git repository.
- [Infisical](https://github.com/Infisical/infisical) - Open source end-to-end encrypted secrets sync for teams and infrastructure.
- [Lade](https://github.com/zifeo/lade) - Automatically load secrets from your preferred vault as environment variables.

## Security

*Validating, lint and best practice in term of Security on code or infrastructure.*

- [checkov](https://github.com/bridgecrewio/checkov) - Prevent cloud misconfigurations and find vulnerabilities during build-time in infrastructure as code, container images and open source packages.
- [Trivy](https://trivy.dev/) - Trivy is the most popular open source security scanner, reliable, fast, and easy to use. Use Trivy to find vulnerabilities & IaC misconfigurations, SBOM discovery, Cloud scanning, Kubernetes security risks,and more.
- [**Kubescape**](https://github.com/kubescape/kubescape) - An open-source Kubernetes security platform for your clusters, CI/CD pipelines, and IDE that seperates out the security signal from the scanner noise.
- [**Teller**](https://tlr.dev/) - Teller is a productivity secret manager for developers supporting cloud-native apps and multiple cloud providers. Mix and match all vaults and other key stores and safely use secrets as you code, test, and build applications. It's quick, easy, and safe.
- [Falco](https://falco.org/) - Falco is a cloud-native security tool designed for Linux systems. It employs custom rules on kernel events, which are enriched with container and Kubernetes metadata, to provide real-time alerts. Falco helps you gain visibility into abnormal behavior, potential security threats, and compliance violations, contributing to comprehensive runtime security.
- [kubearmor](https://kubearmor.io/) - KubeArmor is a runtime Kubernetes security engine. It uses eBPF and Linux Security Modules(LSM) for fortifying workloads based on Cloud Containers, IoT/Edge, and 5G networks. It enforces policy-based controls.
- [External Secrets Operator](https://external-secrets.io/latest/) - External Secrets Operator is a Kubernetes operator that integrates external secret management systems like AWS Secrets Manager, HashiCorp Vault, Google Secrets Manager, Azure Key Vault, IBM Cloud Secrets Manager, CyberArk Conjur and many more. The operator reads information from external APIs and automatically injects the values into a Kubernetes Secret.
- [sigstore](https://docs.sigstore.dev/signing/quickstart/) - Cosign is a command line utility that can sign and verify software artifact, such as container images and blobs.
- [Cert Manager](https://cert-manager.io/docs/) - cert-manager creates TLS certificates for workloads in your Kubernetes or OpenShift cluster and renews the certificates before they expire.


## Sharing

*A collection of tools to help with sharing knowledge and telling the story.*

- [Gitbook](https://github.com/GitbookIO/gitbook) - Modern documentation format and toolchain using Git and Markdown.
- [Docusaurus](https://github.com/facebook/docusaurus) - Easy to maintain open source documentation websites.
- [Docsify](https://github.com/docsifyjs/docsify/) - A magical documentation site generator.
- [MkDocs](https://github.com/mkdocs/mkdocs/) - Project documentation with Markdown.

## VPN

*VPN, routing and firewall.*

- [OpenVPN](https://openvpn.net/) - Flexible VPN solutions to secure your data communications, whether it's for Internet privacy.
- [Pritunl](https://pritunl.com/) - Enterprise Distributed OpenVPN and IPsec Server.
- [VyOS](https://vyos.io/) - Open source network OS that runs on a wide range of hardware, virtual machines, and cloud providers.
- [Algo](https://github.com/trailofbits/algo) - Set up a personal VPN in the cloud.
- [Streisand](https://github.com/StreisandEffect/streisand) - Sets up a new VPN service nearly automatically.
- [Freelan](https://github.com/freelan-developers/freelan) - A peer-to-peer, secure, easy-to-setup, multi-platform, open-source, highly-configurable VPN software.
- [Sshuttle](https://github.com/sshuttle/sshuttle) - Transparent proxy server that works as a poor man's VPN.
- [SoftEther](https://www.softether.org/) - An Open-Source Free Cross-platform Multi-protocol VPN Program.
as an academic project from University of Tsukuba, under the Apache License 2.0.
- [Firezone](https://www.firezone.dev/) - Self-hosted VPN server using WireGuard. Supports MFA, SSO, and has easy deployment options.

# DevSecOps

Below are the essential building blocks and tidbits that can help you arrange for a DevSecOps experiment or help you build out your own DevSecOps program.

This list will not be fully comprehensive and will change as DevSecOps matures.  We intend for it to be an awesome list that grows and changes as the community learns and improves how DevSecOps is implemented and adopted.  To be included in this list, the information, tools, vendors, or initiatives must provide for Free or Open Source capabilities that help with the DevSecOps mission.  Links that lead to a commercial aspect are noted with a (P).

# Information
We've been working across the industry to learn more about the different types of DevOps + Security initiatives.  This collection has been pulled together and includes: Podcasts, Videos, Presentations, and other Media to help you learn more about DevSecOps, SecDevOps, DevOpsSec, and/or DevOps + Security.

## Guidelines
While we're not into the paper-way of doing things, sharing sound advice and good recommendations can make software stronger.  We aim to make these guidelines better through code.

* [Introduction to DevSecOps - DZone Refcard](https://dzone.com/refcardz/introduction-to-devsecops)
* [Security Champions Playbook](https://github.com/c0rdis/security-champions-playbook)
* [Security Guide for Web Developers](https://github.com/FallibleInc/security-guide-for-developers)
* [A practical guide to build DAST with OWASP Zap](https://github.com/Soluto/owasp-zap-glue-ci-images)
* [Introduction to security testing and tools](https://www.omerlh.info/2018/10/04/write-good-code-with-security-tests/)
* [DevSecOps Hub](https://snyk.io/devsecops/)


## Presentations
Many talks are now targeting the change of adding Security into the DevOps environment.  We've added some of the most notable ones here.    

* [DevSecOps: Taking a DevOps Approach to Security](https://www.slideshare.net/AlertLogic/alert-logic-and-chef-dev-ops-webinar)
* [Mozilla's Test Driven Security in Continuous Integration](https://www.youtube.com/watch?v=e2axToBYD68)
* [Security DevOps - staying secure in agile projects](https://christian-schneider.net/slides/OWASP-AppSecEU-2015_SecDevOps.pdf)
* [Veracode's Defending the Cloud from a Full Stack Hack](https://www.rsaconference.com/writable/presentations/file_upload/csv-w03-_defending-the-cloud-from-the-full-stack-hack.pdf)
* [Put Your Robots to Work: Security Automation at Twitter](https://vimeo.com/54250716)
* [The Three Faces of DevSecOps](https://www.infoq.com/presentations/devsecops-2019/)


## Initiatives
There are a variety of initiatives underway to migrate security and compliance into DevOps.  We've included links for active projects here:

* [AWS Labs](https://github.com/awslabs)
* [DevOps and Audit Resources](https://itsanicelife.com/2017/03/13/devops-and-audit-resources/)
* [DevSecOps](http://devsecops.org)
* [OpenDevSecOps](https://opendevsecops.org)
* [Rugged DevOps](http://www.ruggedsoftware.org)


## Keeping Informed
We've discovered a treasure trove of mailing lists and newsletters where DevSecOps like us are sharing their skills and insights.  

* [AWS Security](https://aws.amazon.com/security/)
* [Azure Security](https://azure.microsoft.com/en-us/overview/security/)
* [Ruby Weekly](http://rubyweekly.com)
* [Security Newsletter](https://securitynewsletter.co/)
* [SRE Weekly](https://sreweekly.com/)

## Wardley Maps for Security
One way for people to continue to evolve their capabilities and share common understanding is through the development of Wardley Maps.  We're collecting this information and providing some good examples here.

* [Check out Figure 6 for Comparisons](http://www.cio.co.uk/it-strategy/introduction-wardley-value-chain-mapping-3604565/)
* [DevSecOps Repo for Security Maps](https://github.com/devsecops/wardley-maps)
* [Introduction to Wardley Maps](http://blog.gardeviance.org/2015/02/an-introduction-to-wardley-value-chain.html)
* [Security Industry Example](http://blog.gardeviance.org/2014_08_01_archive.html)
* [SOC Value Chain & Delivery Models](http://blog.blackswansecurity.com/2016/01/soc-value-chain-delivery-models/)


# Training
DevSecOps requires an appetite for learning and agility to quickly acquire new skills.  We've collected these links to help you learn how to do DevSecOps with us.

## Labs
Labs are hands-on learning opportunities to grow your skills in Dev, Sec, and Ops.  All skills are useful and need to be grown so that you can have the empathy, knowledge and trade to operate DevSecOps style.

* [DevSecOps Bootcamp](https://github.com/devsecops/bootcamp)
* [Exercism](http://exercism.io/)
* [Infoseclabs](http://www.infoseclabs.net)
* [Infrastructure Monitoring](https://github.com/appsecco/defcon24-infra-monitoring-workshop)
* [Pentester Lab](https://pentesterlab.com/exercises/)
* [Vulnhub](https://www.vulnhub.com/)


## Vulnerable Test Targets
It's important to build up knowledge by learning how to break applications left vulnerable by security mistakes.  This section contains a list of vulnerable apps that can be deployed to learn what not to do.  These same apps can be made safe by remediating the intentional vulnerabilities to learn how to prevent attackers from gaining access to underlying infrastructure or data.

* [Damn Vulnerable Web Application](https://github.com/ethicalhack3r/DVWA) (PHP/MySQL)
* [LambHack](https://github.com/wickett/lambhack) (Lambda)
* [Metasploitable](https://community.rapid7.com/docs/DOC-1875) (Linux)
* [Mutillidae](http://www.irongeek.com/i.php?page=mutillidae/mutillidae-deliberately-vulnerable-php-owasp-top-10) (PHP)
* [NodeGoat](https://github.com/owasp/nodegoat) (Node)
* [OWASP Damn Vulnerable Serverless Application (DVSA)](https://github.com/owasp/dvsa) (AWS Serverless)
* [OWASP Juice Shop](https://github.com/OWASP/glue) (NodeJS/Angular)
* [RailsGoat](https://github.com/OWASP/railsgoat) (Rails)
* [WebGoat](https://github.com/WebGoat/WebGoat) (Web App)
* [WebGoat.Net](https://github.com/OWASP/WebGoat.NET) (.NET)
* [WebGoatPHP](https://github.com/OWASP/OWASPWebGoatPHP) (PHP)


## Conferences
A body of knowledge for combining DevOps and Security has been delivered via conferences and meetups.  This is a short list of the venues that have dedicated a portion of their agenda to it.

* [AWS re:Inforce](https://reinforce.awsevents.com/)
* [AWS re:Invent](https://reinvent.awsevents.com)
* [DevSecCon](http://devseccon.com)
* [DevOps Connect](http://www.devopsconnect.com/)
* [DevOps Days](http://www.devopsdays.org/)
* [Goto Conference](http://gotocon.com)
* [IP Expo](http://www.ipexpoeurope.com/)
* [ISACA Ireland](http://www.isaca.org/chapters5/Ireland/conference/pages/Agenda.aspx)
* [RSA Conference](http://www.rsaconference.com)
* [All Day DevOps](https://www.alldaydevops.com/)


## Podcasts
A small collection of DevOps and Security podcasts.

* [Arrested DevOps](https://www.arresteddevops.com/)
* [Brakeing Down Security Podcast](http://www.brakeingsecurity.com/)
* [Darknet Diaries](https://darknetdiaries.com)
* [Defensive Security Podcast](http://www.defensivesecurity.org/)
* [DevOps Cafe](http://devopscafe.org/)
* [Down The Security Rabbithole](http://podcast.wh1t3rabbit.net/)
* [Food Fight Show](http://foodfightshow.org/)
* [OWASP 24/7](https://www.owasp.org/index.php/OWASP_Podcast)
* [Risky Business](http://risky.biz/)
* [Social Engineering Podcast](http://www.social-engineer.org/category/podcast/)
* [Software Engineering Radio](http://www.se-radio.net/team/kim-carter/)
* [Take 1 Security Podcast](https://danielmiessler.com/podcast/)
* [Tenable Security Podcast](http://www.tenable.com/podcast)
* [The Secure Developer](http://www.heavybit.com/library/podcasts/the-secure-developer/)
* [Trusted Sec Podcast](https://www.trustedsec.com/podcast/)

## Books
Books focussed around DevSecOps, bringing the security focus upfront.

* [DevOpsSec](http://www.oreilly.com/webops-perf/free/devopssec.csp)
* [Docker Security - Quick Reference](https://binarymist.io/publication/docker-security/)
* [Holistic Info-Sec for Web Developers](https://leanpub.com/b/holisticinfosecforwebdevelopers)
* [Securing DevOps](https://securing-devops.com/book)
* [The DevOps Handbook (Section VI)](https://www.oreilly.com/library/view/the-devops-handbook/9781457191381/)

# Tools
This collection of tools is useful in establishing a DevSecOps platform.  We have divided the tools into several categories that help with the different divisions of DevSecOps.

## Dashboards
Visualization is an important element of identifying, sharing, and evolving the security information that passes from the beginning of the creative process through to operations.

* [Grafana](http://grafana.org/)
* [Kibana](https://www.elastic.co/products/kibana)

## Automation
Automation platforms have the advantage of providing scripted remediation when security defects are surfaced.

* [Demisto](https://www.demisto.com/community/)
* [OWASP Glue](https://github.com/OWASP/glue)
* [StackStorm](https://github.com/StackStorm/st2)
* [Insider CLI](https://github.com/insidersec/insider)

## Hunting
This list of tools provides the capabilities necessary for finding security anomalies and identifying rules that should be automated and extended to support scale demands.

* [GRR](https://github.com/google/grr)
* [kube-hunter](https://github.com/aquasecurity/kube-hunter)
* [mig](https://github.com/mozilla/mig)
* [Mirador](http://fathom.info/mirador/)
* [moloch](https://github.com/aol/moloch)
* [MozDef](https://github.com/mozilla/MozDef)
* [osquery](https://osquery.io/)
* [OSSEC](http://ossec.github.io/)
* [osxcollector](https://github.com/Yelp/osxcollector)


## Testing
Testing is an essential element of a DevSecOps program because it helps to prepare teams for Rugged operations and to determine security defects before they can be exploited.

* [Brakeman](http://brakemanscanner.org)
* [Checkov](https://github.com/bridgecrewio/checkov/)
* [Chef Inspec](https://github.com/chef/inspec)
* [Contrast Security](https://www.contrastsecurity.com)
* [Cohesion](https://secapps.com/cohesion)
* [David](https://david-dm.org/)
* [Deepfence ThreatMapper](https://github.com/deepfence/ThreatMapper)
* [Gauntlt](http://gauntlt.org/)
* [Hakiri](https://hakiri.io)
* [HusckyCI](https://github.com/globocom/huskyci)
* [Infer](http://fbinfer.com/)
* [IronWASP](https://ironwasp.org/)
* [kube-bench](https://github.com/aquasecurity/kube-bench)
* [Lynis](https://cisofy.com/lynis/)
* [microscanner](https://github.com/aquasecurity/microscanner)
* [Node Security Platform](https://nodesecurity.io/)
* [npm-check](https://www.npmjs.com/package/npm-check)
* [npm-outdated](https://docs.npmjs.com/cli/outdated)
* [OSS Fuzz](https://github.com/google/oss-fuzz)
* [OWASP OWTF](https://www.owasp.org/index.php/OWASP_OWTF)
* [OWASP ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)
* [OWASP ZAP Node API](https://github.com/zaproxy/zap-api-nodejs)
* [Progpilot](https://github.com/designsecurity/progpilot)
* [PureSec (Serverless Security)](https://www.puresec.io/)
* [RetireJS](https://github.com/RetireJS/retire.js)
* [RIPS](http://rips-scanner.sourceforge.net/)
* [ShiftLeft Scan](https://slscan.io)
* [Snyk](https://snyk.io)
* [SourceClear](https://www.sourceclear.com)


## Alerting
Once you discover something important, response time is critical and essential to the Incident Response required to remediate a security defect.  These links include some of the projects that provide for Alerting and Notifications.

* [411](https://github.com/kiwiz/411)
* [Alerta](https://github.com/guardian/alerta)
* [Elastalert](https://github.com/yelp/elastalert)
* [MozDef](https://github.com/mozilla/MozDef)

## Threat Intelligence
There are many sources for Threat Intelligence in the world.  Some of these come from IP Intelligence and others from Malware repositories.  This category contains tools that are useful in capturing threat intelligence and collating it.

* [Alien Vault OTX](https://otx.alienvault.com/)
* [Critical Stack](https://intel.criticalstack.com)
* [IBM X-Force](https://exchange.xforce.ibmcloud.com)
* [IntelMQ Feeds](https://github.com/certtools/intelmq-feeds-documentation)
* [OpenTPX](https://www.opentpx.org)
* [Passive Total](https://www.passivetotal.org)
* [STIX, TAXII](https://oasis-open.github.io/cti-documentation/)
* [Threat Connect](https://threatconnect.com/)

## Attack Modeling
DevSecOps requires a common attack modeling capability that can be done at speed and scale.  Thankfully there are efforts underway to create these useful taxonomies that help us operationalize attack modeling and defenses.

* [CAPEC](https://capec.mitre.org)
* [IriusRisk](https://www.continuumsecurity.net/threat-modeling-tool/)
* [Larry Osterman's Threat Modeling](https://blogs.msdn.microsoft.com/larryosterman/2007/10/01/some-final-thoughts-on-threat-modeling/)
* [SDL Threat Modeling Tool](https://www.microsoft.com/en-us/sdl/adopt/threatmodeling.aspx)
* [SeaSponge](http://mozilla.github.io/seasponge/)
* [Threat Risk Modeling](https://www.owasp.org/index.php/Threat_Risk_Modeling)

## Secret Management
To support security as code, sensitive credentials and secrets need to be managed, security, maintained and rotated using automation.  The projects below provide DevOps teams with some good options for securing sensitive details used in building and deploying full stack software deployments.

* [BlackBox](https://github.com/StackExchange/blackbox)
* [Conjur](https://github.com/cyberark/conjur)
* [CredStash](https://github.com/fugue/credstash)
* [Git Secrets](https://github.com/awslabs/git-secrets)
* [Keybase](https://keybase.io)
* [Sops](https://github.com/mozilla/sops)
* [Transcrypt](https://github.com/elasticdog/transcrypt)
* [Vault](https://www.hashicorp.com/blog/vault.html)


## Red Team
These are tools that we find helpful during Red Team and War Game exercises.  The projects in this section help with reconnaissance, exploit development, and other activities common within the Kill Chain.

* [EyeWitness](https://github.com/ChrisTruncer/EyeWitness)
* [Hound](https://github.com/etsy/hound)


## Visualization
Making DevSecOps discoveries is already hard enough with all the APIs and Command Line tools.  This list provides tools to visualize your work either via flowcharts, graphs or maps.

* [Gephi](https://gephi.org)
* [yED](https://www.yworks.com/products/yed)
* [ShadowBuster](https://github.com/indeedops/ShadowBuster)
* [Wazuh](https://wazuh.com/)

## Sharing
A collection of tools to help with sharing knowledge and telling the story.

* [Gitbook](https://www.gitbook.com)
* [Confluence](https://www.atlassian.com/software/confluence)
* [ReadTheDocs](https://about.readthedocs.com/)
* [BookStack](https://www.bookstackapp.com/)
* [Speaker Deck](https://speakerdeck.com)


## ChatOps
One of the greatest changes you can make in your organization is boundaryless communication.  Setting up ChatOps can enable everyone to come together and solve problems.

* [Slack](https://slack.com)
* [RocketChat](https://www.rocket.chat/)
* [Gitter](https://gitter.im)
* [HipChat](https://hipchat.com)
* [MatterMost](https://mattermost.com/)
* [Riot](https://riot.im/)



## Resources

### Books

*Books focused on DevOps, DevSecOps and Site Reliability Engineering.*

- [Effective DevOps: Building a Culture of Collaboration, Affinity, and Tooling at Scale](http://shop.oreilly.com/product/0636920039846.do)
- [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.oreilly.com/library/view/continuous-delivery-reliable/9780321670250/)
- [Hands-On Security in DevOps](https://www.packtpub.com/networking-and-servers/hands-security-devops)
- [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/)
- [The Site Reliability Workbook](https://sre.google/workbook/table-of-contents/)
- [Building Secure & Reliable Systems](https://google.github.io/building-secure-and-reliable-systems/raw/toc.html)
- [Infrastructure as Code: Managing Servers in the Cloud](http://shop.oreilly.com/product/0636920039297.do)
- [The DevOps Handbook](https://www.oreilly.com/library/view/the-devops-handbook/9781457191381/)

### Conferences

- [DevOpsCon](https://devopscon.io/)
- [AWS re:Invent](https://reinvent.awsevents.com/)
- [DevSecOps](https://www.devseccon.com/)
- [ADDO](https://www.alldaydevops.com/)
- [DevOpsConnect](https://www.devopsconnect.com/)
- [@Scale](https://atscaleconference.com/)
- [devopsdays](https://devopsdays.org/)
- [DevOps Enterprise Summit](https://events.itrevolution.com/)

### DevOps Roadmap

Basic understanding and what you should know to become a *DevOps* Engineer, check the roadmap [here](https://roadmap.sh/devops).

## Contributing

Your contributions are always welcome! Please take a look at the [Contribution Guidelines](https://github.com/wmariuss/awesome-devops/blob/main/docs/contribution.md).
