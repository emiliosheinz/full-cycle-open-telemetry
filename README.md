# OpenTelemetry

High-quality, ubiquitous, and portable telemetry to enable effective observability.

[OpenTelemetry](https://opentelemetry.io/) is a collection of APIs, SDKs, and tools. You can use it to instrument, generate, collect, and export telemetry data (metrics, logs, and traces) to help you analyze your software’s performance and behavior. This facilitates seamless integration with various monitoring services, including Datadog, Grafana, Sentry, and New Relic.

## Main Components

OpenTelemetry is currently made up of several main components:

- **Specification:** Describes the cross-language requirements and expectations for all implementations. Beyond a definition of terms, the specification defines the following: API, SDK, and Data.
- **Collector:** It is a vendor-agnostic proxy that can receive, process, and export telemetry data.
- **Language-specific API & SDK implementations** It lets you use the OpenTelemetry API to generate telemetry data with your language of choice and export that data to a preferred backend.
- **K8s operator:** It is an implementation of a Kubernetes Operator. The operator manages the OpenTelemetry Collector and auto-instrumentation of the workloads using OpenTelemetry.
- **Function as a Service assets:** Platforms that enable the development and execution of cloud-based programs. OpenTelemetry's community assets allow you to instrument and gain observability into the features, functions and applications you develop on FaaS platforms.
