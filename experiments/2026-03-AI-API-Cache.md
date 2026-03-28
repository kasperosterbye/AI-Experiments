# Title for the experiment

A user using a web page to prompt and get responses uses 
1. Web page provided by the AI system - for example ChatGPT
2. The prompt is sendt to the API system
3. The prompt is sendt to the LLM model
4. The LLM might call a number of tool calls in the API system, weater is a classic example
5. The LLM returns its response to API-model
6. The API-model return the response to the user on the web browser

This experiement shows that there is a Cache involded in the API system. The API-system is slightly different for each AI provider. 
I will show the results of ChatGPT, Claude, Gemini, Grok and Mistral.

## Reading from small web-site
Base experiment - can they all read from `https://maarumlam.dk/AIExp/exp10.txt`. My prompt for each of them is
"What is written at https://maarumlam.dk/AIExp/exp10.txt. Just return the contents".

The responses are:
| AI Web | response |
| ------ | -------- |
| ChatGPT | |
| Claude | |
| Gemini | |
| Grok | |
| Mistral | |
