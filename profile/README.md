# Little brains in every product.

European AI lab building small, opinionated on-device models.

Every model is free up to 100k monthly active devices per SDK. Unlimited inference per user.

Drop-in SDKs for iOS, Android, Web, and Node, with open weights on [Hugging Face](https://huggingface.co/desert-ant-labs).

<!-- models:start -->
| Model | What it does | Platform | Docs |
| --- | --- | --- | --- |
| **Align** | Word-timestamp refinement for Apple's SpeechAnalyzer pipeline. | Apple | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/align.md) |
| **Clear** | On-device speech enhancement: denoise, dereverb, and loudness-normalize. | Apple · Android · Linux · Windows · Web · Node | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/clear.md) |
| **Clips** | On-device clip selection: a transcript's best non-overlapping moments, ranked. | Apple · Linux · Windows | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/clips.md) |
| **Ear** | On-device spoken language identification across 99 languages. | Apple · Android · Linux · Windows · Web · Node | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/ear.md) |
| **Emo** | Multilingual on-device emoji suggestion. | Apple · Android · Linux · Windows · Web · Node | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/emo.md) |
| **Gist** | Multilingual on-device content topic tagging across a 36-topic taxonomy. | Apple · Android · Linux · Windows · Web · Node | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/gist.md) |
| **Redact** | Multilingual on-device PII detection and redaction. | Apple · Android · Linux · Windows · Web · Node | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/redact.md) |
| **Shapes** | On-device single-stroke shape recognition. | Apple · Android · Linux · Windows · Web · Node | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/shapes.md) |
| **Title** | On-device titles and descriptions: a short factual title and a one- to two-sentence description for any passage of text. | Apple | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/title.md) |
| **Tongue** | On-device language identification for short text across 84 languages. | Apple · Android · Linux · Windows · Web · Node | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/tongue.md) |
| **Uhm** | On-device filler-word detection: frame-precise "uh"/"um"/"hmm" spans. | Apple | [docs](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/uhm.md) |

### In closed beta

Weights exist and the models work, but no SDK ships them yet, so there is
nothing to install today. Ask us if you want early access.

| Model | What it does |
| --- | --- |
| **Eye** | On-device frame scoring: which shot to keep from a burst or a clip. |
| **Face** | On-device face matching across a photo library or through a video. |
| **Moderator** | On-device NSFW image detection, trained only on licensed and synthetic data. |
| **Schemer** | On-device structured extraction into a caller-supplied JSON schema. |
| **Toxic** | On-device hate-speech triage for European languages. |
| **Who** | On-device speaker labeling: per-person turns with timestamps. |
<!-- models:end -->

## Links

- [All SDKs on GitHub](https://github.com/orgs/Desert-Ant-Labs/repositories)
- [Models on Hugging Face](https://huggingface.co/desert-ant-labs)
- [Website](https://desertant.com)
- [License](https://license.desertant.com)
- Commercial licensing: [licensing@desertant.com](mailto:licensing@desertant.com)
- Request early access: [contact@desertant.com](mailto:contact@desertant.com)
