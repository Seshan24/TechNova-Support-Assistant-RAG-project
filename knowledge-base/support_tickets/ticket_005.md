# Support Ticket #005

**Status:** Resolved
**Date opened:** 2024-08-14
**Date closed:** 2024-08-16
**Product:** Nova Tablet 11
**Category:** Software / Stylus

## Customer Issue
Customer reported that their Nova Pen 2 stylus suddenly stopped working with their Nova Tablet 11 after a recent NovaOS Tab 3 update. The pen showed in Bluetooth settings but pressure sensitivity didn't work in any app.

## Diagnosis
This was a known issue with NovaOS Tab 3 version 3.4.1 that affected a subset of stylus drivers. A hotfix (3.4.2) had been released 2 days prior.

## Resolution
Walked customer through manually checking for updates (Settings > System > Software Update > Check Now). After installing 3.4.2 and restarting both the tablet and pen, full functionality returned.

## Notes
The 3.4.1 stylus regression had ~3,400 affected users. Engineering is adding stylus driver regression tests to the CI pipeline. Consider adding a banner notification in the Nova Pen app when a known stylus-related issue exists.
