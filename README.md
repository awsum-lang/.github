# Awsum
Correctness-first, cross-target functional language.

**Correctness-first:** No numeric overflow, underflow, or precision loss. No `NaN`, `null`, `nil`, or `undefined`. No `throw`, no `catch`, no `panic` — errors are values. No stack overflow on tail, non-tail, or even mutual recursion. This trade-off is deliberate: correctness comes ahead of runtime performance, compile speed, and syntactic convenience.

**Cross-target:** The same source compiles to Native (LLVM), JVM, CLR, WASM, or JS, and produces the same result on every one — independent of each target's quirks and built-in types. The compiler accepts only the effects supported by the chosen target and program type.
