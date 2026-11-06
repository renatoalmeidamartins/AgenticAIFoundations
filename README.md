# AgenticAIFoundations

## Labs, course materials, survey
- [Course materials](https://us-east-1.student.classrooms.aws.training/class/ilt%238sBYjfa9yCf36yp1JzR6CL)
- In [MyClass](https://myclass.skillbuilder.aws), you can fill the survey by going to the class in the "Past classes" section and clicking the evaluation button.

## My contact info:
- [Linkedin](https://www.linkedin.com/in/renatodealmeidamartins)
- renatoalmeidamartins@gmail.com
## Reference repos
- [Repo **full** with agentcore samples](https://github.com/awslabs/agentcore-samples/tree/main)
## Day 1 links
- What is series:
    - [Embeddings in Machine Learning](https://aws.amazon.com/what-is/embeddings-in-machine-learning/)
    - [RAG (Retrieval-Augmented Generation)?](https://aws.amazon.com/what-is/retrieval-augmented-generation/)
    - [Agentic AI](https://aws.amazon.com/what-is/agentic-ai/)
    - [Deep learning](https://aws.amazon.com/what-is/deep-learning/)
    - [Machine learning](https://aws.amazon.com/what-is/machine-learning/)
    - [Transformers in AI](https://aws.amazon.com/what-is/transformers-in-artificial-intelligence/)
    - [Prompt engineering](https://aws.amazon.com/what-is/prompt-engineering/)
- [Spatial transformer networks](https://arxiv.org/pdf/1506.02025)
- [Attention is all you need](https://arxiv.org/pdf/1706.03762)
- [The neural network zoo](https://www.asimovinstitute.org/neural-network-zoo/)
- [Built-in algorithms and pretrained models in Amazon SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/algos.html)
- Some agentic frameworks
    - [CrewAI](https://docs.crewai.com/v1.15.33/en/quickstart)
    - [Langchain](https://docs.langchain.com/oss/python/langchain/agents)
    - [Langgraph](https://docs.langchain.com/oss/python/langgraph/agentic-rag)
    - Strands
        - [Introducing Strands Agents, an Open Source AI Agents SDK](https://aws.amazon.com/blogs/opensource/introducing-strands-agents-an-open-source-ai-agents-sdk/)
        - [Strands Agents SDK: A technical deep dive into agent architectures and observability](https://aws.amazon.com/blogs/machine-learning/strands-agents-sdk-a-technical-deep-dive-into-agent-architectures-and-observability/)
    - [Microsoft Agent Framework](https://github.com/microsoft/agent-framework)
- [ReAct: Synergizing Reasoning and Acting in Language Models ](https://research.google/blog/react-synergizing-reasoning-and-acting-in-language-models/)
- [Embeddings projector](https://projector.tensorflow.org/)
- [Model Context Protocol - MCP](https://modelcontextprotocol.io/docs/2026-07-28/learn/architecture)
- [Open source MCP servers for AWS](https://github.com/awslabs/mcp)
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector)
- [Media operations agent](https://aws.amazon.com/media/nab25-demos/media-operations-agent/) - case study where one can "Unlock value in video archives with multi-agent collaboration for video understanding using Amazon Bedrock"
- [Bedrock Flow Samples](https://github.com/aws-samples/amazon-bedrock-flows-samples)
- [Kiro basics](https://kiro.dev/docs/getting-started/first-project/)
- [AI-DLC - one core, many harnesses ](https://github.com/awslabs/aidlc-workflows)

## Day 2 links
- [LlamaIndex quickstart](https://developers.llamaindex.ai/python/framework/getting_started/starter_example/)
- [Use Amazon Bedrock Intelligent Prompt Routing for cost and latency benefits](https://aws.amazon.com/blogs/machine-learning/use-amazon-bedrock-intelligent-prompt-routing-for-cost-and-latency-benefits/)
- [Strands agents tools repo](https://github.com/strands-agents/tools) - this is community based, archived on Nov 4th, 2026 in favor of the [vended SDK tools](https://strandsagents.com/docs/user-guide/sdk/tools/vended-tools/)
- [Built-in strategies for memory extraction strategies](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/memory-strategies.html)
- Agentcore in a bit more detail
    - New features since the course was released
        - [Get to your first working agent in minutes: Announcing new features in Amazon Bedrock AgentCore](https://aws.amazon.com/blogs/machine-learning/get-to-your-first-working-agent-in-minutes-announcing-new-features-in-amazon-bedrock-agentcore/)
        - [Introducing Amazon Bedrock Managed Knowledge Base for faster, more accurate enterprise AI applications](https://aws.amazon.com/blogs/aws/introducing-amazon-bedrock-managed-knowledge-base-for-faster-more-accurate-enterprise-ai-applications/)
        - [Manage agents, tools and skills at scale with AWS Agent Registry](https://aws.amazon.com/blogs/machine-learning/manage-agents-tools-and-skills-at-scale-with-aws-agent-registry/). Keep in mind there was already an [Open Source MCP Registry](https://github.com/modelcontextprotocol/registry)
        - [Amazon Bedrock AgentCore payments is now generally available: Enabling agents to transact safely and autonomously at scale](https://aws.amazon.com/blogs/machine-learning/amazon-bedrock-agentcore-payments-is-now-generally-available-enabling-agents-to-transact-safely-and-autonomously-at-scale/)
        - As part of agentcore evaluations, there are [prompts](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/prompt-templates-builtin.html) for the built-in metrics
- Evaluations in more detail
    - [RAGAS for RAG metrics](https://docs.ragas.io/en/stable/concepts/metrics/available_metrics/)
    - [Example using evaluations](https://github.com/awslabs/agentcore-samples/tree/main/01-features/06-observe-evaluate-optimize-your-agent/02-evaluate)
    - Example above is used in the [evaluations with Ground truth references](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/ground-truth-evaluations.html)
- [Query a knowledge base and retrieve data](https://docs.aws.amazon.com/bedrock/latest/userguide/kb-test-retrieve.html), main operations are [Retrieve](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_agent-runtime_Retrieve.html) and [RetrieveAndGenerate](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_agent-runtime_RetrieveAndGenerate.html)
- Automated reasoning policies
    - [Automated Reasoning policy refinement in Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/automated-reasoning-policy-refinement-in-amazon-bedrock/)
    - [Doc](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails-automated-reasoning-checks.html)
- [Protect Sensitive Data with Amazon CloudWatch Logs](https://aws.amazon.com/blogs/aws/protect-sensitive-data-with-amazon-cloudwatch-logs/)
- [Runtime instances: persistent compute for production AI agents on Amazon Bedrock AgentCore](https://aws.amazon.com/blogs/aws/runtime-instances-persistent-compute-for-production-ai-agents-on-amazon-bedrock-agentcore/)
- [Announcing the Agent2Agent Protocol (A2A)](https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/), with its supporting [repo](https://github.com/a2aproject/a2a)
- [Agentcore CLI](https://github.com/aws/agentcore-cli)


