# Chess Opening Trainer

## Project
- A personal chess opening trainer inspired by ChessReps.
- Mobile-first PWA, tested at a 390px width.

## Zero cost
- No backend, no paid services or APIs.
- All user data is stored locally in IndexedDB, with PGN/JSON export for backup.

## Stack
- Vite + React + TypeScript
- chessground (board)
- chess.js (rules)
- ts-fsrs (spaced repetition)
- Dexie (IndexedDB)
- Lichess Opening Explorer API for human move frequencies

## Spec
- SPEC.md, written in Phase 0 from REA recon, is the source of truth for behavior.
- Never copy ChessReps code, course content or assets.

## Lichess token
- The token is never bundled into the build.
- The app reads it from a Settings field and stores it in IndexedDB on the device.
- `.env` is for local development only and must never be read by client code in production builds.

## Workflow
- One phase per session.
- Commit at the end of each phase with a clear message.

## Hosting
- GitHub Pages.

## Secrets
- Never commit secrets.
