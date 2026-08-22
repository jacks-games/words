# 📖 Jack's Words

### Hear a word. Build it. Score a goal. ⚽

# [▶ PLAY](https://jacks-games.github.io/words/)

![Jack's Words: the word "dog" in rainbow colours inside the sentence "The dog can run."](screenshot.png)

## 🎮 How to play

### 1️⃣ &nbsp; Listen 🔊
Tap the big blue button. A voice says the word.

### 2️⃣ &nbsp; Build it 🧩
Tap the letters. Put them in the right order.

### 3️⃣ &nbsp; Read it 🌈
The word lights up inside a sentence. Tap it to hear the whole sentence.

### ⚽ &nbsp; GOAL!
Every word you build wins a football. Your footballs stay at the top. ⚽⚽⚽

## 🔤 The words

|  |  |
|---|---|
| 🐱 **Short** | cat · dog · sun · hat · bus |
| 📗 **Longer** | book · ball · frog · fish · cake |
| 🏫 **Big ones** | happy · water · school · friend · teacher |

## 🎯 What you get better at

- 👂 &nbsp; Hearing the sounds inside a word
- 🔡 &nbsp; Knowing which letter makes which sound
- 📖 &nbsp; Reading a whole sentence

## 🎈 More games for Jack

[📖 Words](https://github.com/jacks-games/words) · [🥅 Match](https://github.com/jacks-games/match) · [✏️ Letters](https://github.com/jacks-games/letters) · [🔢 Numbers](https://github.com/jacks-games/numbers) · [♟️ Chess](https://github.com/jacks-games/chess)

👉 &nbsp; All of them together: **[jackbenn.ing](https://jackbenn.ing)**

---

<details>
<summary><b>For grown-ups</b> — how it works</summary>

One self-contained `index.html`. No build step, no dependencies, no accounts, no tracking, no network calls after the page loads.

- **Speech** — Web Speech API, preferring a British English female voice. Speech only starts after the ▶ button, because browsers block audio without a tap.
- **Phonics** — a setting turns letter *sounds* (`buh`, `sss`) on instead of letter *names*, matching how it is taught at school.
- **Progress** — footballs and the current word are kept in `localStorage`, per device.
- **Built for** an iPad mini held in either direction; every tap target is finger sized.

Source of truth for all of Jack's games is the [jackbenn.ing repo](https://github.com/google814/Jack); this repo is a copy so the game has its own page and link.

Run it locally:

```bash
python3 -m http.server 8000
```
</details>
