# OpenFaaS ERTIS templates

Additional templates for OpenFaaS

- `python3-http-tensor`: Based on [`python3-http-debian`] template with
  `tensorflow/tensorflow` as the base image
- `python3-http-tensor-arm`: Based on [`python3-http-debian`] template with
  `armswdev/tensorflow-arm-neoverse` as the base image

[`python3-http-debian`]:
  https://github.com/openfaas/python-flask-template/tree/d6080b6f836d1918cbac6fb27602a2fd2a2208bb/template/python3-http-debian

## Downloading the templates

```sh
faas-cli template pull https://github.com/ertis-research/openfaas-template
```

## Usage

Follow each template description for usage instructions
