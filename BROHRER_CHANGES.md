
Modified
`https://github.com/brohrer/TTS/edit/dev/TTS/tts/utils/text/phonemizers/__init__.py`
to catch RuntimeError on Japanese tokenizer import.
There was a RuntimeError
`Failed initializing MeCab.`
that was blocking the build and at the moment we are not working with Japanese texts.
