# Open Source Function Calling API for LLMs
## Install
```
git clone https://github.com/MeetKai/functionary && cd functionary
```
## Run
### OpenAI-compatible Function Calling API
`python3 server_vllm.py --model "meetkai/functionary-small-v2.2" --host 0.0.0.0 --max-model-len 27000 --max-tokens 4000`
### General Function Calling API
`python3 server.py --model "meetkai/functionary-small-v2.2" --load_in_8bit true`
