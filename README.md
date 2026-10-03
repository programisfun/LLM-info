# LLM-info

### Master LLM API Speed & Hong Kong (HK) Availability Matrix

| Model Tier | Average Speed (Tokens/Sec) | API Price (Per 1 Million Tokens) | Direct Local API? (No VPN) | Best Compliant API Route for HK Users |
| :--- | :--- | :--- | :--- | :--- |
| **Llama 3.2 3B / Llama 4 Scout** *(via Groq / Cerebras)* | 🚀 **~1,800 – 2,800+ t/s** | ~\$0.05 – \$0.06 | 🔴 **No** (Directly Geoblocked) | Route requests through proxy aggregators like OpenRouter or DeepInfra. |
| **Llama 3.1 8B** *(via Groq)* | ⚡ **~500 – 650 t/s** | ~\$0.05 – \$0.08 | 🔴 **No** (Directly Geoblocked) | Use OpenRouter to access the ultra-fast specialized hardware backends. |
| **Gemini Flash-Lite** (e.g., 2.5/3.1 Lite) | 💨 **~360+ t/s** | \$0.10 Input / \$0.40 Output | 🔴 **No** *(Via AI Studio)* / 🟢 **Yes** *(Via Vertex)* | Google AI Studio API is geoblocked locally. Use Google Cloud Vertex AI (selecting Tokyo or Singapore data regions) or OpenRouter. |
| **Gemini Flash** (e.g., 2.5/3.8 Flash) | **~250 – 360+ t/s** | \$0.30 Input / \$2.50 Output | 🔴 **No** *(Via AI Studio)* / 🟢 **Yes** *(Via Vertex)* | Google AI Studio API is geoblocked locally. Deploy directly via enterprise Google Cloud Vertex AI or use OpenRouter. |
| **GPT-4o mini** | **~200+ t/s** | \$0.15 Input / \$0.60 Output | 🔴 **No** (Directly Geoblocked) | Provision via Microsoft Azure OpenAI Service (enterprise) or query via OpenRouter. |
| **Claude Haiku** (e.g., 3.5 Haiku) | **~150 – 200 t/s** | \$0.80 Input / \$4.00 Output | 🔴 **No** (Directly Geoblocked) | Access using an aggregator backend like OpenRouter or through Amazon Bedrock. |
| **DeepSeek V3 / V4** | **~60 – 95+ t/s** | ~\$0.25 Input / \$1.00 Output | 🟢 **Yes** | **100% Native & Open.** Directly register on the DeepSeek Developer Platform using international cards. No local network blocks. |
| **Qwen 3.5 / 3.8** (Alibaba) | **~40 – 80+ t/s** | ~\$1.00 – \$2.00 | 🟢 **Yes** | **100% Native & Open.** Sign up directly via Alibaba Cloud Model Studio (DashScope) for seamless local latency routing. |
