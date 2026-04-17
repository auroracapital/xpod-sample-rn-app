# xpod-sample-rn-app

A minimal React Native + Expo template, ready to build on **[xpod.run](https://xpod.run)** — the cloud build service for React Native.

## Build it on xPod in 3 steps

1. **Install the CLI**
   ```bash
   npx xpod login
   ```

2. **Submit a build**
   ```bash
   npx xpod build --platform android --profile preview
   ```

3. **Download the artifact**
   xPod will email you when the build finishes, or watch the live log stream at https://xpod.run/builds.

## Why this template?

- Expo blank-typescript — minimal surface area, no native modules
- No env vars required — builds out of the box on xPod
- Pinned dependencies — reproducible builds

## Local development (optional)

```bash
npm install
npx expo start
```

## License

MIT — fork it, use it, ship it.
