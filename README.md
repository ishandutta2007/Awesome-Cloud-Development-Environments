# Awesome-Cloud-Development-Environments

## Top Cloud Development Environments Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Ephemeral Workspaces, Dev Container Standards & Self-Hosted IDE Infrastructure*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Development Environments (CDEs)**. These tools enable developers to spin up fully configured development environments in seconds—from any machine, any operating system, without the "works on my machine" problem.



**Examples** include GitHub Codespaces, Gitpod, AWS Cloud9, Google Cloud Workstations, Replit Teams, Coder, DevZero, Daytona, Codeanywhere, and StackBlitz (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, Dev Container standards, and open IDE infrastructure—ideal for platform engineers, DevOps teams, and organizations seeking transparent, vendor-independent development environments.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[GitHub Codespaces](https://github.com/features/codespaces)**  

  **Cloud-hosted dev environments defined as code via Dev Containers** . **Instantly launches from any GitHub repo** with terminal, extensions, and port forwarding . **Deep GitHub integration**—prebuilds, secrets, and VS Code in the browser . **The most integrated with GitHub ecosystem** .



- **[AWS Cloud9](https://aws.amazon.com/cloud9/)**  

  **Cloud-based IDE with deep AWS integration** . Features **built-in terminal**, **debugger**, and **AWS service integration** . **Best for AWS-centric development workflows** .



- **[Google Cloud Workstations](https://cloud.google.com/workstations)**  

  **Managed development environments on Google Cloud** . Features **container-based workspaces**, **VPC-SC integration**, and **enterprise security controls** . **Best for GCP-committed organizations** .



- **[Replit Teams](https://replit.com/)**  

  **Browser-based IDE with instant execution, hosting, and AI assistance** . **The most accessible zero-setup option** —starts coding in seconds without any local configuration .



- **[Coder Cloud](https://coder.com/)**  

  **Managed version of the open-source Coder platform** . Features **Terraform-defined workspaces**, **enterprise SSO**, and **multi-cloud support** .



- **[DevZero](https://www.devzero.io/)**  

  **Cloud development environments with instant environment cloning** . Features **environment snapshots**, **dependency caching**, and **microservice support** .



- **[Daytona Cloud](https://www.daytona.io/)**  

  **Managed version of the open-source Daytona platform** . Features **single-command environment creation**, **prebuilt configurations**, and **enterprise security** .



- **[Codeanywhere](https://codeanywhere.com/)**  

  **Cloud IDE with prebuilt environments** for multiple languages . Features **collaboration**, **SSH access**, and **DevOps tooling** .



- **[StackBlitz Enterprise](https://stackblitz.com/)**  

  **Browser-based IDE for web development with instant preview** . **Runs Node.js in-browser via WebContainers** —no server required . **The fastest path to running full-stack JavaScript** in a browser.



## Open-Source GitHub Projects



- **[Gitpod](https://github.com/gitpod-io/gitpod)**  

  **Open-source developer platform for automated workspaces** (AGPL-3.0) . **The most widely adopted open-source cloud development environment** —**13,000+ GitHub stars** . **Ephemeral dev environments** defined in `.gitpod.yml` —each workspace runs in a container with prebuilt dependencies . **Features**: **prebuilds** (dependencies installed before you open the workspace), **browser-based VS Code**, **port forwarding**, **collaboration mode**, and **self-hosted deployment** via Kubernetes . **The reference implementation for automated cloud workspaces** .



- **[Coder](https://github.com/coder/coder)**  

  **Provision remote development environments via Terraform** (AGPL-3.0) . **10,000+ GitHub stars** . **The most infrastructure-flexible CDE platform** —**workspaces are defined as Terraform resources**, enabling provisioning on any cloud, Kubernetes cluster, or bare metal . **Features**: **Terraform-based workspace definitions**, **enterprise SSO**, **RBAC**, **audit logging**, **workspace templates**, and **support for any IDE** (VS Code, JetBrains, terminal) . **The best choice for organizations with existing Terraform infrastructure** who want full control over where workspaces run .



- **[Daytona](https://github.com/daytonaio/daytona)**  

  **The Open Source Dev Environment Manager** (Apache-2.0) . **The fastest path from zero to code** —**single command transforms any VM into a secure, shareable, standardized development environment** . **Features**: **prebuilds**, **Dev Container support**, **multi-IDE support** (VS Code, JetBrains, terminal), **Git provider integration** (GitHub, GitLab, Bitbucket), **resource limits**, and **self-hosted or cloud deployment** . **Daytona 2025 rewrite** moved to a server-first architecture with Python SDK . **The best choice for teams that want a simple, fast, self-hosted CDE** without Kubernetes complexity .



- **[OpenVSCode Server](https://github.com/gitpod-io/openvscode-server)**  

  **Run VS Code on a remote server accessible via browser** (MIT) . **The foundation for most browser-based VS Code experiences** —Gitpod maintains it as the upstream VS Code with minimal modifications . **The reference implementation for browser-based VS Code** .



- **[code-server](https://github.com/coder/code-server)**  

  **Run VS Code on a remote server, accessible through the browser** (MIT) . **60,000+ GitHub stars** . **The most widely deployed open-source browser IDE** —supports any machine with a consistent dev environment . **The best choice for simple browser-based VS Code access** .



- **[Eclipse Theia](https://github.com/eclipse-theia/theia)**  

  **Open-source cloud & desktop IDE** (EPL-2.0) . **Full VS Code extension compatibility**, **vendor-neutral**, and **customizable** . **Used by Google Cloud Shell, Arduino IDE 2.x, and others** . **The best choice for building custom cloud IDEs** —Theia is a framework, not just an application .



- **[DevPod](https://github.com/loft-sh/devpod)**  

  **Codespaces but open-source, client-only and unopinionated** (MPL-2.0) . **5,853+ GitHub stars** . **Works with any IDE and lets you use any cloud, Kubernetes, or localhost Docker** . **Features**: **Dev Container support**, **provider system** (AWS, GCP, Azure, Kubernetes, Docker, SSH), **client-only architecture** (no server to manage), and **IDE integration** (VS Code, JetBrains, terminal) . **The most flexible open-source CDE** —no vendor lock-in, works with your existing infrastructure .



- **[Devbox](https://github.com/jetify-com/devbox)**  

  **Instant, easy, and predictable development environments** (Apache-2.0) . **Nix-powered shell environments** —define your dev environment in JSON, get reproducible shells . **The most reproducible open-source dev environment tool** —no containers required .



- **[Nix](https://github.com/NixOS/nix)**  

  **The purely functional package manager** (LGPL-2.1) . **The foundation for reproducible development environments** —used by Devbox, Flox, and others . **The most rigorous approach to environment reproducibility** .



- **[Flox](https://github.com/flox/flox)**  

  **Developer environments you can take with you** (GPL-2.0) . **Nix-powered environments with a friendly CLI** —makes Nix accessible to teams without Nix expertise .



- **[Dev Containers Specification](https://github.com/devcontainers/spec)**  

  **The development container specification** (MIT) . **The open standard for defining development environments** —used by VS Code, GitHub Codespaces, DevPod, Daytona, and others . **The foundation for portable development environments** .



### Additional Strong Open-Source Options



- **[Nixpacks](https://github.com/railwayapp/nixpacks)** — App source + Nix packages + Docker = OCI image (MIT) . **The fastest path to containerized dev environments** .

- **[Devcontainer CLI](https://github.com/devcontainers/cli)** — Command-line interface for working with Dev Containers (MIT) . **The standard CLI for Dev Container workflows** .

- **[Devcontainer Templates](https://github.com/devcontainers/templates)** — Templates for Dev Containers (MIT) . **Pre-built configurations for common stacks** .

- **[devcontainer-features](https://github.com/devcontainers/features)** — Dev Container Features (MIT) . **Composable add-ons for Dev Containers** .

- **[Tilt](https://github.com/tilt-dev/tilt)** — Microservice development environment (Apache-2.0) . **Live-updating dev environments for Kubernetes** .

- **[Garden](https://github.com/garden-io/garden)** — DevOps automation for Kubernetes and serverless (MPL-2.0) . **Ephemeral preview environments** .

- **[Skaffold](https://github.com/GoogleContainerTools/skaffold)** — Continuous development for Kubernetes (Apache-2.0) . **The standard for local-to-cluster dev loops** .

- Community **n8n** workflows for CDE provisioning and workspace lifecycle automation.



**Frameworks for building custom systems**: Combine **Gitpod** for automated workspace orchestration with **Coder** for Terraform-defined infrastructure, **code-server** or **OpenVSCode Server** for browser-based IDE access, **DevPod** for client-only flexibility, and **Dev Containers Specification** for portable environment definitions—creating a fully self-hosted, enterprise-grade cloud development environment platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud development environments handling source code and credentials must follow security best practices and comply with data protection regulations.

- **Open-source CDEs are mature and production-ready.** Gitpod provides automated workspaces with prebuilds . Coder enables Terraform-defined infrastructure . code-server (60K+ stars) is the most widely deployed browser IDE . **These are genuine alternatives to GitHub Codespaces.**

- **The Dev Container specification is the interoperability layer.** Used by VS Code, GitHub Codespaces, DevPod, Daytona, and others —**Dev Containers are the closest thing to a portable dev environment standard** . Choose tools that support the specification to avoid lock-in.

- **Infrastructure control is the key differentiator.** Coder for Terraform-defined workspaces on any infrastructure . DevPod for client-only, no-server architecture . Gitpod for Kubernetes-native orchestration . **Choose based on where you want workspaces to run.**

- **Startup time matters more than feature lists.** Prebuilds, dependency caching, and snapshot restore are the difference between a 30-second and a 30-minute environment setup . **This directly impacts developer productivity and satisfaction.**

- Self-hosted open-source solutions require proper Kubernetes/infrastructure management, security hardening, and ongoing maintenance. **Development environments are access points to your code**—compromise here undermines everything.



---



**Made for platform engineers, DevOps teams, and organizations building transparent cloud development environment solutions.**  

Let's make Cloud Development Environments more open, data-driven, and reproducible.
