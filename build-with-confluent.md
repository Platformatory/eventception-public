---
title: Build with Confluent Initiative
layout: landing
bodyClass: page-landing
intro_image: "images/landing/build.png"
summary: "Platformatory & Confluent: Empowering Real-Time Data Solutions"
# intro_image_absolute: true
description: "Platformatory is proud to be a part of the Build with Confluent initiative. By verifying our streaming-based use cases with Confluent, you can have confidence that our Confluent-based service offering is not only built on the leading data streaming platform but also verified by the experts at Confluent."
partner_section:
  - title: "Why Confluent?"
    content: "Confluent is the data streaming platform that is pioneering a fundamentally new category of data infrastructure that sets data in motion. Confluent’s cloud-native offering is the foundational platform for data in motion—designed to be the intelligent connective tissue enabling real-time data, from multiple sources, to constantly stream across the organization."
  - content: "With Confluent, organizations can meet the new business imperative of delivering rich, digital front-end customer experiences and transitioning to sophisticated, real-time, software-driven backend operations."
ctas:
  - text: "Contact Us"
    url: "/contact/"
    btn_id: "contact us"
    color: "#0c910c"
sections:
  - title: "Reflexive Eventing for Data-driven Applications"
    description: "Modern applications and infrastructure produce billions of events of interest. These can be"
    segments:
      - "Business “Domain” Events"
      - "RESTful Service & RPC Events"
      - "Network & Infrastructure Events"
  - description: "It becomes important to capture these and share them with the right stakeholders for processing and deriving insights from them. For example, in an e-commerce product, when an order is placed, multiple entities, such as shipping, payment, billing, BI, etc., are interested in the event."
  - description: "In an API context, this typically involves the service performing a dual write to the database and the message broker, or the same changes being passed through to the message broker using an approach like change data capture."
  - description: "These approaches however suffer from one of the two limitations"
    segments:
      - "1. Dual writes are complicated to achieve and require sensitive code changes. Many times, these maybe legacy applications or outside our domain of control"
      - "2. Approaches such as CDC capture row level changes but piecing back domain objects from table and row level changes requires a lot of complex stream processing."
  - description: "And this is specifically what Eventception solves for. It does this by treating the API history as a transactional log. Eventception hooks into common network layer proxies and agents to synthesize, aggregate and distribute events in a variety of formats."
  - description: "Eventception is an ideal platform for various use cases, starting from"
    segments:
      - "<strong>Generic, Durable Event Ingestion (both Push and Pull):</strong> Eventception can be used to ingest events from various L4-L7 proxies, network logging appliances or existing syslog agents. It has support for REST/HTTP style application services, gRPC, HTTP/2, WebSockets."
      - "<strong>Pre-aggregation and filtering:</strong> Eventception can be used to parse, pre-aggregate and filter data using an idiomatic DSL, so as to summarize, roll-up and efficiently manage massive volumes of data over time."
      - "<strong>Forwarding to various systems:</strong> Data can be forwarded to various systems using connectors: Supporting popular SIEM systems, log-storage systems and analytical data stores. Eventception also supports consuming with Kafka consumers, REST or built-in webhook dispatcher, along with CloudEvent bindings (serverless friendly!)"
      - "<strong>API Auditing & Forensics:</strong> Eventception has the ability to mine granular audit logs for RESTful microservices across your entire API surface."
      - "<strong>Advanced Observability:</strong> Support for Open Telemetry APIs for handling logs, traces and metrics."
  - title: "Building with Confluent"
    description: "Naturally, Confluent makes a great choice for our streaming platform. Here's how -"
    segments:
      - "Eventception can support “Bring your own Kafka” - for the primary destination.  → Can support <b>Confluent Cloud, Confluent Platform</b> and edge Kafka clusters"
      - "Our processing DSL is built on top of <b>Apache Flink</b>"
      - Events can be generated in various data formats - JSON, Avro with <b>Confluent Schema Registry</b>
      - "We support Kafka sink connectors to send processed events to destinations → can also leverage <b>Confluent Cloud fully managed connectors</b>"
    ctas:
      - title: "Confluent Connectors"
        img: "/images/landing/icon-connector.png"
        url: "/"
      - title: "Confluent Cloud"
        img: "/images/landing/icon-cloud_dark.png"
        url: "/"
      - title: "Schema Registry"
        img: "/images/landing/icon-schema_registry.png"
        url: "/"
      - title: "Apache Flink"
        img: "/images/landing/icon-Flink.png"
        url: "/"
  - title: "A peek under the hood"
    image_url: "/images/landing/eventception-arch.svg"
  - title: "In action"
    video_url: "https://www.youtube.com/embed/3NL2ctqglfo?si=pWW7QTqML49R122G"
---

## Why Confluent?

Confluent is the data streaming platform that is pioneering a fundamentally new category of data infrastructure that sets data in motion. Confluent’s cloud-native offering is the foundational platform for data in motion—designed to be the intelligent connective tissue enabling real-time data, from multiple sources, to constantly stream across the organization.

With Confluent, organizations can meet the new business imperative of delivering rich, digital front-end customer experiences and transitioning to sophisticated, real-time, software-driven backend operations.

<!-- # Our Joint Solution

Insert text about the joint solution. Provide some background and explain what this solution solves for. Highlight the benefits and the unique value proposition. -->
