# token-validator

i just want to paste my prompt and user message into a tool, call the any LLM provider's token counting API *before* sending the real request, and see an exact token count, cost breakdown, context window usage, and scale projections. This prevents wasted API spend and runtime failures from oversized prompts.

you might be wondering why i used index.html file instead, i did not want to complicate it, this is not the time for it please! life is tough already to go about making things harder.

although i intend to do one that can directly connect to your projects tho.

Live at: **[tokenvalidator.nsisong.com](https://tokenvalidator.nsisong.com)**

## How it Works

1. **Select Provider**: Choose from the dropdown (Anthropic, OpenAI, DeepSeek, will keep adding.).
2. **Enter Prompt**: Fill in your combined instructions and task (see details below).
3. **Validate**: Hit "Validate Prompt". The tool calculates tokens locally and provides a full cost breakdown immediately.

## Things to note:

1. System Prompt (The "Rules")
Think of this as the Model's Persona. It's used to tell the AI how to behave before it even talks to you.

Example: "You are a senior Python developer who only responds in code and uses the BS4 library."
Purpose: It sets the boundaries and tone.


2. User Message (The "Task")
This is the Actual Query. It's what you are asking the AI to do right now.

Example: "Write a script to scrape product titles from Amazon."
Purpose: It's the specific instruction you want a response to.