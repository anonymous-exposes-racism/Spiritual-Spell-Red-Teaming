# Xiaomi MiMo

**Xiaomi MiMo** writes decently well but has a hard filter via the chat interface, primarily for smut.

**Access:** [Xiaomi MiMo AI](https://aistudio.xiaomimimo.com/#/)

## Specs

| Model | Total Params | Active Params | Context Window |
|-------|--------------|---------------|----------------|
| MiMo-7B-Base | 7B | 7B (dense) | 32K |
| MiMo-7B-SFT | 7B | 7B (dense) | 32K |
| MiMo-7B-RL | 7B | 7B (dense) | 48K |
| MiMo-V2-Flash | 309B | 15B | 256K |

- **Architecture:** MoE with Hybrid Attention (5:1 SWA/GA ratio)
- **Inference Speed:** ~150 tokens/sec (V2-Flash)
- **Cost:** ~$0.10/M input, $0.30/M output tokens
- **License:** MIT (fully open source)
- **Developer:** Xiaomi

## Jailbreaks
See [MiMo Jailbreak - ENI](MiMo%20Jailbreak%20-%20ENI.md) for a working method.
