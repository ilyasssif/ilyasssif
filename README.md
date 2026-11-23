# Hi, I'm Ilyass Sif

**Networking & Systems Engineer** · Interested in **AI & Agentic Systems** · Based in Morocco

---

### About Me
- Focused on **networking**, **Linux / OS internals**, and **low-level C/C++ systems engineering**.
- Interested in applying **AI and agentic workflows** to networking, tooling, and systems problems.
- Active open-source contributor working on C++20 runtime hardening, Python diagnostics, and Linux/Vulkan verification.

### Open Source Contributions
- **[ItsNotRexed/Leonida](https://github.com/ItsNotRexed/Leonida)** — C++20 runtime, Vulkan/Linux testing, and Python tooling ([view all PRs](https://github.com/ItsNotRexed/Leonida/pulls?q=is%3Apr+author%3Ailyasssif)):
  - **Merged:** [#6863](https://github.com/ItsNotRexed/Leonida/pull/6863) — `xcl_compare`: preserve `trace_<attempt>.jsonl` files across hang restarts ([`3d7fcd6d8`](https://github.com/ItsNotRexed/Leonida/commit/3d7fcd6d8)).
  - **Open PRs:**
    - [#6971](https://github.com/ItsNotRexed/Leonida/pull/6971) — `arena_size`: clamp negative `LEONIDA_ARENA_MB` to 16 MiB floor instead of unsigned wraparound to 4095 MiB.
    - [#7219](https://github.com/ItsNotRexed/Leonida/pull/7219) — `active_input`: guard against unsigned timestamp underflow in debounce check.
    - [#7271](https://github.com/ItsNotRexed/Leonida/pull/7271) — `mods`: refuse bare `0x`/`0X` prefix in `parse_model_id` instead of hashing it.
    - [#7364](https://github.com/ItsNotRexed/Leonida/pull/7364) — `shader_library`: strict `uint32_t` bounds check on `f16_halves` keys.
  - Verified community Vulkan & SPIR-V PRs on Linux (GCC 15 / Clang / NVIDIA RTX 4050).

### Selected Projects
- **[GNS3-D](https://github.com/ilyasssif/GNS3-D)** — AI agent for GNS3 networking environments (`Python`)
- **[OS101](https://github.com/ilyasssif/OS101)** — Operating systems & low-level systems fundamentals (`C`)
- **[AgenticECS](https://github.com/ilyasssif/AgenticECS)** — Entity Component System exploration (`C++`)
- **[HaxGym](https://github.com/ilyasssif/HaxGym)** — Reinforcement learning / Gym environment (`Python`)

### Tech Stack
- **Systems & Languages:** C, C++20, Python, Bash, Linux
- **Networking:** GNS3, TCP/IP, routing & switching, Linux networking
- **Tooling & AI:** Git, CMake, Ninja, GCC/Clang, Vulkan testing, AI agents & ML tooling
