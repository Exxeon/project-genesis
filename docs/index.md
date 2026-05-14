# Welcome to Genesis

*The KRM-Native Infrastructure Vending Platform.*

---

## 🚀 Mission Statement

To revolutionize enterprise infrastructure delivery by eliminating legacy pipelines and empowering teams with a 100% Kubernetes-native, GitOps-driven vending machine. Genesis transforms the complex provisioning of mission-critical, multi-cloud environments into a seamless, self-sustaining, and zero-Terraform experience.

---

## 📖 Product Overview

Genesis is a next-generation platform designed for IT service providers to deliver production-grade, enterprise Kubernetes environments across major hyper-scalers (AWS, Azure, GCP). 

By leveraging **Crossplane** for infrastructure provisioning and a centralized bootstrapping UI, Genesis drastically lowers the barrier to entry for onboarding new customers. Once the foundational infrastructure is live, Genesis performs a seamless "GitOps Handoff," granting the customer complete, autonomous control over their environment.

### ⚡ The Core Pillars

*   **Zero-Terraform Footprint**
    We speak one language: Kubernetes. From the underlying cloud networking to the core clusters, every resource is provisioned using the Kubernetes Resource Model (KRM). 
*   **The GitOps Handoff**
    Genesis is a vending machine, not a permanent control plane. Once the environment is bootstrapped, the customer's cluster connects to their own GitOps repository (Argo CD or Flux) and takes full autonomous control of its state.
*   **Day-2 Ready Foundation**
    Clusters do not just spin up bare. They are vended fully loaded with enterprise-grade tooling, including Cilium CNI, External DNS, and essential cloud-provider add-ons.
*   **Frictionless Onboarding**
    A clean, guided centralized UI replaces complex configuration files, allowing administrators to rapidly authenticate via OIDC and spin up multi-account architectures with ease.

---

## 🗺️ Next Steps

*   [Explore the Architecture](architecture.md) to understand the bootstrapping workflow and post-provisioning telemetry.
*   [Read the User Stories](user-stories.md) to see how Genesis solves problems for both customers and platform administrators.
*   [Check the Architecture Decision Records (ADRs)](adr/index.md) for deeper technical context on our tooling choices.