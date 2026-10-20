# Harmony Timer 🌈

For Harmony 💗

A rainbow visual timer with a to-do checklist, made for studying together, getting through the day, moving our bodies, and taking turns without fights. You can see time disappear as the rainbow shrinks, so you don't need to read a clock.

It's one HTML file that works offline in any browser. Nothing is sent anywhere, and everything is saved on the device you use it on.

---

## Features

### ⏳ Timer
- A rainbow dial that starts **full for any length of time**, from 20 seconds to 90 minutes, and shrinks to empty at zero.
- Set the time by tapping the clock for quick picks (1–60 min, or exact minutes and seconds), or by dragging a finger around the dial like the real one.
- A number clock (mm:ss) under the dial, which you can hide in settings.

### 📚 Focus (Pomodoro)
- Rounds of focus time and breaks for studying together.
- Adjustable focus length, short break, long break, how often the long break comes, and number of rounds.
- Says "Focus time!" and "Break time!" when each part starts.

### 💪 Move (Tabata)
- Get ready → work → rest intervals for workouts.
- Adjustable work, rest and get-ready times and number of rounds.
- Beeps during the last 3 seconds of every interval, and shows round progress dots.

### 🔄 Turns
- A big picture card for each kid, with **NOW** and *next* badges.
- Starts with 🦄 **Harmony** (pink) and 🦖 **Espen** (green).
- Says "Harmony's turn!" out loud and switches automatically when time is up.
- Tap ✏️ on a card to change the name, picture or color. Tap **＋ Add** for more players.

### ✅ My List
- A checklist with flip switches, like the physical timer. Checking a task plays a chime.
- Tasks can have minutes. The ⏱ button on a task starts a timer for it.
- Unicorn and rainbow confetti when the whole list is done.

### 🎨 Look & feel
- Six rainbow themes: Pastel Rainbow (default), Pink Dream, Unicorn, Bright Rainbow, Ocean and Sunset.
- Three rainbow styles: rings, smooth gradient, or one color.
- Sliders to shift the colors and make them softer or more pastel, plus a color picker for each rainbow band.
- Color pickers for the app background and the timer body.
- A choice of center buddy: 🦄 🌈 ⭐ 💖 🌸 🦋 🐱 🐰

### 🔔 Sound & extras
- Chime or bell sounds, or off, with a volume control.
- Spoken announcements, which you can turn off.
- The screen stays awake while a timer runs, and there's a fullscreen button.
- **Kid lock:** settings open only after holding the ⚙️ button for about a second.
- Export and import of all settings as a backup or to move to another device.

---

## Quick how-to

1. **Open** `rainbow-timer.html` in a browser. A tablet in fullscreen (⛶ button) works best.
2. **Pick a mode** at the top: Timer, Focus, Move or Turns.
3. **Set the time:** tap the clock face and choose a time, or drag around the dial in Timer mode.
4. **Start or pause:** tap the 🦄 in the middle of the dial or the big ▶ button. The spacebar works on a keyboard.
5. **Start over:** ↺. **Skip ahead** to the next part or player: ⏭.
6. **Check off tasks:** tap a task to flip its switch.
7. **Change things:** tap the small ⚙️ in the top-right corner.
   - **Colors:** themes, sliders, background, timer body, center buddy
   - **Timers:** Focus, Move and Turns settings, and players
   - **List:** add, edit, reorder or remove tasks
   - **Sound & more:** sounds, voice, kid lock, backup

> Tip: tap the very first ▶ before expecting sound. Browsers only allow sound after the first tap on the page.

---

## Changing what the voice says

Open `rainbow-timer.html` in a text editor and search (Ctrl+F) for these lines. Only change the words inside the quotes.

| What it says | Search for |
|---|---|
| Focus / break / Move announcements | `const words={focus:` |
| "Harmony's turn!" | `'s turn!` |
| Timer finished message (also shown on screen) | `const msg={timer:` |
| Extra "Great job!" after finishing | `' Great job!'` |
| Whole list done | `You did everything on your list` |
| Voice speed and pitch | `u.rate=0.95;u.pitch=1.25;` |

If your text has an apostrophe (*you're*), wrap it in double quotes: `"You're up!"`. Save the file and refresh the page to hear the change.

---

## Good to know

- Settings, lists and players are saved in **that browser on that device**. Use **Export** in settings to copy them to another device.
- The voice is the device's built-in text-to-speech voice, so it sounds different on an iPad, a Mac or Windows.
- Clearing the browser's site data resets the app to its defaults.
