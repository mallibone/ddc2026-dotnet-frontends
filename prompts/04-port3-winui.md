# Port III: WinUI.

```text
Read CHANGE_REQUEST.md. Port the WPF UI of PrTracker.Wpf to WinUI in PrTracker.WinUI (Windows App SDK, Microsoft.UI.Xaml namespaces only). Reuse PrTracker.Core and port the ViewModels. Fluent design: Mica backdrop, a records list with personal bests highlighted, add/edit in a ContentDialog, Export. Use x:Bind. Build and fix errors. Then start it with `winapp run .` and check your work with the winapp CLI (`winapp ui --help`, `winapp devtools --help`): add a record through the ContentDialog, confirm it appears and is highlighted if it is a personal best, and save a screenshot to verify/winui.png. Fix what you find and check again, then close the app.
```
