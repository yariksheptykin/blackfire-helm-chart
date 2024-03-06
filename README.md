# Blackfire.io helm chart

Unofficial Helm chart for [blackfire.io](https://blackfire.io)

To use this helm chart, you need to:
- clone this repository,
- copy values.yaml to custom-values.yaml file and customize chart values to your needs,
- and run the following command:

```bash
helm upgrade --install blackfire . --values custom-values.yaml
```

After installation run tests to check if everything is working correctly:

```bash
helm test blackfire
```

## Credits

This helm chart is forked from https://github.com/ribeiroplinio/blackfire-helm-chart
