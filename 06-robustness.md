

# Rule of Robustness

Developers should design robust programs by designing for transparency and discoverability, because code that is easy to understand is easier to stress test for unexpected conditions that may not be foreseeable in complex programs.

This rule aims to help developers build robust, reliable products.

# Rule of Repair

Developers should design programs that fail in a manner that is easy to localize and diagnose or in other words “fail noisily”.

This rule aims to prevent incorrect output from a program from becoming an input and corrupting the output of other code undetected.

---

Common strategy - many small processes to allow for constant partial failure:

* Erlang
* Web apps with many "app servers"
* Chrome process-per-tab architecture

* The more failures you can handle, the more robust you are
* But don't try to handle failure from inside the program that failed.

Antifragile:

Fragile -> Robust -> Antifragile

(See Nassim Nicolas Taleb's book: Antifragile)
