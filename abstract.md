# Revised QCon AI abstract

## RIIIR: Rewrite It In *Idiomatic* Rust (with AI)

Agentic development has turned the Rust compiler's reputation as a strict taskmaster from a liability to an advantage. The Rust type system helps agents find bugs and the resulting code runs great.

But agents and Rust could be working even better. **Symposium** is a new Rust tool that automatically installs skills, lints, and other tools based on your current project's dependencies. It addresses a core tension: while agents have accelerated the pace of innovation, agents themselves lag behind the ecosystem's pace of change. Symposium corrects this by allowing Rust crate authors to directly steer your agent to success.

Symposium shows the power of extensibility — but also the limitations of existing extension mechanisms like skills, MCP servers, and hooks. **Agent Client Protocol (ACP)** is a fast-growing protocol being extended into a general-purpose mechanism for building the next generation of LLM-powered applications. I'll explain the ongoing work to make that happen.

# Original Qcon AI abstract

There's a Mod for That: Opening Up AI Agent Development

AI agents are moving amazingly fast — but they could be moving even faster. Today's agents are monolithic: one vendor controls the model, the tools, and the context pipeline. That works, but it leaves an enormous amount of potential on the table. Every time we've opened up a platform — web APIs, app stores, game modding — the result has been an explosion of creativity that no single team could have anticipated. AI agents deserve the same openness.

This talk introduces "agent mods" — portable extensions that teach AI agents new tricks, built on the Agent Client Protocol (ACP). Agent mods go beyond MCP servers, skills, and hooks: they can inject context, provide examples, intercept messages, and transform tool output. And, because ACP is vendor-neutral, agent mods work across any ACP-supporting agent. Using Symposium, an open-source project that brings agent mods to the Rust ecosystem, I'll demo how agent mods can extend the user experience in all kinds of ways, and make the case that an extensible, community-driven approach will produce better agents than any closed system can.

# GOSIM 2026 abstract

 The Rust world moves quickly, and that's only become more true with agents writing more and more code. Frontier models know Rust basics well, but they struggle when presented with new patterns that weren't present in their training data — new language features, new libraries, idioms that diverge from the familiar. The crate authors and language designers who know best how to help have no way to reach in and guide the agent.

This talk introduces Symposium, an open-source system that changes that. Symposium lets crate authors ship skills, tools, and guidance alongside their code — so adding a dependency doesn't just give your agent new APIs to call, it gives your agent the knowledge to use them well. I'll show you how it works and discuss what it means to bring Rust's decentralized, composable ecosystem model to AI tooling.


