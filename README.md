# Application modernization

## Mindmap

### Syntax
[PlantUML's mindmap syntax](https://plantuml.com/fr-dark/mindmap-diagram)

### Generate picture

CLI [doc](https://plantuml.com/command-line)

Install
```shell
curl https://github.com/plantuml/plantuml/releases/download/v1.2025.3/plantuml-1.2025.3.jar --output
export PATH=$PATH;/
```

Generate png
```shell
java -jar plantuml.jar mindmap.puml -tpng
```