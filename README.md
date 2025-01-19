# 🏠 My Homelab  

This repository documents my homelab setup, configuration, and experiments.  

## Why Homelab?  

As a platform engineer by day, I deal with infrastructure, automation, and Kubernetes on a professional level. My homelab serves as a sandbox where I can tinker with new technologies, test out self-hosted applications, and refine my skills. Running workloads at home also gives me hands-on experience with designing scalable, secure, and maintainable systems—something I believe is invaluable.  

## Current Setup  

I'm currently running my homelab on **Proxmox**, leveraging **LXC containers** to keep things lightweight and efficient. While virtual machines offer full isolation, LXC provides a great balance between performance and flexibility.  

## The Plan: Kubernetes on LXC  

The next big step in my homelab is migrating everything to a **Kubernetes cluster running on LXC containers**. Instead of using Talos or K3s, I want to experiment with setting up a cluster directly on Proxmox LXC nodes. This approach comes with its own challenges (e.g., networking, persistent storage), but it's a great way to learn more about Kubernetes at a deeper level.  

## Homelab Goals  

- **Kubernetes Cluster:** Self-hosted, running on Proxmox LXC  
- **GitOps-Driven:** Everything managed declaratively via Git  
- **Storage & Backups:** Centralized storage with automated backups  
- **Self-Hosting Applications:** Running useful apps while learning best practices  
- **Security & Access Control:** Proper RBAC, secrets management, and hardening  

## Hardware  

Currently running a mix of Proxmox LXC containers and some bare-metal nodes. The idea is to maximize resource efficiency while keeping things modular.  

## Future Experiments  

- Exploring **FluxCD/ArgoCD** for GitOps  
- Setting up **Ingress and Load Balancing**  
- Implementing **Centralized Logging & Monitoring**  
- Integrating **Tailscale/VPN for Secure Access**  
- Playing with **Service Mesh & Advanced Networking**  

## Repo Structure  

This repo will evolve as I move towards a full Kubernetes-based setup. Expect to see Terraform, Ansible, Helm charts, and YAML manifests soon!  

Stay tuned for updates. 🚀  
