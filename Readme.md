# HomeTutor 🎓

HomeTutor is a premium, responsive landing page web application engineered to bridge the gap between students and expert educators. Built with an asynchronous UI streaming design, the project segments heavy page layouts into isolated HTML fragments, delivering lightning-fast rendering times, smooth scrolling interactions, and clean local browser session tracking.

---

## 🚀 Key Features

*   **Asynchronous UI Shell Architecture:** Layout sections (`hero`, `about`, `services`, `contact`, `modals`) are completely decoupled into specialized sub-fragments and populated dynamically on page request using non-blocking asynchronous JavaScript `Promise.all` queues.
*   **Dynamic Authentication Session Layer:** The landing interface reads `localStorage` keys to evaluate active authorization tokens, swapping call-to-action controls instantly between access options and active account profile routes.
*   **Bespoke Dark-Theme Modals:** Re-engineered custom screen overlays providing elegant entry fields using soft transparency dark profiles (`#11141a`), custom box-shadow focus parameters, subtle layout backdrop blurs, and wide input fields.
*   **Smart Click Event Delegation Engine:** Utilizes modern event capture logic (`e.target.closest()`) globally to securely register modal interactions even when selecting inner button text typography nodes.

---
