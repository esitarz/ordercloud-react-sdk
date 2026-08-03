## Unreleased

### Feat

- **peers**: expand `react` and `react-dom` peer ranges to `^18.3.1 || ^19.0.0` while retaining React 18.3.1 support

### Fix

- **provider**: register Axios request interceptors with effect cleanup so StrictMode mount/unmount/remount does not leave duplicate interceptors
- **useAuthMutation**: invoke the provided `onError` callback instead of returning the function reference

## 0.2.5 (2025-04-04)

### Refactor

- **provider**: `scope` and `customScope` are now optional for the OrderCloudProvider

## 0.2.4 (2025-04-01)

### Fix

- **query.ts,-package.json**: removes a package that causes build errors in accelerator

## 0.2.3 (2025-03-28)

### Fix

- **gh-actions**: bug fix that ensures build before publish

## 0.2.2 (2025-03-28)

### Fix

- **provider**: explicitly set a return type

## 0.2.0 (2025-02-12)
