# World Model Planner

A Rust implementation of a cross-entropy-method planner over a compact learned-dynamics surrogate. Optimizes action sequences and adds a simple uncertainty penalty to predicted cost.

Run `cargo run --release`. This is a planning-method prototype; the surrogate is explicit and replaceable, and the planner must be evaluated against a real environment to detect model exploitation.
