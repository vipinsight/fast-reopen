# Fast Reopen

![Fast Reopen](src/logo64.png "Fast Reopen")

Keeps your browser running in the background after you close its last window, so it opens faster the next time.

[Get Fast Reopen from the Microsoft Edge Add-ons store](https://microsoftedge.microsoft.com/addons/detail/gpkgfiklomfbkdlkinanbfgcjdeodgff)

![Fast Reopen screenshot](screenshots/Screenshot_1.png)

## How it works

Fast Reopen requests the browser's `background` permission. With that permission the browser process stays alive after the last window is closed, so the next launch skips most of the startup work. This is most noticeable on Windows and Linux, where closing the last window normally exits the browser.

There is no popup, no settings and no code: the extension is just a manifest and an icon.

## Good to know

- The browser keeps using some memory while it runs in the background.
- To go back to normal behaviour, disable or remove the extension.

## Privacy

Fast Reopen does not access, collect, store or send any data and makes no network requests. See the [privacy policy](privacy-policy.md).

## Compatibility

Manifest V3, for Microsoft Edge and other Chromium-based browsers that support the `background` permission.

## License

See [LICENSE](LICENSE).
