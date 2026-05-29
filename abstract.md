# Revised QCon AI abstract

## RIIIR: Rewrite It In *Idiomatic* Rust (with AI)

Agentic development is turning the Rust compiler's reputation as a strict taskmaster from a liability to an advantage. The Rust type system helps agents find bugs, and the resulting code runs great. And, as Bun's high-profile port to Rust showed, it's now possible to port massive codebases from one language to another in a matter of weeks. 

So yes, AI agents and Rust are an exceptionally good fit: but they could be working even better. **Symposium** is a new Rust tool that automatically installs skills, lints, and other tools based on your current project's dependencies and other setup. Symposium helps to address an ironic catch-22 with agentic development: while agents have accelerated the pace of innovation, the agents themselves are effectively a slow-moving average of the web. They do great with long established best practice but are slow to adapt to new things. Symposium helps to correct this by allowing Rust crate authors to directly steer your agent to success.

Symposium shows the power of extensibility but it also shows how the limitations of existing extension mechanisms like skills, MCP servers, and hooks. **Agent Client Protocol (ACP)** is a fast-growing protocol that can change that. ACP's original purpose was to allow editors like Zed and IntelliJ to connect in a uniform way across many agents (NN and counting), but it is also being used to power innovative tools like OpenClaw. I'll explain some of the ongoing work to turn ACP into a general-purpose extension mechanism that can be used to build the next generation of LLM-powered applications.

# Original Qcon AI abstract

There's a Mod for That: Opening Up AI Agent Development

AI agents are moving amazingly fast — but they could be moving even faster. Today's agents are monolithic: one vendor controls the model, the tools, and the context pipeline. That works, but it leaves an enormous amount of potential on the table. Every time we've opened up a platform — web APIs, app stores, game modding — the result has been an explosion of creativity that no single team could have anticipated. AI agents deserve the same openness.

This talk introduces "agent mods" — portable extensions that teach AI agents new tricks, built on the Agent Client Protocol (ACP). Agent mods go beyond MCP servers, skills, and hooks: they can inject context, provide examples, intercept messages, and transform tool output. And, because ACP is vendor-neutral, agent mods work across any ACP-supporting agent. Using Symposium, an open-source project that brings agent mods to the Rust ecosystem, I'll demo how agent mods can extend the user experience in all kinds of ways, and make the case that an extensible, community-driven approach will produce better agents than any closed system can.

# GOSIM 2026 abstract

 The Rust world moves quickly, and that's only become more true with agents writing more and more code. Frontier models know Rust basics well, but they struggle when presented with new patterns that weren't present in their training data — new language features, new libraries, idioms that diverge from the familiar. The crate authors and language designers who know best how to help have no way to reach in and guide the agent.

This talk introduces Symposium, an open-source system that changes that. Symposium lets crate authors ship skills, tools, and guidance alongside their code — so adding a dependency doesn't just give your agent new APIs to call, it gives your agent the knowledge to use them well. I'll show you how it works and discuss what it means to bring Rust's decentralized, composable ecosystem model to AI tooling.


