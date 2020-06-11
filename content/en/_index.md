---
title: KubeSphere | Enterprise container platform, built on Kubernetes
description: KubeSphere is an open source container platform based on Kubernetes for enterprise app development and deployment, suppors installing anywhere from on-premise datacenter to any cloud to edge.


css: scss/index.scss

section1:
  title: KubeSphere Container Platform
  topic: The Kubernetes platform tailored for hybrid multicloud
  content: KubeSphere is a distributed operating system managing cloud native applications with Kubernetes as its kernel, and provides plug-and-play architecture for the seamless integration of third-party applications to boost its ecosystem.
  btnContent1: Install on Kubernetes
  downloadLink1: "https://kubesphere.io/docs/installation/install-on-k8s/"
  btnContent2: Install on Linux
  downloadLink2: "https://kubesphere.io/docs/installation/all-in-one/"

section2:
  title: One Platform for Full Stack Solutions
  content: KubeSphere is also a multi-tenant enterprise-grade container platform with full-stack automated IT operation and streamlined DevOps workflows. It provides developer-friendly wizard web UI, helping enterprises to build out a more robust and feature-rich platform, which includes the most common functionalities needed for enterprise Kubernetes strategies.
  children:
    - name: Open Source
      icon: /images/home/open-source.svg
      content: A CNCF-certified Kubernetes platform, 100% open source, built and improved by the community.

    - name: Easy to Run
      icon: /images/home/easy-to-run.svg
      content: Can be deployed on an existing Kubernetes cluster or Linux machines, supports online and air-gapped installation.

    - name: Rich Features
      icon: /images/home/feature-rich.svg
      content: Deliver DevOps, service mesh, observability, application management, multi-tenancy, storage and networking management in a unified platform.

    - name: Modular & Pluggable
      icon: /images/home/modular-pluggable.svg
      content: The functionalities are modularized and loosely coupled with the platform. Choose the modules according to your business needs.



section3:
  title: Benefits to Different Teams
  content: Multi-tenancy enables different teams to securely deploy and maintain containerized applications from the cloud to the edge. It allows developers to deploy code with several clicks on the friendly console, and brings integrated observability and powerful DevOps strategies for the Ops team. It also helps the Infra team to install and maintain Kubernetes cluster with efficient, flexible network solutions which avoids locking teams into a single-vendor ecosystem.
  children:
    - name: Infra Team
      content: Automated installation, scaling, and upgrades from cloud to data center
      icon: /images/home/7.svg
      children:
        - content: Improve your environment utilization and reduce internal infrastructure costs
        - content: Provide security enhancements, and support multiple storage and network solutions
        - content: Deliver a trustworthy and certified Kubernetes platform and distribution
        - content: Support multi-cloud and multi-cluster Kubernetes management, avoiding vendor lock-in (coming soon)

    - name: Developers
      content: Liberate developers from complicated YAML, enabling them focus on business
      icon: /images/home/74.png
      children:
        - content: Create smooth user experience and reduce the learning curve of the cloud native stack
        - content: Provide toolkits and deployment automation tailored to any application environment
        - content: Offer out-of-box toolkits for building reproducible images from source code, improving development efficiency
        - content: Support application lifecycle management, accelerating time to market

    - name: Ops Team
      content: Build a one-stop enterprise-grade DevOps framework
      icon: /images/home/71.svg
      children:
        - content: Provide centralized log collection, monitoring, alerting, events and audit logs from infrastructure to applications
        - content: Streamlined process of continuous deployment, test, release, upgrade and scaling
        - content: Better tracking, routing and optimized communications within Kubernetes for cloud native apps
        - content: Easy-to-use web terminal and graphical panel, satisfying the needs of different users

    - name: User
      content: Running and using Apps on Kubernetes has never been so easy
      icon: /images/home/80.svg
      children:
        - content: Deploy and upgrade Apps with one click to transparent underlying infrastructure
        - content: Provide on-demand container resources and HPA, hardening the reliabity and flexibility of your applications
        - content: Import any Helm repository in seconds to visually deploy and upgrade applications
        - content: Support operation in application store, including metering and billing for applications (coming soon)

