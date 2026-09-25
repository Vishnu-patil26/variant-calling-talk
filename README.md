# Variant Calling & Where ML Fits

A ten-minute talk for fourth-year Computer Engineering students: what the GATK
variant calling pipeline does to a genome, and where machine learning actually
enters it — mapped onto the CSC701 syllabus.

**Two cuts of the same talk**

| | Length | Link |
|---|---|---|
| **Full** | ~30 min, 117 steps | https://vishnu-patil26.github.io/variant-calling-talk/ |
| **Short** | ~10 min, 44 beats | https://vishnu-patil26.github.io/variant-calling-talk/10min/ |

The short cut is the same sixteen slides and the same animations — it just
stops on fewer of them. Every algorithm is still in it: CART and the Gini
index, k-means, EM on a Gaussian mixture, PCA, the random forest, and the
confusion matrix through to ROC.

Every number on the slides came off a real GRCh38 chr20 run: 1,775 variants,
1,743 of them PASS. Nothing is simulated.

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
