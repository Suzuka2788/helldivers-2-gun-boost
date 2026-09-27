# Suzuka‘s Gun Boost v1.0.0

[Download v1.0.0](https://github.com/Suzuka2788/helldivers-2-gun-boost/releases/tag/v1.0.0)

Requires **Bingus Shared Loader v15+ / API 1**.

## Features

- Eight SMGs and thirteen assault rifles: ballistic direct-hit normal damage +20%, rounded to the nearest ten; durable damage keeps the original +20% integer values.
- P-92 Warrant: magazine 13 → 33 rounds; fire rate 450 → 900 RPM.
- P-2 Peacemaker: automatic fire and 900 → 640 RPM; the original 15-round magazine is unchanged.
- SMG-32 Reprimand: one-handed permission and PDW grip.

SMGs: Defender, Pummeler, Reprimand, Knight, M7S, StA-11, Gallant, and Stoker ballistic fire. Rifles: AR-11, AR-2, AR-23, AR-23A, AR-23C, AR-23P, AR-32, AR-59, AR-61, AR/GL-21, BR-14, MA5C, and StA-52.

## Install

Quit the game, disable previous Gun Boost / ballistic boost and the separate SMG, rifle, P-92, and P-2 packages. Import `Suzukas-Gun-Boost-v1.0.0.zip`, enable it with Bingus Shared Loader, deploy and restart. Do not run older packages alongside this release.

## Verification and limitations

Offline tests passed for packaging, accepted/rejected game versions, damage write/restore, equipment location and one-handed write/restore. Previous runtime logs confirmed rifle and pistol writes and the Reprimand equipment patch. SMG writes after the version-gate fix and actual gameplay damage/animations still require in-game confirmation. Changed or ambiguous records stop writes.

AR-11 bullet identification is inferred. Shared damage records also affect AR-23 Guard Dog attacks and potentially other consumers. Underbarrel weapons, explosions, burning and Stoker flame damage are outside the intended edits.

## Logs

`%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs`:

- `SuzukaSMGFamilyAdaptive.log`: successful damage writes=7.
- `SuzukaARFamilyAdaptive.log`: successful damage writes=11.
- `SuzukaP92WarrantBoost.log` and `SuzukaP2PeacemakerBoost.log`: pistol patch statuses.
- `SuzukaSMG32OneHanded.log`: one-handed/grip writes=2.

## Credits

[Bingus Shared Loader](https://github.com/CowboyBingus/BingusSharedLoader) and [FileDiver](https://github.com/xypwn/filediver).

This repository contains release documentation and the mod ZIP as a Release asset; the automatic Source code archives do not contain the local build tools.
