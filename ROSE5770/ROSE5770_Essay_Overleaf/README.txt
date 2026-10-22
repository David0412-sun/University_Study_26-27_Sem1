ROSE5770 Individual Assessment: English Overleaf project

PURPOSE
This is an AI-assisted study reference. The supplied course rules prohibit
AI-tool use for assessed work. Final work must follow those rules.

COMPILE
Upload this project ZIP to Overleaf. Set main.tex as the main document and use
pdfLaTeX. Compile twice to resolve citations and figure/table numbers.
No external images, bibliography service, shell escape or special fonts are
required. The English text uses only standard TeX packages.

LOCAL PDF PREVIEW (VS CODE / WINDOWS)
Open the University_Study_26-27_Sem1 repository folder in VS Code so its
.vscode/settings.json is loaded. With MiKTeX and LaTeX Workshop installed:
1. Open this project's main.tex.
2. Press Ctrl+Alt+B to compile using the configured "pdfLaTeX x2" recipe.
3. Press Ctrl+Alt+V to open the built-in PDF preview.
Saving a .tex file triggers another build and refreshes the open preview.
The output is main.pdf next to main.tex. The recipe runs pdfLaTeX twice to
resolve cross-references and does not require Perl, latexmk, or BibTeX.
MiKTeX may need to download missing packages on the first build.
Alternatively, run these commands from this project's directory in PowerShell:
  pdflatex -interaction=nonstopmode -halt-on-error -synctex=1 main.tex
  pdflatex -interaction=nonstopmode -halt-on-error -synctex=1 main.tex
Then open main.pdf in any PDF reader.

EDIT
metadata.tex: name, student ID and the two reported word counts.
sections/q1.tex and sections/q2.tex: the two English answers.
tables/tab1_autonomy.tex and tables/tab2_modules.tex: editable table sources.
figures/tikz/: the three editable, original schematic sources.
references.tex: compiled APA 6th-style references to original publications.
references.bib: complete BibTeX metadata for reuse; not loaded by main.tex.
source_notes.txt: source tracing, claim support and attribution boundaries.
When changing the bibliography, keep references.tex and references.bib aligned.

AUTOMATIC IMAGE REPLACEMENT
Upload a clear scan or photograph to replacements/ with the appropriate name:
  fig1_framework.pdf : autonomous architecture
  fig2_mission.pdf   : delivery mission flow
  fig3_recovery.pdf  : moving-deck recovery
  tab1_autonomy.pdf  : optional replacement for the autonomy table
  tab2_modules.pdf   : optional replacement for the module-method table

PNG, JPG and JPEG are also supported with exactly the same base names.
The search order is PDF, PNG, JPG, JPEG. Keep only your preferred version.
Filenames are case-sensitive. Do not replace the .tex fallback source with an
image. The replacement keeps its existing caption, numbering and label.
Images are scaled proportionally inside the page. Crop excessive photo borders
before uploading. Missing image files automatically use the supplied TikZ/table.

WORD COUNTS
The prose is organised as connected essay paragraphs under the two subquestions.
Question 1: 654 English words.
Question 2: 646 English words.
Counts include author-date citations, and exclude
section headings, tables, diagrams/captions and references. Hyphenated words
count as one. These are reproducible token counts, not a guarantee that a
particular submission portal uses an identical tokenizer. Both have ample
margin under 800. The plain text used for counting is in sections/q1_wordcount.txt
and sections/q2_wordcount.txt. Recompute counts after editing the answers.
A second audit splits hyphenated compounds and includes the question headings:
Q1 = 676 words; Q2 = 673 words. See word_count_audit.txt. Both remain below 800.

SOURCE SCOPE
Technical references use original journal articles, conference papers, a book,
a government report and official technical documentation. Sources are verified
through publisher records, author manuscripts or official documentation.
The original supplied set covers Lectures 1-5 and Lecture 7 Part 1. Lecture 6
was not supplied. See source_notes.txt for which references were explicitly
identified in that material and which are additional primary-method sources.
All technical page references now mean printed pages of the original source.
The original DoD report labels Level 4 Fully Autonomous, without Ideal; it
permits emergency intervention and changed human goals. Examples apply the
taxonomy to stated tasks and are not formal product classifications.

DESIGN ASSUMPTIONS
The delivery scenario assumes bounded UGV speed/acceleration, a usable moving
recovery deck, and an accessible balcony tray with a registered visual ID.
Balcony-specific YOLO training, payload interlocks, report acknowledgement,
winch delivery and moving-deck gates are proposed engineering integrations.
The cited publications support individual methods. The full delivery mission
is a proposed integration. Recovery tolerances need platform-specific testing.

FIGURE NOTES
Figure 1: preserve labelled forward commands and feedback routes.
Figure 2: preserve target verification, delivery confirmation and report receipt
as distinct checks. This is a mission flowchart, not a literal behaviour tree.
Figure 3: match horizontal velocity during descent. Vertical relative velocity
approaches zero at touchdown; zero vertical relative speed throughout descent
would prevent closing the height above the deck.

ASSIGNMENT CHECKLIST FROM THE SUPPLIED BRIEF
Two short essays; each at most 800 words excluding references/tables/diagrams.
Name, student ID and word count must be indicated. Use self-created drawings.
References use APA 6th. Deadline: 26 October 2026 at 23:59 (Hong Kong time).
Both Blackboard and VeriGuide submissions are required by the brief.
Originality-check results cannot be predicted from this project.
