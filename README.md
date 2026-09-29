# Create UI Components

**Create UI** is an AI-native design system and component library for **React 19** and **Tailwind CSS v4**. The Figma design system and the React code library stay in sync, so what you design is what you ship. Components are built on accessible primitives (Radix UI and React Aria) for keyboard and screen-reader support, styled with **class-variance-authority (CVA)** variants and semantic design tokens, and ship with full **TypeScript** types, dark mode, and copy-paste installation through the Create UI CLI.

If you are searching for production-ready React UI components, Tailwind CSS components, AI chat components, ready-made blocks, or an accessible design system you can own and extend, this page is the index to all of it.

[Documentation](https://createui.co/docs) · [Component Index](https://createui.co/docs/components) · [Blocks](https://createui.co/blocks) · [Asset Library](https://createui.co/assets) · [Changelog](https://createui.co/docs/changelog) · [Issues](https://github.com/createui/createui-components/issues) · [Discussions](https://github.com/createui/createui-components/discussions)

---

## What's New in 1.5

- **24 new components**, including a full set of **AI chat components** (messages, prompt input, attachments, sources, tool calls, reasoning), a data **Table**, **Calendar** and **Date Picker**, **Filter Bar**, **Tree View**, and **Sparkline**.
- **73 ready-made blocks** in 7 categories: sign-in and sign-up screens, dropdown menus, header and sidebar navigation, modals, and section headers.
- **Asset Library**: icons, country flags, brand logos, payment and social marks, and more, as typed React components.
- **18,500+ variants** in the Figma design system, kept in step with the code.
- **MCP server and agent skill** so AI coding agents build with Create UI components instead of guessing.

Read the full release notes in the [changelog](https://createui.co/docs/changelog).

## Getting Started

Set up Create UI in your project, then add components with the CLI. Each command pulls the component source, its dependencies, and the required tokens into your codebase so you fully own the code:

```bash
npx @create-ui/cli init
npx @create-ui/cli add button
```

See the [installation guide](https://createui.co/docs/installation) for project setup, framework support, and theming. New to code? Start with the [New to Code guide](https://createui.co/docs/new-to-code).

### Free and Pro

Most foundation components are free. Components marked **Pro** in the tables below, and all blocks, are part of [Create UI Pro](https://createui.co/pricing). **Free + Pro** means the free component is fully usable and Pro adds extra variants or features.

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

| Component | Description | Plan |
| --- | --- | --- |
| [Button](https://createui.co/docs/components/button) | Interactive control for primary actions, form submission, and inline triggers. | Free |
| [Button Group](https://createui.co/docs/components/button-group) | Joined row of buttons that share a single bordered surface for segmented toolbars and view switchers. | Free + Pro |
| [Close Button](https://createui.co/docs/components/close-button) | Compact icon button for dismissing dialogs, toasts, banners, and other overlays. | Free |
| [Social Login Button](https://createui.co/docs/components/social-login-button) | Branded sign-in button for OAuth flows across the major social providers. | Free |
| [App Store Badge](https://createui.co/docs/components/app-store-badge) | Branded download CTA for app stores, browser extension marketplaces, and music services. | Free |
| [Fab Button](https://createui.co/docs/components/fab-button) | Floating action button for a primary screen action, compose shortcut, or mobile speed dial. | Pro |

### Form Controls & Inputs

Everything you need to capture and validate user input, from single fields to grouped, labelled form controls and date pickers.

| Component | Description | Plan |
| --- | --- | --- |
| [Field](https://createui.co/docs/components/field) | Layout wrapper that pairs a form control with its label, description, and error. | Free |
| [Label](https://createui.co/docs/components/label) | Caption for a form control, with slots for icons, markers, badges, tooltips, and counters. | Free |
| [Input](https://createui.co/docs/components/input) | Single-line text field for capturing short user input such as names, emails, numbers, and queries. | Free |
| [Textarea](https://createui.co/docs/components/textarea) | Multi-line text input for longer prose, with built-in size, state, and resize controls. | Free |
| [Input Group](https://createui.co/docs/components/input-group) | Compound input shell that composes Input with icons, addons, buttons, and selects inside a single bordered row. | Free |
| [Phone Input](https://createui.co/docs/components/input-group#phone-number) | Country-picker phone field that formats national digits and emits a submit-ready E.164 value. | Free |
| [Date Input](https://createui.co/docs/components/input-group#date) | Masked date field with a configurable DD/MM/YYYY, MDY, or YMD segment order. | Free |
| [Credit Card Input](https://createui.co/docs/components/input-group#credit-card) | Masked card-number field with brand detection, a trailing badge, and a validity marker. | Free |
| [Input OTP](https://createui.co/docs/components/input-otp) | One-time-code input that splits each character into its own slot. | Free |
| [Input Stepper](https://createui.co/docs/components/input-stepper) | Numeric input with attached increment and decrement buttons for tight quantity controls. | Free + Pro |
| [Select](https://createui.co/docs/components/select) | Dropdown for choosing one value from a short list, with built-in keyboard, focus, and form-field composition. | Free |
| [Combobox](https://createui.co/docs/components/combobox) | Type-to-filter picker for long option lists, with optional off-list custom values. | Free |
| [Checkbox](https://createui.co/docs/components/checkbox) | Boolean toggle for binary choices in forms, lists, and bulk-selection rows. | Free |
| [Checkbox Group](https://createui.co/docs/components/checkbox-group) | Labelled checkbox row that pairs a single Checkbox with a label, description, and error footer. | Free |
| [Radio](https://createui.co/docs/components/radio) | Single-choice form control for mutually-exclusive options inside a RadioGroup. | Free |
| [Radio Group](https://createui.co/docs/components/radio-group) | Single-select form group with shared label, helper text, and error footer. | Free |
| [Switch](https://createui.co/docs/components/switch) | Toggle control for on/off settings that commit immediately. | Free |
| [Switch Group](https://createui.co/docs/components/switch-group) | Labelled switch row that pairs a single Switch with a label, description, and footer. | Free |
| [Segmented Control](https://createui.co/docs/components/segmented-control) | Single-select switcher for 2 to 5 inline options, with a flat row or grouped pill style. | Free |
| [Slider](https://createui.co/docs/components/slider) | Draggable track for picking a numeric value within a known range. | Free + Pro |
| [Chip](https://createui.co/docs/components/chip) | Compact interactive label for selection, filtering, and tagging. | Free |
| [Dropzone](https://createui.co/docs/components/dropzone) | Drag-and-drop (or click) file drop area with built-in accept and size validation. | Free |
| [File Upload](https://createui.co/docs/components/file-upload) | Drag-and-drop upload area with a per-file list showing format, progress, and status. | Pro |
| [Input Tag](https://createui.co/docs/components/input-tag) | Type-to-add tag input that turns entries into removable chips inside the field. | Pro |
| [Password Strength](https://createui.co/docs/components/password-strength) | Segmented meter and rule checklist for password requirements below an Input. | Pro |
| [Rating](https://createui.co/docs/components/rating) | Star, heart, emoji, or number rating control for reviews and satisfaction surveys. | Pro |
| [Calendar](https://createui.co/docs/components/calendar) | Date, multi-date, and date-range calendar with month and year pickers, presets, and a footer. | Pro |
| [Date Picker](https://createui.co/docs/components/date-picker) | Click-to-open trigger, styled like an Input, that reveals a Calendar panel in a popover. | Pro |

### Navigation

Wayfinding components that move users between pages, sections, and hierarchies.

| Component | Description | Plan |
| --- | --- | --- |
| [Breadcrumbs](https://createui.co/docs/components/breadcrumbs) | Hierarchical nav trail that shows the path from the app root to the current page. | Free + Pro |
| [Pagination](https://createui.co/docs/components/pagination) | Numbered navigation for splitting long lists across pages. | Free + Pro |
| [Tab Menu](https://createui.co/docs/components/tab-menu) | Compound menu for switching between sections, with vertical or horizontal layouts and an animated active indicator. | Free + Pro |
| [Tabs](https://createui.co/docs/components/tabs) | ARIA tabs that swap a content panel within the same surface, for settings and detail views. | Free + Pro |
| [Dropdown Menu](https://createui.co/docs/components/dropdown-menu) | Action menu that opens from a button, for account controls, row actions, and overflow commands. | Free |
| [Context Menu](https://createui.co/docs/components/context-menu) | Right-click menu attached to a region, for row, canvas, and editor actions. | Free |
| [Stepper](https://createui.co/docs/components/stepper) | Linear, discrete progress indicator for onboarding, checkout, and multi-step forms. | Free + Pro |
| [Text Link](https://createui.co/docs/components/text-link) | Inline anchor for in-body links that stay inside the flow of text. | Free |
| [Navbar](https://createui.co/docs/components/navbar) | Top navigation bar with brand slot, nav links, actions cluster, and responsive mobile menu. | Pro |
| [Sidebar](https://createui.co/docs/components/sidebar) | Collapsible application sidebar with grouped nav items and an icon-rail mode. | Pro |
| [Tree View](https://createui.co/docs/components/tree-view) | Hierarchical list with connector guides, expand and collapse, cascading checkbox selection, and drag-and-drop reordering. | Pro |

### Tables & Data

Components for working with rows of data: tables, the toolbars above them, and compact trends.

| Component | Description | Plan |
| --- | --- | --- |
| [Table](https://createui.co/docs/components/table) | Data table with row selection, column sorting, resizable and pinnable columns, a sticky header, and drag-and-drop row reordering. | Pro |
| [Filter Bar](https://createui.co/docs/components/filter-bar) | Toolbar above a table or list with a view switcher, search field, filters, and actions in one row that stacks on narrow screens. | Pro |
| [Sparkline](https://createui.co/docs/components/sparkline) | Compact trend line for a numeric series, colored by direction and sized by its container. | Pro |

### Data Display

Components for presenting identity, status, counts, and grouped content.

| Component | Description | Plan |
| --- | --- | --- |
| [Avatar](https://createui.co/docs/components/avatar) | Image, initials, or icon thumbnail with optional status badge, ring, and grouping. | Free |
| [Badge](https://createui.co/docs/components/badge) | Compact label for statuses, counts, and metadata. | Free |
| [Status Badge](https://createui.co/docs/components/status-badge) | Colored dot that signals presence or live state next to a label, avatar, or row. | Free |
| [Accordion](https://createui.co/docs/components/accordion) | Stacked disclosure rows that expand a single panel at a time or many in parallel. | Free |
| [File Format](https://createui.co/docs/components/file-format) | File type icon for upload queues, attachment chips, and download cards. | Pro |
| [Featured Icon](https://createui.co/docs/components/featured-icon) | Colored icon container for headers, empty states, and list rows, with semantic variants and a six-step size scale. | Free + Pro |
| [Placeholder Logo](https://createui.co/docs/components/placeholder-logo) | Neutral placeholder brand logos for mockups, templates, and social proof sections, in lockup, mark, and badge types. | Free |

### AI Components

Building blocks for AI chat products and agent interfaces, from the conversation log to the composer.

| Component | Description | Plan |
| --- | --- | --- |
| [Chat Conversation](https://createui.co/docs/components/chat-conversation) | Scrolling log for AI chat that follows streamed replies and lets go when the reader scrolls up. | Pro |
| [Chat Message](https://createui.co/docs/components/chat-message) | Layout for one user or assistant turn in an AI chat, with avatar, body, bubble, content, and media slots. | Pro |
| [Chat Message Actions](https://createui.co/docs/components/chat-message-actions) | Icon action row under a chat message for copying, rating, regenerating, and opening more options. | Pro |
| [Prompt Input](https://createui.co/docs/components/prompt-input) | Chat composer with an autosizing field, toolbar, run states, attachments, a follow-up queue, and inline mentions. | Pro |
| [Prompt Suggestion](https://createui.co/docs/components/prompt-suggestion) | Clickable starter prompts for an empty AI chat, laid out as one-line pills or stacked template cards. | Pro |
| [Chat Attachment](https://createui.co/docs/components/chat-attachment) | File and media previews for AI chat, plus the picker and drop target that collect them. | Pro |
| [Chat Source](https://createui.co/docs/components/chat-source) | Inline citation pills that credit an AI answer's sources, with a hover preview and a collapsible source list. | Pro |
| [Chat Tool](https://createui.co/docs/components/chat-tool) | Collapsible card that shows an agent's tool call, its input, result, errors, and approval step. | Pro |
| [Chain of Thought](https://createui.co/docs/components/chain-of-thought) | Collapsible reasoning timeline that shows how an assistant reached its answer, step by step. | Pro |
| [Chat Loader](https://createui.co/docs/components/chat-loader) | Placeholders for a pending assistant reply, from typing dots to a message-shaped skeleton. | Pro |
| [Chat List View](https://createui.co/docs/components/chat-list-view) | List of chat threads for a history sidebar, with a selected row, previews, timestamps, and per-row actions. | Pro |
| [Markdown](https://createui.co/docs/components/markdown) | Renders AI responses written in markdown with Create UI typography, including while the text is still streaming in. | Pro |
| [Text Shimmer](https://createui.co/docs/components/text-shimmer) | Animated highlight that sweeps across a text label to show thinking, streaming, or loading in progress. | Pro |

### Feedback & Status

Components that communicate progress, system messages, and transient notifications.

| Component | Description | Plan |
| --- | --- | --- |
| [Inline Alert](https://createui.co/docs/components/inline-alert) | In-flow status surface for system messages and contextual notices anchored to a section. | Free |
| [Toast](https://createui.co/docs/components/toast) | Transient, screen-level notification that confirms an action or surfaces a short-lived message. | Free |
| [Tooltip](https://createui.co/docs/components/tooltip) | Short hover hint that names a control or explains a brief detail. | Free |
| [Progress](https://createui.co/docs/components/progress) | Bar or ring that shows how far a known task has advanced. | Free |
| [Spinner](https://createui.co/docs/components/spinner) | Indeterminate loading indicator for async work in buttons, forms, and inline content. | Free |
| [Alert Banner](https://createui.co/docs/components/alert-banner) | Dismissible, page-level announcement bar for status, consent, and outage notices. | Pro |
| [Info Tooltip](https://createui.co/docs/components/info-tooltip) | Icon-triggered tooltip for supplemental help text next to a label or field. | Pro |

### Overlays & Dialogs

Floating surfaces anchored to a trigger, for modal tasks, contextual panels, and popovers.

| Component | Description | Plan |
| --- | --- | --- |
| [Modal](https://createui.co/docs/components/modal) | Accessible modal dialog with overlay, focus trap, and composable header, body, and footer slots. | Pro |
| [Popover](https://createui.co/docs/components/popover) | Anchored floating panel for contextual content positioned next to a trigger. | Pro |

### Layout & Utilities

Structural helpers that hold space, manage scroll, divide content, and add motion to surfaces.

| Component | Description | Plan |
| --- | --- | --- |
| [Aspect Ratio](https://createui.co/docs/components/aspect-ratio) | Reserves a fixed width-to-height ratio for media and embeds so the layout stays put while they load. | Free |
| [Scroll Area](https://createui.co/docs/components/scroll-area) | Styled scroll container with overlay scrollbars for vertical, horizontal, or both axes. | Free |
| [Separator](https://createui.co/docs/components/separator) | Thin horizontal rule for breaking content into visual sections, with optional inline label. | Free + Pro |
| [Mesh Gradient](https://createui.co/docs/components/mesh-gradient) | Animated WebGL mesh-gradient surface that morphs between motion presets, with optional cross-fading status messages. | Pro |

## Blocks

Ready-made, fully composed sections built from Create UI components. Preview each block live, copy the code, or install it with the CLI. Blocks are part of [Create UI Pro](https://createui.co/pricing).

| Category | Blocks | What's inside |
| --- | --- | --- |
| [Login & Sign Up](https://createui.co/blocks/authentication) | 12 | Sign-in, sign-up, password reset, and verification screens, each inside a bordered card. |
| [Full-Page Auth](https://createui.co/blocks/authentication-plain) | 12 | The same auth screens without the card shell, sitting straight on the page. |
| [Dropdown Menus](https://createui.co/blocks/menus) | 24 | Option and action lists anchored to a trigger: dropdowns, right-click menus, pickers, and selects. |
| [Header Navigation](https://createui.co/blocks/header-navigation) | 5 | Top bars with brand, primary links, actions, and the mobile menu they collapse into. |
| [Sidebar Navigation](https://createui.co/blocks/sidebar-navigation) | 3 | Side rails and collapsible app panels with grouped nav, workspace switchers, and account rows. |
| [Modals & Dialogs](https://createui.co/blocks/overlay) | 15 | Modals, drawers, sheets, and confirmation dialogs layered over a page. |
| [Section Headers](https://createui.co/blocks/sections) | 2 | Section headers, toolbars, and in-page structure for content areas. |

Browse all of them on the [blocks page](https://createui.co/blocks).

## Asset Library

Icons, country flags, brand and bank logos, payment and social marks, crypto icons, and badges, shipped as typed React components in the [`@create-ui/assets`](https://www.npmjs.com/package/@create-ui/assets) package. The icon set is Remix Icon 4.9. Search and copy any asset from the [Asset Library](https://createui.co/assets).

```bash
npm install @create-ui/assets
```

## Built for AI Agents

Create UI is built so AI coding agents use your components instead of guessing:

- **[MCP server](https://createui.co/docs/mcp)**: gives agents such as Claude Code, Cursor, and Codex live access to every component's props, variants, and examples.
- **[Agent skill](https://createui.co/docs/skill)**: teaches your agent the Create UI rules for composition, tokens, and icons. Install it with `npx @create-ui/cli skill`.
- **[llms.txt](https://createui.co/llms.txt)**: a plain-text index of the documentation for any LLM.

## Foundation

The design foundation underneath every component: one semantic token system you own and theme. These tokens drive color, type, spacing, radius, and elevation across the whole library, so components stay consistent and adapt to light and dark mode automatically.

| Topic | Description |
| --- | --- |
| [Colors](https://createui.co/docs/colors) | Semantic color tokens for theming, dark mode, and consistent UI. |
| [Typography](https://createui.co/docs/typography) | One type system, seven token families, applied with a single utility class. |
| [Spacing](https://createui.co/docs/spacing) | Responsive, semantic spacing tokens for layout, section, and component rhythm. |
| [Rounded](https://createui.co/docs/rounded) | Responsive, semantic border-radius tokens that scale corners across breakpoints. |
| [Shadows](https://createui.co/docs/shadows) | Semantic shadow tokens for elevation, component states, and depth. |

The same tokens and components live in the [Create UI Figma design system](https://www.figma.com/design/HfaZ9Q7PLS8drGVInGvUVs/Create-UI-%E2%80%94-v1.5-%7BPreview%7D-Design-System?m=auto).

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
- [Blocks](https://createui.co/blocks)
- [Asset Library](https://createui.co/assets)
- [Changelog](https://createui.co/docs/changelog)
- [Pricing](https://createui.co/pricing)
- [Figma Design System](https://www.figma.com/design/HfaZ9Q7PLS8drGVInGvUVs/Create-UI-%E2%80%94-v1.5-%7BPreview%7D-Design-System?m=auto)
- [npm: @create-ui/cli](https://www.npmjs.com/package/@create-ui/cli)
- [X / Twitter](https://x.com/createuico)
- [Discord](https://discord.gg/kYcRZgPgUu)
