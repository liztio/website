---
reviewers:
- sig-cluster-lifecycle
title: Certificate Management with kubeadm
content_template: templates/task
---

{{% capture overview %}}

This page explains various kubeadm-specific topics related to certificate management

{{% /capture %}}

{{% capture steps %}}

# Renewing certificates using the certificates API

`kubeadm alpha certs renew --use-api`

## See Also
* [Managing TLS in a Cluster](https://kubernetes.io/docs/tasks/tls/managing-tls-in-a-cluster/)

# Using Certificate Requests with Kubeadm

`kubeadm init phase certs apiserver --use-csr`

## See Also
* [Kubernetes Certificate](https://kubernetes.io/docs/setup/certificates/)

{{% /capture %}}
