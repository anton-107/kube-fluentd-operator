# CHANGELOG

## [1.3.0](https://github.com/vmware/kube-fluentd-operator/releases/tag/v1.3.0)

* Fluentd: `fluent-plugin-detect-exceptions` to base image

* Fluentd: add `fluent-plugin-out-http-ext` to base image

* Core: add plugin `truncating_remote_syslog` which truncates the tag to 32 bytes as per RFC 5424

* Core: support transparent multi-line stacktrace collapsing

## [1.2.0](https://github.com/vmware/kube-fluentd-operator/releases/tag/v1.2.0)

* Core: Share log streams between namespaces

* Helm: Mount secrets/configmaps (tls mostly) ala elasticsearch (@sneko)

* Fluentd: Update base-image to fluentd-1.1.3-debian

* Fluentd: Include Splunk plugin into base-image (@mhulscher)

* Fix(Helm): properly set the `resources` field of the reloader container. Setting them had no effect until now (@sneko)

## [1.1.0](https://github.com/vmware/kube-fluentd-operator/releases/tag/v1.1.0)

* Core: ingest log files from a container filesystem

* Core: limit impact of log-router to a set of namespaces using `--namespaces`

* Helm: add new property `kubeletRoot`

* Helm: add new property `namespaces[]`:

## [1.0.1](https://github.com/vmware/kube-fluentd-operator/releases/tag/v1.0.1)

* Fluentd: install plugin `fluent-plugin-concat` in Fluentd

* Core: support for default configmap name using `--default-configmap`

## [1.0.0](https://github.com/vmware/kube-fluentd-operator/releases/tag/v1.0.0)

* Initial version
