# Ilm v6

Mobile-first Islamic companion PWA.

## What is included
- Qur’an: all 114 surahs, Arabic + English, search, bookmarks, notes and audio playback/repeat
- Salah: prayer times, calculation method, Asr school, countdown and browser notification permission
- Qibla: location-based bearing + device compass, with Classic, Classy, Tech, Cute, Whimsy, Bold and Minimal designs
- Duas & adhkar, Names of Allah, Tasbih and Islamic calendar
- Learn Islam: Five Pillars, Salah guide and common phrases
- People & Figures: Prophets/Messengers, Sahaba, Ahl al-Bayt, women and classical scholars
- Women in Islam: dedicated people-focused section
- Islamic Books: hadith, tafsir, aqeedah, history and spirituality source links
- Personal profile: local nickname, gender setting and animal avatar choices (sheep, chick, panda, llama, cat, puppy, Nuddles); male avatars show a turban and female avatars show a hijab
- Appearance: simple White and Dark modes
- Local bookmarks, notes and profile data

## Source approach
Qur’an reading/audio and prayer/calendar services use public API endpoints. Hadith and many book entries link to source collections instead of copying entire copyrighted collections. Historical/fiqh material is presented as an introductory study aid, with notes where scholarly differences exist.

## Important limitations
- Browser prayer notifications are not guaranteed when the app/browser is completely closed. Native scheduled notifications would be needed for robust background reminders.
- Device compass support varies by browser/device.
- Prayer calculation methods can produce slightly different times; local mosque/authority settings may differ.

## Run locally
Serve the folder over HTTP/HTTPS (not file://):

    python3 -m http.server 8080

Then open http://localhost:8080/ilm/
