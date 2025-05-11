# @octomatize/tsconfig

A collection of TypeScript configuration presets for different project types.

## Installation

```bash
npm install --save-dev @octomatize/tsconfig

# or using pnpm
pnpm add -D @octomatize/tsconfig
```

## Available Configurations

This package provides the following TypeScript configuration presets:

- `library.json` - Configuration for TypeScript libraries
- `next.json` - Configuration for Next.js projects
- `node.json` - Configuration for Node.js projects

## Usage

To use these configurations, extend them in your `tsconfig.json`:

### For Libraries
```json
{
  "extends": "@octomatize/tsconfig/library.json"
}
```

### For Next.js Projects
```json
{
  "extends": "@octomatize/tsconfig/next.json"
}
```

### For Node.js Projects
```json
{
  "extends": "@octomatize/tsconfig/node.json"
}
```

## License

MIT
