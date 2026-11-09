# Scene demo art and audio attribution

## Pictures and animation
- Style: children's picture-book soft clay / needle-felt look.
- Stills generated with `gpt-image-2.6-sunburst` via an OpenAI-compatible gateway (`/v1/images/generations` for masters and scene/reward art, `/v1/images/edits` for action frames).
- Animations are **post-processed composites** of those stills (cutouts aligned on a shared canvas → short loop as animated WebP + GIF fallback). They are not native model GIF output.
- Bee, bird, frog, rabbit and sheep loops each use a master still plus one or two action poses (frog jump uses a dedicated leaping pose). No crossfade is used, to avoid ghosting.
- Meadow background and completion medal are also model-generated stills, compressed locally to WebP.
- No API keys are stored in this repository or the frontend bundle.

## Speech
- English word, slow-word, sentence and letter-name clips: synthesized with [edge-tts](https://github.com/rany2/edge-tts) using Microsoft `en-US-AnaNeural`.
- Chinese encouragement clips: synthesized with edge-tts using Microsoft `zh-CN-XiaoxiaoNeural`.
- Example sentences: "A bee can fly.", "A bird can sing.", "A frog can jump.", "A rabbit can hop.", "A sheep can eat grass."
- No third-party animal sound effects are bundled (license of stock cries was not verified, so they were omitted).
