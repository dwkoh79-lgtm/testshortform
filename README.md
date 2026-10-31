# 니가타 료칸의 겨울 — HyperFrames 라인 드로잉 영상

30초, 1920×1080, 30fps. 눈 내리는 니가타 료칸과 노천탕을 먹선 라인 드로잉으로 그린 젠 스타일 영상.

- 웹: https://dwkoh79-lgtm.github.io/testshortform/
- 완성본(음악 포함): `niigata-ryokan-v3.mp4`
- HyperFrames 프로젝트: `project/` (장면 `project/compositions/ryokan.html`, 루트 `project/index.html`)
- 음악: `project/assets/bgm/track.wav` — Python으로 합성한 고토(미야코부시 음계) + 저음 드론 + 잔향, -16 LUFS 정규화

```bash
cd project && npx hyperframes preview
npx hyperframes render
```
