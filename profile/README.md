<p align="center">
    <img src="https://user-images.githubusercontent.com/59678453/180375518-92d24d0c-12d5-4255-8746-380a7aca2b20.png#gh-light-mode-only"
        alt="Logo" width=70>
    <img src="https://user-images.githubusercontent.com/59678453/180376465-90aad3ca-85e9-44b4-b61f-01beabca61ba.png#gh-dark-mode-only"
        alt="Logo" width=70>
    <h3 align="center">
        <a href="https://tail.wtf/">Tail.WTF</a>&nbsp;&nbsp;
        <img src="https://img.shields.io/github/stars/tail-wtf/rules?style=social" alt="stars">
    </h3>
    <p align="center">
        Chops Trackers From Shared Link.
    </p>
</p>

---

When you tap share buttons, innocent-looking random strings are placed in the links you get - they are actually
"trackers" tied to you 👀.

Every time your friends open these links, service providers learn more about your social connections such as how often
you talk to a particular friend, topics you discuss, etc 🤨. They can further exploit this information in conjunction with
other data they have about you and your friends.

Tail.WTF protects your privacy by chopping the annoying "tails" off these links 🛡️, also makes them look
nicer.

## Features

- **Whitelist-based rules**: only parameters essential for reaching a specific resource are kept. Stricter and more stable compared to the blacklist-based services.
- **Server-side Support**: short link expansions can be done anonymously on the server side. Unknown or tricky links can be processed by code-based rules.
- **Diverse clients**: Easily sanitize links on mobile devices, in IM apps or even in terminal without relying on specific browsers or extensions.
- **Concise rules in standardized format**: link processing rules can be written by anyone familiar with basic YAML formatting and regular expressions, and can be easily parsed by new client apps.

## Contribute

Tail.WTF is in its early stages and we appreciate your efforts on making it better!

In general, you can get involved by:

- Submit [rule requests](https://github.com/Tail-WTF/Rules/issues/new) for links we can't sanitize yet
- Create new rules via pull requests. Please see the [rule writing instruction (WIP)](#)
- Contribute code. See issues of code repos and our [roadmap](https://github.com/orgs/Tail-WTF/projects/1) to get started

## Contact

Please communicate all general feedbacks and suggestions in [discussion](https://github.com/Tail-WTF/Rules/discussions).
Additionally, you can reach out to project moderators with email address on our GitHub organization page.
