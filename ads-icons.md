# **Atlassian Design System Icon Reference**

This document is a comprehensive reference for icons available in the Atlassian Design System. It is divided into four main sections:

1. **Core Icons**: The primary, officially supported icon set from @atlaskit/icon/core. This should be your default choice.  
2. **Icon Lab**: A separate package for icons contributed by various teams across Atlassian.  
3. **Deprecated Icons**: Legacy icons from @atlaskit/icon/glyph and @atlaskit/icon-object that **MUST NOT** be used in new development.  
4. **Icon Usage & Standard Guidelines**: Best practices for implementing icons in Atlassian applications.

## **1\. Core Icons (@atlaskit/icon/core)**

This is the main set of icons for all modern Atlassian UIs. Always import from the /core entrypoint.

| Icon Name (PascalCase) | Import Path |
| :---- | :---- |
| AccessibilityIcon | import AccessibilityIcon from '@atlaskit/icon/core/accessibility'; |
| AddIcon | import AddIcon from '@atlaskit/icon/core/add'; |
| AiChatIcon | import AiChatIcon from '@atlaskit/icon/core/ai-chat'; |
| AiGenerativeTextSummaryIcon | import AiGenerativeTextSummaryIcon from '@atlaskit/icon/core/ai-generative-text-summary'; |
| AlignTextLeftIcon | import AlignTextLeftIcon from '@atlaskit/icon/core/align-text-left'; |
| AppIcon | import AppIcon from '@atlaskit/icon/core/app'; |
| AppSwitcherIcon | import AppSwitcherIcon from '@atlaskit/icon/core/app-switcher'; |
| AppSwitcherLegacyIcon | import AppSwitcherLegacyIcon from '@atlaskit/icon/core/app-switcher-legacy'; |
| AppsIcon | import AppsIcon from '@atlaskit/icon/core/apps'; |
| ArrowDownIcon | import ArrowDownIcon from '@atlaskit/icon/core/arrow-down'; |
| ArrowLeftIcon | import ArrowLeftIcon from '@atlaskit/icon/core/arrow-left'; |
| ArrowRightIcon | import ArrowRightIcon from '@atlaskit/icon/core/arrow-right'; |
| ArrowUpIcon | import ArrowUpIcon from '@atlaskit/icon/core/arrow-up'; |
| AtlassianIcon | import AtlassianIcon from '@atlaskit/logo'; |
| AttachmentIcon | import AttachmentIcon from '@atlaskit/icon/core/attachment'; |
| AtlassianIntelligenceIcon | import AtlassianIntelligenceIcon from '@atlaskit/icon/core/atlassian-intelligence'; |
| AudioIcon | import AudioIcon from '@atlaskit/icon/core/audio'; |
| BoardIcon | import BoardIcon from '@atlaskit/icon/core/board'; |
| CalendarIcon | import CalendarIcon from '@atlaskit/icon/core/calendar'; |
| CameraIcon | import CameraIcon from '@atlaskit/icon/core/camera'; |
| CashIcon | import CashIcon from '@atlaskit/icon/core/cash'; |
| ChartBarIcon | import ChartBarIcon from '@atlaskit/icon/core/chart-bar'; |
| ChartBubbleIcon | import ChartBubbleIcon from '@atlaskit/icon/core/chart-bubble'; |
| ChartPieIcon | import ChartPieIcon from '@atlaskit/icon/core/chart-pie'; |
| ChartTrendDownIcon | import ChartTrendDownIcon from '@atlaskit/icon/core/chart-trend-down'; |
| ChartTrendUpIcon | import ChartTrendUpIcon from '@atlaskit/icon/core/chart-trend-up'; |
| CheckCircleIcon | import CheckCircleIcon from '@atlaskit/icon/core/check-circle'; |
| CheckCircleUncheckedIcon | import CheckCircleUncheckedIcon from '@atlaskit/icon/core/check-circle-unchecked'; |
| CheckMarkIcon | import CheckMarkIcon from '@atlaskit/icon/core/check-mark'; |
| ChevronDownIcon | import ChevronDownIcon from '@atlaskit/icon/core/chevron-down'; |
| ChevronLeftIcon | import ChevronLeftIcon from '@atlaskit/icon/core/chevron-left'; |
| ChevronRightIcon | import ChevronRightIcon from '@atlaskit/icon/core/chevron-right'; |
| ChevronUpIcon | import ChevronUpIcon from '@atlaskit/icon/core/chevron-up'; |
| ChildWorkItemsIcon | import ChildWorkItemsIcon from '@atlaskit/icon/core/child-work-items'; |
| ClockIcon | import ClockIcon from '@atlaskit/icon/core/clock'; |
| CloseIcon | import CloseIcon from '@atlaskit/icon/core/close'; |
| CodeIcon | import CodeIcon from '@atlaskit/icon/core/code'; |
| CollapseHorizontalIcon | import CollapseHorizontalIcon from '@atlaskit/icon/core/collapse-horizontal'; |
| CollapseVerticalIcon | import CollapseVerticalIcon from '@atlaskit/icon/core/collapse-vertical'; |
| CommentIcon | import CommentIcon from '@atlaskit/icon/core/comment'; |
| CopyIcon | import CopyIcon from '@atlaskit/icon/core/copy'; |
| CrossIcon | import CrossIcon from '@atlaskit/icon/core/cross'; |
| DashboardIcon | import DashboardIcon from '@atlaskit/icon/core/dashboard'; |
| DefectIcon | import DefectIcon from '@atlaskit/icon/core/defect'; |
| DeleteIcon | import DeleteIcon from '@atlaskit/icon/core/delete'; |
| DevicesIcon | import DevicesIcon from '@atlaskit/icon/core/devices'; |
| DocumentIcon | import DocumentIcon from '@atlaskit/icon/core/document'; |
| DownloadIcon | import DownloadIcon from '@atlaskit/icon/core/download'; |
| DragHandleIcon | import DragHandleIcon from '@atlaskit/icon/core/drag-handle'; |
| DragHandleHorizontalIcon | import DragHandleHorizontalIcon from '@atlaskit/icon/core/drag-handle-horizontal'; |
| DragHandleVerticalIcon | import DragHandleVerticalIcon from '@atlaskit/icon/core/drag-handle-vertical'; |
| DrawerLeftIcon | import DrawerLeftIcon from '@atlaskit/icon/core/drawer-left'; |
| DrawerRightIcon | import DrawerRightIcon from '@atlaskit/icon/core/drawer-right'; |
| EditIcon | import EditIcon from '@atlaskit/icon/core/edit'; |
| EmailIcon | import EmailIcon from '@atlaskit/icon/core/email'; |
| EmojiIcon | import EmojiIcon from '@atlaskit/icon/core/emoji'; |
| ExclamationSquareIcon | import ExclamationSquareIcon from '@atlaskit/icon/core/exclamation-square'; |
| ExpandIcon | import ExpandIcon from '@atlaskit/icon/core/expand'; |
| ExpandHorizontalIcon | import ExpandHorizontalIcon from '@atlaskit/icon/core/expand-horizontal'; |
| ExpandVerticalIcon | import ExpandVerticalIcon from '@atlaskit/icon/core/expand-vertical'; |
| ExportIcon | import ExportIcon from '@atlaskit/icon/core/export'; |
| FeedbackIcon | import FeedbackIcon from '@atlaskit/icon/core/feedback'; |
| FilterIcon | import FilterIcon from '@atlaskit/icon/core/filter'; |
| FlagIcon | import FlagIcon from '@atlaskit/icon/core/flag'; |
| FlaskIcon | import FlaskIcon from '@atlaskit/icon/core/flask'; |
| FocusAreaIcon | import FocusAreaIcon from '@atlaskit/icon/core/focus-area'; |
| FolderIcon | import FolderIcon from '@atlaskit/icon/core/folder'; |
| FormIcon | import FormIcon from '@atlaskit/icon/core/form'; |
| GoalIcon | import GoalIcon from '@atlaskit/icon/core/goal'; |
| HeadphonesIcon | import HeadphonesIcon from '@atlaskit/icon/core/headphones'; |
| HelpIcon | import HelpIcon from '@atlaskit/icon/core/help'; |
| HomeIcon | import HomeIcon from '@atlaskit/icon/core/home'; |
| ImageIcon | import ImageIcon from '@atlaskit/icon/core/image'; |
| InfoIcon | import InfoIcon from '@atlaskit/icon/core/info'; |
| InviteTeamIcon | import InviteTeamIcon from '@atlaskit/icon/core/invite-team'; |
| LightbulbIcon | import LightbulbIcon from '@atlaskit/icon/core/lightbulb'; |
| LinkIcon | import LinkIcon from '@atlaskit/icon/core/link'; |
| LinkExternalIcon | import LinkExternalIcon from '@atlaskit/icon/core/link-external'; |
| ListChecklistIcon | import ListChecklistIcon from '@atlaskit/icon/core/list-checklist'; |
| LocationIcon | import LocationIcon from '@atlaskit/icon/core/location'; |
| LockLockedIcon | import LockLockedIcon from '@atlaskit/icon/core/lock-locked'; |
| LockUnlockedIcon | import LockUnlockedIcon from '@atlaskit/icon/core/lock-unlocked'; |
| MagicWandIcon | import MagicWandIcon from '@atlaskit/icon/core/magic-wand'; |
| MegaphoneIcon | import MegaphoneIcon from '@atlaskit/icon/core/megaphone'; |
| MentionIcon | import MentionIcon from '@atlaskit/icon/core/mention'; |
| MenuIcon | import MenuIcon from '@atlaskit/icon/core/menu'; |
| MinusSquareIcon | import MinusSquareIcon from '@atlaskit/icon/core/minus-square'; |
| MoreIcon | import MoreIcon from '@atlaskit/icon/core/more'; |
| NotificationIcon | import NotificationIcon from '@atlaskit/icon/core/notification'; |
| OfficeBuildingIcon | import OfficeBuildingIcon from '@atlaskit/icon/core/office-building'; |
| OnCallIcon | import OnCallIcon from '@atlaskit/icon/core/on-call'; |
| PageIcon | import PageIcon from '@atlaskit/icon/core/page'; |
| PaintPaletteIcon | import PaintPaletteIcon from '@atlaskit/icon/core/paint-palette'; |
| PanelLeftIcon | import PanelLeftIcon from '@atlaskit/icon/core/panel-left'; |
| PanelRightIcon | import PanelRightIcon from '@atlaskit/icon/core/panel-right'; |
| PdfIcon | import PdfIcon from '@atlaskit/icon/core/pdf'; |
| PenIcon | import PenIcon from '@atlaskit/icon/core/pen'; |
| PeopleIcon | import PeopleIcon from '@atlaskit/icon/core/people'; |
| PersonIcon | import PersonIcon from '@atlaskit/icon/core/person'; |
| PersonAvatarIcon | import PersonAvatarIcon from '@atlaskit/icon/core/person-avatar'; |
| PinIcon | import PinIcon from '@atlaskit/icon/core/pin'; |
| PinFilledIcon | import PinFilledIcon from '@atlaskit/icon/core/pin-filled'; |
| PlusSquareIcon | import PlusSquareIcon from '@atlaskit/icon/core/plus-square'; |
| PreferencesIcon | import PreferencesIcon from '@atlaskit/icon/core/preferences'; |
| PresenceActiveIcon | import PresenceActiveIcon from '@atlaskit/icon/core/presence-active'; |
| PriorityBlockerIcon | import PriorityBlockerIcon from '@atlaskit/icon/core/priority-blocker'; |
| PriorityCriticalIcon | import PriorityCriticalIcon from '@atlaskit/icon/core/priority-critical'; |
| PriorityHighIcon | import PriorityHighIcon from '@atlaskit/icon/core/priority-high'; |
| PriorityHighestIcon | import PriorityHighestIcon from '@atlaskit/icon/core/priority-highest'; |
| PriorityLowIcon | import PriorityLowIcon from '@atlaskit/icon/core/priority-low'; |
| PriorityLowestIcon | import PriorityLowestIcon from '@atlaskit/icon/core/priority-lowest'; |
| PriorityMajorIcon | import PriorityMajorIcon from '@atlaskit/icon/core/priority-major'; |
| PriorityMediumIcon | import PriorityMediumIcon from '@atlaskit/icon/core/priority-medium'; |
| PriorityMinorIcon | import PriorityMinorIcon from '@atlaskit/icon/core/priority-minor'; |
| QuestionIcon | import QuestionIcon from '@atlaskit/icon/core/question'; |
| QuoteIcon | import QuoteIcon from '@atlaskit/icon/core/quote'; |
| RefreshIcon | import RefreshIcon from '@atlaskit/icon/core/refresh'; |
| RovoChatIcon | import RovoChatIcon from '@atlaskit/icon/core/rovo-chat'; |
| SaveIcon | import SaveIcon from '@atlaskit/icon/core/save'; |
| SearchIcon | import SearchIcon from '@atlaskit/icon/core/search'; |
| SendIcon | import SendIcon from '@atlaskit/icon/core/send'; |
| SettingsIcon | import SettingsIcon from '@atlaskit/icon/core/settings'; |
| ShapesIcon | import ShapesIcon from '@atlaskit/icon/core/shapes'; |
| ShareIcon | import ShareIcon from '@atlaskit/icon/core/share'; |
| StarIcon | import StarIcon from '@atlaskit/icon/core/star'; |
| StarStarredIcon | import StarStarredIcon from '@atlaskit/icon/core/star-starred'; |
| StarUnstarredIcon | import StarUnstarredIcon from '@atlaskit/icon/core/star-unstarred'; |
| StatusDiscoveryIcon | import StatusDiscoveryIcon from '@atlaskit/icon/core/status-discovery'; |
| StatusErrorIcon | import StatusErrorIcon from '@atlaskit/icon/core/status-error'; |
| StatusInformationIcon | import StatusInformationIcon from '@atlaskit/icon/core/status-information'; |
| StatusSuccessIcon | import StatusSuccessIcon from '@atlaskit/icon/core/status-success'; |
| StatusVerifiedIcon | import StatusVerifiedIcon from '@atlaskit/icon/core/status-verified'; |
| StatusWarningIcon | import StatusWarningIcon from '@atlaskit/icon/core/status-warning'; |
| StopwatchIcon | import StopwatchIcon from '@atlaskit/icon/core/stopwatch'; |
| TableIcon | import TableIcon from '@atlaskit/icon/core/table'; |
| TextStrikethroughIcon | import TextStrikethroughIcon from '@atlaskit/icon/core/text-strikethrough'; |
| TrashIcon | import TrashIcon from '@atlaskit/icon/core/trash'; |
| UndoIcon | import UndoIcon from '@atlaskit/icon/core/undo'; |
| UploadIcon | import UploadIcon from '@atlaskit/icon/core/upload'; |
| VideoIcon | import VideoIcon from '@atlaskit/icon/core/video'; |
| WatchIcon | import WatchIcon from '@atlaskit/icon/core/watch'; |
| WorkItemIcon | import WorkItemIcon from '@atlaskit/icon/core/work-item'; |
| WorkItemsIcon | import WorkItemsIcon from '@atlaskit/icon/core/work-items'; |
| WorldIcon | import WorldIcon from '@atlaskit/icon/core/world'; |

