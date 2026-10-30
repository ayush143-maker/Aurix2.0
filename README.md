# Aurix2.0

This repository contains an Aurix application bundle, `Aurix-app.zip`. The project is stored as an archive rather than an unpacked source tree, so the repository root does not provide a package manifest, application entry point, or confirmed run command.

## Inspect and personalize the bundle

Download or clone the repository, extract `Aurix-app.zip`, and review its files for project documentation, a package manifest, and platform configuration. Follow instructions in the extracted project rather than assuming commands from this repository root.

To personalize visible content, theme, or assets, first locate the relevant files inside the extracted bundle and follow its own documentation. Preserve existing relative paths when editing or moving assets; if a file must move, update its references. This repository snapshot does not identify particular screens, asset names, or settings to edit.

## Browser, platform, and asset review checklist

These are actions to perform after extracting the archive, not verified results. No browser or platform compatibility testing is recorded here.

- [ ] Identify the app type and supported platforms from the extracted files and documentation. Use the documented setup to review it in current browsers relevant to its web stack, if it includes a web app. Review native apps in their relevant development environments; browser testing alone does not verify native behavior.
- [ ] For web review, inspect the browser Console and Network panel for errors, failed requests, and unexpected warnings. Use the appropriate diagnostics in the documented environment for native-only issues.
- [ ] Locate image, audio, video, font, and other resource references in the extracted source and configuration. Confirm local paths match files in the archive and verify remote URLs. Consider how the experience behaves if a remote resource cannot load.
- [ ] Check whether bundled assets are used before removing them; search source and configuration references first. Review unusually large media in relation to its use before considering resizing or compression.
- [ ] Compare mobile-sized and desktop-sized layouts where the extracted project supports them. Check that content and controls remain visible, readable, and usable.
- [ ] Follow the extracted project's instructions to try its visible interactions. Do not infer features or services from the archive name or appearance.

## Accessibility review checklist

These are future checks using the extracted project's documented setup, not compliance claims or verified results:

- [ ] Use a keyboard where supported to reach and operate controls; check focus visibility and keyboard order.
- [ ] Check that controls have meaningful accessible names and that text and controls have sufficient contrast.
- [ ] Check text alternatives for meaningful images and reduced-motion behavior if motion is present.

No review results are recorded here; complete the checks after identifying the app type and supported platforms.