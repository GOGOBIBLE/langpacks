# GoGoBible language packs

Offline speech-recognition models that GoGoBible apps download when a child picks a language
other than English or Korean. Speech is recognised on the device; no audio leaves the phone.

Files are on the [Releases](../../releases) page, one zip per language (`<lang>-v1.zip`).
Each zip holds the unmodified Vosk model under `asr/`, plus `bundle.json`, `SOURCE.txt` (model name, version and
original download URL), `NOTICE.txt` and `LICENSE-APACHE-2.0.txt`.

| File | Language | Model | Original source |
|---|---|---|---|
| es-v1.zip | Spanish | vosk-model-small-es-0.42 | https://alphacephei.com/vosk/models/vosk-model-small-es-0.42.zip |
| pt-v1.zip | Portuguese | vosk-model-small-pt-0.3 | https://alphacephei.com/vosk/models/vosk-model-small-pt-0.3.zip |
| zh-v1.zip | Chinese | vosk-model-small-cn-0.22 | https://alphacephei.com/vosk/models/vosk-model-small-cn-0.22.zip |
| ja-v1.zip | Japanese | vosk-model-small-ja-0.22 | https://alphacephei.com/vosk/models/vosk-model-small-ja-0.22.zip |
| fr-v1.zip | French | vosk-model-small-fr-0.22 | https://alphacephei.com/vosk/models/vosk-model-small-fr-0.22.zip |
| de-v1.zip | German | vosk-model-small-de-0.15 | https://alphacephei.com/vosk/models/vosk-model-small-de-0.15.zip |
| ru-v1.zip | Russian | vosk-model-small-ru-0.22 | https://alphacephei.com/vosk/models/vosk-model-small-ru-0.22.zip |
| hi-v1.zip | Hindi | vosk-model-small-hi-0.22 | https://alphacephei.com/vosk/models/vosk-model-small-hi-0.22.zip |

## License
The models are by Alpha Cephei Inc. (https://alphacephei.com/vosk/models) and are licensed
under the Apache License 2.0 — see [LICENSE](LICENSE) and [NOTICE](NOTICE).
