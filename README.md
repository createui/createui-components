# Create UI Components

**Create UI** is a modern, accessible component library for **React 19** and **Tailwind CSS v4**. Every component is built on **Radix UI** primitives for keyboard and screen-reader support, styled with **class-variance-authority (CVA)** variants and semantic design tokens, and ships with full **TypeScript** types, dark mode, and copy-paste installation through the Create UI CLI.

If you are searching for production-ready React UI components, Tailwind CSS components, an accessible design system, or a shadcn-style component registry you can own and extend, this page is the index to every documented component.

[Documentation](https://createui.co/docs) · [Component Index](https://createui.co/docs/components) · [Installation](https://createui.co/docs/installation) · [Issues](https://github.com/createui/createui-components/issues) · [Discussions](https://github.com/createui/createui-components/discussions)

---

## Getting Started

Add any component to your project with the CLI. Each command pulls the component source, its dependencies, and the required tokens into your codebase so you fully own the code:

```bash
npx @create-ui/cli init
```

See the [installation guide](https://createui.co/docs/installation) for project setup, framework support, and theming.

## How to Navigate the Docs

Every component has a dedicated documentation page that follows the same layout, so you always know where to look:

- **Live preview**: an interactive demo you can inspect at the top of the page.
- **Description**: when to reach for the component and how it relates to its siblings.
- **Installation**: the exact CLI command to add it.
- **Usage**: import paths and copy-paste code snippets.
- **API reference**: props, variants, and slots.

Browse everything from the full [components index](https://createui.co/docs/components), or jump straight to a component from the categorized tables below. Components are grouped by the job they do (actions, forms, navigation, and so on) to match how you build a screen.

## Components

### Buttons & Actions

Interactive controls that trigger actions, submit forms, and surface primary calls to action.

| Component | Description |
| --- | --- |
| [Button](https://createui.co/docs/components/button) | Interactive control for primary actions, form submission, and inline triggers. |
| [Button Group](https://createui.co/docs/components/button-group) | Joined row of buttons that share a single bordered surface for segmented toolbars and view switchers. |
| [Close Button](https://createui.co/docs/components/close-button) | Compact icon button for dismissing dialogs, toasts, banners, and other overlays. |
| [Social Login Button](https://createui.co/docs/components/social-login-button) | Branded sign-in button for OAuth flows across the major social providers. |
| [App Store Badge](https://createui.co/docs/components/app-store-badge) | Branded download CTA for app stores, browser extension marketplaces, and music services. |

### Form Controls & Inputs

Everything you need to capture and validate user input, from single fields to grouped, labelled form controls.

| Component | Description |
| --- | --- |
| [Field](https://createui.co/docs/components/field) | Layout wrapper that pairs a form control with its label, description, and error. |
| [Label](https://createui.co/docs/components/label) | Caption for a form control, with slots for icons, markers, badges, tooltips, and counters. |
| [Input](https://createui.co/docs/components/input) | Single-line text field for capturing short user input such as names, emails, numbers, and queries. |
| [Textarea](https://createui.co/docs/components/textarea) | Multi-line text input for longer prose, with built-in size, state, and resize controls. |
| [Input Group](https://createui.co/docs/components/input-group) | Compound input shell that composes Input with icons, addons, buttons, and selects inside a single bordered row. |
| [Input OTP](https://createui.co/docs/components/input-otp) | One-time-code input that splits each character into its own slot. |
| [Input Stepper](https://createui.co/docs/components/input-stepper) | Numeric input with attached increment and decrement buttons for tight quantity controls. |
| [Select](https://createui.co/docs/components/select) | Dropdown for choosing one value from a short list, with built-in keyboard, focus, and form-field composition. |
| [Checkbox](https://createui.co/docs/components/checkbox) | Boolean toggle for binary choices in forms, lists, and bulk-selection rows. |
| [Checkbox Group](https://createui.co/docs/components/checkbox-group) | Labelled checkbox row that pairs a single Checkbox with a label, description, and error footer. |
| [Radio](https://createui.co/docs/components/radio) | Single-choice form control for mutually-exclusive options inside a RadioGroup. |
| [Radio Group](https://createui.co/docs/components/radio-group) | Single-select form group with shared label, helper text, and error footer. |
| [Switch](https://createui.co/docs/components/switch) | Toggle control for on/off settings that commit immediately. |
| [Switch Group](https://createui.co/docs/components/switch-group) | Labelled switch row that pairs a single Switch with a label, description, and footer. |
| [Segmented Control](https://createui.co/docs/components/segmented-control) | Single-select switcher for 2 to 5 inline options, with a flat row or grouped pill style. |
| [Chip](https://createui.co/docs/components/chip) | Compact interactive label for selection, filtering, and tagging. |

### Navigation

Wayfinding components that move users between pages, sections, and commands.

| Component | Description |
| --- | --- |
| [Breadcrumbs](https://createui.co/docs/components/breadcrumbs) | Hierarchical nav trail that shows the path from the app root to the current page. |
| [Pagination](https://createui.co/docs/components/pagination) | Numbered navigation for splitting long lists across pages. |
| [Tab Menu](https://createui.co/docs/components/tab-menu) | Compound menu for switching between sections, with vertical or horizontal layouts and an animated active indicator. |
| [Dropdown Menu](https://createui.co/docs/components/dropdown-menu) | Action menu that opens from a button, for account controls, row actions, and overflow commands. |
| [Text Link](https://createui.co/docs/components/text-link) | Inline anchor for in-body links that stay inside the flow of text. |

### Data Display

Components for presenting identity, status, counts, and grouped content.

| Component | Description |
| --- | --- |
| [Avatar](https://createui.co/docs/components/avatar) | Image, initials, or icon thumbnail with optional status badge, ring, and grouping. |
| [Badge](https://createui.co/docs/components/badge) | Compact label for statuses, counts, and metadata. |
| [Status Badge](https://createui.co/docs/components/status-badge) | Colored dot that signals presence or live state next to a label, avatar, or row. |
| [Accordion](https://createui.co/docs/components/accordion) | Stacked disclosure rows that expand a single panel at a time or many in parallel. |

### Feedback & Status

Components that communicate progress, system messages, and transient notifications.

| Component | Description |
| --- | --- |
| [Inline Alert](https://createui.co/docs/components/inline-alert) | In-flow status surface for system messages and contextual notices anchored to a section. |
| [Toast](https://createui.co/docs/components/toast) | Transient, screen-level notification that confirms an action or surfaces a short-lived message. |
| [Tooltip](https://createui.co/docs/components/tooltip) | Short hover hint that names a control or explains a brief detail. |
| [Progress](https://createui.co/docs/components/progress) | Bar or ring that shows how far a known task has advanced. |
| [Spinner](https://createui.co/docs/components/spinner) | Indeterminate loading indicator for async work in buttons, forms, and inline content. |

### Layout & Utilities

Structural helpers that hold space, manage scroll, and divide content.

| Component | Description |
| --- | --- |
| [Aspect Ratio](https://createui.co/docs/components/aspect-ratio) | Reserves a fixed width-to-height ratio for media and embeds so the layout stays put while they load. |
| [Scroll Area](https://createui.co/docs/components/scroll-area) | Styled scroll container with overlay scrollbars for vertical, horizontal, or both axes. |
| [Separator](https://createui.co/docs/components/separator) | Thin horizontal rule for breaking content into visual sections, with optional inline label. |

## Foundation

The design foundation underneath every component: one semantic token system you own and theme. These tokens drive color, type, spacing, radius, and elevation across the whole library, so components stay consistent and adapt to light and dark mode automatically.

| Topic | Description |
| --- | --- |
| [Colors](https://createui.co/docs/colors) | Semantic color tokens for theming, dark mode, and consistent UI. |
| [Typography](https://createui.co/docs/typography) | One type system, seven token families, applied with a single utility class. |
| [Spacing](https://createui.co/docs/spacing) | Responsive, semantic spacing tokens for layout, section, and component rhythm. |
| [Rounded](https://createui.co/docs/rounded) | Responsive, semantic border-radius tokens that scale corners across breakpoints. |
| [Shadows](https://createui.co/docs/shadows) | Semantic shadow tokens for elevation, component states, and depth. |

## Contributing & Issues

Create UI is a closed-source library, and this repository exists for community engagement: bug reports, feature requests, and discussion. The component source itself is distributed through the CLI and the [documentation site](https://createui.co/docs).

Before opening an issue:

1. **Search [existing issues](https://github.com/createui/createui-components/issues)** to avoid duplicates.
2. **[Open a new issue](https://github.com/createui/createui-components/issues/new/choose)** and pick the right type:
   - `bug`: something is broken or behaves unexpectedly.
   - `feature`: a new component, variant, or capability you would like to see.
   - `question`: usage help or a request for clarification.
3. Include the component name, your Create UI / React / Tailwind versions, and a minimal reproduction where relevant.

For broader conversations, ideas, and showcase, use [GitHub Discussions](https://github.com/createui/createui-components/discussions).

## Links

- [Documentation](https://createui.co/docs)
- [Component Index](https://createui.co/docs/components)
- [X / Twitter](https://x.com/createuico)
- [Discord](https://discord.gg/kYcRZgPgUu)
