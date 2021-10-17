# resources

## Installation

```
$ helm repo add hatappi https://hatappi.github.io/helm-charts
$ helm install --name resources hatappi/resources
```

## Usage

```
resources:
  - apiVersion: v1
    kind: Namespace
    metadata:
      name: foo
  - apiVersion: v1
    kind: Namespace
    metadata:
      name: bar
```
