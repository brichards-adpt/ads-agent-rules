# **Atlassian Design System Component Reference**

This document contains a comprehensive list of components available in the Atlassian Design System. Use this as a reference to find the correct component and its associated NPM package for any UI task. Components are sourced from the official documentation and package repositories.

### **Forms and inputs**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Button | @atlaskit/button/new | Triggers an event or action. (Root entrypoint deprecated, use /new). | Active |
| IconButton | @atlaskit/button/new | A button that displays only an icon with an optional tooltip. | Active |
| SplitButton | @atlaskit/button/new | A button that splits into a primary action and a dropdown menu. | Active |
| LinkButton | @atlaskit/button/new | A button that renders as an anchor tag for navigation. | Active |
| Calendar | @atlaskit/calendar | An interactive calendar for date selection experiences. | Beta |
| Checkbox | @atlaskit/checkbox | Allows a user to select one or more options. | Active |
| Comment | @atlaskit/comment | Displays discussions and user feedback. | Active |
| Date time picker | @atlaskit/datetime-picker | Allows the user to select an associated date and time. | Active |
| Dropdown menu | @atlaskit/dropdown-menu | Displays a list of actions or options to a user. | Active |
| Form | @atlaskit/form | Allows users to input information and manages form state. | Active |
| Radio | @atlaskit/radio | Allows users to select only one option from a number of choices. | Active |
| Range | @atlaskit/range | Lets users choose an approximate value on a slider. | Active |
| Select | @atlaskit/select | Allows single or multiple selections from a list of options. | Active |
| Text area | @atlaskit/textarea | Lets users enter long form text which spans over multiple lines. | Active |
| Text field | @atlaskit/textfield | An input that allows a user to write or edit text. | Active |
| Toggle | @atlaskit/toggle | Used to view or switch between enabled or disabled states. | Active |

### **Images and icons**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Avatar | @atlaskit/avatar | A visual representation of a user or entity. | Active |
| Avatar group | @atlaskit/avatar-group | Displays a number of avatars grouped together. | Active |
| Icon | @atlaskit/icon/core/\* | New core icons: add, copy, edit, trash, star, comment. | Beta |
| Image | @atlaskit/image | An image component that can switch between light and dark themes. | Beta |
| Logo | @atlaskit/logo | A visual representation of a brand or app. | Active |

### **Layout and structure**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Page header | @atlaskit/page-header | Defines the top of a page, containing a title and actions. | Active |
| Navigation system | @atlaskit/navigation-system | Modern nav layout: Root, TopNav, SideNav, Main. | Early Access |

### **Loading**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Progress bar | @atlaskit/progress-bar | Communicates the status of a system process. | Active |
| Skeleton | @atlaskit/skeleton | Acts as a placeholder for content, usually while loading. | Early Access |
| Spinner | @atlaskit/spinner | An animated spinning icon that lets users know content is loading. | Active |

### **Messaging**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Banner | @atlaskit/banner | Displays a prominent message at the top of the screen. | Active |
| Flag | @atlaskit/flag | For confirmations, alerts, and acknowledgments. | Active |
| Inline message | @atlaskit/inline-message | Alerts users to important information or required actions. | Active |
| Modal dialog | @atlaskit/modal-dialog | Displays content that requires user interaction in a layer. | Active |
| Onboarding | @atlaskit/onboarding | Introduces features via Spotlights and tours. | Active |
| Section message | @atlaskit/section-message | Alerts users to a particular section of the screen. | Active |

### **Navigation**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Breadcrumbs | @atlaskit/breadcrumbs | Shows a user's location in a site or app. | Active |
| Link | @atlaskit/link | Takes people to a new location. | Active |
| Menu | @atlaskit/menu | A list of options to help users navigate or perform actions. | Active |
| Pagination | @atlaskit/pagination | Divides large amounts of content into smaller chunks. | Active |
| Tabs | @atlaskit/tabs | Organizes content by grouping similar information. | Active |

### **Overlays and layering**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Blanket | @atlaskit/blanket | Covers the underlying UI for a layered component. | Active |
| Drawer | @atlaskit/drawer | A panel that slides in from the side of the screen. | Caution |
| Popup | @atlaskit/popup | Displays brief content in an overlay. Replaces Inline Dialog. | Active |
| Tooltip | @atlaskit/tooltip | A floating, non-actionable label to explain a UI element. | Active |

### **Status indicators**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Badge | @atlaskit/badge | A visual indicator for numeric values such as counts. | Active |
| Empty state | @atlaskit/empty-state | Appears when there is no data to display. | Active |
| Lozenge | @atlaskit/lozenge | A visual indicator to highlight an item's status. | Active |
| Progress indicator | @atlaskit/progress-indicator | Shows where users are along steps of a journey. | Active |
| Progress tracker | @atlaskit/progress-tracker | Displays steps and progress through a journey. | Active |
| Tag | @atlaskit/tag | Labels UI objects for quick recognition. | Active |
| Tag group | @atlaskit/tag-group | Controls layout/alignment for a collection of tags. | Active |

