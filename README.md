# PaceSnap voices

Voice model files that the PaceSnap app downloads once on first start, so the
coach can speak offline on the device.

## Contents (release `supertonic-3-int8`)

The int8-quantized **Supertonic 3** text-to-speech model by Supertone Inc., as
packaged by [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)
(`sherpa-onnx-supertonic-3-tts-int8-2026-05-11`), redistributed unmodified.

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| duration_predictor.int8.onnx | 3700147 | c3eb91414d5ff8a7a239b7fe9e34e7e2bf8a8140d8375ffb14718b1c639325db |
| text_encoder.int8.onnx | 36416150 | c7befd5ea8c3119769e8a6c1486c4edc6a3bc8365c67621c881bbb774b9902ff |
| vector_estimator.int8.onnx | 78400833 | 20cd86fa5c6effedfda0e7cffe5b0569ca401c440a0c3a1d72bf39286c0db3fd |
| vocoder.int8.onnx | 25991073 | e923d60f53f95eb1ce235f1dc33ec56d9c057823c96fa6f8acf98f32b0da6152 |
| tts.json | 8253 | 42078d3aef1cd43ab43021f3c54f47d2d75ceb4e75f627f118890128b06a0d09 |
| unicode_indexer.bin | 262144 | 8402ca48e5189a8950138580b0fff64db6f072f24ac07cd54ba8b2fbb9883b30 |
| voice.bin | 517168 | 67d5209b0ee8ce6c74105ffbe12fe6a7628aea3b4ba2fcb308a4a67938a93ce8 |

## License

The model is licensed under the **BigScience Open RAIL-M License**
([LICENSE-MODEL](LICENSE-MODEL), from
[Supertone/supertonic-3](https://huggingface.co/Supertone/supertonic-3)),
including its use-based restrictions (Attachment A), which apply to anyone
using these files. The accompanying Supertonic sample code is MIT-licensed
([LICENSE-CODE-MIT](LICENSE-CODE-MIT)).
