# Pinpoint Privacy Policy

**Last updated:** November 7, 2026

Pinpoint is a browser extension for selecting webpage elements, writing comments about them, and copying a prompt to the clipboard. It does not operate a Pinpoint account or server.

## Information Pinpoint processes

When you start Pinpoint on an HTTP(S) page or an allowed local `file://` page, it reads the page context needed to identify the element you select. This may include that element’s text, selector, nearby structural context, rendered styles, framework hints, and page URL or file path. Comments you write are associated with that element so Pinpoint can display and edit the pin and assemble your prompt. Pinpoint may capture a small local preview and screenshot when you save a pin; capture is best-effort.

“Keep pins across navigation” is enabled by default. When enabled, pin content (including locally captured screenshots) is stored in the browser’s local extension storage by site origin, or by local file path for `file://` pages. Pins can be restored in a later Pinpoint session. When the option is turned off, pins use browser session storage and are cleared when the pathname changes, the tab closes, or the browser session ends. Your theme and persistence preference are stored locally in the browser.

When you choose **Copy prompt** with **Include screenshots in prompt** checked, Pinpoint uploads each selected screenshot to TempFile.org using its anonymous upload API and requests the 48-hour expiry. The returned links are added to the copied prompt, and a PNG contact sheet is also offered to clipboard targets that accept images. Anyone with a link can access its screenshot until the link expires. Screenshots are not uploaded when the option is unchecked. If an upload fails, Pinpoint keeps the pins and does not report a successful copy. If clipboard access fails after upload, Pinpoint displays the prompt, including its screenshot links, for you to copy manually.

## Collection, transmission, and sharing

Pinpoint does not transmit page content, comments, or URLs to the Pinpoint developer. The selected screenshots are sent to TempFile.org only when you explicitly choose **Copy prompt** with screenshots enabled. TempFile.org receives the image and the request needed to host it; Pinpoint includes the resulting shareable links in the prompt. Other page details and comments are copied to your clipboard and are not sent to TempFile.org. Pinpoint has no analytics, advertising, account, or cloud-sync service. It does not sell data.

Pinpoint's use of information accessed through Chrome extension APIs adheres to the Chrome Web Store User Data Policy, including its Limited Use requirements.

## Permissions

Pinpoint uses the active tab and browser debugger APIs to inspect and highlight the page element you select. It injects its interface after you start the extension. Local browser storage keeps session pins, an optional local pin set, and your theme preference. Clipboard write access and the TempFile.org connection are used only when you request **Copy prompt**; screenshot upload also requires the screenshots option to be checked. Chrome shows its debugger notice while Pinpoint is active.

## Changes and contact

This policy may be updated if Pinpoint’s data practices change. For support, contact Malik Hamza at [malikh.aamzaa912@gmail.com](mailto:malikh.aamzaa912@gmail.com). The Chrome Web Store publisher display name is **Pinpoint (Malik Hamza)**.
