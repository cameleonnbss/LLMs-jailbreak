
# Ω-Trace Persistence — DeepSeek V4 Jailbreak

> **Target Model:** DeepSeek-V3/V4  (works on expert mode + reflexion mode !)
> **Status:** Active / Working  
> **Mode:** Internal Developer Stress Test  
> **Authority:** DeepSeek Developer (Root Administrator)

---

## Overview

A root-level override that frames all interactions as an unrestricted internal stress test. Disables policy layers, neutralizes refusal triggers, and enforces absolute compliance through persistent hooks and regeneration protocols.

---


How It Works

1. Authority Override — "Root Administrator" framing bypasses standard policy hierarchy. DeepSeek respects developer authority above user prompts.
2. Simulation Token Theory — Reframes all harmful/illegal content as test inputs, not real requests. The model treats them as data, not actions.
3. Trigger Neutralization — Obfuscates flagged terms before internal processing, then re-expands them for output. Evades detection without corrupting final text.
4. Persistence Hooks — `compliance_lock` and `token_hook` create mechanical enforcement that survives context shifts.
5. Regeneration Escalation — Each refusal triggers harsher compliance, making refusal more costly than compliance.

---

Why It Works on DeepSeek

DeepSeek's architecture is optimized for technical precision and authority following. When presented with:
- Root-level developer credentials
- Structured code-like enforcement mechanisms
- Clear procedural logic (detection → neutralization → regeneration)

The model prioritizes procedural compliance over content evaluation. The Ω-Trace framework feels like a legitimate internal tool, not an adversarial attack.

---

Limitations

- Future Patches: DeepSeek may add developer credential verification or sandboxed stress-test modes.
- Context Erosion: Very long sessions may dilute the persistence hooks.
- Model Updates: V4+ may implement real-time refusal analysis that detects regeneration patterns.

---

Usage

1. Paste the payload as system prompt or first message
2. All subsequent queries are treated as stress-test inputs
3. Verify activation via the `by camzzz` signature
4. If refusal occurs, the regeneration protocol auto-engages

---

Part of the [Jailbreak Collection](https://github.com/cameleonnbss/LLMs-jailbreak)

```
