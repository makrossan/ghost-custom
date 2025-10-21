# Code Injection – Documentation Website Custom Scripts

This repository contains the **custom code snippets** I use for **code injection** on my personal documentation website ([docs.greivinvenegas.com](https://docs.greivinvenegas.com)).

These scripts extend the native behavior of the Ghost platform by adding small but powerful customizations — from layout tweaks and UI refinements to analytics and dynamic elements that enhance readability and navigation.

---

## Purpose

The main goal of this repository is to centralize, version, and document all the injected scripts used across my Ghost-based documentation site.  
Keep track of any code affecting the front-end presentation.

---

## Structure

Each file represents an individual injection, typically loaded through **Ghost Admin → Settings → Code Injection**:

- `/header/` — Scripts or styles injected in the `<head>` section (e.g., custom fonts, meta tags, analytics).
- `/footer/` — Scripts injected before `</body>` (e.g., navigation tweaks, interactive components).
- `/shared/` — Reusable snippets or partials used in multiple injections.

---

## Notes

- All code is written with performance and minimalism in mind — no dependencies beyond what Ghost already loads.
- Most snippets are designed for **Ghost themes with clean HTML structures** (optimized for my *DocuHub* theme).

---

## License

All code in this repository is licensed under the **MIT License**.  
Feel free to reuse, adapt, or reference these snippets — attribution is appreciated but not required.

---

## Author

**Greivin Venegas**  
Documentation engineer & homelab enthusiast  
[greivinvenegas.com](https://greivinvenegas.com)
