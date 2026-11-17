# Word-art attribution

- Style: children's picture-book soft clay / needle-felt (transparent background).
- Stills: 1,201 WebP illustrations at `still/<stem>.webp` (`512×512` transparent canvas; includes 14 curriculum-aligned felt illustrations newly crafted for age appropriateness, semantic clarity, and unified wool-felt style across `smoke`, `operate`, `hunt`, `fight`, `marry`, `firecracker`, `call`, `drive`, `flying`, `alone`, `bee`, `bird`, `rabbit`, and `sheep`, plus clean edge matting across all entries).
- Curated Frame Animations: 72 single-subject felt animations at `anim/<stem>.webp` (8-bit alpha Animated WebP) with transparent fallback GIFs at `gif/<stem>.gif`. Each animated entry shares an identical first-frame composition with `still/<stem>.webp` for zero-jump playback.
- Gentle Motion Fallback: Words without frame animation use gentle CSS picture-book paper-puppet motion (`hop`, `sway`, `nod`, `float`, `tremble`, `pop`) in `WordArt.tsx`, respecting `prefers-reduced-motion`.
- Generated and refined via `scripts/refine-word-art.py` for happyKey lingo. No API keys, tokens, or generation endpoints are stored in this repository.
