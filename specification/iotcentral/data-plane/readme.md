# IoT Central - API client generation
> see https://aka.ms/autorest
This is the AutoRest configuration file for Azure IoT Central.

## Getting Started
To build the SDK for Azure IoT Central, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:
> `autorest readme.md`
To see additional help and options, run:
> `autorest --help`
---

## Configuration

### Basic Information

These are the global settings for the IoT Central API.

``` yaml
openapi-type: data-plane
tag: package-2022-05-31
```

### Tag: package-1.2-preview
These settings apply only when `--tag=package-1.2-preview` is specified on the command line.

```yaml $(tag) == 'package-1.2-preview'
input-file:
  - Microsoft.IoTCentral/preview/1.2-preview/iotcentral.json
```

### Tag: package-1.1-preview
These settings apply only when `--tag=package-1.1-preview` is specified on the command line.

```yaml $(tag) == 'package-1.1-preview'
input-file:
  - Microsoft.IoTCentral/preview/1.1-preview/iotcentral.json
```

### Tag: package-2021-04-30-preview
These settings apply only when `--tag=package-2021-04-30-preview` is specified on the command line.

```yaml $(tag) == 'package-2021-04-30-preview'
input-file:
  - Microsoft.IoTCentral/preview/2021-04-30-preview/iotcentral.json
```

### Tag: package-1.0
These settings apply only when `--tag=package-1.0` is specified on the command line.

```yaml $(tag) == 'package-1.0'
input-file:
  - Microsoft.IoTCentral/stable/1.0/iotcentral.json
```

### Tag: package-2022-05-31
These settings apply only when `--tag=package-2022-05-31` is specified on the command line.

```yaml $(tag) == 'package-2022-05-31'
input-file:
  - Microsoft.IoTCentral/stable/2022-05-31/iotcentral.json
```

### Tag: package-2022-06-30-preview
These settings apply only when `--tag=package-2022-06-30-preview` is specified on the command line.

```yaml $(tag) == 'package-2022-06-30-preview'
input-file:
  - Microsoft.IoTCentral/preview/2022-06-30-preview/iotcentral.json
```
---

# Code Generation

## Python

See configuration in [readme.python.md](./readme.python.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)

## NodeJs

See configuration in [readme.nodejs.md](./readme.nodejs.md)

## CSharp

See configuration in [readme.csharp.md](./readme.csharp.md)

## Go

See configuration in [readme.go.md](./readme.go.md)