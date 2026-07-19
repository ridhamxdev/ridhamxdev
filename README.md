<!-- ══════════════════════ HEADER ══════════════════════ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6EE7B7,50:3B82F6,100:9333EA&height=200&section=header&text=Ridham%20Goyal&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20Software%20Engineer&descAlignY=55&descSize=18" />

<div align="center">

<a href="https://github.com/ridhamxdev">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=3B82F6&center=true&vCenter=true&width=520&lines=Building+things+that+matter.;Node.js+%7C+React+%7C+Python+%7C+Java;Currently+grinding+DSA+on+LeetCode;Let's+build+something+together+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<a href="mailto:ridhamgoyal3@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="Ridham_Goyal_Resume.pdf"><img src="https://img.shields.io/badge/Resume-2563EB?style=for-the-badge&logo=readdotcv&logoColor=white" /></a>
<a href="https://github.com/ridhamxdev"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=ridhamxdev&style=for-the-badge&color=6EE7B7&label=VISITORS" />

</div>

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" />

---

## 🧠 About Me

```ts
const ridham = {
  role:      "Full-Stack Software Engineer",
  focus:     ["Clean architecture", "Impactful products", "Details nobody notices"],
  learning:  ["Data Structures & Algorithms", "The React ecosystem, deeply"],
  believes:  "Technology is a vehicle for meaningful change, not a flex.",
  reach:     "ridhamgoyal3@gmail.com",
};
```

<details>
<summary><b>📖 A little more (click me)</b></summary>

<br/>

- 🔭 I build across the stack — from schema design to the last pixel of the UI.
- ✍️ I care about written communication almost as much as code. Good docs age better than clever code.
- 🧩 I like problems where the constraint *is* the interesting part.
- ⚡ Fun fact: most of my best debugging happens away from the keyboard.

</details>

---

## 🛠️ Tech Arsenal

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=js,ts,python,java,cpp,html,css&theme=dark" />

**Frameworks & Libraries**

<img src="https://skillicons.dev/icons?i=react,nodejs,express,redux,tailwind,rabbitmq,redis&theme=dark" />

**Databases & Cloud**

<img src="https://skillicons.dev/icons?i=mongodb,mysql,postgres,sequelize,docker,aws&theme=dark" />

**Tools**

<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,linux,figma&theme=dark" />

</div>

---

## 📊 The Numbers

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=ridhamxdev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=ridhamxdev&theme=tokyonight&hide_border=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ridhamxdev&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=ridhamxdev&theme=tokyo-night&hide_border=true&area=true" />

<img src="https://github-profile-trophy.vercel.app/?username=ridhamxdev&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" />

</div>

---

# 🎮 Mini-Game: **Escape the Null Pointer**

> You are a junior dev. It is 11:58 PM. Production is down.
> Every choice is a `<details>` block — click to descend. Only one path ships the fix.

<details>
<summary>▶️ <b>PRESS START</b></summary>

<br/>

**PagerDuty screams. The dashboard is a wall of red 500s.** What do you do?

<details>
<summary>🅰️ Roll back the last deploy</summary>

<br/>

Rollback succeeds. Errors drop... then climb again. It wasn't the deploy.

<details>
<summary>➡️ Check the database connection pool</summary>

<br/>

`max_connections: 100`. Active: **100**. Waiting: 4,812.
Something is opening connections and never closing them.

<details>
<summary>🔎 Grep for connections opened inside a loop</summary>

<br/>

```diff
- for (const id of userIds) { const db = await connect(); ... }
+ const db = await connect();
+ for (const id of userIds) { ... }
```

### 🏆 **YOU WIN.** Errors flatline. It's 12:41 AM. You write the postmortem *before* going to bed, because you're that person.

**Achievement unlocked: `Root Cause > Symptom`**

</details>

<details>
<summary>🔁 Just raise max_connections to 1000</summary>

<br/>

💀 **GAME OVER.** It holds for six minutes. Then the database OOMs and takes the read replica with it.
*Scaling a leak only makes a bigger puddle.*

<sub>↩️ Collapse and try another branch.</sub>

</details>

</details>

<details>
<summary>🍕 Order pizza and wait for the senior dev</summary>

<br/>

💀 **GAME OVER.** The senior dev is on a flight. The pizza is cold. So is the incident channel.

<sub>↩️ Collapse and try another branch.</sub>

</details>

</details>

<details>
<summary>🅱️ Read the actual stack trace</summary>

<br/>

`TypeError: Cannot read properties of undefined (reading 'id')` — 12,000 times, all from `/api/checkout`.

<details>
<summary>➡️ Add optional chaining and ship the hotfix</summary>

<br/>

⚠️ **PARTIAL WIN.** The 500s stop. But now checkouts silently fail with a 200.
Users are "buying" nothing. Support tickets incoming in 3... 2...

*Lesson: silencing an error isn't the same as handling it.*

</details>

<details>
<summary>➡️ Ask WHY the user object is undefined</summary>

<br/>

The auth service started returning `{ data: { user } }` instead of `{ user }`.
Someone shipped a breaking API change without a version bump.

### 🏆 **YOU WIN.** You pin the contract, add a schema test in CI, and no one loses a night to this again.

**Achievement unlocked: `Fix the Class, Not the Instance`**

</details>

</details>

<details>
<summary>🅲 Restart the server</summary>

<br/>

It works! For 90 seconds. Then it doesn't.
You have learned nothing, but you have bought 90 seconds.

<sub>↩️ Collapse and pick 🅰️ or 🅱️ — the clock is still running.</sub>

</details>

</details>

<br/>

<details>
<summary>🥚 <i>...you found the easter egg</i></summary>

<br/>

```
      ¯\_(ツ)_/¯
   "It works on my machine"
        — everyone, once
```

If you actually clicked through every branch, email me. I owe you a coffee. ☕

</details>

---

<div align="center">

### 💬 Let's build something

If you're working on something that matters — or something ridiculous — I'd like to hear about it.

<a href="mailto:ridhamgoyal3@gmail.com"><img src="https://img.shields.io/badge/Say%20hello-3B82F6?style=for-the-badge&logo=minutemailer&logoColor=white" /></a>

<img src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg" width="100%" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:9333EA,50:3B82F6,100:6EE7B7&height=140&section=footer" />