### **Text and data display**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Code | @atlaskit/code | Highlights short strings of code snippets inline. | Active |
| Dynamic table | @atlaskit/dynamic-table | Displays data with pagination, sorting, and re-ordering. | Active |
| Heading | @atlaskit/heading | Typography component for different text sizes. | Beta |
| Inline edit | @atlaskit/inline-edit | Switches between reading and editing on the same page. | Active |
| Table tree | @atlaskit/table-tree | Expandable table for showing nested hierarchies. | Active |
| Visually hidden | @atlaskit/visually-hidden | Hides content from screen but not screen readers. | Active |

### **Primitives**

| Component Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| Box | @atlaskit/primitives/compiled | Generic container for design tokens. | Active |
| Inline | @atlaskit/primitives/compiled | Horizontal flexbox layout. | Active |
| Stack | @atlaskit/primitives/compiled | Vertical flexbox layout. | Active |
| Flex | @atlaskit/primitives/compiled | CSS Flexbox API implementation. | Beta |
| Grid | @atlaskit/primitives/compiled | CSS Grid API implementation. | Beta |
| Bleed | @atlaskit/primitives/compiled | Controls negative whitespace. | Active |
| Show | @atlaskit/primitives/compiled | Conditionally shows content at breakpoints. | Active |
| Hide | @atlaskit/primitives/compiled | Conditionally hides content at breakpoints. | Active |
| Text | @atlaskit/primitives/compiled | Token-backed typography component. | Beta |
| Pressable | @atlaskit/primitives/compiled | Primitive for custom buttons. | Active |
| Anchor | @atlaskit/primitives/compiled | Primitive for custom links. | Active |
| Focusable | @atlaskit/primitives/compiled | Replaces Focus Ring for focus management. | Active |

### **Libraries & Tooling**

| Name | NPM Package | Description | Status |
| :---- | :---- | :---- | :---- |
| CSS reset | @atlaskit/css-reset | A base stylesheet for the Atlassian Design System. | Active |
| Design tokens | @atlaskit/tokens | The single source of truth for design decisions. | Active |
| Motion | @atlaskit/motion | Utilities to apply motion in your application. | Active |
| Pragmatic drag and drop | @atlaskit/pragmatic-drag-and-drop | Flexible and fast drag and drop for any experience. | Active |
| ESLint plugin | @atlaskit/eslint-plugin-design-system | Essential ESLint plugin for ADS. | Active |

## **Design and Usage Rules**

### **1\. Styling & Tokens**

* **Strict Tokenization:** Never use hardcoded values. Use token('color.background.brand.bold').  
* **Token Pairing:** Match foreground and background. For dark backgrounds, always use token('color.text.inverse') for contrast.  
* **Compiled Standard:** Prefer @atlaskit/css (using cssMap) over raw Emotion or Styled Components.  
* **Avoid Dynamic Styles:** Do not use dynamic values in css() calls; use the style prop for runtime-only values.

### **2\. Icons & Buttons**

* **Naming:** The three-dot icon is called **"More actions"** (meatballs).  
* **Icon-Only Buttons:** Must use IconButton with a label prop or aria-label.  
* **Placement:** Use iconBefore or iconAfter in the Button component for descriptive actions.

### **3\. Content & Voice**

* **Sentence Case:** Always capitalize the first word and proper nouns only (e.g., "Create new issue").  
* **Curly Punctuation:** Use curly quotes/apostrophes. Shortcuts:  
  * Mac: Option+\[ (open), Option+Shift+\[ (close).  
  * Windows: Alt+0147 (open), Alt+0148 (close).  
* **Lists:** Limit bulleted lists to 6 items or fewer. Use a colon to lead in if items are fragments.  
* **Abbreviations:** Avoid i.e., e.g., or & in UI copy as they are not localization-friendly.

### **4\. Accessibility (A11y)**

* **Heading Hierarchy:** Use Heading levels (h1-h6) semantically, not for visual styling.  
* **Input Labels:** Every input must have a visible label. Do not use placeholders as labels.  
* **Focus Indicators:** Ensure :focus-visible is styled with token('color.border.focused').  
* **Live Regions:** Announce dynamic changes (like "Item deleted") using aria-live.

### **5\. Migration & Status**

* **Deprecated:** @atlaskit/grid, @atlaskit/focus-ring, @atlaskit/inline-dialog.  
* **Replacement:** Use Grid (primitive), Focusable, and Popup respectively.  
* **Navigation:** NavigationSystem is the standard for modern app shell layouts.