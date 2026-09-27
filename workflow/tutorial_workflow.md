# Parent workflow for future math tutorials

1. Agree on the learning goal, a short mental model, and a sample before building. Keep parent-facing explanations concise.
2. Write for a fourth grader. Use examples and brief reasoning questions to help the child eventually choose steps independently.
3. Use italic 𝑥 for the unknown and × for multiplication everywhere: examples, blanks, answers, headings, and revision notes. Explain that 3𝑥 means 3 × 𝑥. In Typora math blocks use `\mathit{x}` and `\times`; in ordinary text and fixed-width blocks use 𝑥 and ×.
4. Keep unchanged terms directly below themselves and equals signs in one column. Move terms only for an explicit rearrangement, carrying each sign along. Use fixed-width layouts or aligned math arrays.
5. Show every mathematical step on its own line. Do not skip the product breakdown, the operation applied to both sides, or multiplication of each term inside brackets. Provide enough working lines for the full solution.
6. Start each new idea with a complete worked example. Progress through empty brackets and missing values, labeled lines, and independent blank lines. Fade prompts, not the expectation to show steps.
7. Begin with single-side expressions: sort numbers and matching variable terms, then combine. Introduce easy equations next, followed by sorting on each side, 𝑥 on the right, and subtraction undone by addition.
8. Explain cancellation through opposite terms making zero. Show the same operation on BOTH sides before canceling. Use forward diagonal slashes through the signed terms with `\cancel{...}` in Typora math blocks; avoid horizontal strikethroughs and unexplained sign-changing shortcuts.
9. Put the common factor BEFORE the brackets. Show: 12 + 18 → (6 × 2) + (6 × 3) → 6 × (2 + 3) → 6 × 5 → 30, with each step on a separate line in the child's material. Begin with familiar units such as thousands and hundreds, then connect to 𝑥 terms.
10. Increase difficulty gradually through equal groups, common factors, multiplication, division, brackets, and two-step equations. Occasionally include larger arithmetic after the underlying idea is familiar; provide scratch space.
11. Organize by learning transitions into four topic-based booklets, each with a short cover page. Use large print and generous working space. Omit name and date fields. Keep the 40 core sections; allow extra pages when explicit steps need room.
12. Deliver Typora-friendly Markdown, a concise child revision reminder, and a separate parent answer file. Maintain the reusable instructions in workflow/tutorial_workflow.md and mirror them at the bottom of output/complete_workbook.md and output/parent/answers_and_workflow.md. Keep all copies synchronized.
13. Check problems, answers, mathematical equivalence, notation, cancellation, and alignment after changes. Check Typora print preview for page breaks and font rendering before printing. Encourage alternate valid routes and checking answers in the original equation.
