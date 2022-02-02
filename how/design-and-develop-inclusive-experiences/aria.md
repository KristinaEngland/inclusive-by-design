# Accessible Rich Internet Applications (ARIA)

## About ARIA

[WAI-ARIA](https://www.w3.org/TR/wai-aria-1.1/), the Accessible Rich Internet Applications Suite, defines a way to make Web content and Web applications more accessible to disabled people. It especially helps with dynamic content and advanced user interface controls developed with HTML, JavaScript, and related technologies.

## Best Practices for ARIA Usage
1. If you can, use a native HTML element or attribute with the semantics and behavior you require already built in, instead of re-purposing an element and adding an ARIA role, state or property to make it accessible, then do so.
2. Do not change native semantics, unless you really have to.
3. All interactive ARIA controls must be usable with the keyboard.
4. Do not use role="presentation" or aria-hidden="true" on a focusable element.
5. All interactive elements must have an [accessible name](http://www.w3.org/TR/accname-aam-1.1/#dfn-accessible-name).
6. Ensure you [use Roles, States, and Properties correctly](https://www.levelaccess.com/how-not-to-misuse-aria-states-properties-and-roles/).
7. [Do not add hidden form instructions using an aria-label](https://sparkbox.com/foundry/using_wai-aria_aria-hidden_aria-label_aria-live_correctly). When developing a form, instructions need to be understood by sighted users and screen reader users.

## Always Check ARIA Support
Support for ARIA is rather complex and currently is not fully supported in any browser or by all types of assistive technology. It's always best to use native HTML before turning to ARIA. If you need to use ARIA, you should validate screen reader and voice control (i.e. speech recognition) support on the [ARIA Accessibility Support site](https://a11ysupport.io/tests/) and confirm support through manual testing.

## Where to start with ARIA

Source: [ARIA Landmark Roles](https://www.washington.edu/accessibility/web/landmarks/), University of Washington

One of the easiest ARIA features to implement, and one that provides significant immediate benefits to screen reader users, is landmark roles. There are eight of these roles, each representing a block of content that occurs commonly on web pages. To use them, simply add a relevant role attribute to an appropriate container within your HTML. Then, screen reader users can quickly jump to that section of the page. The eight ARIA landmark roles are:

- role=”banner”
- role=”navigation” (e.g., a menu)
- role=”main” (the main content of the page)
- role=”complementary” (e.g., a sidebar)
- role=”contentinfo” (meta data about the page, e.g., a copyright statement)
- role=”search”
- role=”form”

If a role is used more than once on a page, the aria-label attribute should also be used in order to distinguish between the two regions.
