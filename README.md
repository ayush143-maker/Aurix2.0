# Aurix2.0

This repository contains an Aurix application bundle, `Aurix-app.zip`. The project is stored as an archive rather than an unpacked source tree, so the repository root does not provide a package manifest, application entry point, or confirmed run command.

## Inspect and personalize the bundle

Download or clone the repository, then extract `Aurix-app.zip` and review its files for project documentation, a package manifest, and platform configuration. Follow run instructions found in the extracted project rather than assuming commands from this repository root.

To personalize visible content, theme, or assets, first locate the relevant files inside the extracted bundle and follow its own project documentation. Preserve existing relative paths when editing or moving assets; if a file must move, update the references that point to it. The archive is the source available in this snapshot, so the repository root does not identify particular screens, asset names, or settings to edit.

## Asset and loading review checklist

These are actions to perform after extracting the archive, not verified results or performance measurements:

- [ ] Use the extracted project's documentation and source files to identify image, audio, video, and font references. Confirm each local reference matches a file in the bundle and the expected path.
- [ ] Check whether bundled assets are used before removing them; search references in the extracted source and configuration first.
- [ ] Look for unusually large media relative to its use. Consider resizing or compressing assets where suitable, then check the resulting appearance or playback.
- [ ] Inspect external font, script, and other remote-resource references in the extracted project. Confirm they are intentional and necessary, and note whether the app remains usable if a resource cannot load.
- [ ] Follow the extracted project's documented setup to review asset loading in the app type and platforms it supports.

## Manual review checklist

These are actions to perform, not verified results:

- [ ] Extract `Aurix-app.zip` and locate the entry page or app entry point using the extracted files and their documentation. Do not assume a root-level run command.
- [ ] Check referenced image and media paths against the extracted files. If you move or replace an asset, update and inspect its references.
- [ ] Follow the extracted project's documented instructions to open or run the app, then try the interactions described there and any visible controls.
- [ ] Inspect the interface at narrow and wide viewport or device sizes supported by the extracted project.

## Accessibility review checklist

First identify the app type, supported platforms, and interactive screens inside `Aurix-app.zip`. These are future checks to perform using the extracted project's documented setup, not compliance claims or verified results:

- [ ] Use a keyboard where the app supports one to reach interactive controls and operate them; check the order is understandable. If the bundle is a native app, include a hardware keyboard where supported.
- [ ] Check that focused controls have a visible focus indicator against the interface backgrounds.
- [ ] Check that buttons, navigation, fields, and icon-only controls have meaningful accessible names appropriate to their purpose.
- [ ] Review text and control contrast against their backgrounds, including any themes or screens found in the extracted bundle.
- [ ] For meaningful images found in the bundle, check that suitable text alternatives are provided; distinguish decorative images from informative ones.
- [ ] If transitions or other motion are present, check that the app responds appropriately to the platform's reduced-motion preference.

No review results are recorded here; record them separately after carrying out the checklists.