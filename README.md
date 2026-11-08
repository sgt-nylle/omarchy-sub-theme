# Omarchy Sub Theme (`omarchy-sub-theme`) ⚓🇸🇪

**Swedish Navy (*Kungliga Flottan*) · HSwMS Gotland (A19) · Deep Baltic Navy Blue, Sonar Cyan & Swedish Gold.**

A dark [Omarchy](https://omarchy.org/) desktop theme inspired by [SubWrite](https://subwrite.se) and [TechTools](https://techtools.subwrite.se), paying tribute to Sweden's legendary **Gotland-class (A19) Stirling AIP submarine (`HSwMS Gotland`)**.

<p align="center">
  <img src="preview.png" alt="Omarchy Sub Theme preview — HSwMS Gotland sailing out at night through the Stockholm Archipelago" width="100%">
</p>

---

## Install

Install and apply directly with the Omarchy CLI:

```bash
omarchy theme install https://github.com/sgt-nylle/omarchy-sub-theme.git
```

### Theme & Wallpaper Commands

```bash
# Re-apply the theme at any time
omarchy theme set sub

# Cycle between the 4 included Gotland-class backgrounds (or press Super + Ctrl + Space)
omarchy theme bg next

# Update all Git-installed Omarchy themes
omarchy theme update

# Remove the theme
omarchy theme remove sub
```

---

## Four Gotland-Class Backgrounds (`2736×1824`)

All four custom wallpapers are rendered at native `2736×1824` (3:2 Retina / Widescreen friendly) and free of distracting text boxes so your terminal and windows stay clean and readable:

<table>
  <tr>
    <td width="50%" align="center">
      <a href="backgrounds/01-stockholm-archipelago-night-patrol.png">
        <img src="backgrounds/01-stockholm-archipelago-night-patrol.png" alt="01 — Stockholm Archipelago Night Departure" width="100%">
      </a>
      <br><b>01 · Stockholm Archipelago Night Departure (Default)</b>
      <br><i>HSwMS Gotland</i> sailing out on the surface at night through <i>Stockholms skärgård</i> under the Milky Way and northern aurora, past pine-covered granite skerries, a glowing Swedish sector lighthouse (<i>ledfyr</i>), a lit archipelago ferry, and moonlit Baltic waters.
    </td>
    <td width="50%" align="center">
      <a href="backgrounds/02-hms-gotland-tactical-blueprint.png">
        <img src="backgrounds/02-hms-gotland-tactical-blueprint.png" alt="02 — HSwMS Gotland Naval Blueprint" width="100%">
      </a>
      <br><b>02 · HSwMS Gotland (A19) Naval Blueprint</b>
      <br>Detailed starboard elevation, top-down plan, and three cross-section views (<code>SECTION A–A</code> Stirling AIP &amp; battery deck, <code>STERN · X-RUDDER</code> 4-fin X-rudder &amp; 7-blade skewback propeller, and <code>BOW · TUBES</code> 4× 533mm + 2× 400mm torpedo tubes).
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <a href="backgrounds/03-baltic-sonar-silent-running.png">
        <img src="backgrounds/03-baltic-sonar-silent-running.png" alt="03 — Baltic Thermocline Silent Running" width="100%">
      </a>
      <br><b>03 · Baltic Thermocline — Silent Running</b>
      <br>Deep Baltic Sea underwater scene below the halocline with a surface warship hull and cavitation trail above, a 17th-century sunken warship wreck on the seabed, bioluminescent marine life, and a passive/active sonar sweep.
    </td>
    <td width="50%" align="center">
      <a href="backgrounds/04-dawn-torpedo-run.png">
        <img src="backgrounds/04-dawn-torpedo-run.png" alt="04 — Dawn Torpedo Run" width="100%">
      </a>
      <br><b>04 · Dawn Torpedo Run (Torped 62)</b>
      <br>A Swedish heavyweight homing torpedo (<i>Torped 62</i>) cruising upward through dark navy water with counter-rotating propellers, wire-guidance filament, cavitation bubble trail, and acoustic homing lock toward a battleship silhouetted against a Baltic dawn horizon.
    </td>
  </tr>
</table>

---

## Color Palette (`colors.toml`)

Every Omarchy 4.5 surface (Hyprland borders, Quickshell bar, menus, launcher, lock screen, Alacritty/Ghostty/Kitty/Foot terminals, Neovim, VS Code, `btop`, and GTK/icons) is generated from `colors.toml`:

| Role | Token | Hex | Description |
| :--- | :--- | :--- | :--- |
| **Background** | `background` | `#07162c` | Deep Baltic Navy CIC Surface |
| **Dark Background** | `dark_background` | `#040e1d` | Abyssal Navy Trench |
| **Darker Background** | `darker_background` | `#020812` | Keel Black-Navy Scrim |
| **Elevated Surface** | `lighter_background` | `#0f2b52` | Elevated Navy Card / Cursor Line |
| **Foreground** | `foreground` | `#e2eeff` | Crisp Naval Readout White-Blue |
| **Bright Foreground** | `bright_foreground` | `#f8fbff` | Periscope Glint Peak White (Cursor) |
| **Muted / Hairline** | `muted` / `hairline` | `#5b82b8` / `#1b457d` | Steel-Navy Comments & Frame Borders |
| **Primary Accent** | `accent` / `cyan` | `#38bdf8` / `#67e8f9` | Periscope & Sonar Telemetry Cyan |
| **Selection** | `selection` | `#164682` | Tactical Navy Selection Highlight |
| **Yellow / Gold** | `yellow` / `bright_yellow` | `#fecc02` / `#fde047` | Swedish Naval Ensign Gold (*Örlogsflagga*) |
| **Blue** | `blue` / `bright_blue` | `#5494f7` / `#82b5ff` | Royal Swedish Navy Blue |
| **Green** | `green` / `bright_green` | `#34d399` / `#4ade80` | Passive Sonar Contact Green |
| **Red** | `red` / `bright_red` | `#ff5c5c` / `#ff8585` | SubWrite Torpedo / Red Alert |
| **Magenta** | `magenta` / `bright_magenta` | `#a78bfa` / `#c4b5fd` | ESM / Acoustic Intercept Violet |

### Included Theme Assets
- `colors.toml` — Complete Omarchy 4.5 semantic token & 16-slot ANSI palette
- `shell.bar.toml`, `shell.controls.toml`, `shell.lock.toml`, `shell.launcher.toml`, `shell.menu.toml`, `shell.popups.toml`, `shell.tooltip.toml` — Coordinated Navy Blue Quickshell bar, menus, and lock screen
- `icons.theme` — `Yaru-blue` icon theme selection
- `unlock.png` & `preview-unlock.png` — Custom `HSwMS Gotland (A19)` lock/unlock emblem
- `backgrounds/` — 4 original `2736×1824` PNG wallpapers

---

## License

Released under the [MIT License](LICENSE). Created by [sgt-nylle](https://github.com/sgt-nylle) ([subwrite.se](https://subwrite.se) / [techtools.subwrite.se](https://techtools.subwrite.se)).
