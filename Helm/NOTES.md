# Helm

## Verify Helm Charts (make sure chart works as intended)

- Lint

```sh
helm lint <chart_directory>
```

- Template

```sh
helm template <chart_directory>
```

- Dry Run

```sh
helm install <chart_directory> --dry-run
```
