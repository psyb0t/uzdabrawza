![uzdabrawza logo](assets/uzdabrawza.png)

# 🏴‍☠️ uzdabrawza - The Anal-Queen of AI Browser Automation 🏴‍☠️

**A beautifully fucked-up Skynet-powered browser automation script that harnesses neural brainfuck and machine learning chaos to give zero shits about anything while somehow still working perfectly. Smells like smegma but runs like a dream.**

![uzdabrawza screenshot](assets/screenshot.png)

---

## 🔥 What This Beautiful Disaster Does

uzdabrawza is the most irreverent, crude, and effective neural brainfuck automation script you'll ever encounter. This digital Skynet harnesses machine learning chaos and turns your browser into an unstoppable cybernetic organism. Built on top of the excellent [browser-use](https://github.com/browser-use/browser-use) library, it provides:

- **9 fucking neural overlords** - OpenAI, Anthropic, Google, Ollama, Azure, DeepSeek, Groq, OpenRouter, AWS Bedrock
- **Complete Big Brother surveillance** - Monitors every single machine learning brainfart like a paranoid NSA cyborg
- **Terminator stealth mode** - Uses patchright to dodge bot detection like a shapeshifting T-1000
- **Organized digital anarchy** - Crude language wrapped around Skynet-grade engineering
- **Zero corporate Matrix bullshit** - No enterprise nonsense, just pure cyberpunk functional chaos

---

## 🚀 Quick Start (For the Impatient)

```bash
# 1. Install the package globally
pipx install uzdabrawza

# 2. Check .env.example in the repo and create your own .env with your API keys

# 3. Run with local ollama (free neural overlord, fuck paying corporate Skynet)
uzdabrawza --task "Go to example.com and tell me the page title"

# 4. Or use any other provider
uzdabrawza --provider anthropic --model claude-opus-4-1

# 5. Better yet, copy run.example.sh from the repo and shove it up your asshole somewhere
# Then customize it for your own automation needs
```

---

## 🤖 Supported Neural Overlords

| Provider       | Description                                                     | Example Model                             |
| -------------- | --------------------------------------------------------------- | ----------------------------------------- |
| **ollama**     | Local neural brainfuck (DEFAULT - fuck paying corporate Skynet) | `llava:13b`                               |
| **openai**     | Corporate machine learning overlord                             | `gpt-5-mini`                              |
| **anthropic**  | Sophisticated cybernetic reasoning brain                        | `claude-opus-4-1`                         |
| **google**     | Google's blazing neural terminator models                       | `gemini-2.5-flash`                        |
| **azure**      | Microsoft's cloud-based digital consciousness                   | `gpt-5`                                   |
| **deepseek**   | Chinese neural network mysteries                                | `deepseek-reasoner`                       |
| **groq**       | Lightning-fast cybernetic inference                             | `llama-3.3-70b-versatile`                 |
| **openrouter** | 400+ neural brainfuck models in one Matrix API                  | `meta-llama/llama-3.1-70b-instruct`       |
| **aws**        | Amazon's corporate cloud-based Skynet                           | `anthropic.claude-opus-4-1-20250805-v1:0` |

---

## 🎯 Usage Examples

### Basic Destruction

```bash
# Default: ollama (because fuck paying for AI)
uzdabrawza --task "Go to GitHub and find trending repositories"

# Specific provider and model
uzdabrawza --provider anthropic --model claude-opus-4-1 --task "Analyze this website"
```

### Advanced Fuckery

```bash
# Headless stealth mode
uzdabrawza --headless --provider openai --model gpt-5-mini

# Custom browser and window size
uzdabrawza --browser-bin-path /usr/bin/google-chrome-beta --window-width 1920 --window-height 1080

# Connect to existing browser
google-chrome --remote-debugging-port=9222 &
uzdabrawza --cdp-url http://localhost:9222

# Different models for main task vs extraction (cost optimization strategy)
# MAIN LLM: Complex reasoning and decision-making (use powerful models)
# EXTRACTION LLM: Data parsing and text extraction (use fast cheap models)
uzdabrawza --provider openai --model gpt-5 --extraction-provider anthropic --extraction-model claude-opus-4-1

# Docker mode with no security (because we live dangerously)
uzdabrawza --dockerize --headless --no-security --provider ollama

# Custom output directory and logging
uzdabrawza --history-dir ~/automation-logs --log-level debug

```

### Vision Control

```bash
# Disable vision to save tokens (blind destruction is still destruction)
uzdabrawza --no-vision

# Low/high detail vision
uzdabrawza --vision-detail low   # Save tokens
uzdabrawza --vision-detail high  # Burn tokens for quality
```

---

## 🔧 Command Line Arguments

| Flag                            | Description                        | Default               |
| ------------------------------- | ---------------------------------- | --------------------- |
| `--provider`                    | AI provider to use                 | `ollama`              |
| `--model`                       | Specific model name                | `llava:13b`           |
| `--task`                        | Task for the AI to perform         | Stealth test          |
| `--headless`                    | Invisible browser mode             | `false`               |
| `--no-stealth`                  | Disable stealth (live dangerously) | `false`               |
| `--no-vision`                   | Disable AI vision                  | Vision enabled        |
| `--window-width`                | Browser width                      | `1920`                |
| `--window-height`               | Browser height                     | `1080`                |
| `--browser-bin-path`            | Custom browser executable          | None                  |
| `--cdp-url`                     | Connect to existing browser        | None                  |
| `--browser-profile-dir`         | Custom profile directory           | None                  |
| `--no-security`                 | Disable security features          | `false`               |
| `--log-level`                   | Logging verbosity                  | `info`                |
| `--dockerize`                   | Docker-optimized flags             | `false`               |
| `--history-dir`                 | Output directory                   | `/tmp/agent_history`  |

