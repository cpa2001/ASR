## Setup
1. run Format_Subtitle to convert srt --> json.
2. run Match_Subtitle2Caption to copy m4a audio into the folder of Subtitle.
3. run cut_audio to cut the m4a audio according to json and convert audio into flac.
4. run whisper_inference to use whisper predicting dataset.
5. (optional) run evaluate_statistics to evaluate total CER of whole json document.