## **2\. Icon Lab (@atlaskit/icon-lab)**

Icon Lab is a separate package for custom icons contributed by various teams across Atlassian. It serves as a centralized home for these icons to ensure consistency and avoid duplication.

* **Import Pattern**: import SomeIcon from '@atlaskit/icon-lab/some-icon';  
* **Usage**: While these icons are available, the Core Icons should be preferred. Use Icon Lab icons when a specific, team-contributed icon is required for a particular context.

## **3\. Deprecated Icons (DO NOT USE)**

The following icon sets are deprecated and **MUST NOT** be used for any new UI development.

### **Deprecated: @atlaskit/icon/glyph**

The /glyph entrypoint is the legacy icon system and has been replaced by /core icons.

* **Do NOT use**: import SomeIcon from '@atlaskit/icon/glyph/some-icon';  
* **Example Legacy Icons (Not Exhaustive)**: add-circle, arrow-left, arrow-right, attachment, audio-circle, backlog, billing, bitbucket/branches, bitbucket/builds, etc.

### **Deprecated: @atlaskit/icon-object**

The @atlaskit/icon-object package is deprecated and has been replaced by the @atlaskit/object component.

| Icon Name | Deprecated Import Path |
| :---- | :---- |
| Blog | @atlaskit/icon-object/glyph/blog/... |
| Branch | @atlaskit/icon-object/glyph/branch/... |
| Bug | @atlaskit/icon-object/glyph/bug/... |
| Epic | @atlaskit/icon-object/glyph/epic/... |
| Task | @atlaskit/icon-object/glyph/task/... |

