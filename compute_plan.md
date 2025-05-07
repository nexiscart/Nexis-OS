# GPU / Compute Needs

Nexis OS is designed to run persistent, multi-model AI systems (NOVEX, HELIX, ZELO, LUMIS) concurrently, without downtime or compromise. We require full-scale infrastructure capable of handling:

- Multiple 13B–65B parameter models in parallel (DeepSeek, WizardCoder, Mistral, LLaMA4)
- Continuous 24/7 execution of inference + orchestration workloads
- Real-time agent coordination, file I/O, memory state persistence, and autonomous rebuilds

**Minimum Recommended Specs:**
- Bare metal A100 or H100 GPUs (4x+)
- 1TB RAM minimum
- NVMe SSD storage (2TB+)
- High-throughput bandwidth for real-time AI tasking
- Persistent orchestration and service queue layers

This is not a test or dev workload. Nexis OS requires **enterprise-scale compute** to deploy the full infrastructure stack in live production mode.

