# OverCue releases

Public distribution channel for OverCue. Nothing here is edited by hand; every
file is written by the release automation in the private source repositories.

- `app/latest.json` is read by the OverCue V2 in-app updater.
- `app/current.json` is read by overcue.gg's download page.
- `firmware/stable.json` and `firmware/beta.json` are read by OverCue V2's
  firmware page and by overcue.gg.
- Installers and firmware images are attached to the releases of this
  repository. Every file has a SHA-256 in the channel that points at it.

Source, issues, and contributions live in the private repositories of the
OverCue-gg organisation.
