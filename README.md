# Plug Key + Independent Plug Protocol (IPP)

**Owner:** Carlos "LowC" Rodrigues (`xxlowcxx`)  
**Family:** Toolaid / T00l-AID  
**Status:** published start — 2026-09-29  
**Rule:** IPP is the language. Plug Key is the USB that speaks it.

This repo exists so the invention is on the record. Exact revival timings stay off this page on purpose.

## What Plug Key is

A USB device that communicates by **how many times it is inserted and removed, and the timing between those events**.

It is not a password file on a stick. It is a physical language plus the presence of the person performing it.

### Origin (the two-key ritual)

Some hosts want **two** physical USB keys to create one security key.

Plug Key was invented to do that job with **one** stick:

1. Create the first key on the stick (A-mode).
2. **Double-plug** to flip the same stick into **B-mode**.
3. Record the second key on that same stick.
4. The host believes two separate USB keys were used.

One piece of plastic. Two births. IPP is the command set that makes the flip and the record mean something.

## What IPP is

**Independent Plug Protocol** — the language and the command set that Plug Key promotes and evolves.

IPP words are not packets on the USB data pipe first. IPP words are:

- insert
- hold
- remove
- gap
- double-seat (B-mode flip)
- confirm cadence

The protocol can evolve without throwing the stick away. New commands are new dances, not new hardware SKUs.

## Why this is a security element

A cloned disk can copy secrets. It cannot copy **hands in time** unless a body is there.

Plug Key adds **user presence**: the operator must perform IPP. That factor still works when:

- the OS is compromised
- the network is dead
- the box is offline
- you do not trust the running system to judge a password file

The interpreter should not live in the sick OS. Early boot, a tiny watcher, or logic on the key itself judges the dance.

## Emergency and system revival

Same stick. Different IPP sentences. Different modes:

| Mode | Job |
|------|-----|
| A | mint / first identity |
| B | second identity after double-plug |
| R | revival — known-good profile, trusted store, local shell |
| X | emergency — network stays dark, only local recovery |

Revival software is the listener that maps a valid IPP sentence onto an action **on machines we own**: unlock a sidecar, boot a rescue stanza, open a sealed vault, refuse the compromised desktop.

Exact sentence timings are not published here.

## What this repo will grow into

- `docs/PROTOCOL.md` — alphabet (no secret cadences)
- `docs/REVIVAL.md` — emergency / offline revival intent
- `docs/ORIGIN.md` — two-key ritual
- decoder stub that only logs insert/remove timestamps

Sister projects (separate repos): Ventoy-MobileSandbox, PhoenixWrap, Hand-0f-G0d, AgentSmith, T00L-AID.

## License / claim

Toolaid original. LowC idea. Do not rename this into a generic "USB auth token." It is IPP spoken by Plug Key.
