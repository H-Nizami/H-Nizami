<h1 align="center">Muhammad Haseeb</h1>

<p align="center">
  <b>AI agents from demo to production on Kubernetes and AWS</b><br>
  AI / Platform Engineer · CKA · CKAD · Remote from Pakistan
</p>

<p align="center">
  <a href="https://linkedin.com/in/muhammad-haseeb-613670212"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <img alt="CKA" src="https://img.shields.io/badge/CKA-certified-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
  <img alt="CKAD" src="https://img.shields.io/badge/CKAD-certified-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
</p>

---

I build LLM agent systems and the platform they run on. For more than two years I have shipped
multi-agent pipelines to production at a Silicon Valley Kubernetes reliability startup. The work
covers LangGraph and Temporal workflows, evaluation harnesses, human-in-the-loop review, and the
Go services that feed them. Before that I did applied deep learning research at NUST.

**Focus areas**

- Agent reliability: evals in CI, guardrails, tracing, budget caps and durable execution.
- Agent and LLM workloads on Kubernetes and EKS: Helm, SLOs and tested failure recovery.
- Infrastructure as code with Terraform and OpenTofu, plus policy and security scanning in pull requests.

## Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [**agent-hardening-kit**](https://github.com/H-Nizami/agent-hardening-kit) | Takes a LangGraph agent from demo to production: tenant-scoped retrieval, guardrails, durable Temporal execution with human approval, sanitized OpenTelemetry, SLO burn-rate alerts, and a Helm chart that passed 3/3 worker pod-kill tests on kind. | Python · LangGraph · Temporal · Helm · OTel |
| [**claude-infra-review**](https://github.com/H-Nizami/claude-infra-review) | Reviews Terraform and Kubernetes pull requests. Deterministic scanners run first, then a read-only LLM reviewer with a spending cap. On a seeded benchmark, scanners alone caught 7/14 misconfigurations; with the reviewer, 14/14. | GitHub Actions · Claude Code · tflint · checkov · trivy |
| [**eks-landing-zone**](https://github.com/H-Nizami/eks-landing-zone) | EKS landing zone for agent and LLM workloads: private control plane, Karpenter, External Secrets and Kyverno. 41/41 mocked plan tests pass on both Terraform 1.17 and OpenTofu 1.13; not yet deployed live. | Terraform · OpenTofu · AWS EKS |

## Tech stack

<p>
  <img alt="Tech stack" src="https://skillicons.dev/icons?i=py,go,ts,bash,kubernetes,docker,aws,terraform,githubactions,postgres,prometheus,grafana,linux&perline=13">
</p>

**AI and agents:** LangGraph, Pydantic AI, MCP, Temporal, evaluation harnesses, human-in-the-loop review, token, latency and cost tuning<br>
**Platform:** Kubernetes, Helm, EKS, ECS, Lambda, SQS/SNS, DynamoDB, CDK, OpenTelemetry, Prometheus<br>
**Languages:** Python, Go, TypeScript, Bash, SQL

## Experience

**Software Engineer I and II, AI agent infrastructure** · Silicon Valley Kubernetes reliability startup · 2024 to present · Remote

- Built a LangGraph multi-agent pipeline. It reached 94% end-to-end accuracy on 800 human-labeled records.
- Productionized a Temporal-backed multi-agent system on ECS workers. Accuracy rose from 58% to 92% over the earlier single-agent workflow.
- Wrote the Go ingestion layer that feeds the agents. It covers more than 155 projects and 10,500 sources.

**Research Assistant** · OPTIMAL Machine Learning Lab, SEECS–NUST · 2023 to 2024

- Built computer-vision pipelines for remote photoplethysmography: heart rate, blood pressure and SpO₂.

## Publications

- *Faithfulness Is Not Free: Auditing Offline KV-Cache Quantization in Retrieval-Augmented Generation.* Grounding Language Models Workshop at EMNLP 2026. [arXiv:2608.30996](https://arxiv.org/abs/2608.30996)
- *Real-Time Deep Learning for Lung Disease Classification: A Step Forward.* IEEE FIT 2024.

## Education and certifications

- B.E. Electrical Engineering, National University of Sciences and Technology (NUST), 2020 to 2024
- Certified Kubernetes Administrator (CKA) and Certified Kubernetes Application Developer (CKAD), 2024
- Deep Learning Specialization (DeepLearning.AI) · Machine Learning Specialization (Stanford)
