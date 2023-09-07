A sample Helm umbrella chart to simplify deployment stack of utilities Anchore Engine, Prometheus, Grafana,
KEDA, ... <br>
For more details, kindly refer
to [My presentation - Topic: Anchore Engine](https://drive.google.com/file/d/1wP3ozJ6eFD6ucL2LtOjSpJuy4IaTdmZz/view?usp=sharing)

## System requires

1. Maven (Tested version 3.8.4)
2. Helm v3 (Tested version v3.8.2)
3. Kubernetes (Tested version v1.23.13 - Runtime: docker - Provisioned by Minikube v1.26.0)

## Build the umbrella chart

```shell
mvn clean install
```
Built chart is located under target/helm/repo/container-security-scanner-ecosystem-x.x.x.tgz
