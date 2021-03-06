# FishNet.CodeAnalysis
 
A set of annotations, Roslyn analyzers & source generators for Fish-Networking (https://github.com/FirstGearGames/FishNet).

## Analyzers' Requirements

- Unity 2020 or later

## Source Generators' Requirements

- Unity 2021 or later

## Installing The Analyzers

1. Download the latest release
2. Extract the downloaded archive
3. Copy the extracted files to a folder inside your `Assets` folder

## Installing The Source Generators

- TBA

## Included Analyzers

- `DontDestroyOnLoadUsageAnalyzer` → Detects invalid usage of `Object.DontDestroyOnLoad` on `NetworkObject`s and `NetworkBehaviour`s
- `NetworkBehaviourCallbackBaseMethodCallAnalyzer` → Detects missing and unordered calls to the base method of `NetworkBehaviour` callbacks
- `NetworkBehaviourConstructorAnalyzer` → Detects `NetworkBehaviour` constructors
- `PreventUsageInsideAnalyzer` → Prevents fields/properties/methods annotated with `PreventUsageInsideAttribute` from being used inside invalid methods
- `RemoteProcedureCallAnalyzer` → Prevents RPCs (`ServerRpc`/`ObserversRpc`/`TargetRpc`) from calling `base` RPC methods

## Included Source Generators

- TBA
