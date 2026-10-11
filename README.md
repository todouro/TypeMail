# TypeMail — Dear Typewriter

A focus-first, browser-based 3D manual typewriter. The machine is the interface: type on your physical keyboard or click the modelled keys, use Enter for a smooth carriage return, and keep sheets in a local manuscript stack.

## Run it

Open `index.html` through GitHub Pages or any static web server. For a quick local preview on Windows, run `serve.bat`, then visit http://localhost:8000.

Three.js and web fonts load from CDNs, so the first launch needs an internet connection. No bundler, account, database, or telemetry is required.

## Features

- Larger, more readable typed text on procedural paper textures.
- Full-screen 3D typewriter with clickable keys, moving carriage, return lever, platen and ribbon.
- Smooth, eased carriage return and paper feed instead of snapping to the next line.
- Enamel colours, paper stock, typefaces, room lighting, correction tape and red/black ribbon.
- Multiple sheets, browser-local autosave, PNG image export, manuscript text download, clipboard copy, print/PDF and email-app handoff.
- Minimal writing view with optional settings and export panels.

## Privacy and email

Writing stays in browser storage until the writer chooses to export or share it. Email is prepared with a `mailto:` link; this website does not send email or store recipient addresses.

## Credits

Built with Three.js and browser APIs. Typeface families are loaded from Google Fonts. The typewriter scene and interface are original procedural code.
