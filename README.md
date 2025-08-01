## Pacstore

**A GNOME-native Software Center for Arch Linux**

Pacstore is a modern, minimalistic software center tailored specifically for Arch Linux and pacman-based distributions. Built using GTK4 and Libadwaita, Pacstore offers a clean, curated, and native app discovery experience that integrates seamlessly with the GNOME desktop environment.

Unlike generic frontends, Pacstore is built *exclusively* for `pacman` and does not support Flatpak, Snap, or PackageKit. This focused approach enables faster performance, tighter integration with the underlying system, and a user experience designed specifically for Arch users who prefer native packages.

---

## Motivation

While tools like Pamac exist, they often rely on their own backends or introduce unnecessary complexity. GNOME Software, on the other hand, excels in design and UX, but lacks true pacman support. Pacstore aims to combine the best of both worlds: the aesthetic and UX of GNOME Software, with the raw power and simplicity of pacman.

Pacstore is:

* **Fast and lightweight** — Built with native pacman tools.
* **Curated** — Not just a package browser; it showcases featured apps and categories.
* **Integrated** — Uses GNOME design guidelines and feels at home on Adwaita-based desktops.

---

## Features (Planned)

- 📦 Discover and install native pacman packages

- 🎨 GNOME-native design using GTK4 and Libadwaita

- 🗂️ Category-based browsing (e.g. Games, Creative, Tools, Internet)

- ⭐ “Featured Apps” section

- 🔍 Integrated package metadata and screenshots

- 🧠 Caching for performance

- 🔧 Lightweight backend without requiring Flatpak, Snap, or PackageKit

---

## Roadmap

### ✅ Phase 1: MVP (Minimum Viable Pretty)

* [ ] GTK4 + Libadwaita UI
* [ ] Static grid of "featured" apps (via JSON)
* [ ] GNOME Software-style presentation

### 🔜 Phase 2: Metadata Layer

* [ ] Parse package info from `pacman -Si` or `-Qi`
* [ ] Fallbacks for missing fields (icon, description)
* [ ] Local caching

### 🔜 Phase 3: Categories

* [ ] Define curated categories (e.g. Games, Creative, Development)
* [ ] JSON map of categories to package names

### 🔜 Phase 4: Actions

* [ ] Install/Remove via `pacman -S/-R`
* [ ] Optional: privilege elevation via `pkexec`/`polkit`
* [ ] Progress tracking & feedback UI

---

## License

Pacstore is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

See [LICENSE](./LICENSE) for more information.

---

## Contribution & Feedback

Pacstore is in early stages. Feedback is welcome — respectfully. This is a passion project created to address a very specific need: a true GNOME-style software center for Arch users.

If you'd like to contribute:

* Bug reports, design suggestions, or pull requests are welcome
* You can also help by contributing curated app lists or metadata mappings

---

## Notes

Everything here is subject to change and not a strict or final plan.
