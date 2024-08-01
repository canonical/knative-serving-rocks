# Knative Serving Rocks

[![Build & Scan](https://github.com/canonical/knative-serving-rocks/actions/workflows/on_pull_request.yaml/badge.svg)](https://github.comcanonical/knative-serving-rocks/actions/workflows/on_pull_request.yaml)
[![Publish](https://github.com/canonical/knative-serving-rocks/actions/workflows/on_push.yaml/badge.svg)](https://github.comcanonical/knative-serving-rocks/actions/workflows/on_push.yaml)

[Rocks](https://canonical-rockcraft.readthedocs-hosted.com/en/latest/) for [Knative Serving](https://knative.dev/docs/serving/).
This repository holds all the necessary files and CI to build and publish Knative Serving rocks.

Automations takes care of:
* Running unit tests for rocks
* Building rocks on merge
* Publishing rocks on merge, to docker.io/charmedkubeflow repository
