# GPT friend with extensible personality
# Add personality files or grow existing personality dynamically
# Friend's personality is retained and accessable each new instance.
* Install in a Python venv with .env file containing export OPENAI_API_KEY=""
* v1.0 - basic friend with temporary memory
* v1.1 - added permenant memory and dynamically growing personality
## Modify basic info in who-i-am.txt
## Add personality files to the my-personality folder
## E.G. To add work details create work.txt and list work details as below. This will then become a part of the friends personality.
## E.G: my-personality/my-work.txt
- I work as a designer.
- I enjoy solving complex design challenges.
- I dream of starting their own design studio one day.