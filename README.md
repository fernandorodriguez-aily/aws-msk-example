# aws-msk-example
Small example on how to use Kafka in AWS MSK. Aily information about MSK and Kafka: https://ailylabs.atlassian.net/wiki/spaces/AIL/pages/1953857723/External+async+communication+Kafka

### Create Docker image for Kafka-UI

### Create topic in Kafka-UI

### Install Python packages

1.  Create a poetry.toml file with content:

```
[virtualenvs]
in-project = true
```

2. Create Python environment
```
poetry init --python ">=3.10.6,<3.11"
```
3. Add cloudsmith to access Aily packages
```
poetry source add cloudsmith https://dl.cloudsmith.io/PRBlnvv3GHFM3KDl/ailylabs/pip/python/simple/
```

4. Add libraries

```
poetry add aily-py-commons
poetry add aily-ai-brain
poetry add jupyter
poetry add confluent-kafka
```

### Run example
