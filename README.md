# helm-chart for Sorbotics aplications

## For use

```bash
helm repo add sorbapp https://wjgb1010.github.io/charts/
helm upgrade my-tree-api sorbapp/tree-api --install
```

## For Build and upgrade
### Create new chart

Para crear un nuevo chart en el directorio helm-chart-sources/

```bash
helm create helm-chart-sources/nombre_repo
```
### Package all chart 

Comando para empaquetar todos los chart en el directorio helm-chart-sources

```bash
helm package helm-chart-sources/*
```

### Update index.yaml file

Comando para actualizar el archivo index.yaml

```bash
helm repo index . --url https://wjgb1010.github.io/charts/
```