section4:
  title: Key Features
  content: If you are seeking an open source project that rivals a commercial product, KubeSphere is your choice. <br> <br>The Roadmap lists the planned features and we welcome everyone to raise a proposal to contribute your ideas.
  children:
    - name: Provisioning Kubernetes
      icon: /images/home/provisioning-kubernetes.svg
      content: Deploy Kubernetes on any infrastructure out of box, including online and air-gapped installation, and support adding GPU nodes

    - name: K8s Resource Management
      icon: /images/home/k-8-s-resource-management.svg
      content: Provide a web console for creating and managing Kubernetes resources with powerful observability

    - name: Multi-tenant Management
      icon: /images/home/multi-tenant-management.svg
      content: Provide unified authentication with fine-grained roles and three-tier authorization system, and support AD/LDAP authentication

  features:
    - name: Application Store
      icon: /images/home/store.svg
      content: Provide an application store for Helm-based applications, and offer application lifecycle management
      link: "https://kubesphere.io/docs/installation/install-openpitrix/"
      color: grape

    - name: Service Mesh (Istio-based)
      icon: /images/home/service.svg
      content: Provide fine-grained traffic management, observability and tracing, and offer visualization for traffic topology
      link: "../service-mesh"
      color: red

    - name: Rich Observability
      icon: /images/home/rich.svg
      content: Multi-dimensional monitoring metrics, multi-tenant log query and collection, and alerting and notification support
      link: "../observability"
      color: green

    - name: DevOps System
      icon: /images/home/dev-ops.svg
      content: Out-of-box CI/CD based on Jenkins, and automated workflow tools including S2I & B2I
      link: "https://kubesphere.io/docs/installation/install-devops/"
      color: orange

    - name: Multiple Storage Solutions
      icon: /images/home/multiple.svg
      content: Support GlusterFS, CephRBD, NFS, LocalPV solutions, and provide CSI plugins to consume storage from multiple cloud providers
      link: "https://kubesphere.io/docs/introduction/features/#multiple-storage-solutions-support"
      color: grape

    - name: Multiple Network Solutions
      icon: /images/home/network.svg
      content: Support Calico and Flannel, and provide load balancer plug-in Porter for Kubernetes installed on physical machines
      link: "https://kubesphere.io/docs/introduction/features/#multiple-network-solutions-support"
      color: green

    - name: Multi-cluster Management
      icon: /images/home/management.svg
      content: Distribute applications across multiple clusters and cloud providers, and provide disaster recovery solutions and cross-cluster discovery
      check: true
      link: ""
      color: orange

section5:
  title: KubeSphere with its Cloud Native Architecture
  frontEnd:
    title: Front End
    project: KubeSphere Console
    children:
      - icon: /images/home/mobx.jpg
      - icon: /images/home/koa.jpg
      - icon: /images/home/react.png

  backEnd:
    title: Back End (REST API)
    project: KubeSphere System
    group:
      - name: API Server
      - name: API Gateway
      - name: Controller Manager
      - name: Account Service


section6:
  title: End User Community
  content: Tons of enterprises and organizations are using KubeSphere Container Platform for research, production and their commercial products.</br> The <a class='inner-a' target='_blank' href='../case'>Case Studies</a> list more detailed user cases and their cloud native transformation stories.
  children:
    - icon: /images/home/section6-anchnet.jpg
    - icon: /images/home/section6-aqara.jpg
    - icon: /images/home/section6-benlai.jpg
    - icon: /images/home/section6-cmft.jpg
    - icon: /images/home/section6-extreme-vision.jpg
    - icon: /images/home/section6-huaxia-bank.jpg
    - icon: /images/home/section6-maxnerva.jpg
    - icon: /images/home/section6-inaccel.jpg
    - icon: /images/home/section6-powersmart.jpg
    - icon: /images/home/section6-sina.jpg
    - icon: /images/home/section6-softtek.jpg
    - icon: /images/home/section6-vng.jpg
    - icon: /images/home/section6-webank.jpg
    - icon: /images/home/section6-wisdom-world.jpg
    - icon: /images/home/section6-yiliu.jpg

  btnContent: Case Studies
  btnLink: case
  link: mailto:kubesphere@gmail.com
  linkContent: Want to join user community and put your logo up there? Send an email to kubesphere@gmail.com
  joinTitle: Join the Revolution, Partner with KubeSphere
  joinContent: We look forward to your joining KubeSphere partner program to improve both ecosystems and grow your business.
  joinLink: partner
  image: /images/home/certification.jpg
---
