<div align="center">

# Sand Samsara · 沙界轮回

A formless realm constructed of particles and dust. All beings drift with karma; every destiny unfolds by conditions alone.

**▶ Play Online: <https://drhycheung.github.io/SandSamsara/>**

English ｜ [简体中文](README.md)

</div>

---

## Opening Statement & Creative Provenance

Sand Samsara is a modern artistic reimagining of the 2005 classic particle sandbox game *Hell of Sand*. All karmic and samsara-themed mechanics are creative artistic interpretations, not orthodox religious doctrine. There is no in-game text or storyline. This documentation only provides background context for interested readers.

---

## Worldview & Gameplay

This work is a falling-particle sandbox art piece that constructs the Realm of Sand — a nameless world condensed from dust and particles. You are no mere spectator but an external condition within this world: with one hand you scatter sand, fire, water, magma and other substances, shaping the circumstances of this world; with the other you watch countless stick-figure beings drift through their fortunes amid the cycle of rebirth. All beings are born here in innocence, carrying no memory of past lives, knowing nothing of samsara and unable to grasp causation. Their temperaments differ: some drift numbly through muddled days; some stir restlessly, rushing about without purpose; some toil wearily, striving at all costs to avoid suffering; others cling to deep obsessions, relentlessly seeking the world's edge and yearning for everlasting existence. All their flight, struggle and pursuit arise from ignorance and deluded attachment: beings imagine they can find peace by altering outward circumstances, yet remain trapped in the fate of endless turning — merely avoiding pain and struggling to survive can never arrive at true liberation.

Hidden within this world lurks the Wheel of Karmic Fire, the concrete embodiment of the collective unwholesome karma accumulated by all beings. The wheel may be dragged and steered by the player, or traverse the world on its own; any being drawn in by its pull becomes entangled in collective karma. The more beings it draws in, the heavier the karmic bonds grow, and the vaster the wheel becomes.

As the wheel keeps expanding, the trapped beings are pressed step by step toward the world's edges. Flames breed along the borders and seal off every side, leaving them nowhere to hide. When collective karma reaches its critical point and the wheel attains its ultimate size, ripened karma triggers the collapse of the world. Fire sweeps across the whole realm; particles scatter and every landscape burns away — this age of the Sand Realm comes to an end.

The destruction of the world is not punishment but the inevitable law of causes and conditions converging. When collective karma matures, the world perishes; after stillness, it resets and is born anew — another round of unknowing beings descends once more, without memory, without past, opening yet another turn of the cycle.

In this endless turning of samsara, the vast majority of beings drift with their karma, struggle in vain, and perish with the world's dissolution. Only a rare few of clear nature can let go of fear, of the craving for survival, and of all restless chasing outwards, abiding in their own hearts, serene and unmoving. When the mind grows pure and unattached, a sublime ascension is triggered: the body turns to golden radiance wreathed in points of light, slowly rising free of the dusty world — severing this cycle of rebirth entirely, never to return. Such liberation is exceedingly rare; in most cycles, not even a single being manages to leave.

You may intervene in the world — shaping circumstances, steering the wheel — becoming one link among ten thousand causes and conditions, yet you cannot dictate the ending or command the karma of beings. Every being carries its own karma and destiny; the player's interference is merely one external condition among many. You can neither awaken on another's behalf nor appoint who ascends and departs. All fates — drifting, ruin, destruction and transcendence — arise from the convergence of innumerable causes; every destiny can only be met with acceptance.

From beginning to end, the game contains no written story, no prompts and no narrated moralising, strictly honouring the Zen principle of "no establishment of words" (不立文字) and letting players apprehend the world's patterns and philosophy purely through observation. This README exists only as an external supplement, reserved for readers interested in the project's creative background and the heart of its worldview; it forms no part of the game experience itself.

---

## Official Naming

| Item | Name |
|------|------|
| Chinese title | 沙界轮回 |
| English title | Sand Samsara |
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
