Helm chart repo for our public Helm charts, and helper charts to apply configuration.

Setup:
------

* configure repo for Github pages, public endpoint is https://caas-team.github.io/helm-charts/

Usage:
------

* put the chart packages into the repo
* (re-)create the repo index page

```
helm repo index --url https://caas-team.github.io/helm-charts/ .
```

Content:
--------

* caas-demoapp
* [rancher-metrics/](charts/rancher-metrics) -
  [(src)](https://github.com/caas-team/helm-charts/tree/main/charts/rancher-metrics)
* py-kube-downscaler -
  [(src)](https://github.com/caas-team/py-kube-downscaler)


Credits:
--------

inspired by [@mattiaperi](https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417)

Frank Kloeker <f.kloeker@telekom.de>

Life is for sharing. If you have an issue with the code or want to improve it,
feel free to open an issue or an pull request.

