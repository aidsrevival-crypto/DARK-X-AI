# DARK X AI

DARK X AI is a mobile-first AI workspace built with Expo and React Native. The project archive contains the application UI, server-side orchestration, authentication scaffolding, conversation persistence, approved-agent registry, live Tavily search integration, and the DARK X AI midnight-console visual system.

## Validation

The repaired source passes TypeScript validation, the unit test suite (with optional credential-dependent tests skipped when secrets are absent), the server production build, lint, and Git whitespace checks. The web export remains environment-sensitive because Metro may fail to hash a generated `react-native-css-interop` cache file; native Android/iOS builds should be run in the project’s configured Expo environment.

## Source archive

The complete source is stored in `dark-x-ai.zip`. Extract it, install dependencies with `pnpm install --frozen-lockfile`, and use the scripts in `package.json` for checking, testing, linting, building, and running the application.
