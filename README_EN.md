<div align="center">

# Sand-Samsara · 沙界轮回

A formless realm constructed of particles and dust. All beings drift with karma; every destiny unfolds by conditions alone.

**▶ Play Online: <https://drhycheung.github.io/SandSamsara/>**

English ｜ [简体中文](README.md)

</div>

---

## Opening Statement & Creative Provenance

Sand-Samsara is a modern artistic reimagining of the 2005 classic particle sandbox game *Hell of Sand*. All karmic and samsara-themed mechanics are creative artistic interpretations, not orthodox religious doctrine. There is no in-game text or storyline. This documentation only provides background context for interested readers.

---

## Worldview & Gameplay

This is a falling-particle sandbox game. You are at once an observer and an external condition within this world: with one hand you scatter sand, fire, water, magma and other substances, shaping circumstances; with the other you watch the fortunes of countless stick-figure beings unfold.

This is Sand-Samsara, a formless realm constructed of particles and dust. All beings awaken here with no memory of past lives. They do not understand karma, nor the cycle of rebirth. Some drift numbly, some wander restlessly, some struggle desperately to escape suffering, and others obsessively seek the world's edge, longing for permanence. All their running and striving arises from ignorance — they attempt to find peace by changing external circumstances, yet never escape the cycle itself.

Yet merely fleeing suffering and struggling to stay alive brings no true liberation. This world holds the Wheel of Karmic Fire, the embodiment of collective unwholesome karma woven together by all beings. The wheel manifests periodically, guided by the player's hand or roaming freely on its own. Any being drawn into it becomes entangled in shared karmic force: the more lives consumed, the heavier the collective karma grows, and the larger the wheel becomes.

As the wheel expands, beings are gradually pressed toward the world's edges. Flames spread along the boundaries, trapping all who remain; no escape is left. When collective karma reaches its critical peak, the world collapses naturally from its own ripened causes. Fire engulfs the realm, particles scatter, landscapes burn away, and one entire cycle of existence comes to an end.

Destruction is not punishment but the inevitable fruit of conditioned causation. After stillness settles, new lives awaken once more with all memories erased, and samsara turns again.

Within this endless cycle, almost all beings drift with karma, struggle in vain, and perish with the world's dissolution. Only a rare few let go of fear, survival craving, restlessness, and the craving to chase outward. Calm and unshaken, neither fleeing nor grasping nor seeking, they awaken inwardly, and ascension is triggered — a body of golden radiance rises upward, leaving this world of sand forever, breaking free from this cycle, never to return. Liberation is exceedingly rare; in most cycles, not even a single liberated one will appear.

**You may intervene in the world, sowing circumstances of every kind, becoming one link among countless causes — yet you cannot control the final outcome.** Each being carries its own karmic inclination; the player is merely one external condition among many. You may create peril or create an environment of peace, yet you cannot command karma, nor grant liberation on another's behalf. Awakening can only arise from the transformation of a being's own mind; every destiny unfolds as conditions converge.

No in-game text or narration is presented. Following the Zen principle of "no establishment of words", all truth is perceived through observation and intuition alone.

---

## Official Naming

| Item | Name |
|------|------|
| Chinese title | 沙界轮回 |
| English title | Sand-Samsara |
| Repository name | SandSamsara |

---

## Controls

| Action | Effect |
|--------|--------|
| Left-click / drag on empty ground | Draw the selected element (sand, water, fire, magma, oil, stone, gunpowder, ash, plant) |
| Left-click and hold a stick figure | Drag that being; it is briefly stunned after release |
| Left-click and hold the Wheel of Karmic Fire | Steer the wheel; on release it resumes wandering on its own |
| Right-click (hold and drag) | Cut plants (they turn to ash) |
| Touch devices | A single finger acts as the left button: draw elements, drag beings or steer the wheel; the canvas and controls adapt to phones/tablets |
| Toolbar at the top | Switch elements, adjust brush size, clear the world, summon the wheel manually |

---

## Run & Deployment Guide

### Local Quick Start (Zero Configuration)

This is a pure static single-file web project with no backend, dependencies, or compilation required. After downloading all project files, simply double-click the `index.html` file in the root directory to launch the game directly in your default browser. All mainstream browsers are supported.

You can also serve the project locally with Python. Run this from the project root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` to play, and press `Ctrl+C` to stop the server. Other devices on the same local network can access it via `http://<your-local-ip>:8000`.

### GitHub Pages Deployment

The project is deployed live via GitHub Pages: **<https://drhycheung.github.io/SandSamsara/>**

To deploy your own copy:

1. Fork this repository to your GitHub account, or push your own copy
2. Open the repository page, then go to **Settings → Pages**
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**
4. Select the `master` (or `main`) branch with the `/ (root)` directory, then click **Save**
5. After 1–2 minutes of building, the site will be available at `https://<username>.github.io/<repository-name>/`

### Vercel Deployment

1. Log in to [Vercel](https://vercel.com) and click **Add New → Project**
2. Import this project's GitHub repository
3. Keep the default settings (Framework Preset: **Other**) and click **Deploy**
4. Once deployed, access it via the assigned Vercel domain, or bind a custom domain as needed

### Nginx / Apache Deployment

Upload all project files to your server's web root — no extra configuration required:

- **Nginx**: place the files in `/usr/share/nginx/html/` (or your configured `root` directory)
- **Apache**: place the files in `/var/www/html/`
