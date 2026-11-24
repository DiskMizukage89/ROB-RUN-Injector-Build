# ROB RUN Injector Build

Download: soon

An injector around the internal module, for players who want the in-process version.

## What it does

Waits for the client, allocates, maps the module, calls its entry. A status window reports each stage: waiting, opening handle, allocated, mapped, entry returned.

## Start

1. Extract, run `injector.exe` as administrator
2. Start ROB RUN while the launcher login is still open
3. Inject
4. INSERT in game

## Trouble matrix

| Stage stuck | Reason |
| --- | --- |
| waiting | client not started |
| handle | missing admin |
| mapped but no menu | build does not match the patch |

## Notes

Internal modules die with a game crash, that is normal. Do not inject twice.

Windows 10/11, Steam, EAC.
