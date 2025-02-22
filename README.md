# Setup Vulkan SDK

## Made by SpargatTeam for help BlockmanLORD production for Vulkan.

## Latest release

![GitHub release (latest by date)](https://img.shields.io/github/v/release/SpargatTeam/setup-vulkan-sdk)

### Usage example

``` yaml
      - name: Setup Vulkan SDK # action name
        uses: SpargatTeam/setup-vulkan-sdk@main
        with:
          version: '1.3.296.0'  # Vulkan SDK version you want
          components: 'Vulkan-Headers,Vulkan-Loader'  # Vulkan components you need
          cache: 'true'  # Vulkan Cache
```

### Working perfect for Linux and Windows, good for macos but no components extra