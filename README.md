About
=====

🐽 trot.to is an organization-specific URL shortening service

This is a Firefox extension that expands the "go" links, like `go/example` into the appropriate full URL.

This extension is a blind copy of the official Chrome extension[0,1], with configuration fixed so that it works with Firefox.

[0] https://github.com/trotto/browser-extension
[1] https://chrome.google.com/webstore/detail/trotto-go-links/nkeoojidblilnkcbbmfhaeebndapehjk


Installation
============

1. Clone/download this repository.
2. In Firefox, open "about:debugging", select "This Firefix", then "Load Temporary Add-on".
3. Choose a file within this extension directory (e.g. manifest.json) in the file selector and open it. Done!


Usage
=====

1. Ensure you are logged into trot.to.
2. Open go links like `go/foo` in the URL bar, and the extension will automatically expand to `tro.to/go/foo` for you.
