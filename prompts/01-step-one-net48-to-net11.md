# Step One: .NET Framework 4.8 to .NET 11 (WinForms). Agent mode, any IDE.

```text
Migrate PrTracker.Ledger from .NET Framework 4.8 to .NET 11. It is a Windows Forms app with an old-style project file and packages.config. Convert it to an SDK-style project targeting net11.0-windows with UseWindowsForms, move the packages to PackageReference, and replace any API that does not work on .NET 11. Keep behaviour and layout identical: no new features, no nullable, no refactoring. Build until there are zero errors, then start the app once to confirm it boots and close it. Do no other checks or verification: no UI automation, no screenshots, no test scripts, no notes files. Commit when you are done. Do not ask me questions.
```
