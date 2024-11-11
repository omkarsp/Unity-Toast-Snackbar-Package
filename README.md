# Unity Toast Snackbar Package

A Unity package for displaying Toast messages on Android and Snackbar notifications on iOS.

## Installation

### Using Git URL (Recommended)
1. Open Unity Package Manager
2. Click + button in the top-left corner
3. Select "Add package from git URL"
4. Enter: `https://github.com/YOUR_USERNAME/Unity-Toast-Snackbar-Package.git`

### Manual Installation
1. Download this repository
2. Extract into your Unity project's Assets folder

## Usage
```csharp
// Show a message
ToastSnackbarManager.Instance.ShowMessage("Hello World!");
```

## Testing
1. Open Unity Test Runner (Window → General → Test Runner)
2. Select PlayMode tab
3. Click "Run All"

## Requirements
- Android: API Level 19+
- iOS: iOS 11.0+

## Demo Scene
Check the Samples folder for usage examples.

## License
[MIT License](LICENSE)
