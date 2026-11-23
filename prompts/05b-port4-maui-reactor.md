# Port IV, variant B: .NET MAUI with MauiReactor, pure C#. Uses DevFlow.

```text
Ticket PRT-104, PR Tracker on phones: the app has to be on the lifters' phones. Lifters log their lifts in the gym, not at a desk: the Ledger as a phone app (.NET MAUI, Android first). A list of the lifts with each exercise's personal best marked, a page to add and edit a lift, swipe to delete. Same rules, same PrTracker.Core, unchanged. Build the ledger for phones in PrTracker.Maui.Reactor using MauiReactor, pure C#, no XAML: a records list with personal bests marked, an add/edit page, swipe to delete. Reuse PrTracker.Core unchanged. Run it on the Android emulator. Then use the DevFlow tools to verify your work: add a record through the UI, confirm it appears and is marked if it is a personal best, take a screenshot. Fix anything you find and verify again.
```
