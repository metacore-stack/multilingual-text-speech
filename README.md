
# EchoCanvas: Multilingual Text-to-Speech Studio

EchoCanvas turns any block of text into expressive audio with a polished Next.js interface. Generate previews instantly, fine-tune voice traits, and export clips ready for podcasts, voice-overs, and accessibility workflows.

## Highlights
- Real-time speech synthesis backed by the Web Speech API
- Responsive, keyboard-friendly controls optimized for rapid iteration
- Voice presets with adjustable rate, pitch, and language selections
- Persistent session history so you can revisit prior renders

## Quick Start
```bash
yarn install
yarn dev
```

Launch the playground at `http://localhost:3000`, enter text, choose a voice preset, then press `Speak` to hear the output. Use `Download` to save the generated audio locally.

## Configuration
- Update default presets in `components/WebApi.tsx`
- Customize appearance in `styles/globals.css` or via Tailwind config
- Set environment-specific options in `next.config.js`

## Tech Stack
- Next.js for the application shell and routing
- React hooks for stateful UI interactions
- Tailwind CSS for rapid, consistent styling
- TypeScript for type-safe component authoring

## Roadmap Ideas
- Offline synthesis fallback using local models
- Batch rendering for long-form scripts
- Clip library with tagging and search

## Contributing
Pull requests are welcome. For substantial changes, please open an issue first to discuss your ideas and align on scope.
