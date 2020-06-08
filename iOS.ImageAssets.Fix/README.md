# iOS.ImageAssets.Fix

## Integration

1. Copy file `iOS.ImageAssets.Fix.targets` to the root of your iOS executable project.
2. Add `<Import Project="iOS.ImageAssets.Fix.targets" />` to the very end executable project file (e.g. `MainApp.iOS.csproj`).
3. (Optional) Add `.generated/` to your gitignore

## Limitations
1. Tested only on environment below
2. All assets and catalogs in solution must have unique names (create your own naming convention).

## Environment
- Mac OS X 10.15.4
- Xamarin.iOS 13.18.2.1
- Xcode 11.5

