# SysDig CRD ideas
  - CRD to define monitors/alerts
  - CRD to define security rule / falco
  - deploy sysdig
    - helm chart
    - operator
    - deploy falco
  - CRD to create dashboard

# TODO
  - Research sysdig
  - Research Falco
  - Read blog posts
    - Istio stuff?
    - Prometheus
    - Custom monitor annotations/definitions
      - Operator/monitor
  - Document Sysdig value props & competitive advantages/SWOT?
  - Compare with grafana & datadog
  - priv sidecar on deployment with annotation instead of daemon set
  - what are falco's value prop and competitive advantages?
  - Where is falco going?
  - where could it go?
  - [ ] turn this all into a checklist
  - [ ] Falco -f rules.yaml -f rules2.yaml -> kubectl create -f falco-rules-crd.yaml
  - [ ] Falco helm chart
  - [ ] Falco operator might be better for this than a crd, no CRD is better
  - [ ] Pros/Cons of CRD vs operator
  - [ ] Figure out how to reload falco or have falco sigup/load new rulesets