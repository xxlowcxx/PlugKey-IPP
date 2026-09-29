# Independent Plug Protocol (IPP)

IPP is the language and command set that Plug Key promotes and evolves.

## Primitives

- INSERT — seat the key
- HOLD — leave it seated for a measured span
- REMOVE — pull the key
- GAP — time between events
- DOUBLE — remove and reseat as one flip command (B-mode)
- CADENCE — a counted sequence of the above

A command is a cadence, not a USB payload. Payloads can come later. The language starts in the hands.

## Evolution

IPP can gain new commands without a new SKU. Old cadences stay valid. New cadences add modes (revival, emergency, confirm).

Do not publish operational timings in this file. Timings are per-operator and live off-repo or in a sealed vault.

## Decoder rule

The judge of a cadence must not be a compromised OS. Prefer:

- early-boot listener
- tiny watcher on the key
- isolated rescue environment

A sick desktop may log USB events. It does not get to decide if revival opens.
