## observability prometheus

### Render template locally
```shell
helm template test-observability ./prometheus \
  -f ./prometheus/dev-values.yaml \
  --output-dir rendered
```