# audio-evaluator 
audio-evaluator is a simple, easy-to-use wrapper for performing Automatic Speech Recognition with PyTorch. 

It is being used as a supporting package for Earudite, a trivia game, to evaluate recording quality relative to a transcript.

### Installation:
`pip install audio-evaluator`

### Example usage:
```py
from audioevaluator import evaluator as AUDIO_EVAL

FILENAME = 'frankenstein.wav' # path to file
TRANSCRIPT = 'frankenstein' # original transcript to compare to the ASR output

print(AUDIO_EVAL.evaluate_audio(FILENAME, TRANSCRIPT))
```