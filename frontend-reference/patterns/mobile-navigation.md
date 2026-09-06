# Mobile Navigation

## Problem

Navigation links need to remain usable in a narrow viewport.

## Approach

Start with a visible, wrapping list of links. Only add a menu button and JavaScript when the assignment requires it. If a menu is collapsible, the button must expose its state and support keyboard users.

Read [MDN navigation landmarks](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/navigation_role) and [MDN button](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button).

## Check

- Is the navigation still reachable without a mouse?
- Does the button name communicate its action?
- Can a user tell whether the menu is open?
