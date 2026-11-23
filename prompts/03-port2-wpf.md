# Port II: WPF.

```text
Read CHANGE_REQUEST.md. Migrate the app: (1) Move all business logic out of the WinForms code-behind (loading/saving ledger.xml, the personal-best rule, CSV export) into PrTracker.Core so that every test in PrTracker.Core.Tests passes. Do not change the tests. (2) Build PrTracker.Wpf with MVVM using CommunityToolkit.Mvvm: a DataGrid of records with personal bests highlighted, Add/Edit/Delete, Export. (3) Point PrTracker.Ledger (WinForms) at PrTracker.Core as well. Run the tests and both apps' builds. Then run the WPF app and check it with the winapp CLI (start with `winapp ui --help`): add a record through the UI, confirm it appears and is highlighted if it is a personal best, and save a screenshot to verify/wpf.png. Fix what you find and check again, then close the app.
```
