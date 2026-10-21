<div align="center">
  <img src="assets/lord-veyra.png" alt="Lord Veyra blue crown" width="144" height="144">
  <h1>Lord Veyra</h1>
  <p><strong>Your space. Your sessions. Your identity.</strong></p>
  <p>A Windows activity launcher with a personal library, session cards, and the Lord Veyra and Veyra Galaxy visual identities.</p>
  <p><a href="https://github.com/LOoOrds/Lord-Veyra/releases"><strong>View releases</strong></a> · <a href="#getting-started">Getting started</a> · <a href="#automatic-updates">Updates</a> · <a href="README.ar.md">العربية</a></p>
  <p>Windows 10 / 11 · x64 · Internet connection and an active account required</p>
</div>

---

## Official distribution

This is the official public download and user-guide repository for **Lord Veyra**, maintained by **Lords**. It contains documentation, brand images, and published installer releases. Application source code and administration tools are not hosted here.

**The first public Setup has not been published yet.** When it is ready, its version, download, and installation notes will appear on the [Releases page](https://github.com/LOoOrds/Lord-Veyra/releases). The guide below describes the application's supported workflow; it does not announce an available installer.

## Made for your sessions

| | What you can do |
|---|---|
| **Discover** | Search the game catalog, review available launch choices, and add games to your library. |
| **Launch** | Choose explicitly between **Normal**, **Local**, and **RPC Call**, where supported. The available choices depend on the selected game. |
| **Keep track** | Use floating session cards, see your active sessions, and review your account's recorded activity in Profile. |
| **Make it yours** | Switch between **Lord Veyra** and **Veyra Galaxy**, choose a gallery size, and use Full or Reduced Motion. |
| **Personalize** | Update your display name and cropped profile image, with a frame that follows your theme. |

## Getting started

1. Obtain your account credentials from Lords. There is no public account-registration form.
2. Download the published **Setup.exe** from this repository's Releases page when available.
3. Run Setup, choose the recommended location or an empty custom folder, and finish installation. Setup can provision Microsoft WebView2 Runtime when it is missing; this step requires internet access.
4. Select **Launch Veyra**, then sign in with your username or email and password. **Remember me** is optional.
5. Open **Add**, search for a supported game, and add it to **Library**. Select **Play** and choose the available launch method you intend to use.

The normal installation does not require a development environment or a separate application-data download.

## Accounts and devices

- An active subscription and ongoing internet access are required.
- The first eligible sign-in links an account to its Windows device. Logging out or uninstalling does not clear that link. Contact Lords if a device reset is needed.
- Account creation, subscription changes, and device resets are managed by Lords. End users do not need the private administration website.
- Remembered sign-in is protected locally by Windows and is still checked online.

## Sessions and Profile

The simultaneous-session limit defaults to **3** and can be set from **1 to 10** in Settings. At most one RPC Call session can run at a time. Lowering the limit keeps existing sessions alive and blocks additional launches until capacity is available.

Closing the main window hides Lord Veyra to the system tray. **End Session** stops the selected session; **Quit Veyra** stops Veyra's active sessions and exits. A completed on-screen 15-minute timer does not automatically end a session.

Profile shows your account, subscription, active device, and recorded game-session history. Session time is a record of tool activity; it is not a guarantee of in-game play time or external quest completion.

## Automatic updates

Eligible installed copies check for deliberately published application updates at authorized startup and during their existing periodic account checks. Uploading a Setup to GitHub is separate from activating an in-app update.

If a newer signed update is available at startup, Lord Veyra shows its download, verification, and installation flow. During use, an update can download in the background; the update offer allows **Update now** or **Later**. Installation waits for active and pending sessions to finish. The exact behavior is described in each published release's notes.

Existing Setup downloads do not rewrite themselves. Use the latest published Setup for a new installation.

## Requirements and installation notes

- Windows 10 or Windows 11, **64-bit**.
- A working internet connection and credentials issued by Lords.
- Microsoft WebView2 Runtime for the application; Setup handles provisioning when required.
- A writable installation folder. The recommended installation is per Windows user; custom installation requires an empty local folder.

The current development builds use a **self-signed development certificate**. They are not signed by a publicly trusted publisher, so Windows may show publisher or reputation warnings. A self-signature does not establish public Windows trust.

## Help and feedback

For account access, subscription changes, or device resets, contact Lords through your existing private support channel. For reproducible application problems, [open an issue](https://github.com/LOoOrds/Lord-Veyra/issues) with the version, Windows version, steps, and a screenshot when useful. Remove account details from screenshots. **Never post passwords, access tokens, or administration keys.**

---

<div align="center">
  <strong>Lord Veyra · Lords</strong><br>
  <sub>© 2026 Lords. Product identity and original documentation.</sub>
</div>
