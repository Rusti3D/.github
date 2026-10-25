# Rusti3D

Rusti3D is an open-source initiative exploring new possibilities for the software behind 3D printing. We take existing tools, rethink how they work, and experiment with what they could become.

Our projects don't start with the usual question, *"What problem are we trying to solve?"* We start with *"What if?"*

> **Credit where it's due:** Our work builds on projects created by talented developers and maintainers. We respect their contributions and encourage everyone to support the upstream projects that inspire ours.


## How We Work 💼

We lean heavily on AI-assisted development to experiment, challenge assumptions, and bring ambitious ideas to life. Much of the code you see here is AI-generated, with a human developer in the loop, reviewing results, and keeping things on track.

Our projects are experimental by nature. We strive to make our software useful, reliable, and safe, but not everything will be polished, and not every idea will pan out.

We take care not to knowingly release software that could damage your printer, but **our projects are provided as-is and used at your own risk.**


## Projects 📁

* **Rusticc**: A custom distribution of the Open Centauris Cosmos ecosystem.
* **Kaliru**: A fresh take on Kalico and Klipper, exploring performance and efficiency.
* **Moonruster**: A Rust-based API server inspired by Moonraker.


## How to Contribute 👨‍💻

Have an idea? Open an issue describing what you'd like to improve or explore, and we'll take it from there.<br>
Prefer to get hands-on? Fork a project, define a clear goal, and open a pull request when you're ready.

We review contributions as time allows. Clear explanations and evidence of your results are always required.


## Development Workflow 🔧

We value curiosity, but experimentation works best when it's methodical. Before changing existing software, understand why it works the way it does. Every change should have a clear purpose, a testable hypothesis, and evidence to support its results.

1. **Understand the existing implementation.** Read the relevant code, follow the execution path, review project conventions, and identify existing assumptions and dependencies. Don't change what you don't yet understand.

2. **Form a hypothesis.** Define what you want to improve, why you expect it to work, and how you'll measure success. Establish a baseline where possible so improvements can be demonstrated rather than assumed.

3. **Implement a focused change.** Follow existing project conventions and keep the scope appropriate. Avoid unrelated refactoring, unnecessary complexity, and changes that risk breaking features outside the scope of your work.

4. **Validate your hypothesis.** Test your implementation against the original baseline. Back up performance claims with numbers, consider edge cases, and verify behavior on real hardware whenever possible. Passing a build is not proof that an implementation works as intended.

5. **Iterate and report.** If the results don't support your hypothesis, investigate, revise, and test again. Document what changed, how it was tested, and what the results demonstrate.

**Our principles are simple:** Understand before changing. Measure instead of guessing. Test beyond the happy path. Verify on real hardware. Keep changes focused.

The goal isn't just to make something work. It's to demonstrate that it works, understand its trade-offs, and avoid creating more problems than we solve.


## Working with AI Agents 🤖

AI-assisted contributions are welcome, provided they produce clean, tangible results and follow this workflow from start to finish. For best results, provide our development workflow to your agent verbatim. <br>

AI-generated code is not exempt from scrutiny: implementations must be understood, hypotheses validated, claims backed by evidence, and behavior verified. <br>

The contributor is responsible for the quality and correctness of the result, regardless of which tools or agents were used to produce it.
