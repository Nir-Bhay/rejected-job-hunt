# REJECTED! — The Job Hunt Chronicles

A free tragicomic 3D job-hunt game you can play in the browser. You play Alex, who has sent 4,712 applications and received 4,712 nos. Five chapters. Five rejections. Tomorrow, he applies again.

**Play it:** [nir-bhay.github.io/rejected-job-hunt](https://nir-bhay.github.io/rejected-job-hunt/)

## Chapters

1. **Inbox Rush** — a three-lane run. Send 12 applications, dodge REJECTED stamps, and jump the spam barriers.
2. **Synergy Night** — collect 8 handshakes in 50 seconds and stay away from the influencers.
3. **The Interview** — answer Mr. Stern at Innovatech. You have 12 seconds for each question. Your interest score changes the rejection email.
4. **Skill Bootcamp** — type 14 falling skills before they hit the firewall.
5. **The Final Storm** — survive 36 seconds of rejection letters, then read the offer that does not last.

Hope is your health. Lose it and you retry that chapter. Every win ends in an email.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | WASD or arrow keys | Press and hold the ground |
| Change lane | A D or left right | Swipe |
| Jump | W, up, or Space | Swipe up or tap |
| Answer the interview | 1 2 3 or click | Tap an answer |
| Type a skill | Type the word. Escape clears the lock | Tap to Type |
| Show controls again | The ? button | The ? button |
| Skip the ending | Click, Enter, or Space | Tap |

## Run it yourself

The game is one file, `index.html`. It loads [Three.js](https://threejs.org/) from a CDN. There is no build step.

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Best run

The furthest chapter you reach is saved in this browser only. A shorter later attempt does not replace it.
