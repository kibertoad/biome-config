# `@kibertoad/biome-config`

ToadStack config for Biome

## Getting started

1. Install required dependencies

   ```sh
   npm install --save-dev @biomejs/biome @kibertoad/biome-config
   ```

2. Create a `biome.json` configuration file

   ```json
   {
     "$schema": "./node_modules/@biomejs/biome/configuration_schema.json",
     "extends": ["./node_modules/@kibertoad/biome-config/configs/biome-package.json"]
   }
   ```
