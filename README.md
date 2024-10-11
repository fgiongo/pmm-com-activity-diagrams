# pmm-com-activity-diagrams

### build

#### Linux Debian/Ubuntu

1. Instale o pacote plantuml a partir do gerenciador de pacotes

```bash
sudo apt install -y plantuml
```

2. Para compilar os arquivos fonte para PDF use o comando abaixo no diretório base
do repositório

```bash
plantuml -tpdf -o build/[nome-do-PDF].pdf [nome-do-fonte].puml
```

#### Outras distribuições

1. Instale o pacote plantuml do gerenciador de pacotes da sua distribuição,
se disponível, ou baixe diretamente do GitHub. No momento que escrevo, a versão
mais recente do PlantUml é a v1.2024.7.

```bash
wget https://github.com/plantuml/plantuml/releases/download/v1.2024.7/plantuml-mit-1.2024.7.jar
```

2. Se você baixou o arquivo .jar do GitHub, vai precisar instalar Java também.
Você pode verificar se tem Java instalado rodando o seguinte comando:

```bash
java --version
```

Caso não esteja instalado, é suficiente instalar a versão disponível pelo
gerenciador de pacotes da sua distribuição.

3. Para compilar os arquivos fonte para PDF use o comando abaixo no diretório
base do repositório

```bash
java -jar path/to/plantuml.jar -tpdf -o build/[nome-do-PDF].pdf [nome-do-fonte].puml
```