## **4\. Icon Usage & Standard Guidelines**

To maintain consistency and accessibility across all Atlassian apps, follow these rules derived from the official Atlassian Design System standards.

### **General Usage**

* **Core Preference**: Always prioritize icons from the @atlaskit/icon/core package. These are optimized for the latest visual refresh and performance.  
* **Pairing with Text**: Icons should ideally be used alongside a text label to provide clarity and context.  
* **Styling Consistency**: Ensure icon colors maintain visual consistency with associated text. Use design tokens (e.g., color.icon) instead of hardcoded hex values.

### **Accessibility & Labeling**

* **Icon-Only Buttons**: If a button contains only an icon, you **must** provide an accessible label via the aria-label prop or the label prop (on IconButton).  
* **Descriptive Purpose**: Labels should describe the *purpose* of the action, not the visual appearance of the icon. For example, use "Delete" instead of "Trash icon".  
* **Screen Reader Context**: Use the VisuallyHidden component for screen reader text when additional context is required that isn't visually obvious.  
* **Presence Indicators**: When using icons for status or presence, ensure the name or label prop describes the state for assistive technologies.

### **Sizing and Layout**

* **Standard Sizing**: Use the standard size prop (small, medium, large).  
  * small: For use inside tight UI elements like breadcrumbs or inline with small text.  
  * medium: Default size for most UI interactions.  
  * large: For high-emphasis areas or large headers.  
