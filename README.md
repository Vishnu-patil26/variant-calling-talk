# Variant Calling & Where ML Fits

A ten-minute talk for fourth-year Computer Engineering students: what the GATK
variant calling pipeline does to a genome, and where machine learning actually
enters it — mapped onto the CSC701 syllabus.

**Three versions of the same talk**

| | Shape | Link |
|---|---|---|
| **Full** | 16 slides, 117 steps, ~30 min | https://vishnu-patil26.github.io/variant-calling-talk/ |
| **Compact** | 10 slides, 3 beats each, ~10 min | https://vishnu-patil26.github.io/variant-calling-talk/compact/ |
| **Step-filtered** | 16 slides, 44 beats (superseded) | https://vishnu-patil26.github.io/variant-calling-talk/10min/ |

The **compact** version is the one to present. It is not the full deck with
steps removed — each of its ten slides carries three beats with copy written
for that beat, so no line depends on a step the audience never saw. Every
algorithm survives: CART and the Gini index, the E and M steps on a Gaussian
mixture, PCA, the random forest, and the confusion matrix through to ROC.

The step-filtered version is kept only so its link does not break; it drops
steps without rewriting the captions, so some lines refer to things that are
no longer on screen.

## Running it

`index.html` is one self-contained file — no build step, no server, no other
files. Open it in any browser, or double-click it after downloading.

## Controls

| Key | Does |
|---|---|
| `space` · `→` · `PageDown` | next step — carries into the next slide at the end |
| `backspace` · `←` · `PageUp` | previous step — carries back into the previous slide |
| `↓` `↑` or `n` `p` | jump a whole slide |
| `Home` / `End` | first / last slide |
| `o` or `Esc` | slide overview — click any slide to jump |
| `f` | fullscreen |

Clicking the slide also advances a step. Each slide remembers where you left it.
