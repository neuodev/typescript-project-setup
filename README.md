# Typescript Setup

This repo is part of [YouTube Tutorial](https://www.youtube.com/watch?v=-Uo5ahVrZ_E)

[![How To Setup a TS project](https://i.ytimg.com/vi/-Uo5ahVrZ_E/hqdefault.jpg?s…AFwAcABBg==&rs=AOn4CLCbJfmRY8N-loO0r0RJqvEuMbURTw)](https://www.youtube.com/watch?v=-Uo5ahVrZ_E&t=208s)

1. Initalize NPM
   ```bash
   npm init
   ```
2. Install TS

   ```bash
   npm i typescript --save-dev
   ```

3. Initalize the porject

   ```bash
   npx tsc --init
   ```

4. Compile TS to JS

   ```bash
   npx tsc
   ```

   - you can use `npx tsc -W` to watch for code changes
   - Create `src` and `dist` folders

5. Download `ts-node-dev`

   ```bash
   npm i ts-node-dev --save-dev
   ```

6. Add new Script to your `package.json`

   ```bash
   ts-node-dev --respawn src/index.ts
   ```
