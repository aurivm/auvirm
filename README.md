<div align="center">
  <a href="https://aurivm.world">
    <img src="https://visionary-cajeta-2f322b.netlify.app/assets/logo-khhyVSLt.png" style="margin: 15px; max-width: 300px" width="50%" alt="Logo">
  </a>
</div>
<p align="center">
  <em>The Enterprise-Grade Production-Ready Multi-Agent Orchestration Framework </em>
</p>

<p align="center">
    <a href="https://pypi.org/project/aurivm/" target="_blank">
        <img alt="Python" src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
        <img alt="Version" src="https://img.shields.io/pypi/v/aurivm?style=for-the-badge&color=3670A0">
    </a>
</p>

## ✨ Features

| Category | Features | Benefits |
|----------|----------|-----------|
| 🏢 Enterprise Architecture | • Production-Ready Infrastructure<br>• High Reliability Systems<br>• Modular Design<br>• Comprehensive Logging | • Reduced downtime<br>• Easier maintenance<br>• Better debugging<br>• Enhanced monitoring |
| 🤖 Agent Orchestration | • Hierarchical Aurivm<br>• Parallel Processing<br>• Sequential Workflows<br>• Graph-based Workflows<br>• Dynamic Agent Rearrangement | • Complex task handling<br>• Improved performance<br>• Flexible workflows<br>• Optimized execution |
| 🔄 Integration Capabilities | • Multi-Model Support<br>• Custom Agent Creation<br>• Extensive Tool Library<br>• Multiple Memory Systems | • Provider flexibility<br>• Custom solutions<br>• Extended functionality<br>• Enhanced memory management |
| 📊 Scalability | • Concurrent Processing<br>• Resource Management<br>• Load Balancing<br>• Horizontal Scaling | • Higher throughput<br>• Efficient resource use<br>• Better performance<br>• Easy scaling |
| 🛠️ Developer Tools | • Simple API<br>• Extensive Documentation<br>• Active Community<br>• CLI Tools | • Faster development<br>• Easy learning curve<br>• Community support<br>• Quick deployment |
| 🔐 Security Features | • Error Handling<br>• Rate Limiting<br>• Monitoring Integration<br>• Audit Logging | • Improved reliability<br>• API protection<br>• Better monitoring<br>• Enhanced tracking |
| 📈 Advanced Features | • SpreadsheetAurivm<br>• Group Chat<br>• Agent Registry<br>• Mixture of Agents | • Mass agent management<br>• Collaborative AI<br>• Centralized control<br>• Complex solutions |
| 🔌 Provider Support | • OpenAI<br>• Anthropic<br>• ChromaDB<br>• Custom Providers | • Provider flexibility<br>• Storage options<br>• Custom integration<br>• Vendor independence |
| 💪 Production Features | • Automatic Retries<br>• Async Support<br>• Environment Management<br>• Type Safety | • Better reliability<br>• Improved performance<br>• Easy configuration<br>• Safer code |
| 🎯 Use Case Support | • Task-Specific Agents<br>• Custom Workflows<br>• Industry Solutions<br>• Extensible Framework | • Quick deployment<br>• Flexible solutions<br>• Industry readiness<br>• Easy customization |

----

## Requirements
- `python3.10` or above!
- `$ pip install -U aurivm` And, don't forget to install aurivm!
- `.env` file with API keys from your providers like `OPENAI_API_KEY`, `ANTHROPIC_API_KEY`
-  Set an `.env` Variable with your desired workspace dir: `WORKSPACE_DIR="agent_workspace"` or do it in your terminal with `export WORKSPACE_DIR="agent_workspace"`
-  Finally, `aurivm onboarding` to get you started.

## Guides and Walkthroughs
Refer to our documentation for production grade implementation details.

| Section              | Links                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------|
| Installation    | [Installation](https://docs.aurivm.world/en/latest/aurivm/install/install/)                                                            |
| Quickstart | [Get Started](https://docs.aurivm.world/en/latest/aurivm/install/quickstart/)                                                 |
| Agent Internal Mechanisms | [Agent Architecture](https://docs.aurivm.world/en/latest/aurivm/framework/agents_explained/)                                                 |
| Agent API | [Agent API](https://docs.aurivm.world/en/latest/aurivm/structs/agent/)                                                 |
| Integrating External Agents Griptape, Autogen, etc | [Integrating External APIs](https://docs.aurivm.world/en/latest/aurivm/agents/external_party_agents/)                                                 |
| Creating Agents from YAML | [Creating Agents from YAML](https://docs.aurivm.world/en/latest/aurivm/agents/create_agents_yaml/)                                                 |
| Why You Need Aurivm | [Why MultiAgent Collaboration is Necessary](https://docs.aurivm.world/en/latest/aurivm/concept/why/)                                                 |
| Swarm Architectures Analysis | [Swarm Architectures](https://docs.aurivm.world/en/latest/aurivm/concept/swarm_architectures/)                                                 |
| Choosing the Right Aurivm for Your Business Problem¶ | [CLICK HERE](https://docs.aurivm.world/en/latest/aurivm/concept/swarm_architectures/)                                                 |
| AgentRearrange Docs| [CLICK HERE](https://docs.aurivm.world/en/latest/aurivm/structs/agent_rearrange/)                                                 |

## Install 💻
Install the following packages with copy and paste

```bash
$ pip3 install -U aurivm aurivm-models aurivm-memory
```

## Onboarding

Now that you have downloaded aurivm with `pip3 install -U aurivm`, we get access to the `CLI`. Get Onboarded with CLI Now with:

```bash
aurivm onboarding
```

You can also run this command for help:

```bash
aurivm help
```

For more documentation on the CLI [CLICK HERE](https://docs.aurivm.world/en/latest/aurivm/cli/main/)

---

# Usage Examples 🤖
Here are some example scripts to get you started. For more comprehensive documentation, visit our [docs](https://docs.aurivm.world/en/latest/).

| Example Name | Description | Type of Examples | Link |
| --- | --- | --- | --- |
| Aurivm Examples | A collection of simple examples to demonstrate Aurivm capabilities. | Basic Usage | [https://github.com/The-Aurivm-Corporation/aurivm-examples?tab=readme-ov-file](https://github.com/The-Aurivm-Corporation/aurivm-examples?tab=readme-ov-file) |
| Cookbook | A comprehensive guide with recipes for various use cases and scenarios. | Advanced Usage | [https://github.com/The-Aurivm-Corporation/Cookbook](https://github.com/The-Aurivm-Corporation/Cookbook) |

---

## `Agent` Class
The `Agent` class is a fundamental component of the Aurivm framework, designed to execute tasks autonomously. It fuses llms, tools and long-term memory capabilities to create a full stack agent. The `Agent` class is highly customizable, allowing for fine-grained control over its behavior and interactions.

### `run` Method
The `run` method is the primary entry point for executing tasks with an `Agent` instance. It accepts a task string as the main input task and processes it according to the agent's configuration. And, it can also accept an `img` parameter such as `img="image_filepath.png`
