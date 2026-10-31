# ItzMasterBlade site

```
index.html          page markup only
css/
  style.css         all styling (themes, glass, layouts, cursor, dock)
js/
  boot.js           loads first: saved theme/layout, ResizeObserver fix
  main.js           ticker, toast, themes, clock, projects, effects
  pixel-world.js    Pixel World game
  contact.js        anonymous message form (set CONTACT_API at the top)
  decor.js          side decorations + string lights
  upgrades.js       custom cursor, dock, layouts, ambient background
assets/img/         put every image here (deco-*.png, sprite-*.png, star-*.png, lights.png, mc-profile-pic.png (rename of "Mc  Profile Pic.png"))
```

Edit projects in `js/main.js` (the `projects` list). Edit theme colours at the top of `css/style.css`.
Open `index.html` through a local server or your host so all files load correctly.
