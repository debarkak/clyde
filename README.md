> [!Note]  
> this repo is archived and now merged to the new ClydeReborn project (https://github.com/ClydeReborn). This repo might wont work and wont be updated.

# Clyde
Recreation of Discord's cancelled AI Bot, Clyde.

# Story
On March 2nd 2023, Discord introduced Clyde, an AI chatbot based on OpenAI's ChatGPT, however it had many flaws, and all people hated it, mostly from NTTS' (No Text To Speech) audience, and Discord killed Clyde on December 1st 2023, as it would cost Discord a lot of money and so they decided to shut it down, the EOL date was announced on November 5th 2023 and all my friends and everyone in the Chomu Paradise Club panicked and was very sad (infact Bohdan/TheBombGuy threw his A30s and cracked the screen even more than it was), however Luna (lun4h) knew that this would happen, and already started working on a backup.

# Information
### Name
The name for this bot is "Sakoma", as suggested by 3177.<br>
You can rename it though by replacing the word "Sakoma" in the designated system prompt with your own name.
### Programming Languages
Clyde uses Python for the bot part and Shell for launching.
###  AI model
It currently uses [Llama2](https://llama2.ai) from the [`python-tgpt`](https://github.com/Simatwa/python-tgpt) library.

We would recommend to use one of the following providers for your instance of Clyde:
- gpt4free: Bing¹, FreeChatgpt², Llama2, Phind⁴
- python-tgpt: Llama2, Phind³

<sub><sup>¹May give CAPTCHAs after a while or when providing the wrong values.</sub></sup><br>
<sub><sup>²If using the vendored provider file.</sub></sup><br>
<sub><sup>³Has the tendency to say something unrelated if it didn't understand your prompt.</sub></sup><br>
<sub><sup>⁴May give errors or blank responses, use the `python-tgpt` implementation.</sub></sup><br>

# How to run?
1. Clone this repo.
```sh
git clone https://github.com/debarkak/clyde.git
```

2. Install Python and required modules.
```sh
pip install -U -r requirements.txt
```

3. Open `clyde.py`, and put your account token in the bottom line.
```
client.run("<TOKEN_GOES_HERE>")
```

4. Replace `<TOKEN_GOES_HERE>` with your account token.<br>
It must be a user account token, use an alt if you're bothered about a ban.

### Testing Providers
To check working providers, run `python test_clyde_full.py` for a comprehensive test, or run `python test_clyde_quick.py` for a quick test.<br>
The comprehensive test may take upwards of 30 minutes to finish!

# Required OS
* This bot can only run on Linux. We recommend using Arch Linux, Fedora or Debian for this.<br>
If you're using Windows, you may be able to run this bot on WSL.

Enjoy!
