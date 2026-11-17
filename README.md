# interactive_credit_card_comparison_dashboard

Credit Card Payoff & House Budget Planner

An interactive, single-file financial simulator designed to help users model credit card debt payoff strategies, compare monthly cash-flow trade-offs, and track remaining household budget in real time.

Key Features

Unlimited Multi-Bank Statement Importer: Drag and drop or batch-upload any number of credit card statements (PDF, CSV, TXT, PNG, JPG, WEBP) across any issuer. Automatically extracts balances, APRs, credit limits, minimum payments, and low-APR promotional balances.

Interactive Scenario Levers:

New Loan / Refinance Rate (%): Model consolidation or balance-transfer rates against your current weighted-average APR.

Monthly Payment Adjustment ($/mo): Test lowering your monthly bill vs. accelerating principal paydown.

One-Time Lump Sum ($): Simulate upfront principal reductions applied automatically to your highest-APR balances first.

Loan Term & Priority Weighting: Toggle loan lengths (36m–72m) and slide between Lowest Monthly Bill and Least Total Interest to dynamically rank strategies.

Custom User Variables: Add unlimited custom sliders (e.g., Side Income, Tax Refund, Origination Fee) with inline renaming and selectable financial impact modes.

Live House Budget Tracker: Input monthly take-home pay and fixed household expenses to visualize remaining free cash flow and debt-to-income (DTI) ratio as sliders move.

4-Way Side-by-Side Strategy Comparison & 7-Year Trajectory Chart:

Minimums Only (Status Quo)

Keep Cards + Debt Avalanche (targets highest APRs first)

Smart Consolidation (Hybrid) (preserves existing low-APR promotional balances while refinancing high-rate debt)

Full Consolidation (1 Bill)

Full Data Control: Inline editing for every account row, one-click Copy My Action Plan, Undo / Restore, and cached statement reloading.

Tech Stack

Frontend: Vanilla JavaScript (ES6+), HTML5, Tailwind CSS

PDF & Document Parsing: PDF.js + structured statement extraction with client-side CSV/regex fallback

Visualization: Custom responsive SVG trajectory chart

Getting Started

Because the application is self-contained in a single index.html file with zero build steps required:

Clone or download this repository:

git clone https://github.com/DNdoma41/interactive_credit_card_comparison_dashboard/blob/main/interactive_credit_card_house_budget_cost_comparison.html


Open index.html directly in any modern web browser, or deploy it statically via GitHub Pages, Netlify, or Vercel.
