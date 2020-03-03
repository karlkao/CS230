This folder forks repositories from third party.

[init]
The way to add these third-party repos into ./third-party folder.

git submodule add https://github.com/karlkao/DeepSpeech.git DeepSpeech
git submodule add https://github.com/karlkao/FFmpeg.git FFmpeg
git submodule add https://github.com/karlkao/py-webrtcvad.git py-webrtcvad
git submodule add https://github.com/karlkao/NeMo.git NeMo
git submodule update --init --recursive
