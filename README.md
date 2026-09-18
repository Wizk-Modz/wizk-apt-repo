# Wizk APT repository

APT repository for the Wizk Termux fork (`com.wizk`, Android 7+, `aarch64`).

- Repo URL for `sources.list`:
  `deb [signed-by=/data/data/com.wizk/files/usr/etc/apt/trusted.gpg.d/wizk-archive-keyring.gpg] https://wizk-modz.github.io/wizk-apt-repo/ stable main`
- Archive signing key: [wizk-archive-keyring.asc](wizk-archive-keyring.asc)
  (`679AA9FDB25D0DB794E2F5B0C8FD6203FBAB7C8B`)

Packages are built by the `Packages` / publish workflows in
[Wizk-Modz/termux-packages](https://github.com/Wizk-Modz/termux-packages)
and published here automatically. Do not push `.deb` files manually.
