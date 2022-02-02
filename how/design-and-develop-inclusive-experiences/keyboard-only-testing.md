# Keyboard-Only Navigation Testing

## Common Issues Identified During Keyboard-Only Navigation Testing
- No focus indicators. Sometimes, a developer will remove the base styling for focus indicators. This means that when you are tabbing through a site, if you have no idea where you are, the focus indicators have been removed and the styling needs to be added back in. This is the most critical barrier for keyboard only users as it prevents them from navigating a site at all.
- No custom designed focus indicators. If you notice the color and design of focus indicators changing across browsers, chances are the focus indicators are only set to use the default browser focus indicators. Not all default browser focus indicators meet color contrast guidelines and are usable so you would want to flag this as an issue and reference Deque's "How to Design Useful and Usable Focus Indicators" when designing custom focus indicators.
- No skip to main content link. This link is crucial for physically disabled people as it allows them to skip the main navigation on the site, improving both the time and energy used to navigate a site.
- Mega menus that expand automatically. When a main menu on a site expands automatically without being activated by a user, this creates excessive and unneeded tabbing for anyone using keyboard-only navigation. Depending on the amount of dropdown items, you could be adding up to 40 tabbing actions to a physically disabled person's navigation process. Instead, each menu item should be activated by the Enter or Space key to allow a user to choose which menu item (if any) that they would like to activate. 
- Tabbing order not accurate. Watch for the tabbing order to be out of sequence with the visual order of content. If this occurs, the tabbing order should be changed to match the visual order.
- Not all interactive elements are reachable by the keyboard. Look for interactive elements, such as buttons, links, and videos that aren't receiving keyboard focus. In addition, look for modal dialog boxes that do not receive focus.
- Non-interactive elements are reachable by the keyboard. Sometimes people accidentally put in tabbing focus on non-interactive elements, such as headings and body content. This creates unneeded navigation for a keyboard only users as they can review the main content of a page by using the up and down arrows. 

## How to Test
The following keyboard commands should be used when testing keyboard only navigation. The keys used for keyboard only navigation are not the same keys used for screen reader navigation. They are basic keys - not complex keyboard shortcut commands - as not all keyboard only navigation users have access to complex keyboard shortcuts so it's important to remember that your site must operate based on these basic keys. 

- Tab - Move through all interactive elements on the page. Note that interactive elements are buttons, links, and form fields. Body content should not be part of the tabbing order. People who use keyboard only will use the up and down arrows to review content on a page.
- Shift + Tab - Navigate backwards through interactive elements.
- Enter/Return - Activates links and buttons. 
- Spacebar - Toggles checkbox values, activates buttons.
- Up and Down Arrow Keys - Scrolls content, moves/selects radio buttons within a group, moves up and down in dropdown lists, and sometimes moves between interactive menu items or tab panels.
- Esc - Use to escape a modal dialog (pop-up window).
