# tcc_aidispatch companion -- releases

Distribution point for the `tcc_aidispatch` companion app: a small Windows program that
captures real microphone audio for voice features in `tcc_aidispatch` (AI dispatch radio) and
`tcc_ainpc` (voice-conversational NPCs), since FXServer's own NUI layer can't do this
reliably. See the [Releases](../../releases) page for downloads.

Source lives in the private `tcc-aicompanion-dev` repo. This repo is deliberately separate
(and public) so the app's own update check -- and anyone downloading it to play -- never needs
access to the private resource repos it's used alongside.

## Running it

1. Download the latest `tcc_aidispatch_companion.exe` from [Releases](../../releases).
2. Run it. A console window opens and stays open -- that's normal, it's the app running.
   Leave it open while you play; close the window to stop it.
3. Windows may ask for microphone/firewall permission the first time -- allow both (the
   firewall prompt is just for the loopback-only local server, not internet access).
