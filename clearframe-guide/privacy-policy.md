# Clearframe Guide Privacy Policy

**Effective date: October 22, 2026**

Clearframe Guide is a privacy-focused Chrome extension that turns browser workflows explicitly started by the user into editable, step-by-step visual guides.

## Information processed

After the user starts recording, Clearframe Guide may process:

- screenshots of visible website content;
- visible page text used to create step descriptions;
- the page origin needed to identify a recorded step; and
- click actions performed during the recording.

This information is processed only to create, edit, review, and export the guide requested by the user.

## Local storage and transmission

Guide data, steps, and screenshots are stored locally on the user's device. Screenshots and guide records are stored in extension-local IndexedDB. Recording state, language preferences, and editor update signals are stored in Chrome local storage.

Clearframe Guide has no account system, server endpoint, telemetry, advertising SDK, remote code, cloud upload, or online AI service. It does not sell, share, or transmit user data to third parties. The developer and other humans cannot access the user's locally stored guide content.

## Browser access

Recording must be explicitly started by the user.

In single-tab mode, Clearframe Guide accesses only the selected regular HTTP or HTTPS page. If the user enables cross-tab recording, Chrome displays its native website-permission prompt. The optional all-sites permission is used only to continue the recording across regular HTTP and HTTPS tabs selected by the user and is removed when recording stops or the browser restarts.

Browser-internal pages, extension pages, and local files are not recorded.

## Privacy protection

Before a screenshot is stored, Clearframe Guide attempts to cover visible passwords, payment-card fields, verification codes, ordinary inputs, editable regions, and visible iframe areas. Sensitive input interactions do not create guide steps.

Automatic detection is based on heuristic rules and cannot identify every sensitive detail in images, video, canvas content, or ordinary page text. Users must complete the built-in privacy review before exporting or sharing a guide.

Users can permanently redact selected image regions. Permanent redaction writes the cover directly into a new PNG and replaces the corresponding locally stored image.

## Exports

Clearframe Guide can export standalone HTML, Markdown and PNG archives, print-ready output for PDF creation, and offline video-project packages. Exports are created only when requested by the user and use the current privacy-reviewed images.

## Retention and deletion

Locally stored data remains on the user's device until the user deletes a guide, clears the extension's data, or uninstalls the extension. Deleting a guide removes its stored steps and screenshots. Deletion is irreversible within Clearframe Guide.

## Limited Use

Clearframe Guide uses information received from Chrome APIs only to provide its single user-facing purpose. Its use of this information complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.

Clearframe Guide does not:

- sell user data;
- transfer user data for advertising or unrelated purposes;
- use user data to determine creditworthiness or for lending; or
- allow humans to read user content.

## Contact

For privacy questions, contact the developer through the repository that publishes this policy:

https://github.com/HaddenHunter/c8software.github.io/issues
