# SpendWise Dashboard Shell

Modern responsive dashboard built with CSS Grid & Flexbox.

**Structure:**
- Sidebar (Flexbox column): Logo + 5 nav items + user card
- Header (Flexbox row): Title + balance KES 84,500
- Main: 6 cards - Food, Transport, Rent, Entertainment, Savings, Utilities

**Requirements:**
1. Grid: `dashboard` uses grid-template-areas sidebar/header/main, cards use repeat(3,1fr)
2. Flexbox: header, sidebar, nav items, card-top all use flex
3. Variables: :root --brand-color, --accent-color, --surface, --text-primary, --text-secondary
4. Responsive: @media max-width 768px → single column, verified in DevTools
5. Micro-interaction: 200ms transform + box-shadow on hover/focus, tabindex=0
6. Dark: prefers-color-scheme: dark overrides only variables

Run: open index.html