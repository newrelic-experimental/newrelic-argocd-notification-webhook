## Getting Started

In order for the application to report to New Relic, you'll need to define a secret containing your New Relic License Key in the `notification-demo` namespace (or wherever you choose to deploy the app).
```
kubectl create secret generic newrelic-license-key -n notification-demo --from-literal=newrelic-license-key=<NEW RELIC LICENSE KEY>
```