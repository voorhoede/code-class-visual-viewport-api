# Code Class: Visual Viewport API

Some user agents have split their viewport into two conceptual viewports, colloquially known as the visual and layout viewports. This separation is useful in enabling a user agent (UA) with a small screen to allow the user to zoom in on parts of the page without causing the page to respond, for example, by obscuring the user's view with position: fixed elements. As another example, mobile UAs often provide an on-screen keyboard (OSK) for user input. Without the visual/layout split, a position: fixed element would be pushed up when the OSK is shown, obscuring the user's view. Informally, the layout viewport is what the web page uses when laying out its UI while the visual viewport is the box on the page that the user can currently see, accounting for transient UI features like pinch-zoom and the OSK.

## Getting started

This project is hosted as a Voorhoede Git repository. Clone it:

```bash
$ git clone git@github.com:voorhoede/code-class-visual-viewport-api.git
```

Install dependencies:

```bash
$ npm install
```

Start server & watch files:

```bash
$ npm run start
```

This wil build the project, start the server and start the watcher. The project is
available on [localhost:3000](http://localhost:3000). The watcher task will automatically
build assets, styles and views. The server will be reloaded on every change.
