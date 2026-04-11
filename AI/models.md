## Structure
**Runtime**: Ollama / llama.cpp
**Interface**: Open WebUI

### Active Models
| Model | Use Case | Quantization |
| --- | --- | --- |
| Qwen 3.0 32b | General assistant | q4_K_M |
| Qwen 2.5 Coder 17b | Quick coding suggestions | q4_K_M |

### Architecture
- Ollama running in Docker, exposed only to local network
- Open WebUI chat interface
- Strictly local on VLAN
- Reverse proxied through pfSense HAProxy with TLS