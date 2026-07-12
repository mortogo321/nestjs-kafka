# NestJS + Kafka Starter

An early-stage NestJS starter for building a Kafka-backed service, with local Kafka/Zookeeper infrastructure via Docker Compose and `kafkajs` as a dependency.

## What's inside

- Docker Compose bringing up Kafka and Zookeeper for local development
- `kafkajs` installed and ready to wire into producers/consumers
- Default NestJS application skeleton (no producer/consumer modules implemented yet)

## Tech stack

- NestJS
- KafkaJS
- Docker Compose (Kafka, Zookeeper)

## Quickstart

```bash
docker compose up -d      # start Kafka + Zookeeper
yarn install
yarn start:dev
```

API: http://localhost:3000

## Structure

```
src/                 NestJS application (module, controller, service)
docker-compose.yml   Kafka + Zookeeper for local development
```
