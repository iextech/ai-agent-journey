# Lessons Learned

* Not all models natively support tools. gemma-3 model is an example model that does not support tools. I had to switch to another model (llama3.1:8b)
* A lot of things are LLM model dependent.
    * From the gemini version with Gemini 2.5 Flash, tool definition needs to be changed. The llama3.1 does not understand departure city is from_city.
    * With the gemini version, I can book another flight, not with ollama-llama3.1:8b. It keeps repeating the same booking.