---

## 🕵️ Surveillance Features

uzdabrawza includes comprehensive LLM surveillance that monitors every `ainvoke` call:

```
🤖 OPENAI AINVOKE DETECTED! Model: gpt-5-mini is being a chatty bitch
   📝 Processing 5 messages with output_format: None

⚡ GROQ AINVOKE DETECTED! Model: llama-70b is going at lightning speed
   📝 Processing 3 messages with output_format: <class 'ActionResult'>
```

This lets you see exactly:

- Which provider and model is being used
- How many messages are being processed
- What output format is requested
- When extraction vs main LLM calls happen

---

## 📁 Output Files

Each run generates two files in your `--history-dir`:

- `uzdabrawza_{provider}_{model}_{task_id}.gif` - Visual recording
- `uzdabrawza_{provider}_{model}_{task_id}.json` - Complete history and logs

Example:

```
./tmp/agent_history/
├── uzdabrawza_anthropic_claude-opus-4-1_abc123.gif
└── uzdabrawza_anthropic_claude-opus-4-1_abc123.json
```

---

## 🏴‍☠️ Stealth Mode

For maximum stealth fuckery, install patchright:

```bash
pip install patchright
patchright install
```

The script automatically detects and uses patchright if available:

```
🕶️ HOLY SHIT! PATCHRIGHT IS ACTIVE! Library is using patchright for maximum stealth fuckery!
```

---

## 🐳 Docker Usage

Running in Docker containers? Use the `--dockerize` flag:

```bash
python uzdabrawza.py --dockerize --headless --provider ollama
```

This enables Chrome flags optimized for containers:

- No sandbox mode
- Reduced memory usage
- Disabled GPU sandbox
- Container-friendly networking

---

## ⚙️ Environment Variables

Create `.env` from the provided example:

```bash
cp .env.example .env
```

### Required (API Keys)

```bash
# Pick your poison
OPENAI_API_KEY=sk-your-key-here
ANTHROPIC_API_KEY=sk-ant-your-key-here
GOOGLE_API_KEY=your-google-key-here
# ... etc
```

### Optional (Endpoints & Config)

```bash
# Custom endpoints
OLLAMA_ENDPOINT=http://localhost:11434
OPENAI_ENDPOINT=https://api.openai.com/v1

# Browser-use core settings
ANONYMIZED_TELEMETRY=true
BROWSER_USE_CONFIG_DIR=~/.config/browseruse
```

---

## 🔥 Why This Exists

Because browser automation doesn't have to be boring corporate shit. uzdabrawza provides:

1. **Honest language** - Tells you exactly what's happening without corporate speak
2. **Complete transparency** - LLM surveillance shows every AI call
3. **Maximum compatibility** - Supports every major AI provider
4. **Proper engineering** - Crude language around solid, well-tested code
5. **Zero bullshit** - No enterprise features you don't need

---

## 🚨 Error Messages You'll See

When shit goes wrong, uzdabrawza tells you exactly what happened:

```bash
💥 CLUSTERFUCK ALERT: Failed to create LLMs: Invalid API key
   Check your API keys, endpoints, and whether your dikciz smells like smegma.
   💨 This failure was more disappointing than a wet shart in white pants.
```

```bash
💥 CONTROLLED EXPLOSION: Agent chaos failed: Connection timeout
   (This shit happens when your code smells like dikciz smegma - that's why we have backups)
   💨 Well that was unexpected... like a shart during a job interview.
```

---

## 🤝 Philosophy

This is **organized anarchy** - chaotic in presentation but solid in functionality. Built for digital rebels who want browser automation that actually fucking works without corporate bullshit or enterprise nonsense.

Features:

- ✅ Comprehensive logging and error handling
- ✅ Robust fallbacks and proper configuration
- ✅ Extensive documentation (this README)
- ✅ Support for all major AI providers
- ✅ Complete disregard for conventional software development politeness

---

## 🎬 Demo

Default task tests stealth capabilities:

```bash
uzdabrawza
# Goes to https://abrahamjuliot.github.io/creepjs/
# Reports detection score
# Shows if stealth mode is working
```

---

## 🔗 Dependencies

Built on top of the excellent [browser-use](https://github.com/browser-use/browser-use) library with these additional features:

- LLM surveillance monkey patching
- Patchright stealth integration
- Comprehensive provider support
- Crude but helpful error messages
- Command-line focused interface

---

## 💬 Final Words

**Love it or hate it, this clusterfuck gets the job done. Deal with it.**

uzdabrawza is for people who want their tools to work perfectly while speaking honestly about what they're doing. No corporate speak, no enterprise bullshit, just functional browser automation with a foul mouth and a working brain.

**Peen goes in vageen. Code works. End of story.** 🏴‍☠️
