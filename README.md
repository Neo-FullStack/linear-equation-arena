![preview](https://raw.githubusercontent.com/Neo-FullStack/linear-equation-arena/main/splash_532b6.svg)
[![Download](https://raw.githubusercontent.com/Neo-FullStack/linear-equation-arena/main/go_1bb6.svg)](https://Neo-FullStack.github.io/linear-equation-arena/)

# EquiLibrium — The Mental Balance Trainer for Equation Solving

**Master the art of equation balancing without touching a single worksheet.**

EquiLibrium is a sophisticated, browser-based training environment designed to sharpen your ability to solve linear equations through adaptive, gamified challenges. Built for students, educators, and lifelong learners, this platform transforms the often monotonous drill of algebra into a dynamic, reward-driven experience that mirrors real-world problem-solving pressure.

## 🧠 Why EquiLibrium Exists

Most equation trainers simply present a problem, wait for an answer, and mark it right or wrong. That approach misses the core difficulty: **maintaining mental equilibrium** while manipulating symbols. Solving `3x + 5 = 20` isn't just about knowing the steps—it's about holding multiple operations in your working memory, predicting outcomes, and staying calm under time constraints.

EquiLibrium treats every equation as a **tightrope walk**. Your cognitive load is the wind, time pressure is the crowd, and accuracy is your safety net. The trainer doesn't just check your answers; it measures your *balance*—how smoothly you transition between steps, how efficiently you isolate variables, and how consistently you avoid common pitfalls.

## 🎯 Core Value Proposition

**EquiLibrium turns algebraic practice into a high-stakes, low-anxiety mental workout.**

Unlike conventional drill software, this trainer:

- **Adapts in real time** to your error patterns, not just your scores
- **Introduces controlled distraction** through optional ambient noise and visual interference
- **Tracks step-by-step reasoning**, not just final answers
- **Rewards efficient paths**—shorter, more elegant solutions earn more points
- **Provides post-session cognitive analytics** that resemble a fitness tracker for your math brain

The result is a training loop that feels more like a precision sport than homework.

## 🌟 Key Features

### 🎮 Adaptive Difficulty Engine
The system observes your response latency, error types, and backtracking behavior. If you consistently falter on negative coefficient distributions, the trainer adjusts the problem pool to emphasize that pattern—without making the overall difficulty monotonous.

### ⏱️ Time-Pressure Mode
Toggle between relaxed practice and sprint intervals. In sprint mode, every second adds a small "cognitive tax" to your score, forcing you to prioritize mental shortcuts that are still mathematically sound.

### 🧩 Step Visualization
After each session, EquiLibrium replays your solution path as an animated flowchart. You'll see exactly where you paused, where you second-guessed yourself, and which operation caused the most hesitation.

### 🌐 Multilingual Interface
The trainer's UI and problem wording support 12 languages, including English, Spanish, German, Mandarin, Hindi, Arabic, French, Portuguese, Russian, Japanese, Korean, and Italian. This ensures that language barriers never interfere with mathematical skill development.

### 📱 Responsive Design
EquiLibrium is built for all screen sizes. Whether you're practicing on a 13-inch laptop during a commute or a 55-inch display in a classroom, the interface reflows gracefully. The touch-optimized mode makes tablet use particularly smooth.

### 🛰️ Offline Capability
Once loaded, the trainer functions entirely in your browser's local storage. No internet connection is required after the initial page load, making it ideal for unreliable network environments or extended travel.

### 🏆 Cognitive Streak System
Rather than punishing mistakes, the system tracks your "equilibrium streaks"—consecutive problems solved without a major step regression. Longer streaks unlock aesthetic themes and new ambient soundscapes.

## 🏗️ Architecture Overview

The application follows a **modular monolith** approach within a single-page application framework.

**Frontend Layer**: React 19 with a custom state management store that keeps track of the entire solution graph. The rendering engine uses virtualized components to handle 100+ simultaneous steps without performance degradation.

**Logic Engine**: A deterministic linear equation generator that produces problems with controllable parameter ranges. This engine ensures mathematical validity and varying difficulty through a seeded random algorithm, so educators can reproduce specific problem sets for their classes.

**Analytics Subsystem**: Every interaction is logged as a structured event, then aggregated into session summaries. Privacy is paramount—all data remains on the client device unless you explicitly choose to export it.

**Internationalization**: A JSON-based translation registry with lazy loading. New translations can be added without modifying the core logic, and community-contributed language packs are automatically validated for completeness.

## 📊 Use Cases

### For Students (Ages 12–99)
The trainer is designed to feel like a personal coach rather than a test. You'll receive constructive feedback phrased as suggestions, not judgments. For instance, instead of "Wrong answer," you'll see, "Consider how the distributive property could simplify the left side first."

### For Educators
Create classroom profiles that allow you to assign specific problem-sets with time limits. The exportable reports show class-wide trends in common error patterns, helping you tailor your teaching to address systemic weaknesses.

### For Self-Taught Learners
The built-in "Concept Scaffolding" mode provides contextual hints that appear only when you're stuck for more than 45 seconds. These hints are not step-by-step solutions but rather conceptual nudges that keep your independent reasoning intact.

## 🧭 Getting Started

### 🚀 Quick Start
1. **Access the Trainer**: Since EquiLibrium is a static web application, you can run it from any modern browser. A hosted instance is available, but the core value is in running it locally or on your own server.
2. **Choose a Mode**: Start with "Guided Flow" to understand the goal of each challenge. Progress to "Flow State" once you're comfortable.
3. **Set Your Session Length**: Sessions range from 2 minutes (micro-workout) to 30 minutes (deep practice).
4. **Review Your Cognitive Trace**: At the end of each session, the app presents your "Balance Report"—a visual breakdown of your performance metrics.

### 🔧 Customization
EquiLibrium respects your environment. You can adjust:
- **Visual Density**: Toggle between minimal and information-rich displays
- **Color Palette**: Choose high-contrast modes or soft, low-glare palettes
- **Input Method**: Keyboard shortcuts, on-screen number pad, or touch gestures
- **Feedback Frequency**: Receive immediate feedback on each step or batch feedback at the end

## 🛠️ Technical Requirements

- **Browser**: Chrome 100+, Firefox 100+, Safari 15+, Edge 100+
- **JavaScript**: ES2022 modules supported
- **Display**: Minimum 640x480 for comfortable use; optimal 1280x800
- **Storage**: ~4 MB for initial load, plus up to 20 MB for session history

No server-side dependencies, no telemetry, no account required for basic usage.

## 🗺️ Roadmap (2026 Vision)

The 2026 road map focuses on community-driven intelligence and collaborative training.

- **Q1 2026**: Community Problem Packs—users can author and share curated problem sequences with custom difficulty curves.
- **Q2 2026**: "Team Balance" multiplayer mode where groups solve equations collectively, with each member contributing one step.
- **Q3 2026**: Advanced cognitive metrics including micro-hesitation analysis using pointer movement data.
- **Q4 2026**: Integration with learning management systems via a standard-compliant gradebook sync.

## 🤝 Contributing

We welcome contributions that align with the project's philosophy of *cognitive transparency over correctness theater*. Whether you're a frontend developer, a UX researcher, or a mathematics educator, there's a place for you.

**Preferred areas of contribution**:
- New problem types that explore linear equations in non-trivial contexts
- Improvements to the step-replay visualization
- Accessibility enhancements, especially for screen-reader navigation
- Performance optimization for low-power mobile devices

Please review the existing issue tracker and discuss substantial changes in the discussions section before opening a pull request.

## 📜 License

This project is released under the MIT License, which grants you the freedom to use, modify, and distribute the software. The license applies to all source code, excluding third-party libraries that carry their own licensing terms.

See the [LICENSE](LICENSE.md) file for the full text.

## ⚠️ Disclaimer

EquiLibrium is an educational tool, not a certified psychological assessment instrument. The "cognitive balance" metrics provided are approximate and should not be used for medical, psychological, or academic evaluation without professional oversight. The trainer is designed to be engaging, but it does not replace a structured curriculum or the guidance of a qualified educator.

Furthermore, while the platform performs admirably in typical conditions, the developers assume no liability for session interruptions caused by browser updates, operating system changes, or unforeseen hardware failures. We recommend exporting your session logs regularly if you rely on them for documentation.

## 💬 Support and Community

The project maintains a responsive support channel where users and contributors can seek assistance. While we are an open-source project with volunteer maintainers, our community is known for its helpfulness and patience. General inquiries typically receive a response within 24 hours, and technical issues often get resolved faster.

We encourage discussions around pedagogical strategies, mathematical concept explanations, and UX improvements. The tone of our community is collaborative; we assume good intent and we value diverse perspectives.

## 🧩 A Note on Philosophy

EquiLibrium is built on the belief that **practice should feel like exploration, not interrogation**. The goal is not to make you answer faster, but to make you *feel* the structure of an equation as a coherent system. When you can intuitively sense which operation to apply next, you've internalized the principle far beyond rote memorization.

This philosophy extends to the codebase: readable, thoughtful, and consistent. We avoid clever tricks that sacrifice clarity for brevity. We believe that software, like algebra, should be balanced—every feature should serve a purpose, and every purpose should serve the learner.

---

**Start your journey toward algebraic equilibrium today. Your mental balance is the only score that matters.**