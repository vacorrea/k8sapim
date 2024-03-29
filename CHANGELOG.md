# Changelog
All notable changes to this project 2.6.x per each release will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [v2.6.0.6] - 2019-06-20

### Added

- Added resources for deployment of kubernetes manifests and helm charts on AKS using Azurefiles as persistent storage instead of NFS.

## [v2.6.0.5] - 2019-06-13

### Added
- Kubernetes resources for WSO2 API Management deployment pattern 3

### Changed
- Fix an issue with creating WSO2 Subscription Kubernetes Secret in WSO2 API Management Helm resources
(see [issue](https://github.com/wso2/kubernetes-apim/issues/190))

## [v2.6.0.4] - 2019-05-27

### Changed
- Fix an issue which comments out Kubernetes client commands in the deployment management script of WSO2 API Manager deployment pattern 2

## [v2.6.0.3] - 2019-05-25

### Added
- Kubernetes resources for a simplified, WSO2 API Manager with Analytics deployment
- Define Kubernetes Deployment resource requests and limits
- Integrate support in Kubernetes resources for users with and without WSO2 subscriptions
- Integrate support in Helm resources for users with and without WSO2 subscriptions

### Changed
- Upgrade API version of Kubernetes Deployment resources
- Improvements to Kubernetes deployment management scripts

## [v2.6.0.2] - 2019-04-26

### Changed
- Fix erroneous Kubernetes Persistent Volume mount path in Helm resources for WSO2 API Management deployment pattern 1

## [v2.6.0.1] - 2018-10-10

### Added
- Kubernetes resources for WSO2 API Management deployment patterns 1 and 2
- Helm resources for WSO2 API Management deployment patterns 1 and 2

[v2.6.0.6]: https://github.com/wso2/kubernetes-apim/compare/v2.6.0.5...v2.6.0.6
