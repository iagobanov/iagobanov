# Hey, I'm Iago 👋

Infrastructure engineer who ended up deep in observability, and stayed.

I started on the AWS side of things: ECS, then EKS, Terraform for all of it, and eventually GitOps with Flux and Argo. Years of running Kubernetes in production and being the person paged when it misbehaved. At some point I moved to the vendor side of observability, and my day job became looking at other people's production systems. Hundreds of them by now. You learn a lot about how systems fail when you watch forty different companies hit the same wall.

These days most of what I write is OpenTelemetry plumbing or AI agents that do parts of my old job: reading a codebase and pointing out missing instrumentation, splitting queries too big to run, drafting the weekly updates nobody enjoys writing.

A few things I believe after all this:

- Telemetry you can't query during an incident is just expensive storage.
- Most dashboards are write-only. The good ones answer a question someone actually asked.
- Sampling is not lying. Paying to store 100% of traces nobody reads might be.

## Public stuff

| Project | What it is |
|---|---|
| [observability-copilot](https://github.com/iagobanov/observability-copilot) | Scans a repo, reports observability gaps, suggests OpenTelemetry instrumentation. Web app or GitHub Action. |
| [tam-central-hub](https://github.com/iagobanov/tam-central-hub) | TAM-OS. One Claude agent per customer, pulling context from Slack, Jira and Notion to draft weekly briefs. |
| [cx-dataprime-batch](https://github.com/iagobanov/cx-dataprime-batch) | Splits oversized Coralogix DataPrime queries into time chunks, runs them in parallel, retries whatever hits the scan limit. |
| [cx-centralized-observability-gateway](https://github.com/iagobanov/cx-centralized-observability-gateway) | OpenTelemetry gateway for Kubernetes fleets. Tail sampling and routing in one place. |

## Stack

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000?style=flat-square&logo=opentelemetry&logoColor=f5a800)
![AWS](https://img.shields.io/badge/AWS-232f3e?style=flat-square&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white)
![Argo](https://img.shields.io/badge/Argo-ef7b4d?style=flat-square&logo=argo&logoColor=white)
![Flux](https://img.shields.io/badge/Flux-5468ff?style=flat-square&logo=flux&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-ffda18?style=flat-square&logo=opentofu&logoColor=black)
![Claude](https://img.shields.io/badge/Claude%20agents-d97757?style=flat-square&logo=anthropic&logoColor=white)

Most of my recent work lives in private repos. The public stuff above is representative.
