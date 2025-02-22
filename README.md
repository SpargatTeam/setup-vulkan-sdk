# Setup Vulkan SDK

## Made by SpargatTeam for help BlockmanLORD production for Vulkan.

## Latest release

![GitHub release (latest by date)](https://img.shields.io/github/v/release/SpargatTeam/setup-vulkan-sdk)

## You can see the extension on Marketplace <a>https://github.com/marketplace/actions/setup-vulkan-sdk-multiplatform</a>

## Usage example

``` yaml
      - name: Setup Vulkan SDK # action name
        uses: SpargatTeam/setup-vulkan-sdk@v1.0.0
        with:
          version: '1.3.296.0'  # Vulkan SDK version you want
          components: 'Vulkan-Headers,Vulkan-Loader'  # Vulkan components you need
          cache: 'true'  # Vulkan Cache
```

## Working perfect for Linux and Windows, good for macos but no components extra
