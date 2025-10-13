# ⚡ Stream Real time Blockchain Data via Kafka Protobuf

**bitquery-protobuf** is an official **npm package** for consuming **Kafka Protobuf messages** from **[Bitquery](https://bitquery.io/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=bitquery_home&utm_term=bitquery)** — a leading on-chain data provider offering **blockchain data APIs**, **WebSocket streams**, and **Kafka Protobuf feeds** for real-time analytics.

This library allows developers to easily **consume, decode, and handle low-latency blockchain event streams** without the hassle of managing `.proto` files or Kafka configurations in real time.

---

## 🚀 Overview

**bitquery-protobuf** simplifies working with **Bitquery’s Protobuf Kafka Streams**, which deliver **real-time on-chain data** from multiple blockchains (Bitcoin, Ethereum, BSC, and more).  
It’s perfect for developers building **crypto dashboards, data pipelines, trading bots**, or **blockchain analytics applications** requiring **ultra-low latency**.

👉 Learn more about **Bitquery’s Kafka Streaming Concepts** in the  
**[official documentation](https://docs.bitquery.io/docs/streams/kafka-streaming-concepts/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=kafka_streaming_docs&utm_term=kafka_streaming)**.

---

## ⚙️ Installation

Install the npm package directly:

```shell
npm install bitquery-protobuf
````

You can find it on npm here:
📦 [bitquery-protobuf on npm](https://www.npmjs.com/package/bitquery-protobuf?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=npm_page&utm_term=bitquery_protobuf)

---

## 🧩 Usage Example

Create a new JavaScript file, e.g., `test.js`, and add the following:

```js
const { runProto } = require('bitquery-protobuf');

runProto("<username>", "<password>", "topic");
```

Then run the file:

```shell
node test.js
```

### Parameters

* `<username>` and `<password>` — Credentials for accessing the **Bitquery Kafka Stream**.
  To obtain your credentials, contact our team at
  📧 [sales@bitquery.io](mailto:sales@bitquery.io?subject=Kafka%20Protobuf%20Access&utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=sales_email&utm_term=bitquery_kafka) or via [Telegram](https://t.me/Bloxy_info/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=telegram_channel&utm_term=bitquery_kafka).

* `<topic>` — The topic of the **Kafka Protobuf stream** you wish to subscribe to (e.g., Bitcoin transactions, Ethereum events, etc.).

This package serves as a **“Getting Started” utility** for testing and demonstrating real time **Bitquery Protobuf streams**.
For **custom or production-grade solutions**, contact the Bitquery team for tailored support:
🌐 [Contact Bitquery](https://t.me/Bloxy_info?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=telegram_channel&utm_term=bitquery_contact) or fill out the [form](https://bitquery.io/forms/api/??utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=sales_form&utm_term=bitquery_contact)

---

## 🧾 Example Topics

You can explore available topics and blockchain event types here:
🔗 [Bitquery Streaming Documentation](https://docs.bitquery.io/docs/streams/protobuf/chains/Bitcoin-protobuf/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=protobuf_kafka_docs&utm_term=protobuf_kafka)

---

## 🤝 Contributing

We welcome community contributions!
Please report issues or submit pull requests on the official repository:
👉 [bitquery-protobuf GitHub Repository](https://github.com/bitquery/bitquery-protobuf?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=github_repo&utm_term=bitquery_protobuf)

---

## 🧭 Documentation Resources

| Resource                             | Description                                      | Link                                                                                                                                                                                                                        |
| ------------------------------------ | ------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Kafka Streaming Concepts**         | Learn about how Bitquery streams blockchain data | [Read Docs](https://docs.bitquery.io/docs/streams/kafka-streaming-concepts/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=kafka_streaming_docs&utm_term=kafka_streaming)          |
| **Protobuf Kafka (Bitcoin Example)** | Example for decoding Bitcoin data streams        | [View Example](https://docs.bitquery.io/docs/streams/protobuf/chains/Bitcoin-protobuf/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=protobuf_kafka_docs&utm_term=protobuf_kafka) |
| **Bitquery API Hub**                 | Explore blockchain data APIs and GraphQL queries | [Explore APIs](https://docs.bitquery.io/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=bitquery_docs&utm_term=bitquery_docs)                                                      |
| **Bitquery Home**                    | Learn more about Bitquery and its data products  | [Visit Bitquery.io](https://bitquery.io/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=bitquery_home&utm_term=bitquery)                                                           |

---

## 📜 License

**ISC License © 2025 bitquery-protobuf**

This package is open-source and free to use.
Attribution to **[Bitquery](https://bitquery.io/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=bitquery_home&utm_term=bitquery)** is appreciated.

---

### ✨ Built with [Bitquery](https://bitquery.io/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=bitquery_home&utm_term=bitquery)

Delivering real-time blockchain data through GraphQL, WebSocket, and Kafka Protobuf streams. [Signup](https://account.bitquery.io/auth/signup?redirect_to=https://ide.bitquery.io/?utm_source=github_readme&utm_medium=referral&utm_campaign=bitquery_protobuf&utm_content=bitquery_signup&utm_term=bitquery) today.