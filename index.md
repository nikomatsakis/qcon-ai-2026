class: center
name: title
count: false

.p60[![Symposium](./images/symposium5_vase-ferris.svg)]

## RIIIR: Rewrite It In *Idiomatic* Rust (with AI)

.me[.grey[*by* **Nicholas Matsakis**]]
.left[.citation[View slides at `https://nikomatsakis.github.io/qcon-ai-2026/`]]

---

# Who am I?

One of the lead designers of Rust

.center[.p60[![Ferris](./images/ferris.svg)]]

---

# Who am I?

Senior Principal Engineer at Amazon

.center[.p60[![Amazon logo](./images/amazon-logo.png)]]

---

# Been working on Rust a long time

---

# Not heard of Rust?

.abspos.top25.left519.width300px[![Rust](./images/rust-logo-512x512.png)]

*Low-level enough for a kernel...*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *usable enough for an application*

---

# Low-level enough for a kernel?

--

.abspos.top122.left98.width700px.bordered[![RFL](./images/rfl.png)]

--

.abspos.top282.left98.width700px.bordered[![RFL](./images/rust-in-windows-kernel.png)]

---

# High-level enough for an application?

--

.abspos.left50.top180.bordered[
<video controls autoplay muted loop style="width: 800px">
<source src="./images/ratatui.webm" type="video/webm">
</video>
]

.abspos.top563.left236[TUI oscilliscope written using ratatui]

---

# "Eat your Spinach"

.center.p80[!["You don't win friends with Salad" from the Simpsons](./images/you-dont-win-friends-with-salad.gif)]

---

.center[
    .p40[![Popeye](./images/popeye-spinach1.gif)]
    .p40[![Olive oil](./images/popeye-olive-oil.gif)]
]


---

.center[
    .p40[![Popeye](./images/popeye-spinach1.gif)]
    .p40[![Olive oil](./images/popeye-olive-oil.gif)]
]

.center[.p60[![Strong Ferris](./images/strong-ferris.jpg)]]

