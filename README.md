# Scoop Bucket for TransactRx

A [Scoop](https://scoop.sh/) bucket for TransactRx tools.

## Installation

```powershell
scoop bucket add transactrx https://github.com/transactrx/scoop-bucket
scoop install nats-discover
```

## Available Apps

- **nats-discover** - CLI tool to discover NATS services using the nats-service framework

## Usage

After installation:

```powershell
# List all services
nats-discover -s nats://localhost:4222

# Get API docs for a specific service
nats-discover -s nats://localhost:4222 -S orders.api

# Show version
nats-discover --version
```

For more information, see the [nats-service repository](https://github.com/transactrx/nats-service).
