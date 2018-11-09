# Example Rift mod

This repository contains a minimal Rift project. It's sole purpose is being copied to quickly start a new project. 

## Files to change
- `build.gradle`
- `src/main/resources/riftmod.json`
- `src/main/resources/pack.mcmeta`
- this readme

## Requirements:
- OpenJDK 8 or higher

## Tasks
- Development:
    ```sh
    ./gradlew setupDevWorkspace [eclipse,idea]
    ```
    After this, import in your IDE as Gradle project.

- Build:
    ```sh
    ./gradlew build
    ```