* **Navigation System**: In SideNav or TopNav, use icons within the elemBefore or elemAfter props to ensure correct alignment and spacing within menu items.

### **Branding & Logos**

* **Atlassian Identity**: For "Home" navigation or branding, use the CustomLogo component from @atlaskit/navigation-system. This component correctly pairs the AtlassianIcon and AtlassianLogo.  
* **Third-Party Icons**: Only use team-contributed icons from @atlaskit/icon-lab if a suitable equivalent does not exist in Core.

### **Technical Implementation**

* **Deprecated Sets**: Do not use icons from @atlaskit/icon/glyph or @atlaskit/icon-object in new development. Transition legacy usage to the @atlaskit/icon/core equivalents.  
* **Bidi Support**: Be aware of bidirectional text rendering; some icons (like arrows) may need to be mirrored for RTL languages.

#### **Works cited**

1. Changelog \- Icon \- Atlassian Frontend Development \- Atlaskit, accessed on October 29, 2025, [https://atlaskit.atlassian.com/packages/core/icon/changelog](https://atlaskit.atlassian.com/packages/core/icon/changelog)  
2. atlaskit/icon \- Yarn Classic, accessed on October 29, 2025, [https://classic.yarnpkg.com/en/package/@atlaskit/icon](https://classic.yarnpkg.com/en/package/@atlaskit/icon)  
3. Behind the screens: Building Atlassian's new icon system, accessed on October 29, 2025, [https://www.atlassian.com/blog/design/behind-the-screens-building-atlassians-new-icon-system](https://www.atlassian.com/blog/design/behind-the-screens-building-atlassians-new-icon-system)  
4. atlaskit/icon-lab \- NPM, accessed on October 29, 2025, [https://www.npmjs.com/package/@atlaskit/icon-lab](https://www.npmjs.com/package/@atlaskit/icon-lab)  
5. Icon (legacy) \- Icon explorer \- Components \- Atlassian Design System, accessed on October 29, 2025, [https://atlassian.design/components/icon/icon-legacy](https://atlassian.design/components/icon/icon-legacy)  
6. @atlaskit/icon-01-icon-explorer \- Codesandbox, accessed on October 29, 2025, [https://codesandbox.io/s/atlaskiticon-01-icon-explorer-3md41](https://codesandbox.io/s/atlaskiticon-01-icon-explorer-3md41)  
7. Icon object \- Icon explorer \- Components \- Atlassian Design System, accessed on October 29, 2025, [https://atlassian.design/components/icon-object](https://atlassian.design/components/icon-object)