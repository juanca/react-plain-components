# React Plain Components

Collection of useful presentational components for web applications.
These components only focus on **functionality** and **accessibility**.
There is minimal styling for purposes of laying out the components through composition.

### Why focus on just functionality and accessibility?

Web applications always have their own theme.
I believe providing open-source components with opinionated styling is a hinderance to product development.
It takes time and effort to override existing stylesheets.
It is inefficient to override and have dead styles in a stylesheet bundle.
However, the prevailing requirements is always functionality (as presented in a demo page).

I believe accessibility should always be considered as a means of lower technical debt.
It provides functionality without Javascript.
It provides guiding principles for designing components.

### How do I style a component?

Components will have a deterministic DOM structure.
By default, these nodes contain CSS classnames without any associated stylesheets.
In addition, all components can override their CSS classnames through their properties interface.
