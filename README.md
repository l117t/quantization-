# quantization-
Task report
Track 2: Quantization of Language models
In this task, the quantization of the GPT2 to INT8 was performed. The
GPTQ algorithm was used. RedPajama-Data-V2 was selected as the calibration dataset. The neural network was tested using lm-eval and BoolQ.
The metric values for the pre-trained GPT2
• accuracy: 0.2892 (lm-eval)
• normalized accuracy: 0.3114 (lm-eval)
The metric values for the quantized GPT2
• accuracy: 0.2888 (lm-eval)
• normalized accuracy: 0.3120 (lm-eval)
• accuracy: 0.6250 (BoolQ)
Auto-AWQ quantization is most likely not supported by this model.
