# Session 14: Kubernetes Troubleshooting & Debugging

## Overview
This directory contains the completed assignment submissions, diagnostic steps, terminal logs, and verified screenshots for **Session 14: Kubernetes Troubleshooting & Debugging**.

---

## 1. `kubectl get` — Pods & Wide Inspection
Inspecting cluster state, pod readiness, restart counts, and IP address / node allocations using `kubectl get pods -o wide`.

![kubectl get demonstration](./screenshots/image-1.png)

![kubectl get pods wide output](./screenshots/image-2.png)

---

## 2. `kubectl describe` & `kubectl logs`
Deep-dive inspection of pod metadata, conditions, scheduling events, stdout logs, and stream tailing.

![kubectl describe & logs demonstration](./screenshots/image-3.png)

---

## 3. `kubectl exec` & Kubernetes Cluster Events
Container shell access, remote execution, and monitoring cluster-wide event streams via `kubectl get events`.

![kubectl exec & events demonstration](./screenshots/image-4.png)

---

## 4. Debugging `CrashLoopBackOff`
Diagnosing application exit codes, crash loops, and verifying fixed pod startup logs.

![CrashLoopBackOff debugging](./screenshots/image-5.png)

---

## 5. Resolving `ImagePullBackOff` & `ErrImagePull`
Identifying invalid image tags/registries and inspecting image pull failure events.

![ImagePullBackOff debugging](./screenshots/image-6.png)

---

## 6. Troubleshooting `Pending` Pods & Node Selectors
Investigating unschedulable pods caused by unmatched node selectors or affinity rules.

![Pending Pods debugging](./screenshots/image-7.png)

---

## 7. Service Endpoints, CoreDNS & HTTP Connectivity
Validating Service endpoint mappings, CoreDNS internal resolution via `nslookup`, and HTTP `wget` verification.

![Service & DNS troubleshooting](./screenshots/image-8.png)
