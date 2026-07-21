# 05 – UI Component Library

## Document Status

**Status:** Design Milestone – Foundation  
**Applies To:** CompareBuddy Website

This document defines the reusable interface components used throughout the CompareBuddy website.

The UI Component Library converts the principles defined in:

- 01 – CompareBuddy Design & Brand Guide
- 02 – Website Blueprint
- 03 – Design System
- 04 – Homepage Master Design
- 06 – Buddy Style Guide

into consistent, reusable interface components.

---

# 1. Purpose

The Design System defines the overall design principles.

The UI Component Library defines the actual reusable building blocks used to create the website.

The purpose of this library is to ensure that the same component does not look different from page to page.

For example:

- A primary button should always look like a primary button.
- A pricing card should follow the same structure wherever it appears.
- Form fields should behave consistently.
- Headings should follow the approved typography hierarchy.
- Spacing should follow the approved spacing scale.

Components should be reused rather than recreated unnecessarily.

---

# 2. Component Design Principles

All components should be:

- Clear
- Consistent
- Accessible
- Professional
- Responsive
- Reusable
- Easy to understand

Components should not be created simply to add visual variety.

Consistency is more important than novelty.

---

# 3. Spacing Scale

The website should use a consistent spacing scale.

Approved spacing values:

```text
8 px
16 px
24 px
32 px
48 px
64 px
96 px
128 px

These values should be used wherever practical for:

Padding
Margins
Section spacing
Card spacing
Grid gaps
Text spacing
Component spacing

Avoid introducing random spacing values without a clear design reason.

4. Buttons

Buttons must clearly communicate the action that will occur when clicked.

Buttons should use clear, action-oriented language.

Examples:

Start Free Trial
Subscribe Now
View Plans
Learn More
Watch Product Tour
Contact Us

Avoid vague labels such as:

Click Here
Submit
More
Go

unless the context makes the action completely clear.

4.1 Primary Button
Purpose

Used for the most important action in a section.

Examples:

Start Your 14-Day Trial
Subscribe Now
Visual Priority

Highest.

Use

Use one primary button per major action area where possible.

Avoid placing multiple competing primary buttons next to each other.

Style
Strong brand colour
High contrast text
Clear visual hierarchy
Consistent corner radius
Comfortable click area
States

The primary button must have:

Default state
Hover state
Focus state
Active state
Disabled state
Loading state where applicable
4.2 Secondary Button
Purpose

Used for important but secondary actions.

Examples:

View Plans
Learn More
Watch Product Tour
Visual Priority

Secondary.

The button should remain clearly visible but should not compete with the primary CTA.

4.3 Ghost Button
Purpose

Used for lower-priority actions.

Examples:

Read More
Explore
View Details

Ghost buttons should not be used for the most important conversion action.

4.4 Icon Button
Purpose

Used for actions represented primarily by an icon.

Examples:

Mobile menu
Close
Search
Back
Next

Icon buttons must:

Have a clear purpose.
Have an accessible label.
Provide a visible focus state.
Have a sufficiently large clickable area.
5. Cards

Cards should group related information into a clear visual unit.

Cards should not be overused.

If every section is placed inside a card, the page can become visually fragmented and cluttered.

Cards should be used when they improve organisation or comparison.

5.1 Feature Card

Used for:

Product features
Benefits
Capabilities

Recommended structure:

Icon or visual indicator
Heading
Short supporting description
Optional link

Feature cards should remain concise.

5.2 Pricing Card

Used for:

Subscription plans
Trial options
Team plans
Enterprise options

Recommended structure:

Plan name
Short description
Price
Billing period
Included features
Primary action

Pricing cards must make it easy to compare options.

The selected or recommended plan may receive additional visual emphasis.

5.3 Testimonial Card

Used for genuine customer feedback.

Recommended structure:

Testimonial
Customer name
Job title or role
Company, where approved
Optional photograph

Fake testimonials must never be used.

5.4 FAQ Item

FAQ items should use a clear expandable structure.

Recommended behaviour:

Question is visible.
Answer expands when selected.
The interaction is clearly understandable.
Keyboard users can operate the component.

Avoid opening too many answers simultaneously unless there is a clear usability reason.

6. Navigation

Navigation must remain simple and predictable.

Recommended desktop navigation:

Logo
Features
How It Works
Plans & Pricing
FAQ
Contact
Start Free Trial

The primary CTA should be visually distinct.

6.1 Desktop Navigation

Desktop navigation should:

Remain clean.
Have sufficient spacing.
Use clear labels.
Avoid unnecessary dropdowns.
Keep the primary CTA visible.
6.2 Mobile Navigation

On smaller screens:

Navigation collapses into a menu.
The menu must be easy to open and close.
Navigation links must have comfortable touch targets.
The primary CTA should remain easy to find.
6.3 Sticky Navigation

A sticky navigation may be used if it improves navigation.

If used:

It should not become visually heavy.
It should not take up excessive screen space.
It should remain readable.
It should maintain the same brand styling.
6.4 Dropdowns

Dropdowns should only be used when they improve navigation.

Avoid unnecessary multi-level navigation.

Dropdowns must:

Open predictably.
Be easy to close.
Work with keyboard navigation.
Be usable on touch devices.
7. Forms

Forms should be short, clear, and easy to complete.

Only request information that is genuinely necessary.

7.1 Text Input

Used for:

Name
Company
Address
Other text information

Must include:

Clear label
Visible input area
Focus state
Error state where applicable
7.2 Email Input

Used for email addresses.

The system should validate that the input is in a valid email format.

Error messages should be helpful and clear.

Example:

Please enter a valid email address.

7.3 Password Input

Password fields should:

Hide password characters by default.
Provide a show/hide option where appropriate.
Clearly explain requirements.
Provide helpful validation feedback.
7.4 Dropdown

Use dropdowns when the user must choose from a predefined list.

Avoid dropdowns when there are only two simple options that could be represented more clearly with another control.

7.5 Checkbox

Checkboxes should be used for:

Agreement
Multiple selections
Optional preferences

Labels must clearly explain what is being selected.

7.6 Validation Messages

Validation messages should:

Clearly explain the problem.
Appear near the relevant field.
Explain how to correct the issue.
Avoid technical language.

Avoid generic messages such as:

Error.

Prefer:

Please enter your work email address.

8. Typography Components

Typography must follow the hierarchy defined in the Design System.

Recommended hierarchy:

H1 – Primary page headline
H2 – Major section heading
H3 – Subsection heading
H4 – Component heading
Body – Main supporting content
Small Text – Supporting information
Label – Form and interface labels
Button Text – Action labels

Typography should be consistent across the entire website.

9. Page Sections

Sections should have a clear purpose.

Each section should answer one of the following questions:

What is this?
Who is it for?
What problem does it solve?
How does it work?
Why should I trust it?
What should I do next?

Avoid adding sections simply to make the page longer.

10. Hero Component

The hero is the most important visual section of the homepage.

It should contain:

Eyebrow
Primary headline
Supporting text
Primary CTA
Optional secondary action
Product visual
Appropriate Buddy asset where approved

The hero must communicate the value of CompareBuddy quickly.

The hero should not be overloaded with multiple messages.

11. CTA Components

Calls to action should follow the approved CTA strategy.

Primary actions include:

Start Your 14-Day Trial
Subscribe Now

Secondary actions include:

View Plans
Learn More
Watch Product Tour
Contact Us

The website should avoid repeatedly presenting the same CTA in every section.

The visitor should not be confused about where to click.

12. Pricing Components

The Plans & Pricing section must support the subscription model.

CompareBuddy uses:

Monthly subscriptions
Annual subscriptions

The pricing section should provide a clear way to switch between:

Monthly
Annual

Annual pricing should clearly communicate savings where applicable.

Pricing cards should clearly show:

Plan name
Price
Billing period
User count
Included features
Appropriate action

The free trial is presented as one option alongside the paid subscription plans.

13. Badges

Badges may be used to communicate important information.

Examples:

Recommended
Most Popular
Save 15%
New

Badges should be used sparingly.

Do not place badges on every card.

14. Icons

Icons should support understanding.

Icons must not be used simply as decoration.

The icon style should remain consistent throughout the website.

Recommended characteristics:

Clean
Simple
Professional
Consistent stroke or visual weight

Avoid mixing unrelated icon styles.

Icons should not overpower text.

15. Buddy Component Rules

Buddy is governed by:

06 - Buddy Style Guide.md

Buddy should be used selectively.

Buddy must:

Remain visually consistent.
Use approved artwork.
Maintain correct proportions.
Have sufficient clear space.
Support the purpose of the section.

Buddy must not be used as a replacement for clear content or interface design.

The product remains the hero.

16. Alerts and Notifications

Alerts should clearly communicate important information.

Types may include:

Information
Success
Warning
Error

Alerts must:

Use clear language.
Explain what happened.
Explain what the user should do next where appropriate.

Avoid alarming language unless the situation genuinely requires it.

17. Loading States

Loading states should reassure the user that the system is working.

They should:

Be visually clear.
Avoid unnecessary animation.
Not create confusion.

Where possible, explain what is loading.

18. Empty States

Empty states should help the user understand what to do next.

A good empty state may include:

Short explanation
Helpful illustration or Buddy asset where appropriate
Clear next action

Do not leave users staring at a completely blank area without explanation.

19. Modals

Modals should be used only when necessary.

They may be used for:

Important confirmation
Focused actions
Required information
Important warnings

Avoid using modals for information that could simply be displayed on the page.

Modals must:

Be easy to close.
Have a clear heading.
Have a clear action.
Work on smaller screens.
20. Responsive Components

Every component must be designed for:

Desktop
Laptop
Tablet
Mobile

Components should adapt naturally.

Avoid:

Horizontal overflow.
Text being cut off.
Buttons becoming too small.
Cards becoming unusably narrow.
Content being hidden without a clear reason.
21. Accessibility

Components must support accessible use.

Important principles include:

Sufficient colour contrast.
Clear focus states.
Keyboard navigation where applicable.
Descriptive labels.
Meaningful alternative text for important images.
Sufficient clickable areas.
Clear error messages.

Accessibility is part of professional design.

22. Component Consistency Rule

Before creating a new component, ask:

Does an existing component already solve this problem?

If yes, reuse the existing component.

If no, determine whether a new reusable component is genuinely necessary.

Avoid creating one-off components without a clear reason.

23. Component Quality Standard

Every component should be evaluated against the following questions:

Is its purpose clear?
Is it easy to understand?
Is it visually consistent?
Is it reusable?
Is it responsive?
Is it accessible?
Does it improve the user experience?
24. Final Quality Standard

Every component should be evaluated against one question:

Would a premium software company proudly publish this?

If the answer is no, the component should be refined before approval.
