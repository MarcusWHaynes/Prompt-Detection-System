To Do/Goals:

Have a frontend with an input box for prompt, returns the risk of the prompt and if its malicious or not.

Flow of prompt 

Input 
↓
Normalisation 
↓
Heuristic Detection
↓
ML Classification
↓
Risk Scoring
↓
Final Repsonse 

Using https://genai.owasp.org/llmrisk/llm01-prompt-injection/ list of example injections
A list of Heuristic Detectors I would like to include are, regex for just direct injection, Indirect injection
Obfuscated attacks through unicode, leakage through code injection, jailbreaking through suffixs

Prompts need to be sanitized, thus a normaliser program will be nessersary to clean up Capitalisaitons, Unicode, whitespace, weird symbols

N.B to decide on how the ml classification will work 