# calculator_frontend

This container currently contains only environment configuration (`.env`) and **does not yet include a React application scaffold** (no `package.json`, `src/`, ESLint config, etc.). As a result, static analysis (linting/typecheck) cannot be executed meaningfully.

## Expected static analysis commands (once the React project exists)

After the React app is created/restored in this directory:

1. Install dependencies:

```bash
npm ci
```

2. Run linting:

```bash
npm run lint
```

3. Run typechecking (if TypeScript is used):

```bash
npm run typecheck
```

## Recommended next step

Generate or restore a standard React project structure in this directory (e.g., Vite or Create React App), including:
- `package.json`
- `src/`
- ESLint configuration (`eslint.config.*` or `.eslintrc.*`)
- (Optional) TypeScript config (`tsconfig.json`) if using TS
- `npm` scripts for `lint` and `typecheck`

Once those exist, static analysis can be run and concrete findings/fixes can be produced.
