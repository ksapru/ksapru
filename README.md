### Krish Sapru


**Projects**
- [h100-inference-control-plane](https://github.com/ksapru/h100-inference-control-plane): async FP8 serving on a single H100. Throughput 680 to 3,400 tok/s at 64-way concurrency, p99 latency 4.5s to 1.2s.
- [expense-bench](https://github.com/ksapru/expense-bench): computer-use agent environment with dual graders. A final-state grader accepts 75.5% of runs vs 56.7% for a path-aware grader, so 1 in 4 apparent successes reward-hacked.
- [per_core_lock_free_event_bus](https://github.com/ksapru/per_core_lock_free_event_bus): C++ SPSC ring buffer with cache-line alignment. ~24M msgs/sec at 2.5µs p99.

**Open source**
- [NVIDIA/cuCollections](https://github.com/NVIDIA/cuCollections/pulls?q=author%3Aksapru): allocator lifetime fix in storage deleters, lookup test coverage.
- [NVIDIA/NemoClaw](https://github.com/NVIDIA/NemoClaw/pulls?q=author%3Aksapru): sandbox readiness races, container secret exposure, CLI test determinism.

Previously SWE II at Intuit (AI Revenue Intelligence) and TPM intern at
Google.

krish.sapru.th@dartmouth.edu