.footnote[
    [Strong ferris source](https://jackyzhen.github.io/rust-vs-go-slides/strongFerris.jpg)
]

---

# Amazon "then"

.abspos.top62.left153[.p80[![Aurora DSQL](./images/aurora-dsql.png)]]

.footnote[
    [Link to blog post](https://www.allthingsdistributed.com/2025/05/just-make-it-scale-an-aurora-dsql-story.html)
]

---

# Amazon "now"

--

.center.megamoj[
    🤐
]

---

# Microsoft

> My goal is to eliminate every line of C and C++ from Microsoft by 2030. Our strategy is to combine AI *and* Algorithms to **rewrite Microsoft’s largest codebases**. Our North Star is “1 engineer, 1 month, 1 million lines of code”.<br>
> <br>
> &mdash; Distinguished Engineer at Microsoft, [talking about a research project](https://www.linkedin.com/posts/galenh_principal-software-engineer-coreai-microsoft-activity-7407863239289729024-WTzf/) (emphasis mine)

???

I can neither confirm nor deny that similar things are happened at Amazon. And I'm willing to bet at many other companies.

---

.abspos.top36.left104.width700px[![Bun](./images/bun-zig-to-rust.png)]

---

# Roadrunner

.abspos.top141.left206.width600px[![Roadrunner](./images/roadrunner-bird-running.gif)]


--

.abspos.arrow.top401.left395.textbox.red[Rust before]

--

.abspos.arrow.top323.left598.textbox.red[Rust with AI]

---

# Eat your vegetables

.center.p80[![Eat your vegetables](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXY5Z2NxZGRjb3Vzam8zeWEydWNrbHJ4MWs1eWlpYWU3MDZncWJtdCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l2Jed7zxVciKPV9Qs/giphy.gif)]

---

# Roadrunner

.abspos.top147.left453.width400px[![Roadrunner](./images/roadrunner-bird-running.gif)]

--

.abspos.top167.left67.width400px[![Wily](./images/roadrunner-coyote-running.gif)]

--

.abspos.arrow.top328.left134.textbox.red[Mythos]

.abspos.arrow.top315.left617.textbox.red[C++]

.abspos.arrow.top372.left789.textbox.red[Rust]

---

# Rust is used in Android Mobile

.abspos.top98.left45.p80.bordered[!['Move fast and fix things' blog post](images/android-move-fast.png)]

.abspos.top256.left252.width600px.bordered[![Ubuntu](./images/google-memory-unsafe-code.png)]

--

.abspos.arrow.top317.left397.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top339.left463.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top385.left524.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top425.left585.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top441.left660.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top465.left723.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top477.left787.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top349.left593.textbox.purple[Notice any relationship<br>between these lines?]

---

# Not just Google

!['Rust will save linux from AI'](./images/rust-will-save-linux-from-ai.png)

--
.abspos.arrow.top256.left651.rotate135[![Arrow](./images/Arrow.png)]

--

.abspos.top351.left561.width200px[![Schitt's creek](./images/schitts-creek-shocked.gif)]

---

# If coding is cheap...

Pick a language, libraries, etc based not on the code you have now,

but based on the **code you want to maintain going forward**.

---

# When your slogan is "a stich in time, saves nine" in an agentic world...

--

.abspos.top146.left273.width400px[![Alexis happily flipping her hair!](./images/alexis-happy.gif)]

.abspos.top580.left385[Rust right now]

---

# Rust + LLM = dream-team?

* Guardrails

--
template:guardrails

.p80[![Greg Brockman saying Rust is a great language for agents](./images/greg-brockman-tweet.jpg)]

.footnote[
    Co-founder and president of OpenAI.
]


---

# Rust + LLM = dream-team?

* Guardrails
* Versatility

--

.abspos.width600px.bordered.top212.left150[![Codex adopts Rust](./images/codex-rust-rewrite.png)]

---

# Rust + LLM = dream-team?

* Guardrails
* Versatility
* Efficiency

--

.abspos.top100.left295.width600px.bordered[![Rust win](./images/rust-win-3.png)]

.abspos.top229.left40.width600px.bordered[![Rust win](./images/rust-win-2.png)]

.abspos.top332.left292.width600px.bordered[![Rust win](./images/rust-win-1.png)]

---

# Rust + LLM = dream-team?

* Guardrails
* Versatility
* Efficiency
* Investment in error messages

--

.center.megamoj[🤔]

---

# Error messages?

![Error message from the Rust compiler](./images/error-messages.png)

--

.abspos.arrow.top183.left260.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top163.left302.textbox.purple[The base error]

--

.abspos.arrow.top353.left298.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top341.left341.textbox.purple[Needed context]

--

.abspos.arrow.top441.left244.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top426.left284.textbox.purple[How to fix]

---

# So... Rust + agents are good

## But could they be better?

---
name:toasty

# Example: Toasty

![Toasty](./images/toasty-blog.png)

---
template:toasty
.abspos.arrow.top152.left1[![Arrow](./images/Arrow.png)]

---
template:toasty
.abspos.arrow.top326.left303.rotate135[![Arrow](./images/Arrow.png)]

---
template:toasty

.abspos.arrow.top389.left168.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top491.left175.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top546.left193.rotate135[![Arrow](./images/Arrow.png)]

---
name: using-toasty
# Example: Using Toasty

![Toasty](./images/toasty-use.png)

---
template: using-toasty
.abspos.arrow.top143.left237.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top129.left280.textbox.purple[Macros and custom syntax]

---
template: using-toasty

.abspos.arrow.top293.left390.rotate130[![Arrow](./images/Arrow.png)]

.abspos.arrow.top263.left424.textbox.purple[New methods]

--

* **Guardrails:** API enforces type-safety, correct column names, etc
* **Versatility:** High-level and declarative
* **Efficiency:** Compiles to efficient code

---
template: using-toasty

* **Guardrails:** API enforces type-safety, correct column names, etc
* **Versatility:** High-level and declarative
* **Efficiency:** Compiles to efficient code

.abspos.arrow.top302.left569.rotate130[![Arrow](./images/Arrow.png)]

.abspos.arrow.top278.left610.textbox.purple[Type-safe, efficient]

---

# Claude doesn't even know it exists

"What library do you recommend for working with sqlite in Rust?"

![Answer](./images/claude-sql-recs.png)

.footnote[
    For the record, these too are all excellent libraries!
]

---

# Claude, can you use toasty?

![Answer](./images/claude-make-executable-prompt.png)

---

# Claude, can you use toasty?

![Answer](./images/claude-make-executable-work.png)

--

.abspos.arrow.top163.left572.textbox.purple[That's a lot of tokens...]

---

# Claude, can you use toasty?

![Answer](./images/claude-make-executable.png)

--

.abspos.arrow.top268.left608.rotate110[![Arrow](./images/Arrow.png)]

---

# Toasty on crates.io

![Answer](./images/toasty-on-cio.png)

--

.abspos.arrow.top288.left168.rotate110[![Arrow](./images/Arrow.png)]

---

# The world is moving faster than ever

## Training data can't keep up

--

![Answer](./images/claude-make-executable.png)

--

.abspos.arrow.top566.left230.rotate180[![Arrow](./images/Arrow.png)]

.abspos.arrow.top574.left282.textbox.purple[Rust 2024 hit stable Feb 2025]

---

# Most frustrating thing of all?

--

## ...the Rust org cannot help

.center[![Help me obi-wan kanobe, you're my only help](./images/help-me-obi-wan.gif)]
.abspos.arrow.top366.left313.textbox.purple[&nbsp;&nbsp;Anthropic<sup>1</sup>&nbsp;&nbsp;]

.footnote[
    <sup>1</sup> I should say: I tried that toasty example twice, and the second time, Claude did use Toasty 0.5. But it still made a Rust crate in the 2021 edition.
]

---

# ..and this is where Symposium comes in

.center[.p60[![Symposium](./images/symposium5_vase-ferris.svg)]]

---

# Member of the Rust Foundation's Innovation Lab

![RIL](./images/RIL.png)


---

# Install symposium

```
$ cargo install symposium   # or cargo binstall!
```

--

```
$ cargo agents init
Setting up symposium for your user account.

Which agents do you use? (space to select, enter to confirm):
> [x] Claude Code
  [x] Codex CLI
  [ ] GitHub Copilot
  [ ] Gemini CLI
  [ ] Goose
  [x] Kiro
  [ ] OpenCode
```

---

# Symposium gives general guidance

* General Rust guidance, e.g.,
    * Use Rust 2024
    * Use `cargo add` to add crates so you get the latest version
    * Run `cargo fmt` after making edits

---

# Symposium lets you write skills for crates

![Toasty skill](./images/toasty-skill.png)

--

.abspos.top182.left27.arrow[![Arrow](./images/Arrow.png)]

---

# Symposium installs skills automatically

* Install hooks:
    * After every tool use, we check for new relevant skills and install them
    * **Result:** After agent runs `cargo add toasty`, it knows how to use it

---
name: crate-info
# Symposium provides APIs to help agents

```bash
> cargo agents crate-info serde
Crate: serde
Version: 1.0.228
Source: /Users/nikomat/.cargo/registry/src/index.crates.io/serde-1.0.228
```

---
template: crate-info

.abspos.arrow.top153.left219.rotate135[![Arrow](./images/Arrow.png)]

.abspos.arrow.top139.left261.textbox.purple[Correct version used by your code]

---
template: crate-info

.abspos.arrow.top237.left326.rotate210[![Arrow](./images/Arrow.png)]

.abspos.arrow.top280.left374.textbox.purple[Let the agent browse full sources]

---

# Symposium aims to make agents extensible

.center["Everybody has something unique to offer"]

.center[.p60[![Release the river](./images/release-the-river.gif)]]

.abspos.arrow.top518.left305.textbox.purple[*"Release the Rust ecosystem!"*]

---

# Symposium provides for interoperability

As a library author, write one set of extensions that work across agents...

--

...good luck with that.

---

# Even AGENTS.md is not universally supported

--

.abspos.bordered.width600px[![Agents](./images/agents.md.png)]

.abspos.bordered.width600px.top315.left224[![Agents](./images/agents.md.scoll.png)]

---

# Niko to vendors...

.abspos.top165.left222[![Help me help you](./images/help-me-help-you.gif)]

---

# Symposium does the best we can

* Library (crate) provides extensions
    * MCP servers
    * Skills
    * Hooks
--


* User picks agent

--


* Symposium adapts
    * Load skills into the right directories for the agent user chose
    * Converts between hook formats

---

# Conclusions

* If you want something to be amazing:
    * Unleash the ecosystem!

--

* Symposium aims to take a good thing (Rust + LLMs) and make it **better**:
    * Skills and extensions based on what you use
    * Up-to-date guidance

--

Use Rust? Try it now!

```
$ cargo binstall symposium
$ cargo agents init
```

.abspos.top353.left459[![Make it so](./images/make-it-so.gif)]