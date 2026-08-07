# HomeTutor 🎓

HomeTutor is a premium, responsive landing page web application engineered to bridge the gap between students and expert educators. Built with an asynchronous UI streaming design, the project segments heavy page layouts into isolated HTML fragments, delivering lightning-fast rendering times, smooth scrolling interactions, and clean local browser session tracking.

---

## 🚀 Key Features

*   **Asynchronous UI Shell Architecture:** Layout sections (`hero`, `about`, `services`, `contact`, `modals`) are completely decoupled into specialized sub-fragments and populated dynamically on page request using non-blocking asynchronous JavaScript `Promise.all` queues.
*   **Dynamic Authentication Session Layer:** The landing interface reads `localStorage` keys to evaluate active authorization tokens, swapping call-to-action controls instantly between access options and active account profile routes.
*   **Bespoke Dark-Theme Modals:** Re-engineered custom screen overlays providing elegant entry fields using soft transparency dark profiles (`#11141a`), custom box-shadow focus parameters, subtle layout backdrop blurs, and wide input fields.
*   **Smart Click Event Delegation Engine:** Utilizes modern event capture logic (`e.target.closest()`) globally to securely register modal interactions even when selecting inner button text typography nodes.

---

## 🎨 Tech Stack & Dependencies

The application relies on these production distributions to supply typography styling, icon libraries, and standard framework grids:

*   **Markup Standard:** HTML5 Semantic Structure Markup
*   **CSS Layout Framework:** [Bootstrap CSS v5.3.0](https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css) (Supplies structural grid assets and responsive utility classes)
*   **System Layout Scripts:** [Bootstrap Bundle JS v5.3.0](https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js) (Manages internal framework helper systems)
*   **Primary Iconography Pack:** [Bootstrap Icons v1.11.3](https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css) (Handles structural navbar visual layouts)
*   **Secondary Graphic Assets:** [FontAwesome Fonts v6.4.0](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css) (Supplies secondary custom utility font glyph vectors)
*   **Runtime Logic:** Vanilla ECMAScript (Native DOM manipulation, Fetch API streams, and Client-side Web Storage)

---
