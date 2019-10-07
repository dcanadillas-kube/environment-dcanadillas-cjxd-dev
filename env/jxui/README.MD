# jxui

|App Metadata||
|---|---|
| **Version** | 0.0.821 |
| **Description** | UI for the CloudBees Jxui V3 product |
| **Chart Repository** | https://charts.cloudbees.com/cjxd/cloudbees |

## App README.MD

# UI for the CloudBees Jxui v3 product

This helm chart includes both the UI and jxui API server.

## Install

Install via Helm. Ensure you have the Jenkins X Helm repo added:

### Prerequisite

```
helm init
helm repo add chartmuseum http://chartmuseum.jenkins-x.io
```

or to update your helm repos

```
helm repo update
```

