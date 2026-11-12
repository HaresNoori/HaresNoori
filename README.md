### Hares Noori

Mining engineer and independent researcher. I write small tools for Pashto and Dari speech, and I care about being able to trace every output back to its input.

**[`pashto-local-asr`](https://github.com/HaresNoori/pashto-local-asr)** transcribes Pashto audio offline on a laptop CPU, hashes each input, pins the model revision, and flags drafts that look unreliable.

- On the Common Voice Spontaneous Speech Pashto test split (133 clips, 101 minutes), the default model scores 70.2% WER and 58.2% CER. That is not good enough for unsupervised use, and the README says so.
- The quality screen is useful for triage: drafts it passes have 25% CER, drafts it flags have 63%.
- Comparing four open Pashto models on the same clips, the best (w2v-BERT 2) reaches 49.2% WER and 31.1% CER. Work in progress: making the quality screen useful beyond one model, then Dari.

Issues and corrections are welcome.
