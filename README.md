

# token-validator

i just want to paste my prompt and user message into a tool, call the any LLM provider's token counting API *before* sending the real request, and see an exact token count, cost breakdown, context window usage, and scale projections. This prevents wasted API spend and runtime failures from oversized prompts.


--

you might be wondering why i used index.html file instead, i did not want to complicate it, this is not the time for it please! life is tough already to go about making things harder.

although i intend to do one that can directly connect to your projects tho.

Live at: **[tokenvalidator.nsisong.com](https://tokenvalidator.nsisong.com)**

## 📸 Screenshots (Coding & Reasoning)

````carousel
![Anthropic Haiku 4.5 Coding Validation](screenshots/anthropic_no_key.png)
<!-- slide -->
![OpenAI GPT-5.4 logic Performance](screenshots/openai_no_key.png)
<!-- slide -->
![DeepSeek Reasoning Analysis](screenshots/deepseek_no_key.png)
<!-- slide -->
![xAI Grok 4.20 Distributed Systems Logic](screenshots/grok_no_key.png)

## How it Works

1. **Select Provider**: Choose from the dropdown (Anthropic, OpenAI, DeepSeek, will keep adding.).
2. **Enter Prompt**: Fill in your system and user messages.
3. **Validate**: Hit "Validate Prompt". The tool calculates tokens locally and provides a full cost breakdown immediately.