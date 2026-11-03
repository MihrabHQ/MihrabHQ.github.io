# Mihrab Web

[Mihrab](https://mihrab.elghamri.se/) in your browser, at **https://mihrabhq.github.io/**: prayer times for
where you are, with browser notifications at each prayer, and the Qur'an — the Madinah muṣḥaf with tajwīd
colours, the IndoPak, Warsh, Qālūn and Shuʿbah texts, hard-word meanings, and Husary's recitation
highlighted word by word.

Everything you set is kept in your browser. The muṣḥaf and tajwīd fonts, the four riwāyāt, the word timings
and the word meanings are served from `files/`; recitation streams from everyayah.com. See the
[privacy policy](https://github.com/MihrabHQ/Mihrab/blob/main/PRIVACY_POLICY.md) ("Mihrab Web").

This repository is generated. The source is [MihrabHQ/Mihrab](https://github.com/MihrabHQ/Mihrab):
`npx webpack --mode production --env web` in `desktop/`, then `desktop/scripts/build-web.js`.
