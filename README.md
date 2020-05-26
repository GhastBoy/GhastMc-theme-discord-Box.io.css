/* Imports */
@import "https://fonts.googleapis.com/css2?family=Chelsea+Market";
@import "https://monstrousdev.github.io/themes/addons/user-tags.css";
/* @import "https://monstrousdev.github.io/themes/addons/filter.css"; */
@import "https://www.themonster.xyz/styles/google-fonts.css";
@import url("https://discord-custom-covers.github.io/usrbg/snippets/userPopouts.css");

/* Variables */
:root {
  --theme-version: "1.5";
  --main-color: #16356d;
  --hover-color: #1c4faf;
  --online: #43b581;
  --idle: #faa61a;
  --dnd: #f04747;
  --offline: #636b75;
  --invisible: #747f8d;
  --streaming: #643da7;
  --home-color: #eee;
  --home-size: 24px;
  --roundness: 0px;
  --spoiler-blur: 5px;
  --shadow: rgba(0,0,0,.4);
  --alert-display: block;
  --accent: var(--main-color);
}
/* Table of Contents
    ======== STATIC ==========
 1. Title Bar
  1.a. Main Title Bar
  1.b. Mac Main Title Bar
  1.c. Windows Buttons
  1.d. Mac Buttons
  1.e. Erase & Change SVGs

 2. Chat Header
  2.a. Coloring and Spacing
  2.b. Search Bars
  2.c. Change Icons

 3. User Settings
  3.a. General Sidebar
  3.b. General Content Area
  3.c. Cards and Items
  3.d. Buttons, Switches, and Bars
  3.e. Overlay Notifications
  3.f. Nitro and Hypesquad Section

 4. Guilds Wrapper
  4.a. Mains Guilds Wrapper
  4.b. Guilds
  4.c. Guilds Add
  4.d. Badges

 5. Channels
  5.a. Main Channels Area
  5.b. Light Theme Recolor
  5.c. Channel Font Colors
  5.d. Channels
  5.e. Unread Indicator
  5.f. Categories
  5.g. DM List
  5.h. Unread Messages Popout

 6. Account Area
  6.a. Main Container
  6.b. Buttons
  6.c. Light Theme Recolor
  6.d. Listening Along

 7. Members List
  7.a. Main Member List
  7.b. Hoisted Roles

 8. Chat
  8.a. Main Chat Area
  8.b. Messages
  8.c. Blocked Messages
  8.d. Spoiler Messages
  8.e. Chat Dividers
  8.f. Mentions
  8.g. Code Blocks
  8.h. New Messages Bar and Loading Symbols
  8.i. DM Chat
  8.j. Bot Message
  8.k. Embeds
  8.l. Text Area
  8.m. Typing Bar
  8.n. Notification Bar
  8.o. Search Results
  8.p. Video Calling
  8.q. Streaming

 9. Friends List
  9.a. Main Friends List
  9.b. Action Buttons

10. Games Tab, Library, Store and Server Directory
  10.a. Tab
  10.b. Library
  10.c. Store
  10.d. Server Directory

11. Avatars
  11.a. Remove Mask
  11.b. Status

12. Shadows

13. Roundness

14. Scrollbars

================== SLIDE INS ====================
15. Popouts
  15.a. Pinned Messages and Recent Mentions
  15.b. Emoji Picker and Reactions
  15.c. Autocomplete
  15.d. User Popout
  15.e. Add Role User Popout
  15.f. Search Popout
  15.g. Server Settings
  15.h. Group DM Invite Popout
  15.i. Tooltips
  15.j. @Everyone Popout
  15.k. Attach Popout
  15.l. RTC Connection Popout
  15.m. More Users Popout
  15.n. Overflow Roles Popout
  15.o. Dropdown Menu Popout
  15.p. DM Call Region Select Popout

16. Menus
  16.a. Context Menus
  16.b. Status Picker
  16.c. Message Menu
  16.d. Color Picker

17. Modals
  17.a. Help Modal
  17.b. User Profile Modal
  17.c. Instant Invite Modal
  17.d. Join or Create New Guild
  17.e. Upload Modal
  17.f. Game Preview Modal
  17.g. Quick Switcher
  17.h. Screenshare Modal
  17.i. Phone Verification Modal
  17.j. Smartphone Modal
  17.k. Drag and Drop Modal
  17.l. Generic Modal
  17.m. Gift Nitro Modal & Nitro Boost
  17.n. Server Templates

18. Login Page

19. Keyframes

20. Misc
  20.a. Plugin Optimization
    20.a.1. BetterFormatting
    20.a.2. Permission Viewer
    20.a.3. Character Counter
    20.a.4. Reply System
    20.a.5. Server Folders
    20.a.6. Share Button
    20.a.7. Theme and Plugin Repo
    20.a.8. Personal Pins
    20.a.9. Detailed Tooltip
    20.a.10 Ghost Ping
  
  20.b. Addon Optimization
    20.b.1. Custom Popouts

21. Custom CSS

22. @Media Edits
*/




/* ================================= STATIC =======================================*/

/* 1. Title Bar */
  /* 1.a. Main Title Bar */
#app-mount .bg-h5JY_x {
  background: transparent !important;
}

.titleBar-AC4pGV {
  transform: translateY(-6px);
  height: 0px;
  margin-top: 0px;
}

.titleBar-AC4pGV:before {
  content: '';
  position: absolute;
  left: 0;
  right: 0;
  top: 6px;
  height: 14px;
  z-index: 3002;
  -webkit-app-region: drag !important;
	pointer-events: none;
}

.titleBar-AC4pGV:after {
  content: '';
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  height: 6px;
  z-index: 3002 !important;
	pointer-events: none;
}

.titleBar-AC4pGV div {
	transform: scale(0.8) !important;
}

.title-3qD0b-,
.titleCall-_b9o8P {
  height: 46px;
}

  /* 1.b. Mac Main Title Bar*/
.typeMacOS-3EmCyP.titleBar-AC4pGV { 
	transform: none; 
	position: relative; 
}

  /* 1.c. Windows Buttons */
  .winButton-iRh8-Z {
  top: 9px;
  height: 36px;
  width: 30px;
  right: 8px;
  background-position: center;
  opacity: .6;
  transition: .2s ease !important;
}

.winButton-iRh8-Z:hover {
  -webkit-transition: all .2s ease-in-out;
  transition: all .2s ease-in-out;
  background-color: var(--hover-color) !important;
  border-radius: 3px;
  opacity: 1 !important;
}

.titleBar-AC4pGV .winButtonClose-1HsbF- {
	background-image: url(https://monstrousdev.github.io/themes/assets/svgs/cancel.svg) !important;
	background-repeat: no-repeat;
	background-position: center;
	background-size: 24px;
}

.titleBar-AC4pGV .winButton-iRh8-Z:nth-child(3) {
	background-image: url(https://monstrousdev.github.io/themes/assets/svgs/fullscreen.svg) !important;
	background-repeat: no-repeat;
	background-position: center;
	background-size: 24px;
}

.titleBar-AC4pGV .winButton-iRh8-Z:nth-child(4) {
	background-image: url(https://monstrousdev.github.io/themes/assets/svgs/minimize.svg) !important;
	background-repeat: no-repeat;
	background-position: center 7px;
	background-size: 24px;
}

  /* 1.d. Mac Buttons */
.typeMacOS-3EmCyP.titleBar-AC4pGV {
  width: 100%;
  justify-content: flex-start;
}

.typeMacOS-3EmCyP.titleBar-AC4pGV .macButton-c_Adir { 
  background-image: none !important;
  margin: 0px 3px; 
}


  /* 1.e. Erase & Change SVGs */
.titleBar-AC4pGV rect,
.wordmark-2iDDfm,
.winButton-iRh8-Z svg,
.topic-2QX7LI:before,
.divider-2PMBlV { display: none;}

.theme-dark .icon-22AiRD {
  color: #ccc;
}

.theme-light .icon-22AiRD {
  color: #222;
}

svg[name="Nova_Bell"] path,
svg[name="Nova_BellOff"] path,
svg[name="Nova_Pin"] path,
svg[name="Nova_People"] path,
svg[name="Nova_At"] path,
svg[name="Nova-CallJoin"] path,
svg[name="PersonWaving"] path,
svg[name="NitroWheel"] path,
svg[name="Library"] path,
svg[name="Activity"] path{
  display: none;
}

svg[name="Nova_Bell"] {
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/svgs/bell.svg) center/100% no-repeat;
  mask: url(https://monstrousdev.github.io/themes/assets/svgs/bell.svg) center/100% no-repeat;
}

svg[name="Nova_BellOff"] {
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/svgs/bell-off.svg) center/100% no-repeat;
  mask: url(https://monstrousdev.github.io/themes/assets/svgs/bell.svg) center/100% no-repeat;
}

svg[name="Nova_Pin"] {
  background-color: currentColor;
  -webkit-mask: url("data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOC4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+DQo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgdmlld0JveD0iMCAwIDI0IDI0IiBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCAyNCAyNCIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+DQo8cGF0aCBmaWxsPSJub25lIiBkPSJNMCwwaDI0djI0SDBWMHoiLz4NCjxwb2x5Z29uIGZpbGw9IiNGRkZGRkYiIHBvaW50cz0iMTcuOSwxMy43IDE1LjgsMTIuNiAxNS4xLDUuMyAxNi40LDUgMTYuNCwzIDcuNiwzIDcuNiw1IDguOSw1LjMgOC4yLDEyLjYgNi4xLDEzLjcgNi4xLDE1LjcgDQoJMTEsMTUuNyAxMSwyMSAxMywyMSAxMywxNS43IDE3LjksMTUuNyAiLz4NCjwvc3ZnPg0K") center/100% no-repeat;
  mask: url("data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOC4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+DQo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgdmlld0JveD0iMCAwIDI0IDI0IiBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCAyNCAyNCIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+DQo8cGF0aCBmaWxsPSJub25lIiBkPSJNMCwwaDI0djI0SDBWMHoiLz4NCjxwb2x5Z29uIGZpbGw9IiNGRkZGRkYiIHBvaW50cz0iMTcuOSwxMy43IDE1LjgsMTIuNiAxNS4xLDUuMyAxNi40LDUgMTYuNCwzIDcuNiwzIDcuNiw1IDguOSw1LjMgOC4yLDEyLjYgNi4xLDEzLjcgNi4xLDE1LjcgDQoJMTEsMTUuNyAxMSwyMSAxMywyMSAxMywxNS43IDE3LjksMTUuNyAiLz4NCjwvc3ZnPg0K") center/100% no-repeat;
  transform: scaleX(-1)
}

svg[name="Nova_People"] {
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/home-tabs/friends.svg) center/100% no-repeat;
  mask: url(https://monstrousdev.github.io/themes/assets/home-tabs/friends.svg) center/100% no-repeat;
}

svg[name="Nova_At"] {
  background-color: currentColor;
  -webkit-mask: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' name='Mention' class='iconInactive-g2AXfB icon-1R19_H da-iconInactive da-icon' width='16' height='16' viewBox='0 0 24 24'%3E%3Cpath fill='currentColor' class='iconForeground-3y9f0B da-iconForeground' fill-rule='evenodd' d='M12.2608,9.57136 C11.91424,9.57136 11.6072,9.67136 11.3464,9.87136 C11.0856,10.07136 10.86432,10.32496 10.68208,10.63568 C10.5,10.94288 10.36432,11.2856 10.26784,11.65712 C10.17488,12.02864 10.12496,12.38944 10.12496,12.73216 C10.12496,12.90352 10.14288,13.08576 10.17856,13.28224 C10.21424,13.47504 10.2856,13.6536 10.39632,13.82144 C10.50352,13.9856 10.64624,14.12144 10.82128,14.22864 C10.99632,14.33584 11.22848,14.38944 11.51776,14.38944 C11.91056,14.38944 12.24272,14.2928 12.51776,14.1 C12.7928,13.9072 13.01776,13.66416 13.1928,13.36784 C13.36784,13.07504 13.4928,12.7536 13.57504,12.41088 C13.6536,12.068 13.6928,11.75008 13.6928,11.46432 C13.6928,11.23568 13.67136,11.01072 13.62864,10.78576 C13.58576,10.56432 13.51088,10.36432 13.4,10.18224 C13.2928,10.00368 13.14288,9.85728 12.9536,9.74288 C12.76784,9.62864 12.53584,9.57136 12.2608,9.57136 L12.2608,9.57136 Z M18.57808,16.8728 C18.84672,17.16224 18.84672,17.63168 18.55136,17.89328 C17.81248,18.54608 16.96928,19.0408 16.02144,19.37504 C14.8464,19.7928 13.6072,20 12.30352,20 C11.05696,20 9.92128,19.80352 8.9,19.4072 C7.87856,19.0144 7.00352,18.46416 6.28208,17.7608 C5.55712,17.05728 4.99632,16.21424 4.59632,15.23216 C4.19648,14.24992 4,13.17856 4,12.01792 C4,10.87136 4.21792,9.81072 4.6536,8.83568 C5.08928,7.86064 5.68208,7.01424 6.43568,6.29632 C7.18928,5.57856 8.06784,5.01776 9.07856,4.60704 C10.08208,4.20352 11.16064,4 12.30352,4 C13.28912,4 14.2464,4.14288 15.17136,4.42864 C16.1,4.7144 16.92144,5.1464 17.63936,5.71792 C18.35712,6.29296 18.92864,7.0072 19.35712,7.86784 C19.78576,8.72864 20,9.73936 20,10.9 C20,11.76064 19.88224,12.52144 19.64288,13.17856 C19.40368,13.8392 19.08592,14.38928 18.68592,14.83568 C18.28592,15.28208 17.83232,15.61408 17.31792,15.83568 C16.80368,16.05712 16.26448,16.16768 15.70016,16.16768 C15.1216,16.16768 14.65728,16.032 14.30736,15.76064 C13.96096,15.48912 13.78592,15.14272 13.78592,14.72848 L13.67872,14.72848 C13.46096,15.07136 13.12864,15.39984 12.67872,15.70704 C12.2288,16.01424 11.67872,16.1712 11.02512,16.1712 C10.03936,16.1712 9.27872,15.84976 8.74288,15.20336 C8.2072,14.55696 7.93936,13.72112 7.93936,12.6856 C7.93936,12.08192 8.03936,11.48912 8.24288,10.89984 C8.4464,10.31056 8.73584,9.78912 9.11072,9.32848 C9.48576,8.87136 9.93568,8.49984 10.45712,8.22128 C10.97856,7.94272 11.55712,7.80352 12.19648,7.80352 C12.74656,7.80352 13.21088,7.91776 13.58928,8.1464 C13.96432,8.37504 14.21088,8.65712 14.32864,8.98576 L14.35008,8.98576 L14.38288,8.82512 C14.46144,8.4384 14.8448,8.12512 15.23936,8.12512 L15.74656,8.12512 C16.14128,8.12512 16.3952,8.43792 16.31408,8.824 L15.60736,12.19296 C15.57872,12.39296 15.53936,12.6144 15.48944,12.8608 C15.43952,13.10384 15.4144,13.33232 15.4144,13.55024 C15.4144,13.79312 15.46096,13.99664 15.55744,14.16448 C15.65024,14.3288 15.836,14.41104 16.11088,14.41104 C16.6752,14.41104 17.14304,14.11088 17.51456,13.50752 C17.8824,12.904 18.068,12.0968 18.068,11.07888 C18.068,10.21824 17.9216,9.45392 17.63232,8.7896 C17.34288,8.12176 16.93936,7.56464 16.42512,7.11104 C15.91088,6.66112 15.29648,6.31824 14.58928,6.0896 C13.87872,5.86096 13.10368,5.74672 12.26448,5.74672 C11.35008,5.74672 10.5144,5.90736 9.75376,6.22896 C8.99296,6.5504 8.34304,6.9968 7.8072,7.56112 C7.27152,8.12896 6.85376,8.79328 6.55728,9.56112 C6.25728,10.32544 6.10736,11.15408 6.10736,12.04336 C6.10736,12.98976 6.26448,13.84336 6.5752,14.604 C6.88592,15.36464 7.32528,16.0112 7.88944,16.5504 C8.4536,17.0896 9.1288,17.50048 9.91088,17.78624 C10.69312,18.07184 11.55728,18.21472 12.49664,18.21472 C13.67168,18.21472 14.6824,18.02912 15.5288,17.65408 C16.16528,17.37488 16.76304,17.01264 17.32304,16.56944 C17.632,16.3248 18.08192,16.3384 18.35056,16.62768 L18.57808,16.8728 L18.57808,16.8728 Z'%3E%3C/path%3E%3C/svg%3E") center/100% no-repeat;
  mask: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' name='Mention' class='iconInactive-g2AXfB icon-1R19_H da-iconInactive da-icon' width='16' height='16' viewBox='0 0 24 24'%3E%3Cpath fill='currentColor' class='iconForeground-3y9f0B da-iconForeground' fill-rule='evenodd' d='M12.2608,9.57136 C11.91424,9.57136 11.6072,9.67136 11.3464,9.87136 C11.0856,10.07136 10.86432,10.32496 10.68208,10.63568 C10.5,10.94288 10.36432,11.2856 10.26784,11.65712 C10.17488,12.02864 10.12496,12.38944 10.12496,12.73216 C10.12496,12.90352 10.14288,13.08576 10.17856,13.28224 C10.21424,13.47504 10.2856,13.6536 10.39632,13.82144 C10.50352,13.9856 10.64624,14.12144 10.82128,14.22864 C10.99632,14.33584 11.22848,14.38944 11.51776,14.38944 C11.91056,14.38944 12.24272,14.2928 12.51776,14.1 C12.7928,13.9072 13.01776,13.66416 13.1928,13.36784 C13.36784,13.07504 13.4928,12.7536 13.57504,12.41088 C13.6536,12.068 13.6928,11.75008 13.6928,11.46432 C13.6928,11.23568 13.67136,11.01072 13.62864,10.78576 C13.58576,10.56432 13.51088,10.36432 13.4,10.18224 C13.2928,10.00368 13.14288,9.85728 12.9536,9.74288 C12.76784,9.62864 12.53584,9.57136 12.2608,9.57136 L12.2608,9.57136 Z M18.57808,16.8728 C18.84672,17.16224 18.84672,17.63168 18.55136,17.89328 C17.81248,18.54608 16.96928,19.0408 16.02144,19.37504 C14.8464,19.7928 13.6072,20 12.30352,20 C11.05696,20 9.92128,19.80352 8.9,19.4072 C7.87856,19.0144 7.00352,18.46416 6.28208,17.7608 C5.55712,17.05728 4.99632,16.21424 4.59632,15.23216 C4.19648,14.24992 4,13.17856 4,12.01792 C4,10.87136 4.21792,9.81072 4.6536,8.83568 C5.08928,7.86064 5.68208,7.01424 6.43568,6.29632 C7.18928,5.57856 8.06784,5.01776 9.07856,4.60704 C10.08208,4.20352 11.16064,4 12.30352,4 C13.28912,4 14.2464,4.14288 15.17136,4.42864 C16.1,4.7144 16.92144,5.1464 17.63936,5.71792 C18.35712,6.29296 18.92864,7.0072 19.35712,7.86784 C19.78576,8.72864 20,9.73936 20,10.9 C20,11.76064 19.88224,12.52144 19.64288,13.17856 C19.40368,13.8392 19.08592,14.38928 18.68592,14.83568 C18.28592,15.28208 17.83232,15.61408 17.31792,15.83568 C16.80368,16.05712 16.26448,16.16768 15.70016,16.16768 C15.1216,16.16768 14.65728,16.032 14.30736,15.76064 C13.96096,15.48912 13.78592,15.14272 13.78592,14.72848 L13.67872,14.72848 C13.46096,15.07136 13.12864,15.39984 12.67872,15.70704 C12.2288,16.01424 11.67872,16.1712 11.02512,16.1712 C10.03936,16.1712 9.27872,15.84976 8.74288,15.20336 C8.2072,14.55696 7.93936,13.72112 7.93936,12.6856 C7.93936,12.08192 8.03936,11.48912 8.24288,10.89984 C8.4464,10.31056 8.73584,9.78912 9.11072,9.32848 C9.48576,8.87136 9.93568,8.49984 10.45712,8.22128 C10.97856,7.94272 11.55712,7.80352 12.19648,7.80352 C12.74656,7.80352 13.21088,7.91776 13.58928,8.1464 C13.96432,8.37504 14.21088,8.65712 14.32864,8.98576 L14.35008,8.98576 L14.38288,8.82512 C14.46144,8.4384 14.8448,8.12512 15.23936,8.12512 L15.74656,8.12512 C16.14128,8.12512 16.3952,8.43792 16.31408,8.824 L15.60736,12.19296 C15.57872,12.39296 15.53936,12.6144 15.48944,12.8608 C15.43952,13.10384 15.4144,13.33232 15.4144,13.55024 C15.4144,13.79312 15.46096,13.99664 15.55744,14.16448 C15.65024,14.3288 15.836,14.41104 16.11088,14.41104 C16.6752,14.41104 17.14304,14.11088 17.51456,13.50752 C17.8824,12.904 18.068,12.0968 18.068,11.07888 C18.068,10.21824 17.9216,9.45392 17.63232,8.7896 C17.34288,8.12176 16.93936,7.56464 16.42512,7.11104 C15.91088,6.66112 15.29648,6.31824 14.58928,6.0896 C13.87872,5.86096 13.10368,5.74672 12.26448,5.74672 C11.35008,5.74672 10.5144,5.90736 9.75376,6.22896 C8.99296,6.5504 8.34304,6.9968 7.8072,7.56112 C7.27152,8.12896 6.85376,8.79328 6.55728,9.56112 C6.25728,10.32544 6.10736,11.15408 6.10736,12.04336 C6.10736,12.98976 6.26448,13.84336 6.5752,14.604 C6.88592,15.36464 7.32528,16.0112 7.88944,16.5504 C8.4536,17.0896 9.1288,17.50048 9.91088,17.78624 C10.69312,18.07184 11.55728,18.21472 12.49664,18.21472 C13.67168,18.21472 14.6824,18.02912 15.5288,17.65408 C16.16528,17.37488 16.76304,17.01264 17.32304,16.56944 C17.632,16.3248 18.08192,16.3384 18.35056,16.62768 L18.57808,16.8728 L18.57808,16.8728 Z'%3E%3C/path%3E%3C/svg%3E") center/100% no-repeat;
}

svg[name="Nova_CallJoin"] {
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/svgs/phone-call.svg) center/100% no-repeat;
  mask: url(https://monstrousdev.github.io/themes/assets/svgs/phone-call.svg) center/100% no-repeat;
}

svg[name="Nova_CallVideo"] {
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/svgs/video-call.svg) center/100% no-repeat;
  mask: url(https://monstrousdev.github.io/themes/assets/svgs/video-call.svg) center/100% no-repeat;
}

.channel-2QD9_O[href="/channels/@me"] .avatar-3uk_u9 svg {
  color: inherit !important;
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/home-tabs/friends.svg) center/100% no-repeat;;
}

.channel-2QD9_O[href="/store"] .avatar-3uk_u9 svg {
  color: inherit !important;
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/home-tabs/nitro.svg) center/100% no-repeat;;
}

.channel-2QD9_O[href="/library"] .avatar-3uk_u9 svg {
  color: inherit !important;
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/home-tabs/library.svg) center/100% no-repeat;;
}

svg[name="Activity"] {
  color: inherit !important;
  background-color: currentColor;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/home-tabs/activity.svg) center/100% no-repeat;;
}

/* 2. Chat Header */
  /* 2.a. Coloring and Spacing */
.platform-win .toolbar-1t6TWx {
  margin-right: 96px;
}

.title-3qD0b-,
.header-2o-2hj,
.headerBar-UHpsPw {
  box-shadow: none;
  border-bottom: 2px solid var(--main-color) !important;
}

#app-mount .title-3qD0b-.transparent-2ZlE3R {
  background: transparent !important;
  border-bottom: 2px solid transparent !important;
}

.headerBar-UHpsPw.titleCall-_b9o8P {
  border-bottom: none !important;
}

.title-3qD0b-, 
.titleCall-_b9o8P {
  height: 48px;
}

.children-19S4PO:after {
  display: none;
}

#app-mount .container-1r6BKw {
  box-shadow: none;
  border-bottom: 2px solid var(--main-color);
}

.headerBar-UHpsPw {
  height: 48px;
  padding: 0 8px 0 12px;
}

.header-2o-2hj .name-3YKhmS {
  line-height: unset;
  position: relative;
  top: 4px;
  left: 2%;
}

.wrapper-1Rf91z:not(.foldercontent) .scrollerWrap-1IAIlv .scroller-2TZvBN>.listItem-2P_4kh:first-child,
.wrapper-1Rf91z:not(.foldercontent) .scrollerWrap-1IAIlv .scroller-2TZvBN>.tutorialContainer-1v44GL {
  margin-top: -58px;
  width: 72px;
  position: sticky;
  top: -58px;
  z-index: 2;
  height: 46px;
  margin-bottom: 15px
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN>.listItem-2P_4kh:first-child .pill-2uzAFe,
.wrapper-1Rf91z:not(.foldercontent) .scrollerWrap-1IAIlv .scroller-2TZvBN>.tutorialContainer-1v44GL .pill-2uzAFe {
  display: none;
}

.wrapper-1Rf91z:not(.foldercontent) .scrollerWrap-1IAIlv .scroller-2TZvBN>.listItem-2P_4kh:first-child .wrapper-25eVIn,
.wrapper-1Rf91z:not(.foldercontent) .scrollerWrap-1IAIlv .scroller-2TZvBN>.tutorialContainer-1v44GL {
  background-color: transparent !important;
  border-bottom: 2px solid var(--main-color);
  border-radius: 0px !important;
  width: 100%;
  transition: all 1s ease-in-out;
}

#app-mount .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN>.listItem-2P_4kh:first-child .listItemWrapper-3X98Pc {
  height: 100%;
  width: 100%;
}

#app-mount .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN>.listItem-2P_4kh:first-child .wrapper-25eVIn .svg-1X37T1 {
  height: 100% !important;
  width: 100% !important;
}

#app-mount foreignObject {
  mask: none !important;
  -webkit-mask: none !important;
  overflow: hidden;
}

#app-mount .button-OhfaWu {
  background-color: transparent;
}

.homeIcon-tEMBK1 {
  -webkit-mask-position: center;
  margin-left: -6px;
}

#app-mount .homeIcon-tEMBK1 path {
  display: none;
}

  /* 2.b. Search Bars */

.search-2oPWTC .searchBar-3dMhjb .icon-38sknP {
  margin-top: 23px;
  transform: translateY(-50%);
}

#app-mount .searchBar-6Kv8R2 .searchBarComponent-32dTOx {
  background-color: transparent;
}

.search-2oPWTC .DraftEditor-root {
  line-height: 42px;
}

#app-mount .container-cMG81i {
  background-color: transparent;
}

.search .searchBarIcon-1J6sKG {
  width: 35px;
}

.searchBarTag-2xRzm8 {
  background: transparent !important;
  border: 1px solid var(--main-color);
}

.browseSearch-e9jF-f .browseSearchInput-Jt8kg0.input-cIJ7To {
  background: transparent !important;
  color: white;
}

.search-2oPWTC .searchBar-3dMhjb {
  background-color: transparent !important;
  height: 46px;
  border-radius: 0px;
}

.titleCall-_b9o8p .search .search-bar,
.searchBar-2_Yu-C,
.searchBar-2_Yu-C .searchBarInner-1_Tg2R {
  background-color: transparent !important;
}

.search-bar .search-bar-inner {
  background: transparent;
  border-color: transparent;
}

.search-2oPWTC .DraftEditor-root {
  line-height: 39px;
}

.search-2oPWTC .DraftEditor-root .public-DraftEditorPlaceholder-root {
  color: #cecece !important;
  padding-left: 17px;
}

.searchAnswer-3Dz2-q,
.searchFilter-2ESiM3 {
  height: 30px;
  line-height: 30px;
  background-color: var(--secondary-color) !important;
}

.searchAnswer-3Dz2-q {
  padding: 0px 6px 1px 0px;
}

.searchFilter-2ESiM3 {
  border-radius: 3px;
  padding: 0px 8px 1px 6px;
}

.privateChannels-1nO12o .searchBar-6Kv8R2 {
  border-bottom: 2px solid var(--main-color);
  padding: 0px;
  height: 46px;
  box-shadow: 0px 0px transparent !important
}

.privateChannels-1nO12o .searchBar-6Kv8R2 input,
.search-2oPWTC .DraftEditor-root .DraftEditor-editorContainer {
  height: 100%;
}

.privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarInner-1_Tg2R {
  border: 0px solid transparent;
  border-radius: 0px;
  padding: 0px;
  height: 100%;
}

  /* 2.c. Change Icons */

.homeIcon-tEMBK1 {
  background-color: var(--home-color);
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/svgs/home.svg);
  -webkit-mask-size: var(--home-size);
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-position: center;
}

.homeIcon-tEMBK1 defs,
.homeIcon-tEMBK1 g {
  display: none;
}

.base-3dtUhz {
  border-radius: 0 !important;
}

.platform-osx .base-3dtUhz {
  margin-top: 32px;
}

.wrapper-1Rf91z {
  border-radius: 0;
}

#app-mount .wrapper-1BJsBx .childWrapper-anI2G9 {
  background-color: transparent;
}



/* 3. User Settings */
  /* 3.a. General Sidebar */

.standardSidebarView-3F1I7i .sidebarRegion-VFTUkN, 
.standardSidebarView-3F1I7i .sidebarRegion-VFTUkN .sidebarRegionScroller-3MXcoP {
  justify-content: flex-start;
}

.standardSidebarView-3F1I7i .sidebarRegion-VFTUkN {
  -ms-flex: 0;
  -ms-flex-pack: end;
  flex: 0;
  z-index: 1;
}

.info-1VyQPT::before {
  content: var(--theme-name) " " var(--theme-version);
  font-size: 12px;
  line-height: 16px;
  font-weight: 500;
  color: var(--main-color);
}

  /* 3.b. General Content Area */

#app-mount .contentRegionScroller-26nc1e {
  background: transparent;
}

.standardSidebarView-3F1I7i .contentColumnDefault-1VQkGM {
  padding: 20px 40px 80px;
}

.standardSidebarView-3F1I7i .contentRegionScroller-26nc1e {
  width: 100%;
}

.standardSidebarView-3F1I7i .contentColumn-2hrIYH, 
.standardSidebarView-3F1I7i .customColumn-Rb6toI {
  -ms-flex: 1 1 auto;
  -webkit-box-flex: 1;
  flex: 1 1 auto;
  max-width: 100%;
  min-height: 100%;
  min-width: 460px;
}

.standardSidebarView-3F1I7i .customScroller-26gWhv>div {
  max-width: 100%;
  margin-right: 98px;
}

.theme-dark .standardSidebarView-3F1I7i .contentRegion-3nDuYy {
  width: calc(100% - 226px);
  min-width: 553px;
  padding: 0;
}

.sidebarScrollable-1qPI87 {
  width: 24%;
}

.scroller-305q3I {
  background: transparent;
}

.sidebarScrollable-1qPI87+.content-1rPSz4 {
  max-width: 100%;
  margin-left: 25%;
}

.standardSidebarView-3F1I7i .noticeRegion-1YviSH {
  transform: translateX(25%) !important;
}

.premium-settings .premium-header,
.premium-settings .features-vNGwn7 {
  max-width: 98%;
}

#app-mount .paymentPane-3bwJ6A,
#app-mount .paymentRow-2e7VM6 {
  background-color: var(--tertiary-color);
}

#app-mount .paymentRow-2e7VM6 {
  border-color: var(--quaternary-color);
}

.expandedInfo-3kfShd {
  background: transparent !important;
}

.hoverablePayment-Yc6mK7:hover {
  background-color: var(--quaternary-color) !important;
}

.top-28JiJ- .itemSelected-1qLhcL {
  border-bottom-color: var(--main-color) !important;
  color: var(--main-color) !important;
}

.top-28JiJ- .itemDefault-3Jdr52:hover, 
.top-28JiJ- .itemHover-EnbcjT:hover {
  border-bottom-color: var(--hover-color) !important;
  color: var(--hover-color) !important;
}

.video-27HGyZ {
  width: auto;
}

.videoWrapper-3YdgHH {
  display: flex;
  justify-content: center;
}

.userSettingsVoice-iwdUCU .previewOverlay-2O7_KC {
  background-color: var(--secondary-color) !important;
  border-color: transparent !important;
}

  /* 3.c. Cards and Items */

.side-8zPYf6 .itemSelected-1qLhcL,
#bd-settings-sidebar .ui-tab-bar-item.selected,
.questionMark-CWEQZn {
  background-color: var(--main-color) !important;
}

.accountBtnInner-sj5jLs{
  background-color: var(--primary-color) !important;
  border-color: var(--tertiary-color) !important;
}

.accountBtn-2Nozo3 {
  transition: transform .2s ease-in-out;
}

.accountBtn-2Nozo3:hover {
  transform: scale(1.2);
}

.cardPrimary-1Hv-to,
.cardPrimaryEditable-3KtE4g,
.authedApp-mj2Hmd,
.wrapper-3UweLa,
.descriptionBox-1EKQKL {
  background: var(--quaternary-color) !important;
  border: none;
}

.theme-dark .card-FDVird:before,
.side-8zPYf6 .item-PXvHYJ:hover {
	background-color: var(--secondary-color) !important; 
	border-color: var(--secondary-color) !important 
}

#app-mount .item-3eFBNF,
#app-mount .game-1ipmAa {
  -webkit-box-shadow: inset 0 -1px 0 0 var(--tertiary-color);
  box-shadow: inset 0 -1px 0 0 var(--tertiary-color);
}

.item-3eFBNF.selected-2DeaDa {
  background-color: var(--quaternary-color);
}

#app-mount .card-FDVird:before {
  background-color: var(--quaternary-color);
  border-color: var(--ssecondary-color);
}

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch.checked,
.bda-slist .bda-footer button,
.bd-switch.bd-switch-checked {
  background: var(--main-color)
}

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch,
.bd-switch {
  background: var(--quaternary-color);
}

#app-mount .bd-addon-list .bd-addon-card {
  background: var(--tertiary-color)
}

#app-mount .bda-slist li,
#app-mount .emptyApplications-3GTmw-,
#app-mount .emptyUsers--hiToV  {
  background-color: var(--secondary-color);
  border-color: var(--tertiary-color);
}

.button-mM-y8i {
  background-color: var(--secondary-color) !important
}

/*.user-settings-games .game-name-input:focus,
.user-settings-games .game-name-input:hover {
	background-color: var(--tertiary-color) !important 
}*/

.notDetected-33MY4s {
  background-color: var(--tertiary-color) !important;
}

.addGamePopout-2RY8Ju {
  background-color: var(--tertiary-color) !important;
}

.applications-3KXbc1 {
  width: auto;
  justify-content: center;
}

.theme-dark .finePrint-xGGTK5,
.theme-dark .description-1W0DiL {
  color: #aaa;
}

.theme-light .finePrint-xGGTK5,
.theme-light .description-1W0DiL {
  color: #555;
}

.side-8zPYf6 .item-PXvHYJ[style*="color: rgb(114, 137, 218)"] {
  color: var(--main-color) !important;
}

.side-8zPYf6 .item-PXvHYJ[style*="background-color: rgb(114, 137, 218); color: rgb(255, 255, 255);"],
.side-8zPYf6 .item-PXvHYJ[style*="color: rgb(255, 255, 255); background-color: rgb(114, 137, 218);"] {
  color: white !important;
}

  /* 3.d. Buttons, Switches, and Bars */
.lookFilled-1Gx00P.colorBrand-3pXr91,
.themeDefault-24hCdX.valueChecked-m-4IJZ,
.barFill-23-gu-,
[style*="border-color: rgb(114, 137, 218); background-color: rgb(114, 137, 218);"],
.bd-pfbtn,
#pubslayer button,
#bd-pub-button {
  background-color: var(--main-color) !important;
}

.bar-2Qqk5Z,
.lookFilled-1Gx00P.colorTransparent-1ewNp9 {
  background-color: var(--quaternary-color) !important;
}

.lookFilled-1Gx00P.colorBrand-3pXr91:hover,
#pubslayer button:hover {
  background-color: var(--hover-color) !important;
}

.checkbox-3kaeSU .checkboxInner-3yjcPe .checkboxElement-1qV33p:checked+span,
.checked-3_4uQ9 {
  background-color: var(--main-color) !important;
  border-color: var(--hover-color) !important;
}

svg[name*="Checkmark"] {
  filter: brightness(10);
}

.privateChannels-1nO12o .channel-2QD9_O .linkButtonIcon-Mlm5d6 path {
  display: none;
}

.privateChannels-1nO12o .channel-2QD9_O .linkButtonIcon-Mlm5d6 {
  background-size: 24px;
  background-position: center;
  background-repeat: no-repeat;
}

.theme-light .privateChannels-1nO12o .channel-2QD9_O .linkButtonIcon-Mlm5d6 {
  filter: invert(100%);
}

.premiumIndicator-1XvbfM,
.standardSidebarView-3F1I7i #editor-detached button {
  background-color: var(--main-color);
}

.standardSidebarView-3F1I7i .contentRegionScroller-26nc1e .tools-3-3s-N {
  z-index: 1000;
}

.hiddenLibraryApplication-2esFER:hover .restoreButton-22-SIW {
  opacity: 0.5;
}

.hiddenLibraryApplication-2esFER:hover .restoreButton-22-SIW:hover {
opacity: 1;
transform: scale(1.2);
}

.hiddenLibraryApplication-2esFER:hover .restoreButton-22-SIW:active {
  opacity: 1;
  transform: scale(0.8);
}

.restoreButton-22-SIW {
background-color: var(--primary-color) !important;
border: 1px solid var(--dnd);
transition: transform .2s ease-in-out;
}

.restoreIcon-2YLu1X {
color: var(--dnd) !important;
}

.theme-dark .progress-1IcQ3A,
.theme-light .progress-1IcQ3A {
  background-color: var(--quaternary-color);
}

#app-mount .side-8zPYf6 .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ, 
#app-mount .topPill-30KHOu .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ {
  background-color: var(--main-color)
}

#app-mount .side-8zPYf6 .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ:hover, 
#app-mount .topPill-30KHOu .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ:hover {
  background-color: var(--hover-color);
}

#app-mount .friendSelected-3J_Uh8 {
  background-color: var(--secondary-color);
}

  /* 3.e. Overlay Notifications */
.wrapper-3jrx9n {
  border-color: var(--main-color);
}

.selected-mKYnfr.option-n0icdO {
  background-color: var(--main-color);
  border-color: var(--main-color);
}

.option-n0icdO:hover {
  background-color: var(--hover-color)
}

  /* 3.f. Nitro and Hypesquad Section */
.grandfatheredMessage-2QgLnw {
  justify-content: center;
}

.tier1Banner-1B_WXY,
.details-39BP6c {
  width: 660px;
}

.sectionHeader-B058Rx,
.subsectionHeader-2euE2f,
.sectionHeader-127c3L {
  text-align: center;
}

.mechaWumpus-10tlHF {
  right: -50px;
}

.tier1Banner-1B_WXY,
.container-2Zlzt0,
.detailsBlock-FoDTGA,
.premiumSubscriptionAccountCredit-25i0tQ {
  background-color: var(--quaternary-color) !important;
}

.popout-3sVMXz.popoutBottom-1YbShG.noShadow-321ZPm[style*="top: 286px"] {
  margin-top: 15px !important;
}

.codeRedemptionRedirect-1wVR4b {
  background-color: var(--quaternary-color) !important;
  border-color: var(--quaternary-color) !important;
}

.premiumContainer-2Iux5m,
.banner-3Kac2g,
.tier1Banner-1BTgv0 {
  max-width: unset;
}

#app-mount {
  max-width: unset;
  background-color: var(--tertiary-color);
}

.details-1YZMDP {
  min-width: 100%;
  margin-left: unset;
  transform: none;
}

.detailsBlock-FoDTGA {
  min-width: 45%;
}

.tier1Banner-1B_WXY {
  width: unset;
}

/* 4. Guilds Wrapper */
 /* 4.a. Main Guilds Wrapper */
.scroller-2TZvBN {
  contain: initial;
}

.guildsWrapper-5TJh6A,
.wrapper-1Rf91z {
  z-index: 6;
}

#app-mount .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN {
  padding: 58px 0 20px 0 !important;
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .friendsOnline-2JkivW {
  margin-top: 10px;
}

.theme-light .guildsWrapper-5TJh6A .guilds-1q_RqH .friendsOnline-_wi_fM,
.theme-light .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .friendsOnline-2JkivW {
  color: #000;
}

.guildSeparator-1X4GQ1:after,
.guildSeparator-3s64Iy::after {
  background-color: transparent !important;
}


  /* 4.b. Guilds */
.container-2td-dC .wrapper-2lTRaf,
.container-1aNBdK .wrapper-2lTRaf {
  background: transparent !important;
  overflow: visible;
}

.container-1aNBdK .wrapper-2lTRaf {
  border-radius: 0px !important
}

.item-2hkk8m {
  background: var(--main-color);
  box-shadow: 0 0 12px var(--main-color);
  height: 10px;
  width: 10px;
}

#app-mount .acronym-2mOFsV {
  background-color: transparent;
  border: 2px solid var(--main-color);
  box-sizing: border-box;
  transition: all 200ms ease-in-out;
}

#app-mount .acronym-2mOFsV:hover {
  border: none;
  background-color: var(--main-color);
}

.item-2hkk8m[style*="opacity: 0.7"] {
  opacity: 1 !important;
}

.item-2hkk8m[style*="height: 40px"] {
  border-radius: 0;
  box-shadow: none;
}

.pill-31IEus {
  overflow: visible;
}

.guildSeparator-3s64Iy {
  background: transparent;
}

.dragfix-1wSxtO:active {
  border-radius: var(--roundness);
}

#app-mount .dragPlaceholder-D9-haY,
#app-mount .placeholderMask-3K9THS .dragInner-_SHftW {
  background-color: transparent;
  border: 2px dashed var(--primary-color);
  height: 100%;
  width: 100%;
  box-sizing: border-box;
}

#app-mount .placeholderMask-3K9THS .dragInner-_SHftW {
border-color: 2px dashed rgba(255, 255, 255, .1);
}

.createJoinContainer-2Av064 {
  margin-bottom: 10px;
}

.guildsError-b7zR5H {
  background: transparent !important;
}

.guildsError-b7zR5H:hover {
  background: var(--dnd) !important;
}

#app-mount .folder-21wGz3,
  #app-mount .expandedFolderBackground-2sPsd- {
    background-color: transparent;
  }

#app-mount .expandedFolderBackground-2sPsd-::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background-color: var(--main-color);
  opacity: .2;
  transition: all 200ms ease-in-out;
}

#app-mount .expandedFolderBackground-2sPsd-.collapsed-1GMuSb::before {
  background-color: transparent;
}

#app-mount .folderIconWrapper-226oVY {
  border-radius: calc(var(--roundness)/5);
}

#app-mount .folder-21wGz3 [style*="background-color: rgba(114, 137, 218, 0.2)"]::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background-color: var(--main-color);
  opacity: .2;
}

#app-mount .folder-21wGz3 [style*="background-color: rgba(114, 137, 218, 0.2)"] {
  background-color: transparent !important;
}

#app-mount svg[name="Folder"][style*="color: rgb(114, 137, 218)"] {
  color: var(--main-color) !important;
}

  /* 4.c. Guilds Add */
#app-mount .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .circleIconButton-jET_ig {
  background-color: var(--main-color);
  color: white;
}

#app-mount .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .circleIconButton-jET_ig svg {
  height: 24px;
  width: 24px;
  position: unset;
  left: unset;
  transform: none;
}

/* .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .circleIconButton-jET_ig,
.wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .circleIconButton-jET_ig span {
  position: relative;
  border: 0px;
  background: transparent;
  transition: all 200ms ease;
  font-size: 32px;
  font-weight: 600;
  left: 0;
  color: transparent;
  height: 50px;
  padding: 0;
  z-index: 1000;
} */


.wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .circleIconButton-jET_ig {
  box-shadow: 0 10px 15px rgba(0, 0, 0, .4), 0 -1px 0px rgba(0, 0, 0, 0.2) inset, 0 2px 1px rgba(255, 255, 255, 0.2) inset;
  background-color: var(--main-color);
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN>div.container-1ETFDs:first-child .badge-14ZoDd{
  border-radius: 40px;
  background-color: var(--main-color);
  margin-bottom: 0px;
  margin-right: 10px;
  border: 2px solid var(--hover-color);
}

.container-2td-dC.audio-2KA0-x::after,
.container-2td-dC.video-2jNDI4::after {
  background-color: var(--main-color) !important;
}

  /* 4.d. Badges */
#app-mount .iconBadge-2wi9r4 {
  background-color: var(--main-color);
}

.badge-_BgAUQ {
  background-color: var(--dnd);
}

  /* 4.e. Unread Indicator */
.unreadMentionsIndicatorBottom-BXS58x {
  z-index: 1000;
}

.unreadMentionsIndicatorTop-gA6RCh {
  top: 46px;
}

.mention-1f5kbO {
  background-color: var(--main-color);
}

.mention-1f5kbO:hover {
  background-color: var(--hover-color);
}
  
/* 5. Channels */
  /* 5.a Main Channels Area */

.platform-win #app-mount .sidebar-2K8pFh {
  border-radius: 0px;
}

  /* 5.b. Light Theme Recolor*/

.theme-light .icon-1KK5se,
.theme-light path[d*="M11.5,9 C13.1575,9 14.5,7.6575 14.5,6 C14.5,4.3425 13.1575,3 11.5,3 C9.8425,3 8.5,4.3425 8.5,6 C8.5,7.6575 9.8425,9 11.5,9 Z M4,7 L4,5 L3,5 L3,7 L1,7 L1,8 L3,8 L3,10 L4,10 L4,8 L6,8 L6,7 L4,7 Z M11.5,10 C9.4975,10 6,11.005 6,13 L6,15 L17,15 L17,13 C17,11.005 13.5025,10 11.5,10 Z"] {
  fill: #000 !important;
}

.theme-light .privateChannels-1nO12o .channel a[href*="/channels/@me"],
.theme-light .actionIcon-2Hi9ZG,
.theme-light .privateChannels-1nO12o .channel .channel-name,
.theme-light .nameHoveredVoice-YJ1Vfd,
.theme-light .wrapperHoveredText-2geN_M .nameUnreadText-DfkrI4,
.theme-light .wrapperHoveredText-2geN_M .nameHoveredText-1uO31y {
  color: #000 !important;
}

.theme-light .privateChannels-1nO12o .channel .close {
  filter: invert();
}

.theme-light .privateChannels-1nO12o .channel:hover .channel-activity {
    color: #5a5a5a;
}

.theme-light path[d*="M4.5 4.5l9 9"],
.theme-light path[d*="M13.5 4.5l-9 9"] {
  stroke: #000;
}

.theme-light .nameSelectedText-sp_EUw,
.theme-light .nameSelectedVoice-1qSph5 {
  color: #5d5d5d;
}

  /* 5.c. Channel Font Colors */
.nameMutedText-3Vj4bM,
.nameMutedVoice-3oxyQZ {
  color: #909090;
  opacity: 0.4;
}

.nameDefaultText-24KCy5,
.nameDefaultVoice-3WUH7s,
.nameLockedText-3pqQcL,
.nameLockedVoice-26MhB1,
.iconCollapsed-3hFp_8,
.iconDefault-3Gr8d2,
.nameCollapsed-34uFWo,
.nameDefault-2DI02H {
  color: #909090;
}

.nameUnreadText-DfkrI4,
.nameUnreadVoice-EVo-wI {
  color: #ffffff;
}

.theme-light .nameUnreadText-DfkrI4,
.nameUnreadVoice-EVo-wI {
  color: #303030;
}

.wrapperHoveredText-2geN_M .nameUnreadText-DfkrI4,
.wrapperHoveredText-2geN_M .nameHoveredText-1uO31y {
  color: #c6c6c6 !important;
}

.iconMuted-1HVBGH,
.nameMuted-1MCOt4 {
  color: #909090;
  opacity: 0.6;
}

  /* 5.d. Channels */
#app-mount .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU, 
#app-mount .wrapper-1ucjTd.modeSelected-1zApJ_:hover .content-3at_AU,
#app-mount .wrapper-1ucjTd:hover .content-3at_AU {
  background-color: transparent;
}

.wrapper-1ucjTd {
  border-left: 2px solid transparent;
}

.wrapper-1ucjTd.modeSelected-1zApJ_ {
  background-color: var(--quaternary-color);
  border-left-color: var(--main-color);
}

#app-mount .wrapper-pZmgj4 {
  background-color: var(--tertiary-color);
}

#app-mount .total-3tKGEB {
  background-color: var(--quaternary-color);
}

#app-mount .total-3tKGEB:after {
  border-right-color: var(--quaternary-color);
}

.wrapper-CU3qI5 {
  height: 100%;
}

.icon-WnO6o2 {
  top: unset;
}

.channels-Ie2l6A, 
.container-PNkimc {
  z-index: 2;
}

  /* 5.e. Unread Indicator */
.unread-1Dp-OI {
  background-color: var(--hover-color);
  transition: .1s all linear;
}

.wrapperHoveredText-2geN_M .unread-1Dp-OI {
  height: 32px;
  left: 0px;
  border-radius: 0px;
  width: 2px;
  margin-top: 0px;
  top: 1px;
}

.wrapperHoveredText-2geN_M .unread-1Dp-OI~.contentHoveredText-2D9B-x {
  border-left: 2px solid transparent !important;
}

  /* 5.f. Categories */
.containerDefault-3GGEv_, 
.containerDragAfter-3TEhpe, 
.containerDragBefore-3Dzc5x, 
.containerUserOver-1Tcb7l {
  padding-top: 0;
  margin-top: 12px;
  margin-bottom: 6px;
  background-color: var(--quaternary-color);
  margin-left: 0px;
  height: 31.11px;
  padding: 0 8px;
  border-radius: 0px;
}
  
.channels-Ie2l6A .scroller-2FKFPG>[class*=container-]>[class*=container]+[class*=container-] {
  margin-top: 6px;
}
  
.wrapperCollapsed-3Fbxl6, .wrapperDefault-10Jfvz, .wrapperHovered-28fu1D, .wrapperHoveredCollapsed-1PADEo, .wrapperMuted-3KeA2M, .wrapperUnread-1JPWj3{
  margin-left: 0px;
  height: 31.11px;
  border-radius: 3px;
  background-color: transparent;
  padding: 0px;
}
  
.iconCollapsed-3hFp_8, 
.iconDefault-3Gr8d2, .iconHovered-2L3-fB, 
.iconHoveredCollapsed-3caIIZ, 
.iconMuted-1HVBGH, 
.iconUnread-2eGkvX {
  height: 31.11px;
  width: 16px;
  position: relative;
  margin-left: -3px;
  margin-top: -4px;
  margin-right: 8px;
}

.nameCollapsed-34uFWo, 
.nameDefault-2DI02H, 
.nameHovered-1gxhWH, 
.nameHoveredCollapsed-2orEWB, 
.nameMuted-1MCOt4, 
.nameUnread-njOjIS {
  height: 31.11px;
  line-height: 32px;
}
  
.channels-Ie2l6A .scroller-2FKFPG>[class*=container-] .horizontal-1ae9ci>.flex-1xMQg5:last-child {
  margin-top: 6px;
}
  
.channelNotices-41mJbj .channelNotice-1-XFjC,
#app-mount .listDefault-2y5Z9D .clickable-23RaYz:hover .content-3xS9Lh {
  background-color: var(--tertiary-color) !important;
}

.channelNotices-41mJbj .channelNotice-1-XFjC .message-3SOT5P .btn-11C5_u {
  background-color: var(--main-color);
  border-color: var(--main-color);
  transition: all .2s ease-in-out;
}

.channelNotices-41mJbj .channelNotice-1-XFjC .message-3SOT5P .btn-11C5_u:hover {
  background-color: var(--hover-color);
  border-color: var(--hover-color);
}

.container-1UB9sr {
  border-bottom: 0px solid transparent;
}

  /* 5.g. DM List */
/* .privateChannels-1nO12o .channel-2QD9_O .numberBadge-2s8kKX {
  position: absolute;
  top: 5px;
  right: 4px;
} */

.privateChannels-1nO12o a.channel-2QD9_O {
  margin: unset;
  border-radius: 0px;
  border-left: 2px solid transparent;
  transition: border-color .2s ease-in-out;
}

.privateChannels-1nO12o a.channel-2QD9_O:hover {
  background: var(--quaternary-color);
  border-color: var(--hover-color);
}

.privateChannels-1nO12o .channel-2fhmY8:hover .selectedLink-3dsNZ6 {
  background-color: var(--tertiary-color)
}

.privateChannels-1nO12o a.selected-aXhQR6.container-2Pjhx- {
  background-color: var(--quaternary-color);
  border-left: 2px solid var(--main-color);
}

.privateChannels-1nO12o a.selected-aXhQR6.container-2Pjhx-:hover {
  border-left: 2px solid var(--main-color) !important;
}

#app-mount .selected-aXhQR6 .layout-2DM8Md,
#app-mount .clickable-1JJAn8:hover .layout-2DM8Md {
  background-color: transparent;
}

  /* 5.h. Unread Messages Popout */
.container-35XQWE {
  z-index: 2;
}

.unread-1xRYoj,
.unreadBar-3YD_k9 {
  background-color: var(--primary-color);
  border: 1px solid var(--main-color);
  transition: background-color .2s ease-in-out;
}

.unread-1xRYoj:hover,
.unreadBar-3YD_k9 {
  background-color: var(--main-color);
}

.unread-1xRYoj.mention-1f5kbO {
  background-color: var(--main-color);
}

.unreadBar-3YD_k9.mention-1f5kbO:hover {
  background-color: var(--hover-color);
}

  /* 5.i. Verified Servers Banner */
.animatedContainer-1pJv5C {
  background-color: transparent;
  box-shadow: none;
  -webkit-box-shadow: none;
}

.bannerImage-1jOskm {
  top: 48px;
  height: 128px;
}

.banner-1TiK82 .header-2o-2hj {
  max-width: 240px;
  bottom: unset;
  top: 0;
  position: fixed;
}

.scroller-2wx7Hm .flexChild-faoVW3 ~ .container-0.container-2xaHGu {
  margin-top: 15px;
}

#app-mount .bannerImage-1jOskm {
  -webkit-mask: linear-gradient(black, transparent);
  mask: linear-gradient(black, transparent)
}

.guildIconContainer-E1JUVt {
  margin-top: 21px;
  transform: translateY(-50%);
}

/* 6. Account Area */
  /* 6.a. Main Container */

#app-mount .container-3baos1 {
  background: transparent;
  border-bottom: transparent;
  padding-right: 0;
}

.container-2Thooq {
  height: 53px !important;
  z-index: 1;
}

.container-3baos1 .button-14-BFJ {
  height: 53px;
  width: 35px;
  border-radius: 0px;
}

.button-14-BFJ:hover {
  background-color: var(--tertiary-color) !important;
}

.nameTag-3uD-yy .usernameContainer-1fp4nu {
  font-family: Montserrat;
  color: var(--main-color);
  font-size: 13px;
  height: 18px;
  line-height: 18px;
}

.nameTag-3uD-yy .usernameContainer-1fp4nu .title-eS5yk3 {
  color: inherit;
  font-weight: normal;
}

.container-2Thooq  {
  padding-right:0;
}

  /* 6.d. Listening Along */
.listeningAlong-2UPsxf {
  background-color: var(--quaternary-color) !important;
  margin: 0 !important;
}



/* 7. Members List */
  /* 7.a. Main Member List */
.membersWrap-2h-GB4 {
  z-index: 1;
}

.member-3W1lQa {
  border-right: 2px solid transparent;
  border-radius: 0;
}

.member-3W1lQa:hover,
.member-3W1lQa.popout-open {
  border-color: var(--main-color);
}

.member-3W1lQa:hover,
.member-3W1lQa.popout-open {
  background-color: var(--quaternary-color) !important;
  color: #fff;
}

.content-OzHfo4 {
  flex-grow: 0 !important;
  height: 40px !important;
}

.member-3W1lQa .activityText-sLG0UL {
  font-size: 10px;
}

.member-3W1lQa .content-3QAtGj .nameTag-3p0yK- {
  font-size: 15px;
}

.username-1cB_5E {
  clear: left;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

  /* 7.b. Hoisted Roles */
.membersGroup-v9BXpm {
  color: var(--main-color) !important;
  border-bottom: 3px solid;
  border-image: linear-gradient(90deg, transparent, var(--main-color), transparent);
  border-image-slice: 1;
  padding: 19px 16px 6px 16px;
  margin: 4px 0px 10px 15px;
  font-weight: 600;
  text-align: center;
  border-radius: 3px;
  width: 175px;
  line-height: 15px;
}





/* 8. Chat */
  /* 8.a Main Chat Area */
.noChannel-Z1DQK7::before {
  content: '';
  position: absolute;
  height: 48px;
  width: 1px;
  border-left: 2px solid var(--main-color)
}

.operations-36ENbA>a,
a,
.itemContainer-WiE19S .anchor-3Z-8Bb,
.welcomeMessage-3_Mcht .h1-1IDj26 {
  color: var(--main-color);
}

.item-1Yvehc.brand-3igrJY {
  color: var(--main-color) !important;
}

.item-1Yvehc.brand-3igrJY:hover {
  color: var(--hover-color) !important;
}

.messages-3amgkR.scroller-2FKFPG {
  padding-bottom: 10px;
  background: transparent;
}

.containerCompactBounded-cYR5cW:last-child {
  padding: 10px 0 20px 0;
}

.icon-2shpbb {
  -webkit-mask-size: 95%;
  -webkit-mask-position: center;
  -webkit-mask-repeat: no-repeat;
  background-color: var(--main-color);
  background-image: none !important;
}

.exclamation-1mi7Vi {
  -webkit-mask-image: url(https://discordapp.com/assets/7616be62f9b90270b5a2e1fe9d2ece4f.svg);
}

.share-1EA-d2 {
  -webkit-mask-image: url(https://discordapp.com/assets/07778297eb1e1e3d9bd3cd302920d5fb.svg);
}

.mobile-3_KEmF {
  -webkit-mask-image: url(https://discordapp.com/assets/83d501f2b7dd2987302ce29b321f4494.svg);
}

.twitter-1TN3uJ {
  -webkit-mask-image: url(https://discordapp.com/assets/326d79eb53886c88437e99a3754b1cd0.svg);
  -webkit-mask-size: 77%;
}

#app-mount .attachment-33OFj0 {
  background-color: var(--quaternary-color);
  border-color: var(--quaternary-color);
}

  /* 8.b Messages */
.containerCozy-jafyvG:not(:last-child) {
  padding: 15px 0px !important;
}

.messagesWrapper-3lZDfY .containerCozy-jafyvG:last-child {
  padding-top: 15px 0px 28px!important;
}

.wrapper-FtzxDk.vertical-V37hAW.flex-101GKY.directionColumn-35P_nr.wrapper-2h3Puq.vertical-V37hAW.flex-101GKY.directionColumn-35P_nr.alignEnd-1D6PQi.spacer-1fA9zc {
  margin-top: 55px !important;
}

.wrapper-2aW0bm {
  background: var(--quaternary-color) !important;
}

.scroller-3sQKXg:after {
  height: 15px;
}

.message-2qnXI6.selected-2P5D_Z {
  background-color: var(--secondary-color);
}

.mouse-mode .message-2qnXI6:hover {
  background-color: transparent;
}

  /* 8.c Blocked Messages */
.messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh- {
  background: var(--tertiary-color) !important;
  color: var(--main-color)!important;
}

.messageGroupBlocked-3wrQQX.revealed-1_RKsf,
.messageGroupBlocked-3wrQQX {
  background: var(--tertiary-color) !important;
  border-color: var(--secondary-color) !important;
}

  /* 8.d. Spoiler Messages */

.spoilerText-3p6IlD.hidden-HHr2R9,
.spoilerText-3p6IlD {
  position: relative;
  background: transparent !important;
}

.spoilerText-3p6IlD.hidden-HHr2R9 .inlineContent-3ZjPuv {
  opacity: 1;
  filter: blur(var(--spoiler-blur));
}

.spoilerWarning-2aAZq1 {
  background-color: var(--quaternary-color) !important;
  color: white !important;
}

.spoilerContainer-331r0R:hover .spoilerWarning-2aAZq1 {
  background-color: var(--main-color) !important;
}

  /* 8.e. Chat Dividers */
.chat-3bRxxu .divider-JfaTT5 {
  height: 28px;
  background-color: transparent;
  margin: 10px 0px;
  border: none;
}

.friends-table .messages-3amgkR .divider:not(.isUnread-3Ef-o9) span,
.messagesWrapper-3lZDfY .messages-3amgkR .divider-JfaTT5:not(.isUnread-3Ef-o9) span {
  opacity: 1;
}

.chat-3bRxxu .divider-JfaTT5>span {
  color: #a0a0a0 !important;
  border-radius: 3px;
  position: relative;
  text-align: left;
  font-size: 12px;
  text-transform: uppercase;
  margin: 0px 0px;
  opacity: 1;
  padding: 5px 15px;
  width: 100%;
  background: transparent !important;
  box-sizing: border-box !important;
}

.chat-3bRxxu .divider-JfaTT5.isUnread-3Ef-o9:not(.hasContent-1cNJDh)>span,
.chat-3bRxxu .divider-JfaTT5.isUnread-3Ef-o9.hasContent-1cNJDh {
  color: var(--main-color) !important;
  background-color: var(--quaternary-color) !important;
  border-radius: 3px;
  justify-content: center;
  left: 0px;
  padding: 10px 0;
}

.chat-3bRxxu .divider-JfaTT5.isUnread-3Ef-o9.hasContent-1cNJDh {
  display: flex;
  flex-flow: row-reverse wrap;
  justify-content: center;
  align-items: center;
}

.chat-3bRxxu .divider-JfaTT5.isUnread-3Ef-o9.hasContent-1cNJDh span {
  background: transparent;
  color: var(--main-color) !important;
}

.chat-3bRxxu .divider-JfaTT5.isUnread-3Ef-o9.hasContent-1cNJDh>.unreadPill-2HyYtt {
  margin-top: 7px;
  margin-right: 5px;
  height: 100%;
  width: fit-content !important;
  padding-right: 0px;
}

.chat-3bRxxu .divider-JfaTT5.isUnread-3Ef-o9.hasContent-1cNJDh>.unreadPill-2HyYtt::after {
  content: "|";
  margin-left: 5px;
}

.chat-3bRxxu .divider-JfaTT5.isUnread-3Ef-o9.hasContent-1cNJDh>.content-1o0f9g {
  text-align: center;
  padding: 0;
  margin-top: -7px;
  width: fit-content !important;
}

.unreadPillCap-3_K2q2,
.unreadPillCapStroke-7rkHbg {
  display: none;
}

.containerCozy-jafyvG .isMentionedCozy-3isp7y:after,
.containerCozy-jafyvG .divider-32i8lo,
.dividerContent-2L12VI:after, 
.dividerContent-2L12VI:before,
.jumpToPresentBar-9P20AM button:first-of-type {
  display: none;
}

  /* 8.f. Mentions */
.containerCozy-jafyvG .isMentioned-N-h9aa {
  background: var(--quaternary-color);
  box-shadow: 0px 0px 5px var(--quaternary-color);
  border-left: 3px solid var(--main-color);
  padding: 0px 0px 0px 3px;
  border-radius: 0px;
}

.channelHeader-3Gd2xq {
  padding: 12px 16px;
  background: var(--quaternary-color);
  border-radius: 5px 5px 0 0;
  margin-top: 10px;
}

.messageContainer-gbhlwo {
  border-radius: 0 0 5px 5px;
  background: var(--secondary-color);
  box-shadow: 0 4px 10px var(--shadow)
}

.mention {
  padding: 1px 3px 1.4px 2px !important;
}

.isMentioned-N-h9aa .mention {
  transition: all .2s linear;
  background: var(--tertiary-color) !important;
}

.isMentioned-N-h9aa .mention:hover {
  color: #fff !important;
  text-decoration: none;
  background: var(--main-color);
}

.containerCozy-jafyvG .isMentioned-N-h9aa .mention:hover, 
.mention:hover {
  background-color: transparent !important;
  color: #fff !important;
}

  /* 8.g. Code Blocks */
pre, code {
  padding: 0px !important;
  margin-left: 3px !important;
  margin: 0px !important;
  line-height: 20px !important;
  border: none !important;
  padding-bottom: 6px !important;
  border-radius: 3px !important;
}

code.inline,
.after_inlineCode-1KfVgj, 
.before_inlineCode-1G9rTK, 
.inlineCode-2ngu6Y {
  background: var(--tertiary-color) !important;
}

code:not(.inline) {
  background: repeating-linear-gradient(0deg, var(--secondary-color) 5px, var(--secondary-color) 25px, var(--tertiary-color) 0, var(--tertiary-color) 45px) !important;
}

pre {
  background: transparent !important;
}

pre>*, code>* {
  padding-left: 3px !important;
}

pre {
  padding-bottom: 0x !important;
}

  /* 8.h. New messages Bar and Loading Symbols */
.spinner-pulsing-ellipsis .spinner-item,
.spinner-wandering-cubes .spinner-item,
.chat-3bRxxu .newMessagesBar-mujexs {
  background-color: var(--main-color) !important;
}

.chat-3bRxxu .newMessagesBar-mujexs:hover {
  background-color: var(--hover-color) !important;
}

.chat-3bRxxu .hasMore-3e72_v {
  background: var(--quaternary-color) !important;
  border: 1px solid var(--quaternary-color) !important;
  color: var(--main-color) !important;
}

.chat-3bRxxu .jumpToPresentBar-9P20AM {
  background-color: var(--main-color) !important;
  bottom: 15px;
  border-radius: 20px;
  right: 50px !important;
  width: auto !important;
  box-shadow: 0 2px 20px rgba(0, 0, 0, .1);
  left: auto !important;
  animation: slide-up .7s cubic-bezier(.4, 0, 0, 1), opacity .7s ease;
  padding-bottom: 0px;
}

.chat-3bRxxu .jumpToPresentBar-9P20AM:before {
  content: "";
  width: 20px;
  background: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMiIgaGVpZ2h0PSIxMiI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDEyVjBoMTJ2MTIiLz4KICAgIDxwYXRoIGZpbGw9IiNGRkYiIGQ9Ik01LjI0ODI5MTAyIDJ2NS4yMTg2ODg5NkwzIDUgMiA2bDQgNCA0LTQtMS0xLTIuMjg0MTE4NjUgMi4yMTg2ODg5NlYyIi8+CiAgPC9nPgo8L3N2Zz4=);
  background-repeat: no-repeat;
  background-position: 50%;
  margin-right: -15px;
  padding-left: 10px;
}

.chat-3bRxxu .jumpToPresentBar-9P20AM button:last-child {
  text-align: center;
  font-family: Montserrat;
  font-size: 11px;
}

.chat-3bRxxu .jumpToPresentBar-9P20AM .spinner-2enMB9 {
  margin-left: 20px !important;
  margin-top: 10px;
  padding-right: 15px;
  margin-bottom: 10px;
  -ms-transform: scale(1.3);
  transform: scale(1.3)
}

  /* 8.i. DM Chat */

.private-channel-call.minimum .private-channel-call-info,
.private-channel-call.normal .private-channel-call-info,
.private-channel-call .private-channel-call-info {
  padding: 0px;
}

  /* 8.j. Bot Message */
.isLocalBot-38G0P0 {
  background-image: var(--primary-color) !important;
  margin-left: 0px;
  box-shadow: none !important;
  -webkit-box-shadow: none !important;
  padding-left: 0 !important;
}

  /* 8.k. Embeds */
.embedPill-1Zntps {
  border-radius: 0px;
  width: 3px;
}

.embedInner-1-fpTo,
#app-mount .guildIconImage-3qTk45,
.embedFull-2tM8-- {
  background-color: var(--quaternary-color) !important;
  border-color: var(--quaternary-color);
  border-radius: 0px;
}

[style*="background-color: rgb(114, 137, 218);"] {
  background-color: var(--main-color) !important;
}

[style*="color: rgb(255, 255, 255); background-color: rgb(114, 137, 218);"],
[style*="color: rgb(114, 137, 218); background-color: rgb(114, 137, 218);"] {
  color: white;
}

.wrapper-35wsBm {
  background-color: var(--quaternary-color) !important;
  border-color: transparent !important;
}

#app-mount .tile-2OwFgW,
#app-mount .tile-QA_yMc {
  background-color: var(--secondary-color);
}

#app-mount .tile-2OwFgW:hover,
#app-mount .tile-QA_yMc:hover {
  background-color: var(--primary-color);
}
  /* 8.l. Text Area */
.chat-3bRxxu .attachButtonDivider-3Glu60 {
  display: none;
}

.channelTextArea-2VhZ6z {
  background: transparent;
}

.toolbar-2bjZV7 {
  background-color: var(--quaternary-color);
}

.toolbar-2bjZV7:before {
  border-top-color: var(--quaternary-color);
}

.active-2HPddW, .hover-28QbSq:hover {
  background-color: var(--tertiary-color);
}

.active-2HPddW .icon-KgGMGo, .hover-28QbSq:hover .icon-KgGMGo {
  color: var(--main-color);
}

.buttons-3JBrkn {
  padding: 5px;
}

.attachWrapper-1_D-pj,
.form-2fGMdU,
.attachWrapper-2TRKBi {
  border-top: none;
  border-right: none;
}

.scrollableContainer-38zsVD,
.scrollableContainer-2NUZem {
  border-radius: 0px;
}

.chat-3bRxxu .attachButton-1UjEWA,
.attachButton-2WznTc {
  margin: 5px 10px;
}

.chat-3bRxxu .attachButtonPlus-rUdX-B {
  opacity: .55;
  height: 22px;
  margin: 16px 10px;
}

.chat-3bRxxu .textArea-2Spzkt,
.chat-3bRxxu .textArea-12jD-V {
  background-color: transparent !important;
  line-height: 1.25rem !important;
  margin-top: 8px;
}

.chat-3bRxxu .textArea-2Spzkt.textAreaDisabled-2_o-kZ {
  margin-top: 7px;
  margin-bottom: 7px;
}

.chat-3bRxxu .textArea-2Spzkt.textAreaEnabledNoAttach-1WxUwj {
  line-height: 1.25rem !important;
  margin-top: 2px;
}

.chat-3bRxxu .innerNoAutocomplete-1WpcVO {
  border-radius: 0px;
}

.form-2fGMdU {
  padding: 0;
}

.form-2fGMdU:before {
  display: none;
}

.chat-3bRxxu .channelTextArea-rNsIhG {
  margin: 0px 0 0px;
  padding: 0;
  border: none;
}

.chat-3bRxxu .channelTextAreaEnabledNoAttach-3tPFmT.channelTextArea-1LDbYG.channelTextArea-rNsIhG {
  margin: 4px 0 6px !important;
}

.chat-3bRxxu form {
  margin: 0px;
}

  /* 8.m. Typing Bar */
.chat-3bRxxu form .typing-2GQL18 {
  background-color: var(--quaternary-color) !important;
  bottom: 100%;
  padding-left: 5px;
  z-index: 0;
  animation: opacity 300ms ease;
  -ms-transform-origin: bottom left;
  transform-origin: bottom left;
  -ms-transform: scale(1);
  transform: scale(1);
  width: fit-content;
  display: -webkit-box;
  padding-right: 20px;
  padding-top: 0px;
  border-radius: 5px 5px 0 0;
  margin-left: 15px;
  box-shadow: 0 -3px 20px rgba(0, 0, 0, .1);
  opacity: 1;
  transition: all 200ms ease;
  text-overflow: ellipsis;
  z-index: 5;
  overflow: hidden;
}

.typing-2GQL18 .text-1y-e8- {
  line-height: 26px;
  text-overflow: ellipsis;
}

.base-gE7OpD .cooldownWrapper-3joyFc {
  margin-left: unset;
}

  /* 8.n. Notification Bar */
.notice-2FJMB4,
.BDFD-notice,
#pluginNotice {
  font-size: 0px !important;
  line-height: 18px;
  position: absolute;
  top: 46px;
  width: 100%;
  transition: all .2s linear;
  background-color: transparent !important;
  z-index: 999999999 !important;
  box-shadow: none !important;
}

.notice-2FJMB4,
.notice-2FJMB4.BDFDB-notice,
#pluginNotice {
  top: 46px;
}

.notice-2FJMB4 .textLink-27KAGV {
  font-size: 0px !important;
  line-height: 18px;
}

.notice-2FJMB4:hover .textLink-27KAGV {
  font-size: 14px !important;
  line-height: 38px;
}

.noticePremiumTier1-3Zywvl {
  background-image: none;
}

.noticePremium-12Zvj9 .premiumIcon-2lve6h {
  transform: scale(0);
  transition: all 200ms ease-in-out;
}

.noticePremium-12Zvj9:hover .premiumIcon-2lve6h {
  transform: scale(1);
}

.notice-2FJMB4::before {
  content: '';
  position: absolute;
  top: 0;
  left: 50%;
  transform: translatex(-50%);
  width: 100%;
  height: 4px;
  z-index: -1;
  transition: all 200ms ease-in-out;
  background-color: dodgerblue;
  box-shadow: var(--elevation-low);
}

.noticeDanger-7u-yT9::before {
  background-color: var(--dnd);
}

.notice-2FJMB4:hover::before,
.BDFD-notice.notice-2FJMB4:hover::before,
#pluginNotice::before {
  height: 38px !important;
}

.notice-2FJMB4:hover,
.BDFD-notice.notice-2FJMB4:hover,
#pluginNotice {
  font-size: 14px !important;
  line-height: 38px;
  width: 100%;
}

.notice-2FJMB4 .dismiss-SCAH9H {
  opacity: 0;
}

.notice-2FJMB4:hover .dismiss-SCAH9H,
.BDFD-notice.notice-2FJMB4:hover .dismiss-SCAH9H,
#pluginNotice .dismiss-SCAH9H {
  opacity: 1;
  height: 36px;
  margin-right: 100px;
  transition: all .2s linear;
}

#app-mount .noticePremiumGrandfathered-ollUxF {
  background: transparent;
}

.notice-2FJMB4 .button-1MICoQ,
.noticePremiumGrandfathered-ollUxF .premiumIcon-2lve6h,
.notice-2FJMB4 .platformIcon-2NdO9F {
  transform: scale(0);
  opacity: 0;
  display: inline-block !important;
  transition: transform .1s linear, opacity .2s linear;
}

.notice-2FJMB4:hover .button-1MICoQ, 
.noticePremiumGrandfathered-ollUxF:hover .premiumIcon-2lve6h,
.notice-2FJMB4:hover .platformIcon-2NdO9F  {
  transform: none;
  opacity: 1;
}

  /* 8.o. Search Results */
.searchResultsWrap-3-pOjs {
  z-index: 1;
  background: var(--primary-color);
}

.searchResult-2N9RV4.expanded-ovgtuV {
  background: var(--primary-color);
}

.searchResultsWrap-3-pOjs .searchHeader-1EzJGH {
  background-color: var(--quaternary-color) !important;
}

.searchResultsWrap-3-pOjs .searchResult-2N9RV4:before {
  background-image: linear-gradient(0deg, rgba(47, 49, 54, 0), var(--primary-color)) !important;
}

.searchResultsWrap-3-pOjs .searchResult-2N9RV4:after {
  background-image: linear-gradient(180deg, rgba(47, 49, 54, 0), var(--primary-color)) !important;
}

.searchResultsWrap-3-pOjs .searchResult-2N9RV4 .searchResultMessage-30QnSN.hit-1CXhXT {
  border: 2px solid var(--quaternary-color) !important;
}

.searchResultsWrap-3-pOjs .searchResult-2N9RV4 .hit-1CXhXT {
  background-color: var(--quaternary-color) !important;
  box-shadow: 0 0 10px 6px var(--primary-color) !important;
}

.searchResultsWrap-3-pOjs .searchResult-2N9RV4 .hit-1CXhXT:hover {
  border: 2px solid var(--main-color) !important;
}

.searchResultsWrap-3-pOjs .channelSeparator-dTqJ4K:before {
  display: none;
}

.searchResultsWrap-3-pOjs .channelSeparator-dTqJ4K .channelName-wvgELL {
  background-color: var(--main-color) !important;
  color: #fff;
  margin-left: -10px;
  padding: 8px 8px 8px 6px;
}

.searchResultsWrap-3-pOjs .actionButtons-14P9IC .jumpButton-Ia2hRJ {
  background-color: var(--main-color) !important;
  color: #fff;
  padding: 1px 7px 3px 6px;
}

.calendarPicker-2yf6Ci .react-datepicker,
.calendarPicker-2yf6Ci .react-datepicker__header {
  border-radius: 0px !important;
  background: var(--primary-color) !important;
}

.calendarPicker-2yf6Ci .react-datepicker__current-month,
.datePicker--XZbmJ .datePickerHint-3Q1Udw,
.calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--next, 
.calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--previous,
.calendarPicker-2yf6Ci .react-datepicker__day {
  border-color: var(--tertiary-color) !important;
}

.calendarPicker-2yf6Ci .react-datepicker__day {
  background: var(--secondary-color) !important;
}

.calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--disabled, 
.calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--disabled:hover {
  background: var(--quaternary-color) !important;
}

.calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--selected:hover, 
.calendarPicker-2yf6Ci .react-datepicker__day:hover,
.datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z:hover {
  background-color: var(--hover-color) !important;
}

.calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--selected:after,
.datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z {
  background-color: var(--main-color) !important;
}

  /* 8.p. Video Calling */
.callAvatarBorder-1D_KaE.video-3GgX2M.selected-2esnyn:not(.speaking-oCqYMI):not(.soundsharing-102bS9) {
  box-shadow: inset 0 0 2px var(--main-color);
}

.videoHeight-Qp_9vC::before {
  content: '';
  position: absolute;
  height: 48px;
  width: 1px;
  border-left: 2px solid var(--main-color);
  z-index:10;
}

  /* 8.q. Streaming */
#app-mount .videoControls-3glNbo {
  padding: 0px;
}

#app-mount .bottomControls-UTyHwG,
#app-mount .headerTitle-1EzOnI {
  width: unset;
  padding: 0px 16px 16px;
}

#app-mount .headerTitle-1EzOnI {
  padding-top: 4px;
}

#app-mount .root-25RxKh.miniPlayer-3Ms77e .container-1r6BKw {
  background: transparent;
  border-bottom: none;
}

#app-mount .root-25RxKh.miniPlayer-3Ms77e .container-1r6BKw {
  background: transparent;
  border-bottom: none;
}

#app-mount .miniPlayer-3Ms77e .videoControls-3glNbo {
  padding: 8px;
}

/* 9. Friends List */
  /* 9.a. Main Friends List */

.peopleList-3c4jOR,
.nowPlayingColumn-2sl4cE {
  background: transparent;
}

#app-mount .container-1D34oG {
  background: var(--primary-color) !important;
}

.peopleListItem-2nzedh:hover,
.wrapper-3D2qGf,
.emptyCard-1RJw8n {
  background: var(--tertiary-color);
}

#app-mount .inset-3sAvek {
  background: var(--secondary-color);
}

/* 9.b. Action Buttons */
.actionButton-uPB8Fs {
  background: var(--quaternary-color);
}

.actionButton-uPB8Fs.highlight-Lf97TE {
  background: var(--main-color);
  color: white;
}

.actionButton-uPB8Fs {
  transition: background-color .2s ease-in-out;
}

.actionButton-uPB8Fs.actionAccept-LV-szU:hover {
  background-color: var(--online);
  color: white !important;
}

.actionButton-uPB8Fs.actionDeny-de_uKj:hover {
  background-color: var(--dnd);
  color: white !important;
}

/* 10. Games Activity, Library, Store, and Server Directory */
  /* 10.a Activity*/
.card-7JP0BX,
.article-3kb3qm,
.carousel-2WxMes {
  background-color: transparent !important;
}

.article-FleDq5,
.body-SKIE6r {
  background-color: var(--secondary-color) !important;
}

.header-1RC2Wb:hover {
  background-color: var(--secondary-color) !important
}

.headerButtonColor-G7_f-V {
  background-color: var(--tertiary-color) !important;
}

.theme-dark .lookFilled-1Gx00P.hoverBrand-1_Fxlk.hasHover-3X1-zV:hover, 
.theme-light .lookFilled-1Gx00P.hoverBrand-1_Fxlk.hasHover-3X1-zV:hover {
  background-color: var(--hover-color) !important;
}

.lookFilled-1Gx00P.colorPrimary-3b3xI6 {
  background-color: var(--primary-color) !important;
}

.lookFilled-1Gx00P.colorPrimary-3b3xI6:hover {
  background-color: var(--tertiary-color) !important;
}

.header-1RC2Wb {
  background-color: var(--tertiary-color) !important;
  transition: all .2s ease-in-out;
}

.news-2GDtLJ {
  background: transparent !important;
}

.player-1kJMbj .da-flex::after {
  margin-left: 5px
}

.splashArt-3I5Qmp {
  opacity: .5;
  -webkit-mask: -webkit-gradient(linear,right top,left top,from(#202225), to(transparent));
}

.paginationText-30Kp6m::after {
  display: none;
}

.paginationItem-2lUq0s {
  background: transparent;
}

.selectedPage-2JQS2s,
.paginationItem-2lUq0s:hover {
  background: var(--primary-color);
}

.paginationItem-2lUq0s:before {
  background: var(--main-color);
}

.paginationItem-2lUq0s:after {
  display: none;
}

.voiceSectionGuildImage-2r1uIp, 
.voiceSectionNoGuildImageWrapper-40qwqb {
  mask: none;
  -webkit-mask: none;
}

.voiceSectionIconWrapper-3YFjHm {
  right: -5px;
  bottom: -5px;
}

#app-mount .partyMember-923s4S,
#app-mount .partyMemberOverflow-Nei5T6 {
  mask: none;
  -webkit-mask: none;
  margin: 0 2px;
}

#app-mount .partyMemberOverflow-Nei5T6,
.guildIconEmptyBackground-14tfYf {
  background-color: var(--main-color) !important;
}

.guildIconEmptyIcon-rSyLPf,
#app-mount .partyMemberOverflow-Nei5T6 {
  color: white !important;
}

.partyMemberBackground-aSF9mc {
  background-color: var(--secondary-color) !important;
}

.theme-dark .partyMemberUnknownIcon-2zv8ar {
  color: white;
}

.theme-light .partyMemberUnknownIcon-2zv8ar {
  color: #191919;
}

.dockItem-2kQDqg:hover {
  background-color: var(--secondary-color) !important;
  transition: all 200ms ease-in-out;
}

.info-P9dFwH {
  background: transparent;
}

.root-1bFE0x,
.searchBox-3Y2Vi7 {
  background-color: var(--quaternary-color) !important;
}

.searchBox-3Y2Vi7 .input-cIJ7To {
  background-color: transparent !important;
}

.section-7tu4tu:not(:last-child) {
  border-color: var(--main-color) !important;
}

.arrow-1-DaGi {
  color: var(--main-color)
}

.dot-22bIa4 {
  background-color: var(--main-color);
}

#app-mount .outer-2IVh5n,
#app-mount .popout-3G62UL,
#app-mount .unwrapped-37iUtM,
#app-mount .inset-GQDQYw,
#app-mount .recentlyPlayedContainer-2F3MqS,
#app-mount .wrapped-15rg6t {
  background-color: var(--secondary-color);
}

#app-mount .wrapper-3rh-14:hover,
#app-mount .memberListItem-vHCzSI:hover,
#app-mount .popoutContainer-3WC9HR:hover,
#app-mount .unwrapped-37iUtM:hover,
#app-mount .wrapped-15rg6t.clickable-nnkAZy:hover {
  background-color: var(--quaternary-color);
}

#app-mount .multipleIconWrapper-2TXVB4, 
#app-mount .section-3TvauS {
  background-color: var(--tertiary-color);
}

.cap-HS8vCE {
  background-color: var(--main-color);
}

#app-mount .searchOption-8nCYo-.selected-1r_nkg {
  background-color: var(--quaternary-color);
}

#app-mount .memberListItem-2ZX2pl:hover {
  background-color: var(--quaternary-color);  
}

#app-mount .multipleIconWrapper-1PjkRO, 
#app-mount .section-2VKIPC,
#app-mount .emptyCard-3CNsz2 {
  background-color: var(--secondary-color);
}

.buttonColor-1agP3J {
  background-color: var(--main-color);
}

.buttonColor-1agP3J:hover {
  background-color: var(--hover-color);
}

  /* 10.b. Library */

#app-mount .scroller-1IIF0A,
#app-mount .scroller-5bBood,
.scroller-2XE8rp  {
  background: transparent;
}

.rowWrapperActive-2L7i9f {
  background-color: var(--tertiary-color) !important;
}

.rowBackground-3MeNoN {
  -webkit-mask: radial-gradient(100% 100% at top left,hsla(0,0%,100%,.5) 0,hsla(0,0%,100%,0) 100%);
}

.header-39GIC8 {
  background-color: var(--quaternary-color) !important;
}

.defaultIndicator-2X8Auf,
.defaultIndicator-G3c16x {
  background-color: var(--main-color) !important;
}

.gameUpdates-2GPqBU,
.topPill-30KHOu .item-PXvHYJ:hover:not(.itemSelected-1qLhcL) {
  background-color: var(--quaternary-color) !important;
}

[style*="background-color: rgb(24, 25, 28)"] {
  background-color: var(--quaternary-color) !important;
}

.downloadProgressCircle-neZab7 {
  top: 5px;
  right: 5px;
}

.circleBackground-OqqxHM {
  fill: var(--tertiary-color);
  stroke: var(--quaternary-color);
}

[style*="background: linear-gradient(to right, rgb(199, 208, 240), rgb(114, 137, 218))"] {
  background: linear-gradient(to right, transparent, var(--main-color)) !important;
}

[stroke*="#4f545c"] {
  stroke: var(--main-color) !important;
}

.nitroIcon-2_2ZKS {
  color: var(--main-color) !important;
}

.progressCircle-1hzs_b>svg>defs>linearGradient stop:nth-child(1) {
  stop-color: rgba(255, 255, 255, 0.8) !important;
}

.progressCircle-1hzs_b>svg>defs>linearGradient stop:nth-child(2) {
  stop-color: var(--main-color) !important;
}

.installSize-1eXbBX {
  background-color: var(--main-color) !important;
  color: white !important;
}

.bodyButtonColor-3yTLJ1 {
  background-color: var(--main-color) !important;
  color: white !important;
}

.bodyButtonColor-3yTLJ1:hover {
  background-color: var(--hover-color) !important;
}

.moreUsers-1s5Her,
.playerOverflow-3X56UI,
.playerOverflow-2Hf77M,
.voiceSectionIconWrapper-3YFjHm,
#app-mount .partyMemberOverflow-1tfvpb,
#app-mount .overflowPlayerCount-_jrNfw {
  background-color: var(--main-color) !important;
  color: white;
}

.libraryFilter-31ZUa2 {
  transition: all 200ms ease-in-out;
}

  /* 10.c. Store */
#app-mount .defaultIndicator-3WqGFB {
  background-color: var(--main-color)
}

#app-mount .scroller-9moviB,
#app-moung .scroller-1JpcIc {
  background: transparent;
}

#app-mount .gradientOverlayRight-3vMuS8 {
  background-image: -webkit-gradient(linear,left top,right top,from(transparent),to(var(--quaternary-color)));
  background-image: linear-gradient(90deg,transparent,var(--quaternary-color));
}

#app-mount .gradientOverlayLeft-3w159C {
  background-image: -webkit-gradient(linear,left top,right top,from(var(--quaternary-color)),to(transparent));
  background-image: linear-gradient(90deg,var(--quaternary-color),transparent);
}

.itemBackground-2vEldQ::before {
  background: radial-gradient(ellipse at top,transparent,var(--primary-color)),linear-gradient(90deg,var(--primary-color) 0,transparent 40%,transparent 60%,var(--primary-color)),linear-gradient(0deg,var(--primary-color) 10%,transparent 70%) !important;
}

.tileMedia-24cT6_,
.body-1CAT0-,
.content-35aVm0,
.item-2yFVoY,
.openBody-1HeDPG,
.card-NB61oR,
.tileWrapper-2khh-w,
.bodySection-jqkkIP,
.row-1bU71H,
.applicationTile-1Goy1W,
.itemBackground-2vEldQ,
.tileMedia-1q3guD,
.iconCircle-1dlYo0,
#app-mount .card-3DjzTQ, 
#app-mount .cardPlaceholder-1zrbbe {
  background-color: var(--quaternary-color) !important;
}

.bodySection-jqkkIP {
  border-top-color: var(--main-color) !important;
}

.mediaFade-1SdEfL {
  background: linear-gradient(180deg,transparent 90%,var(--quaternary-color)) !important;
}

.description-3rB3Rp {
  background: linear-gradient(180deg,transparent,rgba(0,0,0,.75) 45%,var(--quaternary-color)) !important;
}

.tile-2H4MQG,
.tile-367QuY {
  background-color: var(--primary-color) !important;
}

.tile-2H4MQG:hover,
.tile-367QuY:hover,
.tileMedia-1q3guD:hover {
  background-color: var(--secondary-color) !important;
}

.overlappingBorder-1-XPGl,
.overlappingBorder-1ysb12,
.overlappingBorder-3aFng4 {
  border-color: var(--main-color) !important;
}

.announcingNitro-3Ptg6m,
.purchaseUnitOperatingSystem-cnbJPz,
.nextArrow-_BbNud, 
.prevArrow-GBsQ1m,
.arrow-vOpU7R {
  color: var(--main-color) !important;
}

.announcingNitro-3Ptg6m:hover,
.lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover {
  color: var(--hover-color) !important
}

.lookOutlined-3sRXeN.colorBrand-3pXr91:active {
  border-color: var(--main-color);
}

.lookOutlined-3sRXeN.colorBrand-3pXr91::before {
  position: absolute;
  content: "";
  top: -1px;
  left: -1px;
  height: calc(1px + 100%);
  width: calc(1px + 100%);
  border-radius: 5px;
  background: var(--main-color);
  opacity: .1;
}

.lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover {
  border-color: var(--hover-color);
}

.lookOutlined-3sRXeN.colorBrand-3pXr91 {
  border-color: var(--main-color);
  color: var(--main-color);
}

.lookOutlined-3sRXeN.colorBrand-3pXr91:hover {
  border-color: var(--hover-color);
}

.filterByTitleInput-2U3yVW:focus {
  border-bottom-color: var(--main-color) !important;
}

.bubble-1gL_TN,
.price-1ynJAt,
.price-NUANu6,
.entitledHeader-3LRNDT,
.dot-2Q_mMZ,
.pulsingEllipsisItem-32hhWL,
.genreTag-3QLRUJ {
  background-color: var(--main-color) !important;
}

.bubble-1gL_TN:after {
  border-top-color: var(--main-color) !important;
}

.listingLarge-3Rix7u,
.browse-3H33-E, .filters--5q7-h {
  max-width: none;
}

.assetWrapper-2Qw_5D {
  background: transparent !important;
}

  /* 10.d. Server Directory */
.bg-AYqtMd {
  -webkit-mask: linear-gradient(black, transparent);
}

#app-mount .loading-17PYl_ {
  background-color: var(--secondary-color);
}

#app-mount .emptySearchResults-1ba__I {
  background: transparent;
}

.searchHelpText-19imBp {
  margin-bottom: -20px;
}

#app-mount .wrapper-39oAo3,
#app-mount .css-1b86x2o-control,
#app-mount .css-9wh895-control,
#app-mount .css-1o55ng5-control,
#app-mount .css-123uooi-menu,
#app-mount .pageButton-MknE-_:hover,
.emojiContainer-1u-_sQ {
  background-color: var(--quaternary-color);
}

#app-mount .css-1gnr91b-option {
  transition: all 200ms ease-in-out;
  box-shadow: inset 0 0 10px var(--hover-color);
}

#app-mount .activeButton-1BJAiN {
  background-color: var(--main-color);
  transition: background 200ms ease-in-out;
}
 
#app-mount .activeButton-1BJAiN:hover {
  background-color: var(--hover-color);
}

.placeholder-2erB-x {
  background-color: var(--tertiary-color);
}

.discoverHeader-1TWTqG {
  position: fixed;
  margin: 0;
  padding: 16px 16px 0 16px;
  width: 208px;
  border-bottom: 2px solid var(--main-color);
  box-shadow: 0 2px 20px var(--shadow) !important;
}

.discoverHeader-1TWTqG + .categoryItem-3zFJns {
  margin-top: 50px;
}

#app-mount .categoryItem-3zFJns.selectedCategoryItem-3X8ujp .itemInner-3gVXMG {
  background-color: var(--main-color);
}

.search-1iTphC .searchBox-2_mAlO .searchBoxInput-K6mkng {
  color: white;
}

/* 11. Avatars */
  /* 11.a. Remove Mask */
.mask-3OgeRz,
.image-33JSyf {
  -webkit-mask: none;
  mask: none;
}

.avatarMasked-1s1eiJ {
  -webkit-mask-image: none;
  mask-image: none;
}
  
  /* 11.b. Status */
.mask-1l8v16 {
  contain: none;
}
.wrapper-3t9DeA foreignObject+rect[mask*="svg-mask-status"],
.wrapper-3t9DeA[class*="avatar"] foreignObject+rect[y="22"] {
  x: 1 !important;
  y: 1 !important;
  rx: var(--roundness) !important;
  mask: none !important;
  -webkit-mask: none !important;
  fill-opacity: -.1 !important;
  stroke-width: 2px;
  transition: stroke 200ms ease-in-out;
}

.wrapper-3t9DeA foreignObject+svg+rect[mask*="svg-mask-status"],
.wrapper-3t9DeA[class*="avatar"] foreignObject+svg+rect[y="22"] {
  opacity: 0;
}

#app-mount .wrapper-3t9DeA foreignObject+svg rect {
  position: absolute;
  height: 32px !important;
  width: 32px !important;
  top: 0;
  left: 0;
  mask: none !important;
  transform: translate(-14.5px, -17px);
  fill-opacity: 0;
  stroke-width: 2px;
  rx: var(--roundness) !important;
  transition: stroke 200ms ease-in-out;
}

#app-mount .wrapper-3t9DeA[style*="height: 24px"] rect[mask*="svg-mask-status"] {
  height: 22px !important;
  width: 24px !important;
}

#app-mount .wrapper-3t9DeA[style*="height: 32px"] rect[mask*="svg-mask-status"],
#app-mount .wrapper-3t9DeA[style*="height: 32px"] rect[y="22"] {
  height: 32px !important;
  width: 32px !important;
}

#app-mount .wrapper-3t9DeA[style*="height: 40px"] rect[mask*="svg-mask-status"],
#app-mount .wrapper-3t9DeA[style*="height: 40px"] rect[y="28"] {
  height: 38px !important;
  width: 40px !important;
}

#app-mount .wrapper-3t9DeA[style*="height: 80px"] rect[mask*="svg-mask-status"],
#app-mount .wrapper-3t9DeA[style*="height: 80px"] foreignObject+svg rect {
  height: 78px !important;
  width: 80px !important;
}

#app-mount .wrapper-3t9DeA[style*="height: 80px"] foreignObject+svg rect:not([x*="60"]) {
  transform: translate(-48px, -51px);
}

#app-mount svg:not(:root),
.userInfo-2zN2z8 {
  overflow: visible !important;
}

.wrapper-3t9DeA rect[mask*="svg-mask-status"][fill*="#43b581"],
.wrapper-3t9DeA rect[mask*="svg-mask-status"][mask*="online"],
.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(67, 181, 129, 1)"] {
  -webkit-text-stroke-color: var(--online);
  stroke: var(--online);
}

.wrapper-3t9DeA rect[mask*="svg-mask-status"][fill*="#f04747"],
.wrapper-3t9DeA rect[mask*="svg-mask-status"][mask*="dnd"],
.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(240, 71, 71, 1)"] {
  -webkit-text-stroke-color: var(--dnd);
  stroke: var(--dnd);
}

.wrapper-3t9DeA rect[mask*="svg-mask-status"][fill*="#faa61a"],
.wrapper-3t9DeA rect[mask*="svg-mask-status"][mask*="idle"],
.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(250, 166, 26, 1)"] {
  -webkit-text-stroke-color: var(--idle);
  stroke: var(--idle);
}

.wrapper-3t9DeA rect[mask*="svg-mask-status"][fill*="#593695"],
.wrapper-3t9DeA rect[mask*="svg-mask-status"][mask*="streaming"],
.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(89, 54, 149, 1)"] {
  -webkit-text-stroke-color: var(--streaming);
  stroke: var(--streaming);
}

.wrapper-3t9DeA[class*="avatar"] rect:not([mask*="svg-mask-status"])[y="22"][fill="transparent"] {
  -webkit-text-stroke-color: var(--offline);
  stroke: var(--offline);
}

.wrapper-3t9DeA rect[mask*="svg-mask-status"][fill*="#747f8d"],
.wrapper-3t9DeA rect[mask*="svg-mask-status"][mask*="invisible"],
.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(116, 127, 141, 1)"] {
  stroke: var(--offline);
  -webkit-text-stroke-color: var(--offline);
}

.avatarWrapperNormal-3wFMbf:hover .avatarHint-1qgaV3 {
  width: 79.5px;
  height: 77.5px;
  transition: opacity 200ms ease-in-out;
  margin: 1px 1px 1px 1px;
}

foreignObject[mask*="mobile"] {
  overflow: visible !important;
}

.privateChannels-1nO12o a.channel-2QD9_O .content-3QAtGj,
.member-3-YXUe .content-3QAtGj {
  max-width: 120px
}

.privateChannels-1nO12o a.channel-2QD9_O foreignObject[mask*="mobile"]::before,
.privateChannels-1nO12o a.channel-2QD9_O foreignObject[mask*="mobile"]::after {
  left: 165px;
  height: 20px;
  width: 20px;
}

.privateChannels-1nO12o a.channel-2QD9_O .children-gzQq2t {
  margin-left: 20px;
}

foreignObject[mask*="mobile"]::before,
foreignObject[mask*="mobile"]::after {
  position: absolute;
  content: "";
  height: 25px;
  width: 25px;
  background: rgba(0,0,0,.4);
  top: 50%;
  left: 170px;
  transform: translateY(-50%);
  border-radius: 50%;
  opacity: .6;
}

foreignObject[mask*="mobile"]::after {
  background: var(--online);
  mask: url("https://monstrousdev.github.io/themes/assets/svgs/phone.svg") center/70% no-repeat;
  -webkit-mask: url("https://monstrousdev.github.io/themes/assets/svgs/phone.svg") center/70% no-repeat;
}

.avatarHint-1qgaV3 foreignObject[mask*="mobile"]::before,
.avatarHint-1qgaV3 foreignObject[mask*="mobile"]::after {
  display: none;
}

.userPopout-3XzG_A foreignObject[mask*="mobile"]::before,
.userPopout-3XzG_A foreignObject[mask*="mobile"]::after,
.modal-3c3bKg foreignObject[mask*="mobile"]::before,
.modal-3c3bKg foreignObject[mask*="mobile"]::after {
  top: -19px;
  left: unset;
  right: -85px;
  height: 35px;
  width: 35px;
  opacity: 1;
  transform: none;
}

.modal-3c3bKg foreignObject[mask*="mobile"]::before,
.modal-3c3bKg foreignObject[mask*="mobile"]::after {
  top: -20px;
  right: -500px;
}

.userPopout-3XzG_A foreignObject[mask*="mobile"]::before,
.modal-3c3bKg foreignObject[mask*="mobile"]::before {
  border-radius: 0px;
  border-bottom-left-radius: 25%;
  background: rgba(0, 0, 0, .7)
}

  /* 11.c. Typing */
#app-mount .wrapper-3t9DeA[style*="height: 32px"] foreignObject+svg+rect[width="25"] {
  fill: rgba(0, 0, 0, .5);
  x: 0 !important;
  y: 0 !important;
  rx: var(--roundness);
  height: 32px;
  width: 32px;
  opacity: 1;
  transition: fill 500ms ease-in-out;
  position: absolute;
  top: 0;
  left: 0;
  opacity: 1;
}

.avatarUploaderInner-3UNxY3 {
  background-color: var(--main-color);
}

.wrapper-3t9DeA foreignObject+svg rect+svg.dots-3Bkt3k g{
  position: absolute;
  top: 0;
  left: 0;
  transform: translate(-11.5px, -10px);
}

.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(67, 181, 129, 1)"]+svg.dots-3Bkt3k g circle {
  fill: var(--online) !important;
}

.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(240, 71, 71, 1)"]+svg.dots-3Bkt3k g circle {
  fill: var(--dnd) !important;
}

.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(250, 166, 26, 1)"]+svg.dots-3Bkt3k g circle {
  fill: var(--idle) !important;
}

.wrapper-3t9DeA foreignObject+svg rect[fill="rgba(89, 54, 149, 1)"]+svg.dots-3Bkt3k g circle {
  fill: var(--streaming) !important;
}

/* 12. Shadows */
.popout-3sVMXz.popoutBottomRight-2JrySt.noArrow-3BYQ0Z.noShadow-321ZPm,
.title-3qD0b-,
.headerBar-UHpsPw,
.elevationBorderHigh-2WYJ09,
.form-2fGMdU .inner-MADQqc {
  -webkit-box-shadow: none !important;
  box-shadow: none !important;
}

.channel-members-wrap,
.guildsWrapper-5TJh6A:not(.foldercontent),
.wrapper-1Rf91z,
.channels-wrap .flexChild-faoVW3,
#friends .friends-header,
.chat-3bRxxu .title-wrap,
.chat-3bRxxu form .channel-text-area-default,
.searchResultsWrap-2DKFzt,
.embed-IeVjo6,
.emojiPicker-3m1S-j,
.channels-Ie2l6A,
.wrapper-35wsBm,
.cardPrimary-1Hv-to,
.cardPrimaryEditable-3KtE4g,
.authedApp-mj2Hmd,
.modal-3HD5ck .message-2qRu38,
.theme-dark .autocomplete-1vrmpx,
#app-mount .menu-Sp6bN1,
#permissions-modal-wrapper .role-side,
.sidebar-2K8pFh,
.inner-MADQqc,
.peopleColumn-29fq28 {
  box-shadow: 0 2px 20px var(--shadow) !important;
}

.sidebar-2K8pFh {
  z-index: 2;
}

.members-1998pB {
  box-shadow: 0 -2px 20px var(--shadow) !important;
}




/* 13. Roundness */
.guild-1EfMGQ .guildInner-3DSoA4,
#app-mount foreignObject {
  border-radius: 0 !important;
}

#app-mount .acronym-2mOFsV,
.guild-1EfMGQ .guildIcon-CT-ZDq,
.guilds-1q_RqH .guildPlaceholder-1ioaid,
.dragPlaceholder-D9-haY,
.wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .container-2td-dC,
.guildsWrapper-5TJh6A .guild-1EfMGQ.guildsAdd-21_IdK::after,
.container-2td-dC.audio-2KA0-x::after,
.container-2td-dC.video-2jNDI4::after,
.dragfix-1wSxtO:active,
.container-2td-dC .wrapper-2lTRaf,
.friendsTable-133bsv .friends-column.friends-column-guilds .icon-3o6xvg,
.status-oxiHuE,
.image-33JSyf,
.avatar-small,
.avatar-xxlarge,
.wrapper-2F3Zv8,
.status-oxiHuE.typing-1KJk_j .pulsingEllipsisItem-32hhWL,
.avatarHint-1qgaV3,
.partyMemberOverflow-3VhFIX .partyMemberBackground-aSF9mc,
.listRow-hutiT_ .listAvatar-1NlAhb,
.avatar-uploader-inner,
.avatarUploaderIndicator-2G-aIZ,
.avatarDefault-35WC3R,
.avatarSpeaking-1wJCNq,
.callAvatar-v-u4BM.voice-2D-tt_,
.callAvatar-v-u4BM .callAvatarStatus-3y6S04,
.callAvatarBorder-1D_KaE.voice-2D-tt_.speaking-oCqYMI,
.callAvatarWrapper-TICyxO.voice-2D-tt_ .ripple-16ZT2p,
.from-mPWN2E, 
.to-2819fF,
.friendsTable-133bsv .friendsRow-2yicud .friends-column-guilds .more-mutual-guilds-btn,
.reviewCircle-1o-MOB,
.circle-1nK_79,
.guild-1EfMGQ.audio-3vVhBi:after, 
.guild-1EfMGQ.video-15yGu3:after,
.inner-1W0Bkn,
.iconInactive-98JN5i,
.friendsTable-133bsv .friendsRow-2yicud .friendsColumnGuilds-2we6jb .moreMutualGuildsBtn-2VwbkO,
.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9,
.guildIconEmptyBackground-14tfYf,
.guildsError-3cFMtY,
.avatar-1BDn8e,
.avatarUploaderInner-3UNxY3,
.icon-3o6xvg,
.gameIcon-gg34Dz,
#app-mount .partyMember-923s4S,
#app-mount .partyMemberOverflow-Nei5T6,
.moreUsers-1s5Her,
.playerOverflow-3X56UI,
.playerOverflow-2Hf77M,
.voiceSectionIconWrapper-3YFjHm,
.voiceSectionGuildImage-2r1uIp, 
.voiceSectionNoGuildImageWrapper-40qwqb,
.wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .circleIconButton-jET_ig svg,
.wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .circleIconButton-jET_ig span,
.guildsError-b7zR5H,
.base-PmTxvP,
#app-mount .avatar-3elDyV,
.avatar-3bWpYy, 
.clickableAvatar-1wQpeh, 
.emptyUser-7txhlW,
#app-mount .acronym-2mOFsV,
#app-mount .wrapper-1BJsBx,
#app-mount .wrapper-3t9DeA foreignObject .avatar-VxgULZ,
#app-mount .avatarHint-1qgaV3 foreignObject .avatarHintInner-Dco91E,
#app-mount .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN .circleIconButton-jET_ig {
  border-radius: var(--roundness) !important;
}

#app-mount .wrapper-1BJsBx {
  overflow: hidden;
}



/* 14. Scrollbars */
.emojiPicker-3m1S-j .premiumPromo-yVfLiA,
#autocomplete-popout .scroller::-webkit-scrollbar,
#bda-qem-favourite-container .scroller-wrap .scroller::-webkit-scrollbar,
#bda-qem-twitch-container .scroller-wrap .scroller::-webkit-scrollbar,
.emojiPicker-3m1S-j .scrollerWrap-2lJEkd .scroller-2FKFPG::-webkit-scrollbar {
  display: none;
}

#bd-settingspane-container .scroller-wrap .scroller::-webkit-scrollbar {
  width: 5px;
}

#bd-settingspane-container .scroller-wrap .scroller::-webkit-scrollbar-thumb,
#bd-settingspane-container .scroller-wrap .scroller::-webkit-scrollbar-track-piece {
  border-radius: 40px;
}

#bda-qem-favourite-container .scroller-wrap .scroller::-webkit-scrollbar-thumb,
#bda-qem-twitch-container .scroller-wrap .scroller::-webkit-scrollbar-thumb,
.emojiPicker-3m1S-j .scrollerWrap-2lJEkd .scroller-2FKFPG::-webkit-scrollbar-thumb {
  border: none !important;
  background-color: rgba(225, 225, 225, 0.2) !important;
  display: initial;
}

.friends-table .scroller-wrap ::-webkit-scrollbar-track-piece, 
.messagesWrapper-3lZDfY .scroller-wrap ::-webkit-scrollbar-track-piece,
.scrollerWrap-2lJEkd .scroller-2CvAgC::-webkit-scrollbar-track-piece,
.scrollerWrap-2lJEkd .scroller-2FKFPG::-webkit-scrollbar-track,
.sb-menu-scroller:hover::-webkit-scrollbar-track-piece,
.scrollerWrap-2su1QI::-webkit-scrollbar-track-piece,
.scrollerWrap-2su1QI::-webkit-scrollbar-track,
.scroller-2FKFPG::-webkit-scrollbar-track,
.scroller-2FKFPG::-webkit-scrollbar-track-piece {
  background-color: transparent !important;
  border-color: transparent !important;
}

.friends-table .scroller-wrap ::-webkit-scrollbar-thumb, 
.messagesWrapper-3lZDfY .scroller-wrap ::-webkit-scrollbar-thumb,
.scrollerThemed-2oenus.themeGhostHairlineChannels-3G0x9_ .scroller-2FKFPG::-webkit-scrollbar-thumb, 
.scrollerThemed-2oenus.themeGhost-28MSn0 .scroller-2FKFPG::-webkit-scrollbar-thumb, 
.scrollerThemed-2oenus.themeDark-2cjlUp .scroller-2FKFPG::-webkit-scrollbar-thumb, 
.scrollerWrap-2lJEkd .scroller-2FKFPG::-webkit-scrollbar-thumb, 
.scrollerThemed-2oenus.themeDark-2cjlUp .scroller-2FKFPG::-webkit-scrollbar-thumb,
.scroller::-webkit-scrollbar-thumb,
.scrollerWrap-2lJEkd .scroller-2CvAgC::-webkit-scrollbar-thumb,
.chat-3bRxxu .textArea-2Spzkt::-webkit-scrollbar-thumb,
.sb-menu-scroller::-webkit-scrollbar-thumb {
  background-color: var(--main-color) !important;
  border-color: transparent !important;
  border-radius: 40px;
}

.scroller-2FKFPG::-webkit-scrollbar-track, 
.scroller-wrap .scroller::-webkit-scrollbar-track-piece {
  border-radius: 0px;
}

.scroller-wrap .scroller::-webkit-scrollbar {
  width: 11px;
}

.scroller-2FKFPG::-webkit-scrollbar {
  width: 12px;
}

.scroller-wrap .scroller::-webkit-scrollbar-thumb, 
.scroller-wrap .scroller::-webkit-scrollbar-track-piece {
  visibility: hidden !important;
  transition: .2s visibility linear;
}

.scroller-wrap .scroller:hover::-webkit-scrollbar-thumb, 
.scroller-wrap .scroller:hover::-webkit-scrollbar-track-piece {
  visibility: visible !important;
}

.rolesList-22qj2L::-webkit-scrollbar {
  height: 8px;
  width: 12px;
}





/* =================================== SLIDE INS ================================== */
/* 15. Popouts */
  /* 15.a. Pinned Messages and Recent Mentions*/
.themedPopout-25DgLi {
  border-left: 2px solid var(--main-color);
  border-right: 2px solid var(--main-color);
  border-bottom: 2px solid var(--main-color);
  border-top: 0px solid transparent;
}

#app-mount .themedPopout-25DgLi .header-SsaQ8X {
  border-radius: 0px;
}

#app-mount .messagesPopout-24nkyi {
  background: transparent;
}

#app-mount .messagesPopoutWrap-1MQ1bW {
  border-radius: 0 !important;
  border-left: 2px solid var(--main-color);
  border-right: 2px solid var(--main-color);
  border-bottom: 2px solid var(--main-color);
  border-top: 0;
  animation: popoutanim 300ms cubic-bezier(.4, 0, 0, 1), opacity 100ms ease 100ms backwards;
  transform-origin: 50% -10%;
  box-shadow: 0 2px 20px rgba(0,0,0,.4) !important;
  margin-top: 3px;
  background-color: var(--primary-color);
}

#app-mount .header-ykumBX,
#app-mount .footer-1kmXd4 {
  background-color: var(--tertiary-color);
}

.messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .messageGroupWrapper-o-Zw7G {
  background-color: var(--quaternary-color) !important;
  border-color: var(--quaternary-color) !important;
}

.messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .messageGroupWrapper-o-Zw7G:hover {
  background-color: var(--quaternary-color) !important;
  border-color: var(--main-color) !important;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .messageGroupWrapper-o-Zw7G:hover .actionButtons-1sUUug {
  background-color: transparent !important;
  box-shadow: none !important;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .message-group .actionButtons-1sUUug .jumpButton-3DTcS_ {
  background-color: var(--main-color) !important;
  color: #fff !important;
  padding: 2px 7px 3px 7px;
}

.themedPopout-25DgLi .header-SsaQ8X .subtitle, .themedPopout-25DgLi .text {
  color: #fff !important;
}

.jumpButton-3DTcS_ {
  background-color: var(--main-color) !important;
}

.hasMoreButton-1MELpI {
  background-color: var(--primary-color) !important;
  border-color: var(--primary-color) !important;
  color: var(--main-color) !important
}

  /* 15.b. Emoji Picker and Reactions */
.emojiPicker-3m1S-j,
.emojiPicker-3m1S-j .dimmer-3iH-5D.visible-3k45bQ,
.diversitySelector-tmmMv0 .popout-2nUePc,
.emojiPicker-3PwZFl {
  background: var(--primary-color) !important;
  border: 1px solid var(--primary-color);
  border-radius: 10px !important;
}

.infoBar-U6oBFk,
.emojiPicker-3m1S-j .categories-1feg4n,
.wrapper-2N7X54,
.categoryWrapper-UZ5YNj,
.inspector-sdLnLS {
  background-color: var(--quaternary-color)
}

.emojiPicker-3m1S-j .dimmer-3iH-5D.visible-3k45bQ {
  opacity: 0.7;
}

.emojiPicker-3m1S-j .header-1nkwgG .searchBar-2pWH0_ {
  background: transparent !important;
  opacity: 0.8
}

.emojiItem-14v6tW.emojiItemSelected-1aLkfV,
.guildIcon-3h-1IH {
  background: transparent;
}

#app-mount .emojiItemImageLoading-1yEIxx {
  opacity: 0;
}

.contentWrapper-2txmjs,
.categoryItemDefaultCategorySelected-_HCKoz, 
.categoryItemDefaultCategorySelected-_HCKoz:hover {
  background-color: var(--primary-color)
}

.emojiItem-14v6tW.emojiItemSelected-1aLkfV::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  opacity: .5;
  box-sizing: border-box;
  border: 2px solid var(--main-color);
}

.emojiPicker-3m1S-j .scroller-2FKFPG .emojiItem-109bjA {
  background-size: contain !important;
  background-position: 50% !important;
  background-repeat: no-repeat !important;
}

.emojiPicker-3m1S-j .scroller-2FKFPG .emojiItem-109bjA.disabled-1H1CfW {
  cursor: not-allowed;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq,
.categoryItemDefaultCategory-aBZ6nJ {
  opacity: .4;
  border: none !important;
  transition: all 50ms ease;
  background-position: center;
  background-repeat: no-repeat;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq svg,
.categoryItemDefaultCategory-aBZ6nJ svg {
  display: none;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:hover,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq.selected-39BZ4S,
.categoryItemDefaultCategory-aBZ6nJ:hover,
.categoryItemDefaultCategory-aBZ6nJ.categoryItemDefaultCategorySelected-_HCKoz {
  opacity: 1
}

.navButtonActive-3RPAJy {
  background-color: var(--main-color)
}

.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S {
  background-color: var(--hover-color) !important;
}

.emojiPicker-3m1S-j .category-2U57w6 {
  color: rgba(2555, 255, 255, 0.5);
  background: transparent !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(1),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(1).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(1):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='recent'],
.categoryItemDefaultCategory-aBZ6nJ[id*='recent'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='recent']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/frequent.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(2),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(2).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(2):hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/custom.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(3),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(3).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(3):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='people'],
.categoryItemDefaultCategory-aBZ6nJ[id*='people'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='people']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/people.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(4),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(4).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(4):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='nature'],
.categoryItemDefaultCategory-aBZ6nJ[id*='nature'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='nature']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/nature.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(5),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(5).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(5):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='food'],
.categoryItemDefaultCategory-aBZ6nJ[id*='food'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='food']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/food.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(6),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(6).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(6):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='activity'],
.categoryItemDefaultCategory-aBZ6nJ[id*='activity'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='activity']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/activity.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(7),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(7).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(7):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='travel'],
.categoryItemDefaultCategory-aBZ6nJ[id*='travel'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='travel']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/travel.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(8),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(8).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(8):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='objects'],
.categoryItemDefaultCategory-aBZ6nJ[id*='objects'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='objects']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/objects.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(9),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(9).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(9):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='symbols'],
.categoryItemDefaultCategory-aBZ6nJ[id*='symbols'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='symbols']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/symbols.svg) !important
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(10),
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(10).selected-39BZ4S,
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-child(10):hover,
.categoryItemDefaultCategory-aBZ6nJ[id*='flags'],
.categoryItemDefaultCategory-aBZ6nJ[id*='flags'].categoryItemDefaultCategorySelected-_HCKoz,
.categoryItemDefaultCategory-aBZ6nJ[id*='flags']:hover {
  background-image: url(https://monstrousdev.github.io/themes/assets/emojiCategory/flags.svg) !important
}

.emojiPicker-3m1S-j .no-search-results .sad-discord {
  background-image: url(../assets/svgs/sadDiscord.svg);
}

.emojiPicker-3m1S-j .stickyHeader-1SS0JU {
  width: 98% !important;
  background: var(--primary-color) !important;
}

.emojiPicker-3m1S-j .search-bar input {
  color: #fff !important;
  border-bottom: 2px solid rgba(255, 255, 255, .1);
  padding-bottom: 3px;
  padding-right: 25px;
  height: 30px
}

.emojiPicker-3m1S-j .search-bar input:focus {
  border-bottom: 2px solid var(--hover-color);
}

.searchBar-2_Yu-C.searchBarLight-1NxoDG .searchBarInner-1_Tg2R {
  background: transparent !important;
  color: var(--white10) !important
}

.reactionDefault-GBA58K, 
.reactionSelected-1pqISm {
  border: 1px solid transparent;
  transition: all .2s ease-in-out;
}

.reactionDefault-GBA58K:hover {
  background-color: transparent !important;
  border-color: var(--hover-color);
}

.reactionSelected-1pqISm {
  background-color: transparent !important;
  border-color: var(--main-color);
}

  /* 15.b.1. BBD Emote Menu */
  #app-mount #bda-qem {
    background: var(--primary-color) !important;
    border-bottom: 1px solid var(--quaternary-color) !important;
  }
  
  #bda-qem-twitch-container, #bda-qem-favourite-container {
    background-color: var(--primary-color) !important;
  }
    
  #app-mount #bda-qem button {
    background: var(--secondary-color);
    border-left: 1px solid var(--quaternary-color);
    box-shadow: var(--quaternary-color) 1px 0 0 0;
  }
  
  #bda-qem button:hover {
    background-color: var(--quaternary-color) !important;
  }
  
  #bda-qem button.active {
    background-color: var(--quaternary-color) !important;
  }
  
  .theme-dark #bda-qem button {
    color: #eee;
  }
    
  .theme-light #bda-qem button {
    color: #111;
  }
  
  .emote-container {
    border: 2px solid transparent !important;
    box-sizing: border-box;
  }
  
  .emote-container:hover {
    border-color: var(--hover-color) !important;
    background-color: transparent !important;
  }

  /* 15.c. Autocomplete */
.autocomplete-1vrmpx {
  background-color: var(--quaternary-color) !important;
}

.result-3w1ZcL[style*="background-color: rgb(146, 154, 250)"] {
  background-color: var(--hover-color) !important;
}

.result-3w1ZcL[style*="background-color: rgb(179, 174, 255)"],
.result-3w1ZcL[style*="background-color: rgb(115, 142, 245)"] {
  background-color: var(--main-color) !important;
}

.placeholder-1kJjXI {
  background: var(--quaternary-color) !important;
}

.autocompleteInner-zh20B_ {
  padding-bottom: 20px;
}

.selectable-3dP3y- {
  border: 1px solid transparent;
}

.selectorSelected-1_M1WV {
  border-color: var(--hover-color);
  background-color: var(--quaternary-color) !important;
}

.theme-dark .focused-1En8bG:after, 
.theme-dark .result-3w1ZcL:hover:after {
  box-shadow: inset 0 0 0 2px var(--main-color),
  inset 0 0 0 3px var(--quaternary-color);
}

.emptyHintCard-2mUdMe {
  background: var(--background-image) center/cover no-repeat;
  background-attachment: fixed;
  border-color: var(--main-color) !important;
  overflow: hidden;
}

.emptyHintCard-2mUdMe::before {
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: var(--primary-color);
}

.emptyHintCard-2mUdMe * {
  z-index: 1;
}

  /* 15.d. User Popout */
.headerNormal-T_seeN {
  background-color: var(--quaternary-color) !important;
}

.headerPlaying-j0WQBV {
  background: var(--main-color);
}

.headerFill-adLl4x .top-28JiJ- .itemDefault-3Jdr52:hover {
  color: #d1d1d3 !important;
  border-bottom-color: #d1d1d3 !important
}

#app-mount .bodyInner-245q0L {
  background: transparent;
}

.body-3iLsc4, 
.footer-1fjuF6 {
  background-color: var(--primary-color) !important;
}

.bodyTitle-Y0qMQz {
  color: #d1d1d3;
}

.footer-1fjuF6 {
  border-top: 2px solid var(--main-color) !important;
}

.rolesList-22qj2L {
  max-height: 14vh;
  overflow-y: auto;
}

.role-2irmRk {
  border-width: 1px;
  border-style: solid;
  border-radius: 2px;
  box-sizing: content-box;
  height: 16px;
  margin: 3px;
  padding: 2px;
  position: relative;
  line-height: 16px;
  font-size: 10px;
  font-weight: 400;
  text-transform: uppercase;
  overflow: visible;
}

.role-2irmRk::before {
  content: '';
  position: absolute;
  top: 0;
  left: -1px;
  height: 100%;
  width: calc(100% + 1px);
  border-top: 21px solid;
  border-color: inherit;
  opacity: 0.5;
}

.roleName-32vpEy {
  margin: 0 4px;
  z-index: unset !important;
}

.roleCircleButton-377y0l {
  padding: 0;
  position: absolute;
  z-index: 2;
  height: 22px;
  top: -1px;
  left: -1px;
  border-radius: 2px 0 0 2px;
  width: 0px;
  display: flex !important;
  transition: width 0.2s;
}

.roleCircle-3xAZ1j {
  display: none;
}

.addButton-pcyyf6 {
  line-height: 10px;
  width: 22px;
  box-sizing: border-box;
  height: 22px;
}

.roleRemoveIcon-2-TeGW {
  display: block;
  opacity: 0;
  transition: opacity 200ms ease-in-out;
}

.role-2irmRk:hover .roleCircleButton-377y0l {
  transition: width 0.2s;
  width: 22px;
}

.role-2irmRk:hover .roleRemoveIcon-2-TeGW {
  opacity: 1;
}

.addButtonIcon-1NMJ8u {
  height: 7px;
  width: 7px;
}

.note-3kmerW textarea:focus {
  background-color: var(--quaternary-color) !important;
}

.quickMessage-1yeL4E {
  background-color: var(--quaternary-color) !important;
  border-color: var(--quaternary-color) !important;
  border-radius: 0px !important;
}

.gameIcon-_0rmMm[style*="/assets/a5eba102f5b5e413df2b65c73f288afa.svg"] {
  background-image: url(https://monstrousdev.github.io/themes/assets/svgs/no-game.svg) !important;
  border: 2px solid rgba(255, 255, 255, .5);
  box-sizing: border-box;
}

  /* 15.e. Add Role User Popout */
.autocompleteArrow-Zxoy9H, 
.autocompleteHeaderBackground-30T70q,
.row-rrHHJU.selected-1pIgLL {
  background: var(--quaternary-color) !important;
}

.container-VSDcQc .headerText-3i6A8K,
.container-VSDcQc .input-1ppKdn {
  color: #666 !important;
}

.row-rrHHJU.selected-1pIgLL {
  border-left: 2px solid var(--main-color);
}

.container-VSDcQc .sectionTag-pXyto9 {
  background-color: var(--primary-color) !important;
}

  /* 15.f. Search Popout */
.popoutBottom-2GAFPg.noArrow-2foL9g {
  margin-top: -1px !important;
}

.popout-3sVMXz.popoutBottom-1YbShG.noShadow-321ZPm[style*="top: 37px;"] {
  top: 46px !important;
}

.container-3ayLPN.elevationBorderHigh-2WYJ09 {
  margin-top: -8px !important;
}

.searchPopout-1vUlP3,
.container-3ayLPN {
  background-color: var(--primary-color) !important;
  border-radius: 0 !important;
  border: none !important;
  border-left: 2px solid var(--main-color) !important;
  border-right: 2px solid var(--main-color) !important;
  border-bottom: 2px solid var(--main-color) !important;
}

.searchPopout-1vUlP3 .resultsGroup-r_nuzN,
.searchPopout-1vUlP3,
.container-3ayLPN {
  animation: popoutanim 300ms cubic-bezier(.4, 0, 0, 1), opacity 100ms ease 100ms backwards;
  transform-origin: 50% -10%;
  box-sizing: content-box;
}

.resultsGroup-r_nuzN .header-2N-gMV {
  background-color: var(--quaternary-color);
  padding: 10px 20px;
}

.resultsGroup-r_nuzN .searchClearHistory-2cSSMO,
.resultsGroup-r_nuzN .searchLearnMore-3SQUAj {
  top: 17px;
}

.option-96V44q,
.result-2S5Awv {
  border-left: 2px solid transparent;
  border-radius: 0px;
}

.option-96V44q:after,
.option-96V44q.selected-rZcOL-:after {
  display: none;
}

.queryContainer-RKFJW- {
  background-color: var(--quaternary-color) !important;
}

.option-96V44q.selected-rZcOL-,
.result-2S5Awv.focused-1Yu0L3 {
  background-color: var(--quaternary-color) !important;
  border-color: var(--hover-color);
}

.option-96V44q.searchQuery-1B7rtx.selected-rZcOL-,
.queryContainer-RKFJW- {
  border-color: transparent;
}

.dim-1l4L4y span {
  background-color: var(--main-color) !important;
  color: white !important;
}

.option-96V44q span {
  overflow: visible;
}

  /* 15.g. Server Settings */
.layer-v9HyYc[style*="; top: 5"][id*="popout_"] .menu-3sdvDG {
  left: -25px !important;
  top: -10px !important;
  width: 230px !important;
  height: auto;
  -ms-transform: none !important;
  transform: none !important;
  position: absolute;
  border-radius: 0px;
  transform-origin: 50% -10%;
  z-index: 99;
  overflow: visible !important;
  box-shadow: none;
}

.layer-v9HyYc[style*="; top: 5"][id*="popout_"] .itemBase-1Qj4z6 {
  margin: 0;
  padding: 10px 25px;
}

.layer-v9HyYc[style*="; top: 5"][id*="popout_"] .menu-3sdvDG {
  padding: 0;
  border-radius: 0px;
  width: 100%;
  border-left: 2px solid var(--main-color);
  border-right: 2px solid var(--main-color);
  border-bottom: 2px solid var(--main-color);
  animation: popoutanim 300ms cubic-bezier(.4, 0, 0, 1);
  transform-origin: 50% -10%;
  box-shadow: 0 5px 15px rgba(0, 0, 0, .5);
  box-sizing: border-box;
}

.menu-3sdvDG .separator-2I32lJ {
  display: none;
}

.item-1tOPte:hover,
.item-1tOPte.focused-3afm-j {
  background-color: var(--quaternary-color) !important;
}

.item-1tOPte:not([id*="invite-people"]):hover .icon-2doZ3q {
  filter: grayscale(100%) brightness(250%);
}

.item-1tOPte[id*="invite-people"] .icon-2doZ3q,
.item-1tOPte[id*="leave"] .icon-2doZ3q {
  background-image: none !important;
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-position: right;
}

.item-1tOPte[id*="invite-people"] .icon-2doZ3q {
  -webkit-mask: url("https://discordapp.com/assets/d4ff0d2af68cd1119f0d16ef79d1369c.svg");
  background-color: var(--main-color) !important;
}

.item-1tOPte[id*="leave"] .icon-2doZ3q {
  -webkit-mask: url("https://discordapp.com/assets/00de6b3cbb5c4dbcec817c91262f5f5b.svg");
  background-color: var(--dnd) !important;
  opacity: 0.7;
}

.item-1tOPte[id*="invite-people"] {
  color: var(--main-color) !important;
  font-weight: 600;
}

.item-1tOPte[id*="leave"] {
  color: var(--dnd) !important;
}

.item-1tOPte:hover[id*="invite-people"] .icon-2doZ3q {
  background-color: var(--hover-color) !important;
}

.item-1tOPte:hover[id*="leave"] .icon-2doZ3q {
  opacity: 1;
  filter: none !important;
}

.item-1tOPte:hover[id*="invite-people"] {
  color: var(--hover-color) !important
}

.popoutList-T9CKZQ {
  background-color: var(--tertiary-color) !important;
}

.searchBar-1MOL6S,
#app-mount .container-2XeR5Z {
  background-color: var(--quaternary-color) !important;
}

.selectableItem-1MP3MQ:hover {
  background-color: var(--quaternary-color) !important;
}

[style*="background: rgb(114, 137, 218)"] {
  background: var(--main-color) !important;
}

  /* 15.h. Group DM Invite Popout */
.modal-yWgWj- {
  background-color: var(--primary-color) !important;
}

.modal-yWgWj-.popout-103y-5 {
  margin-top: 3px;
  border-right: 2px solid var(--main-color);
  border-left: 2px solid var(--main-color);
  border-bottom: 2px solid var(--main-color);
  border-radius: 0px;
  transform-origin: 50% -10%;
  animation: popoutanim 300ms cubic-bezier(.4, 0, 0, 1), opacity 100ms ease 100ms backwards;
}

.modal-yWgWj- .searchBar-2_Yu-C {
  background-color: var(--quaternary-color) !important;
}

#app-mount .friendSelected-1sa4bG {
  background-color: var(--quaternary-color) !important;
}

.modal-yWgWj- .checked-3_4uQ9 {
  background-color: var(--main-color) !important;
  border-color: var(--hover-color) !important;
}

.tag-2gHSR7 {
  background: var(--secondary-color) !important;
}

.modal-yWgWj- .checked-3_4uQ9::after {
  content: '';
  position: absolute;
  height: 100%;
  width: 24px;
  background-color: #eee;
  -webkit-mask: url("https://monstrousdev.github.io/themes/assets/svgs/check.svg");
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-position: center;
  -webkit-mask-size: 95%;
}

.modal-yWgWj- .checked-3_4uQ9 svg,
.modal-yWgWj- .checked-3_4uQ9 g {
  display: none;
} 

  /* 15.i. Tooltips */
#app-mount  .tooltip-2QfLtc {
  border-radius: 0px !important;
  background: var(--main-color);
}

#app-mount .tooltipRed-8-9NeP {
  background-color: var(--dnd);
}

#app-mount .tooltipRed-8-9NeP .tooltipPointer-3ZfirK {
  border-top-color: var(--dnd);
}

#app-mount .tooltip-2QfLtc.tooltipGreen-WdeQwd {
  background: var(--online);
}

#app-mount .tooltipGreen-WdeQwd .tooltipPointer-3ZfirK {
  border-top-color: var(--online);
}

#app-mount .tooltipBlack-PPG47z .tooltipPointer-3ZfirK {
  border-top-color: var(--main-color);
}

/* tropix's fade in tooltip anim */

.layerContainer-yqaFcK .tooltip-2QfLtc.tooltipRight-2JM5PQ {
  animation: fadeFromRight 200ms
}

.layerContainer-yqaFcK .tooltip-2QfLtc.tooltipBottom-3ARrEK {
  animation: fadeFromBottom 200ms
}

.layerContainer-yqaFcK .tooltip-2QfLtc[class*="tooltipLeft-"] {
  animation: fadeFromLeft 200ms
}

.layerContainer-yqaFcK .tooltip-2QfLtc.tooltipTop-XDDSxx{
  animation: fadeFromTop 200ms;
}

  /* 15.j. @Everyone Popout */
.everyonePopout-nEbJY3{
	background-color: var(--secondary-color) !important;
}

.everyonePopout-nEbJY3 .footer-2aTx0s{
	background-color: var(--tertiary-color) !important;
}

.everyonePopout-nEbJY3 .lookOutlined-3sRXeN.colorBrand-3pXr91 {
	color: var(--main-color);
	border-color: var(--main-color);
	transition: all .2s ease-in-out;
}

.everyonePopout-nEbJY3 .lookOutlined-3sRXeN.colorBrand-3pXr91:hover {
	filter: grayscale(50%);
}

  /* 15.k. Attach Popout */
.attachPopout-1n-ZKM {
  background-color: var(--tertiary-color) !important;
}

.attachPopoutRow-KrE-f6:hover {
  background-color: var(--primary-color) !important;
}

  /* 15.l. RTC Connection Popout */
.popoutTopRight-3BzFIE section:before, 
.popoutTop-3uu9vG section:before,
.container-2x5lvQ section:after,
.popout-2GtBL-:after {
  border-top-color: var(--primary-color) !important;
}

  /* 15.m. More Users Popout */
.header-2B7Ri8,
.moreUsers-7v8yWY {
  background-color: var(--quaternary-color) !important;
}

.content-2KAjC9,
.userList-1kLH8B::before {
  background-color: var(--primary-color) !important;
}

.userList-1kLH8B,
.userList-1kLH8B::before {
  border-color: var(--primary-color) !important;
}

  /* 15.n. Overflow Roles Popout */
.overflowRolesPopout-140n9i, 
.overflowRolesPopoutArrow-2O66oH {
  background-color: var(--primary-color) !important;
}

  /* 15.o. Dropdown Menu Popout */
.popout-2sKjHu,
#app-mount .css-181m2lf-menu {
  background-color: var(--quaternary-color) !important;
  border-color: var(--quaternary-color) !important;
}

.optionActive-KkAdqq,
#app-mount .css-12o7ek3-option {
  background-color: var(--main-color) !important;
}

.optionLabel-2CkCZx,
#app-mount .css-181m2lf-menu .css-1ye7vu0 [class*="-option"] {
  border: 1px solid transparent;
}

.optionNormal-12VR9V:hover,
#app-mount .css-1gnr91b-option {
  background: transparent !important;
  border-color: var(--hover-color) !important
}

  /* 15.p. DM Call Region Select Popout */
.quickSelectPopout-X1hvgV {
  background-color: var(--primary-color) !important;
}

.quickSelectPopoutOption-opKBx9 {
  border: 1px solid transparent;
  box-sizing: border-box;
}

.quickSelectPopoutOption-opKBx9:hover {
  background-color: transparent !important;
  border-color: var(--main-color);
}

.check-2by_h9 {
  background-image: none !important;
  background-color: var(--main-color);
  -webkit-mask-image: url(https://monstrousdev.github.io/themes/assets/svgs/check.svg);
  -webkit-mask-size: 18px;
  -webkit-mask-position: center;
  -webkit-mask-repeat: no-repeat;
}

  /* 15.q. Guild Popout */
#app-mount .guildPopout-3CgKqR {
  background-color: var(--quaternary-color);
}

/* 16. Menus */
  /* 16.a. Context Menu */
.contextMenu-HLZMGh {
  background: var(--quaternary-color) !important;
  border-radius: 2px;
  padding: 10px 0px;
  box-shadow: 0 2px 25px rgba(0, 0, 0, 0.4) !important;
  animation: opacity 100ms ease, context-open-new 300ms cubic-bezier(0, 0, 0, 1);
  transform-origin: top;
  border: 1px solid var(--quaternary-color) !important;
}

.contextMenu-HLZMGh .itemGroup-1tL0uz:not(:first-child):not(:empty) {
  border-color: var(--quaternary-color) !important;
}

.theme-dark.contextMenu-HLZMGh .itemGroup-1tL0uz,
.theme-light.contextMenu-HLZMGh .itemGroup-1tL0uz {
  border-color: rgba(255, 255, 255, .03) !important
}

.contextMenu-HLZMGh .itemBase-tz5SeC {
  background: transparent !important;
  border-radius: 0px;
  transition: all 80ms ease;
  cursor: pointer;
  margin: 0px;
  padding: 7px 15px;
  color: #fff;
  animation: opacity 200ms 100ms backwards;
}

.contextMenu-HLZMGh .itemBase-tz5SeC:hover {
  background: rgba(225, 225, 225, 0.03) !important;
  color: #fff;
  transition: all 0ms;
}

.contextMenu-HLZMGh .itemBase-tz5SeC.danger-2dXSTE {
  color: rgb(180, 43, 43);
}

.contextMenu-HLZMGh .itemBase-tz5SeC.danger-2dXSTE:hover {
  color: #F04747 !important;
}

.contextMenu-HLZMGh .itemBase-tz5SeC.danger-2dXSTE:active {
  background: #F04747 !important;
  color: #fff !important;
}

.theme-dark.contextMenu-HLZMGh .itemSubMenu-1vN_Yn,
.theme-light.contextMenu-HLZMGh .itemSubMenu-1vN_Yn {
  position: relative;
}

.contextMenu-HLZMGh .slider-1PF9SW .track-11EASc {
  right: 0px !important;
  left: 3px !important;
}

.contextMenu-HLZMGh .slider-1PF9SW .bar-2Qqk5Z {
  height: 3px
}

.item-1Yvehc.itemSubMenu-1vN_Yn::after {
  content: url(https://monstrousdev.github.io/themes/assets/svgs/arrow.svg);
  position: absolute;
  right: 5px;
  opacity: .6;
  transition: all 100ms ease;
  top: 5px;
}

.item-1Yvehc.itemSubMenu-1vN_Yn:hover::after {
  opacity: 1;
}

  /* 16.b. Status Picker */
  .popout-3sVMXz.popoutTop-3uu9vG,
  .popout-3sVMXz.popoutTopLeft-b5Eb3O {
    overflow: visible !important;
  }
  
  .popoutBottom-2GAFPg.noArrow-2foL9g[style*="z-index: 20"] {
    margin-top: 10px !important;
  }
  
  .popout-3sVMXz.popoutTopLeft-b5Eb3O {
    margin-left: -10px;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG {
    animation: show-status 300ms linear;
    border: none;
    width: 240px;
    height: 68px;
    padding: 0;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .scroller-3BxosC {
    padding: 0;
    overflow: visible;
  }
  
  .layer-v9HyYc[style*="; bottom: "][id*="popout_"] .menu-3sdvDG {
    position: fixed;
    left: -10px !important;
    bottom: -5px !important;
  }
  
  .popoutTopLeft-3B0mFf.noArrow-2foL9g[style*="height: 80px;"] {
    height: 100px !important;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:not(:nth-child(7)) .status-1fhblQ {
    color: transparent;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte .description-2L932D,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .separator-2I32lJ {
    display: none;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte {
    position: relative;
    display: inline-block;
    width: 58px;
    height: 68px;
    vertical-align: top;
    background: transparent;
    overflow: hidden;
    transform: perspective(1px) scale(1);
    animation: status 300ms ease backwards;
    margin: 0;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte .statusItem-33LqPf {
    display: block;
    position: relative;
    height: 100%;
    width: 100%;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(3) {
    animation-delay: 100ms !important;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(4) {
    animation-delay: 200ms !important;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(5) {
    animation-delay: 300ms !important;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:hover {
    background: transparent !important;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(7) {
    background-color: var(--primary-color);
    width: 100%;
    transition: color 200ms ease-in, background-color 200ms ease-in;
    z-index: -1;
    position: absolute;
    height: 35px;
    margin-top: -35px;
    box-shadow: 0 2px 20px var(--shadow) !important;
    transform: translateX(0%) translateY(100%) translateZ(0);
    animation: show-custom 300ms ease forwards 400ms;
    opacity: 0;
    pointer-events: none;
    top: 0;
    display: flex;
    flex-flow: row nowrap;
    justify-content: space-between;
  }
  
  .clearStatusButton-1Mxs1q {
    width: fit-content;
    margin-left: auto;
  }
  
  .customStatusContentIcon-2sionu {
    height: 100%;
    width: 100%;
    justify-content: center;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(7):hover {
    background-color: var(--quaternary-color) !important;
    color: var(--main-color);
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(7) > div {
    position: relative;
    width: 100%;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(7) .customStatusWithEmoji-8-XZ8I,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(7) .statusItem-33LqPf {
    display: flex;
    flex-flow: row wrap;
    justify-content: flex-start;
    padding: 0 15px;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(7) .status-1fhblQ,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(7) .customText-tY5LJn {
    margin-left: 10px;
    max-width: 75%;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:hover .icon-1IxfJ2 {
    transform: scale(1.9);
    transition: all 200ms ease-in-out;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte .icon-1IxfJ2 {
    position: absolute;
    width: 40px;
    height: 40px;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: auto !important;
    border-radius: 50%;
    transform: scale(1);
    transition: all 200ms ease-in-out;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(1) .icon-1IxfJ2,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(1):hover .icon-1IxfJ2 {
    color: var(--online);
    border-radius: 0;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(3) .icon-1IxfJ2,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(3):hover .icon-1IxfJ2 {
    color: var(--idle);
    border-radius: 0;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(4) .icon-1IxfJ2,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(4):hover .icon-1IxfJ2 {
    color: var(--dnd);
    border-radius: 0;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(5) .icon-1IxfJ2,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(5):hover .icon-1IxfJ2 {
    color: var(--invisible);
    border-radius: 0;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:hover [class*="status"].online-2S838R:after,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:hover [class*="status"].idle-3DEnRT:after,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:hover [class*="status"].dnd-1_xrcq:after,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:hover [class*="status"].invisible-1kp8Z0:after {
    opacity: 1;
    visibility: visible;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte [class*="status"].online-2S838R:after,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte [class*="status"].idle-3DEnRT:after,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte [class*="status"].dnd-1_xrcq:after,
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte [class*="status"].invisible-1kp8Z0:after {
    content: " ";
    display: block;
    position: absolute;
    width: 26px;
    height: 26px;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: auto !important;
    background-size: 100% 100%;
    background-repeat: no-repeat;
    background-position: center;
    opacity: 0;
    visibility: hidden;
    transition: all 200ms ease-in-out;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:not(:nth-child(7)) .status-1fhblQ {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background-position:center;
    background-size: 40px;
    background-repeat: no-repeat;
    opacity: 0;
    transition: all 200ms ease-in-out;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:hover:not(:nth-child(7)) .status-1fhblQ {
    opacity: 1;
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(1) .status-1fhblQ {
    background-image: url(https://monstrousdev.github.io/themes/assets/status/online.svg);
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(3) .status-1fhblQ {
    background-image: url(https://monstrousdev.github.io/themes/assets/status/idle.svg);
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(4) .status-1fhblQ {
    background-image: url(https://monstrousdev.github.io/themes/assets/status/dnd.svg);
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte:nth-child(5) .status-1fhblQ {
    background-image: url(https://monstrousdev.github.io/themes/assets/status/invisi.svg);
  }
  
  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-3sdvDG .item-1tOPte .icon-1IxfJ2 .status-oxiHuE {
    position: absolute !important;
    top: 0;
    left: 0;
    height: 100% !important;
    width: 100% !important;
    margin-right: 0px !important;
    transition: all 200ms ease-in-out;
  }

  /* 16.c. Message Menu */
.container-3cGP6G {
  background-color: var(--tertiary-color) !important;
}

.item-2J1YMK:active, 
.item-2J1YMK:hover {
  background-color: var(--quaternary-color) !important;
}

  /* 16.d. Color Picker */
.colorPickerCustom-2CWBn2 {
  background-color: var(--primary-color) !important;
  border-color: var(--quaternary-color) !important;
}




/* 17. Modals */
  /* 17.a. BD Error Modal */

  .bd-modal-wrapper .bd-modal-inner {
    border-color: var(--tertiary-color);
  }
  
  .bd-modal-wrapper .header {
    background-color: var(--quaternary-color);
  }
  
  .bd-modal-wrapper .bd-modal-body,
  .bd-modal-wrapper .footer {
    background-color: var(--primary-color) !important;
  }
  
  .bd-modal-wrapper .footer button {
    background-color: var(--main-color);
  }
  
  .bd-modal-wrapper .footer button:hover {
    background-color: var(--hover-color);
  }
  
  .bd-modal-wrapper .tab-bar-container .tab-bar-item.selected {
    text-align: center;
  }

  /* 17.b. User Profile Modal */

.tabBarContainer-1s1u-z {
  border-color: transparent;
}

.topSectionNormal-2-vo2m  .tab-bar.tabBar-2MuP6- .tabBarItem-1b8RUP.selected {
  border-bottom-color: var(--main-color);
  color: var(--main-color);
}

.topSectionNormal-2-vo2m .tab-bar.tabBar-2MuP6- .tabBarItem-1b8RUP:hover {
  border-bottom-color: var(--hover-color);
  color: var(--hover-color);
  transition: all .2s ease-in-out;
}

.topSectionPlaying-1J5E4n {
  background: var(--main-color);
}

.topSectionPlaying-1J5E4n .top-28JiJ- .itemSelected-1qLhcL {
  color: #eee !important;
}

.body-3ND3kc {
  background-color: var(--primary-color) !important;
}

.connectedAccount-36nQx7 {
  background-color: var(--quaternary-color);
  border-color: var(--quaternary-color) !important;
}

.root-SR8cQa .note-QfFU8y textarea:focus {
  background-color: var(--quaternary-color) !important;
}

.listRow-hutiT_:hover {
  background: linear-gradient(90deg,var(--tertiary-color) 90%,transparent) !important;
}

.listRow-hutiT_ .listAvatar-1NlAhb {
  transition: transform .2s ease-in-out;
}

.listRow-hutiT_:hover .listAvatar-1NlAhb {
  transform: scale(1.1);
}

  /* 17.c. Instant Invite Modal */
#app-mount .modal-3v8ziU,
#app-mount .modal-yWgWj- {
  background-color: var(--primary-color);
}

.inviteRow-2L02ae:hover {
  background-color: var(--tertiary-color) !important;
}

.inviteRow-2L02ae .wrapper-2F3Zv8 {
  transition: transform 0.2s ease-in-out;
}

.inviteRow-2L02ae:hover .wrapper-2F3Zv8 {
  transform: scale(1.2);
}

.inviteRowInfo-I9V9v- {
  overflow: visible;
}

.contentWrapper-3WC1ID {
  background-color: var(--primary-color) !important;
}

  /* 17.d. Join or Create New Guild */
.sampleLink-KPFu3I,
.title-2Dc-Cb,
.theme-dark .header-3ZP1MY, 
.theme-light .header-3ZP1MY,
.theme-dark .action-1lSjCi, 
.theme-light .action-1lSjCi,
.theme-dark .create-3jownz .actionHeader-2CT5c7, 
.theme-light .create-3jownz .actionHeader-2CT5c7
.action-1lSjCi:hover .actionHeader-2CT5c7,
.create-3jownz .colorStandard-2KCXvj,
.heading-bH--BU,
.title-1NPKvY,
.sidebarContainer-1ZTKHt .protip-2rGG0r .colorStandard-2KCXvj,
.title-1EYJBg {
  color: var(--main-color) !important;
}

.join-33Tr-7 .colorStandard-2KCXvj {
  color: var(--online);
}

.theme-light .slide-2pHaq5, 
.theme-dark .slide-2pHaq5,
.theme-dark .theme-light .slide-2pHaq5 {
   background-color: var(--primary-color);
  }

.theme-dark .theme-dark .actionIcon-2IISM_, 
.theme-dark .theme-light .actionIcon-2IISM_ {
  filter: none;
}

.theme-dark .create-3jownz .actionIcon-2IISM_, 
.theme-light .create-3jownz .actionIcon-2IISM_ {
  position: relative;
  background-image: none;
  background-color: var(--main-color);
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/svgs/add-btn.svg) center/112px 78px no-repeat;
}

.theme-dark .create-3jownz .actionIcon-2IISM_::after, 
.theme-light .create-3jownz .actionIcon-2IISM_::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background: white;
  opacity: .4;
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/svgs/add-btn-two.svg) center/112px 78px no-repeat;
}

.theme-dark .join-33Tr-7 .actionIcon-2IISM_, 
.theme-light .join-33Tr-7 .actionIcon-2IISM_ {
  background-image: url(https://monstrousdev.github.io/themes/assets/images/join-btn.png);
}

.theme-dark .channelListContainer-1VKoaZ {
  background-color: var(--secondary-color);
}

.unreadIndicator-2zrk6b {
  background-color: var(--main-color)
}

.channelNameUnread-1J_UP0 {
  color: #fff;
}

#app-mount .modal-yWgWj- .footer-3rDWdC {
  box-shadow: inset 0 1px 0 rgba(0,0,0,0.6)
}

.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover {
  background-color: var(--primary-color) !important;
}

.theme-dark .regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce, 
.theme-dark .regionSelect-3lf4eE:hover button, 
.theme-light .regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce, 
.theme-light .regionSelect-3lf4eE:hover button {
  border-color: var(--main-color);
}

.theme-dark .regionSelect-3lf4eE:hover button, 
.theme-light .regionSelect-3lf4eE:hover button {
  background-color: var(--main-color);
}

.theme-dark .action-1lSjCi, 
.theme-light .action-1lSjCi,
.theme-dark .theme-dark .action-1lSjCi, 
.theme-dark .theme-light .action-1lSjCi {
  background: var(--tertiary-color);
  border-color: var(--secondary-color);
}

.form-deprecated .btn-primary, 
.form.deprecated .btn-primary,
.theme-dark .actionButton-2PeQbJ, 
.theme-light .actionButton-2PeQbJ {
  background-color: var(--main-color);
}

.form-deprecated .btn-primary:hover, 
.form.deprecated .btn-primary:hover,
.theme-dark .create-3jownz:hover .actionButton-2PeQbJ, 
.theme-light .create-3jownz:hover .actionButton-2PeQbJ {
  background-color: var(--hover-color);
}

.avatar-uploader-inner {
  background-color: var(--main-color);
  border-color: var(--quaternary-color);
}

.regionSelect-3lf4eE .regionSelectInner-24f4Ce,
.regionSelect-3lf4eE button {
  border-color: var(--quaternary-color);
}

.regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce,
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover,
.regionSelect-3lf4eE:hover button,
.form-deprecated .btn-default:hover, 
.form.deprecated .btn-default:hover {
  border-color: var(--hover-color);
}

.regionSelect-3lf4eE button,
.create-guild-container-new.deprecated h5,
.regionSelectModal-12e-57 .regionSelectModalHeader-21khC1 {
  color: var(--main-color);
}

#app-mount .regionSelect-3lf4eE:hover button {
  background-color: var(--hover-color);
  color: white;
}

.form-deprecated .form-actions, 
.form.deprecated .form-actions,
#app-mount .regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3 {
  background-color: var(--quaternary-color);
  border-color: var(--tertiary-color);
}

.form-deprecated .btn-default, 
.form.deprecated .btn-default {
  background-color: transparent;
  border-color: var(--tertiary-color);
}

#guild-name { text-align: center }

.bottomLayer-XCk80b.hover-3nZwuJ {
	fill: var(--hover-color) !important;
	fill-opacity: 0.8;
}

.topLayer-1eMqbv.hover-3nZwuJ,
.secondaryAccent-24W-RJ.hover-3nZwuJ {
	fill: var(--main-color) !important;
}

.topLayer-1eMqbv.hover-3nZwuJ.green-1kY_LT,
.bottomLayer-XCk80b.hover-3nZwuJ.green-1kY_LT,
.secondaryAccent-24W-RJ.hover-3nZwuJ.green-1kY_LT {
	fill: var(--online) !important;
}

.lookFilled-1Gx00P.colorGreen-29iAKY {
	background-color: var(--online);
}

.lookFilled-1Gx00P.colorGreen-29iAKY:hover {
	filter: brightness(80%);
}

  /* 17.e. Upload Modal */
#app-mount .uploadModal-2ifh8j {
  background-color: var(--main-color);
}

.uploadModal-2ifh8j .inner-3nWsbo {
  border-color: rgba(255,255,255,0.4);
}

.uploadModal-2ifh8j .footer-3mqk7D {
  background-color: var(--hover-color);
  color: white;
}

.theme-brand .content-Qb0rXO {
  color: white;
}

.uploadModal-2ifh8j .footer-3mqk7D button[type*="button"] .contents-18-Yxp {
  display: none;
}

.uploadModal-2ifh8j .footer-3mqk7D button {
  background-color: transparent;
  min-width: 36px;
  max-width: 36px;
  margin-top: -3px;
  margin-right: 5px;
  transition: all .2s ease-in-out;
  color: transparent;
}

.uploadModal-2ifh8j .footer-3mqk7D button[type*="submit"] {
  -webkit-mask-image: url(https://monstrousdev.github.io/themes/assets/svgs/check.svg);
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-position: center;
  background-color: rgba(33, 219, 135, 0.6);
}

.uploadModal-2ifh8j .footer-3mqk7D button[type*="button"] {
  -webkit-mask: url(https://monstrousdev.github.io/themes/assets/svgs/cancel.svg);
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-position: center;
  background-color: rgba(240, 71, 71, 0.6);
}

.uploadModal-2ifh8j .footer-3mqk7D button[type*="submit"]:hover {
  background-color: #21db87 !important;
  transform: scale(1.5);
}

.uploadModal-2ifh8j .footer-3mqk7D button[type*="button"]:hover {
  background-color: #f04747;
  transform: scale(1.5);
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.image-2yrs5j {
  border-color: var(--hover-color);
  margin-top: 0;
  transform: translateY(-50%);
  transition: all .3s ease-in-out;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.image-2yrs5j:hover {
  height: 208px;
  width: calc(100% - 28px);
  transform: translateY(calc(-50% - 10px));
}

.invite-18yqGF {
  background: var(--quaternary-color) !important;
  border: none !important;
}

.coverImageNotActionable-1MP2Mx {
  opacity: 0.5;
}

  /* 17.f. Game Preview Modal */
.gamePreview-9weYR2,
.footer-3J5oP4,
#app-mount .popout-3sVMXz .news-2KwXHF {
  background-color: var(--quaternary-color) !important;
} 

.body-1SVoBw {
  background-color: var(--secondary-color) !important;
}

.news-2KwXHF {
  background-color: var(--secondary-color) !important;
}

#app-mount .player-3zB-0D:hover {
  background-color: var(--quaternary-color);
}

  /* 17.g. Quick Switcher */
#app-mount .scroller-zPkAnE {
  background: transparent;
}

.input-2VB9rf {
  background-color: var(--quaternary-color) !important;
}

.resultFocused-3aIoYe {
  background-color: var(--tertiary-color) !important;
}

  /* 17.h. Screenshare Modal */
.tiles-2aXG_k,
.tile-2silOL:hover .sourceThumbnail-14Iubx {
  background-color: var(--quaternary-color) !important;
}

.tile-2silOL:hover .sourceThumbnail-14Iubx {
  -webkit-box-shadow: inset 0 0 0 2px #7289da;
  box-shadow: inset 0 0 0 2px #7289da;
}

.selectorButtonSelected-1j4DmC {
  background-color: var(--main-color);
}

.item-1TLUig:hover {
  border-bottom: 2px solid var(--hover-color);
  color: var(--hover-color);
}

.selected-P8xTeN {
  border-color: var(--main-color) !important;
  color: var(--main-color) !important;
}

  /* 17.i. Phone Verification Modal */
.phoneField-38N1bJ {
  background-color: var(--quaternary-color) !important;
}

.phoneField-38N1bJ .countryButton-3xq3Ts {
  background-color: var(--main-color) !important;
}

.phoneField-38N1bJ .countryButton-3xq3Ts:hover {
  background-color: var(--hover-color) !important;
}

.phoneField-38N1bJ .inputField-aNPXsv {
  background: transparent !important;
}

  /* 17.j. Smartphone Modal */
.downloadApps-wbBFdZ .header-nJMe-Q,
.downloadApps-wbBFdZ .footer-1nkeBm a {
  color: var(--main-color);
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236.active-iLSdWQ p {
  color: var(--hover-color);
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236.active-iLSdWQ {
  border-color: var(--hover-color);
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236.active-iLSdWQ .downloadButton-1bWXpg {
  background-color: var(--hover-color);
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236 .icon-2Pk7pb {
  background-image: none !important;
  background-color: #99aab5;
  -webkit-mask-size: cover;
  -webkit-mask-position: center;
  -webkit-mask-repeat: no-repeat;
  transition: all .2s ease-in-out;
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236.active-iLSdWQ .icon-2Pk7pb {
    background-color: var(--hover-color);
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236.active-iLSdWQ .icon-2Pk7pb {
  opacity: 1 !important;
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236.active-iLSdWQ .icon-2Pk7pb.active-iLSdWQ {
  display: none !important;
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236 .icon-2Pk7pb.apple-1fKN59 {
  -webkit-mask-image: url(https://discordapp.com/assets/57568e1cfc37c81cf56db9498b4f128a.svg);
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236 .icon-2Pk7pb.windows-29yOum {
  -webkit-mask-image: url(https://discordapp.com/assets/d6221c5e88f5cb89f125868c077e9859.svg)
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236 .icon-2Pk7pb.linux-15cW1y {
  -webkit-mask-image: url(https://discordapp.com/assets/a3bee2061afed80c5bd76ff38cd18f0e.svg);
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236 .icon-2Pk7pb.ios-Z7K-rr {
  -webkit-mask-image: url(https://discordapp.com/assets/0c460e9b848f5c4cc964ae9c62c0f9b9.svg);
}

.downloadApps-wbBFdZ .platforms-28Rb-3 .platform-iik236 .icon-2Pk7pb.android-gGrHJu {
  -webkit-mask-image: url(https://discordapp.com/assets/676bfec9f4343f6fcdf0a12ae313a3de.svg);
}

  /* 17.k Drag and Drop Modal */
.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .bgScale-1otPtc {
  background: var(--main-color);

}

  /* 17.l. Generic Modal */
  #app-mount .modal-yWgWj-, 
  #app-mount .root-1gCeng {
    background-color: var(--primary-color);
  }

  #app-mount .footer-3rDWdC {
    background-color: var(--quaternary-color);
  }

.footer-2yfCgX {
  box-shadow: inset 0 1px 0 var(--tertiary-color) !important;
}

.select-2TCrqx .Select-menu-outer {
  background: var(--primary-color) !important;
  border-color: var(--quaternary-color) !important;
}

.select-2TCrqx .Select-option.is-focused, 
.select-2TCrqx .Select-option:hover {
  background: var(--secondary-color) !important;
}

.select-2TCrqx .Select-control {
  background-color: var(--quaternary-color) !important;
  border-color: var(--tertiary-color) !important;
}

.select-2TCrqx .Select-option.is-selected {
  background: var(--quaternary-color) !important;
}

.lookLink-9FtZy-.colorBrand-3pXr91:hover .contents-18-Yxp {
  background-image: linear-gradient(0deg,transparent,transparent 1px,var(--main-color) 0,var(--main-color) 2px,transparent 0)
}

.contentWrapper-3WC1ID:only-child {
  background-color: var(--primary-color) !important;
}

  /* 17.m. Gift Nitro Modal & Nitro Boost */
.option-1l2vXE,
.table-39R0Oe,
#app-mount .perk-2WeBWW,
#app-mount .tierNoneContainer-3hhK3h,
#app-mount .tierBody-16Chc9,
#app-mount .tierBody-x9kBBp,
#app-mount .header-Qk7iwL,
#app-mount .tierInProgress-3mBoXq,
#app-mount .barBackground-2EEiLw,
#app-mount .tierMarker-5HkGJ_[style*="linear-gradient(to right, rgb(32, 34, 37), rgb(32, 34, 37))"],
#app-mount .boostCount-UFqabz,
#app-mount .guildGraphicBackground-wbfC17, 
#app-mount .guildGraphicContainer-_IAetM,
#app-mount .subscriptionDuration-3WXA_o,
#app-mount .tierPill-1yRO48,
#app-mount .info-3UT5_W,
.guildSubscriptionSlots-JPXXvN,
#app-mount .ctaBar-2UsjF2 {
  background-color: var(--quaternary-color) !important;
}

#app-mount .tierMarker-5HkGJ_[style*="linear-gradient(to right, rgb(32, 34, 37), rgb(32, 34, 37))"] {
  background-image: none !important;
}

#app-mount .info-3NKfPL,
#app-mount .tierHeaderLocked-1a2opw,
#app-mount .tierHeaderLocked-1s2JJz,
.guildHeader-3nh5RK {
  background-color: var(--secondary-color);
}

.cardWrapper-2Min21 {
  background: transparent;
}



#app-mount .background-3xPPFc,
#app-mount .gemIndicatorContainer-2jdECl {
  color: var(--quaternary-color);
}

#app-mount .carouselRightGradientEdge-2Z3H8D {
  background-image: linear-gradient(270deg,var(--quaternary-color),transparent);
}

#app-mount .carouselLeftGradientEdge-3P4spl {
  background-image: linear-gradient(90deg,var(--quaternary-color),transparent);
}

  /* 17.n. Server Templates */
.ctaSection-izWwhs,
.formSection-1NFAGI {
  background: transparent;
}

.usagePill-_nSrnP,
.channelsWrapper-2HhUER, 
.rolesWrapper-2yOx9S {
  background: var(--quaternary-color);
}

/* 18. Login Page */
.input-cIJ7To:focus {
  border-color: var(--hover-color);
}

.authBox-hW6HRx {
  background: var(--primary-color);
}

.lookLink-9FtZy-.colorBrand-3pXr91 {
  color: var(--main-color)
}

.wrapper-3Q5DdO {
  background: var(--primary-color) !important;
}

.input-cIJ7To {
  background-color: var(--quaternary-color) !important;
}





/* 19. Keyframes */

@keyframes fadeFromTop {
  0% {
      opacity: 0;
      transform: translateY(-50%)
  }
  100% {
      opacity: 0.9;
      transform: none
  }
}

@keyframes fadeFromRight {
  0% {
      opacity: 0;
      transform: translateX(50%)
  }
  100% {
      opacity: 0.9;
      transform: none
  }
}

@keyframes fadeFromBottom {
  0% {
      opacity: 0;
      transform: translateY(50%)
  }
  100% {
      opacity: 0.9;
      transform: none
  }
}

@keyframes fadeFromLeft {
  0% {
      opacity: 0;
      transform: translateX(-50%)
  }
  100% {
      opacity: 0.9;
      transform: none
  }
}

@keyframes slide-up {
  from {
    transform: translate(0, 100%);
  }
}

@keyframes slide-down {
  from {
    transform: translate(0, -100%);
  }
}

@keyframes slide-left {
  from {
    transform: translate(-100);
  }
}

@keyframes slide-right {
  from {
    transform: translate(100%);
  }
}

@-webkit-keyframes mentionpulse {
  0% {
    -webkit-box-shadow: 0 0 0 0 var(--main-color);
  }
  70% {
    -webkit-box-shadow: 0 0 0 5px rgba(204, 169, 44, 0);
  }
  100% {
    -webkit-box-shadow: 0 0 0 0 rgba(204, 169, 44, 0);
  }
}

@keyframes show-status {
  from {
    transform: translateY(100%) translateX(0%) translateZ(0px);
  }
}

@keyframes status {
  from {
    transform: perspective(1px) scale(0);
    opacity: 0
  }
}

@keyframes context-open-invertY {
  0% {
    padding-top: 0px;
    padding-bottom: 0px;
    margin-top: 0px;
  }
}

@keyframes context-open-new {
  0% {
    transform: scale(1, 0.8);
  }
}

@keyframes context-open {
  0% {
    padding-top: 0px;
    padding-bottom: 0px;
  }
}

@keyframes popoutanim-inner {
  0% {
    transform: scale(2);
  }
  100% {
    transform: scale(1);
  }
}

@keyframes popoutanim {
  0% {
    transform: scale(0) perspective(1px);
  }
  100% {
    transform: scale(1) perspective(1px);
  }
}

@keyframes show-custom {
  to {
    opacity: 1;
    transform: translateY(0) translateX(0%) translateZ(0px);
    pointer-events: all;
  }
}





/* 20. Misc */
.form-deprecated .control-group input[type=email], 
.form-deprecated .control-group input[type=number], 
.form-deprecated .control-group input[type=password], 
.form-deprecated .control-group input[type=text], 
.form-deprecated .control-group textarea, 
.form.deprecated .control-group input[type=email], 
.form.deprecated .control-group input[type=number], 
.form.deprecated .control-group input[type=password], 
.form.deprecated .control-group input[type=text], 
.form.deprecated .control-group textarea,
.gameNameInput-385LoS:focus,
.gameNameInput-385LoS:hover {
  background-color: var(--quaternary-color) !important;
  border-color: var(--quaternary-color);
}

.theme-dark .form-deprecated .control-group input[type=email],
.theme-dark .form-deprecated .control-group input[type=number],
.theme-dark .form-deprecated .control-group input[type=password],
.theme-dark .form-deprecated .control-group input[type=text],
.theme-dark .form-deprecated .control-group textarea,
.theme-dark .form.deprecated .control-group input[type=email],
.theme-dark .form.deprecated .control-group input[type=number],
.theme-dark .form.deprecated .control-group input[type=password],
.theme-dark .form.deprecated .control-group input[type=text],
.theme-dark .form.deprecated .control-group textarea
.theme-dark .gameNameInput-385LoS:focus, 
.theme-dark .gameNameInput-385LoS:hover {
  color: #efefef;
}

.theme-light .form-deprecated .control-group input[type=email],
.theme-light .form-deprecated .control-group input[type=number],
.theme-light .form-deprecated .control-group input[type=password],
.theme-light .form-deprecated .control-group input[type=text],
.theme-light .form-deprecated .control-group textarea,
.theme-light .form.deprecated .control-group input[type=email],
.theme-light .form.deprecated .control-group input[type=number],
.theme-light .form.deprecated .control-group input[type=password],
.theme-light .form.deprecated .control-group input[type=text],
.theme-light .form.deprecated .control-group textarea,
.theme-light .gameNameInput-385LoS:focus, 
.theme-light .gameNameInput-385LoS:hover {
  color: #101010;
}

.form-deprecated .control-group input[type=email]:focus,
.form-deprecated .control-group input[type=number]:focus,
.form-deprecated .control-group input[type=password]:focus,
.form-deprecated .control-group input[type=text]:focus,
.form-deprecated .control-group textarea:focus,
.form.deprecated .control-group input[type=email]:focus,
.form.deprecated .control-group input[type=number]:focus,
.form.deprecated .control-group input[type=password]:focus,
.form.deprecated .control-group input[type=text]:focus,
.form.deprecated .control-group textarea:focus,
.imageSelected-4Kl81J {
  border-color: var(--main-color);
}

.message-2qRu38 {
  background-color: var(--tertiary-color) !important;
}

.tile-2gi3tr {
  background-color: transparent;
}

.button-3WOKuZ {
  background-color: var(--main-color);
}

.botTagRegular-2HEhHi,
.aka-1mqp34,
#app-mount .akaBadge-1M-1Gw,
.wanderingCubesItem-WPXqao,
#pubslayer .ui-tab-bar-item.selected,
.bd-server-card.bd-server-card-pinned:after,
.keybindShortcut-1BD6Z1 span {
  background-color: var(--main-color) !important;
}

.mediaBarInteractionDragging-2QurIZ .mediaBarGrabber-1FqnbN,
.mediaBarProgress-1xaPtl,
.mediaBarProgress-1xaPtl:after,
.mediaBarProgress-1xaPtl:before,
.mediaBarInteraction-37i2O4:hover .mediaBarGrabber-1FqnbN,
#app-mount .barForeground-3KglC8,
.theme-dark .categoryFadeBlurple-1j72_A, 
.theme-light .categoryFadeBlurple-1j72_A {
  background-color: var(--main-color);
}

.content-N9xlZF {
  background: var(--main-color);
}

.theme-dark .categoryFadeBlurple-1j72_A, 
.theme-light .categoryFadeBlurple-1j72_A {
  opacity: 0.8;
}

.elevationHigh-1PneE4,
.styleFixed-sX-yHV,
.styleFlexible-wGDiIL {
  background-color: var(--primary-color) !important;
}

.bubble-3we2di,
#pubslayer .ui-tab-bar-item.selected:hover,
.theme-dark .categoryFadeBlurple-1j72_A:hover, 
.theme-light .categoryFadeBlurple-1j72_A:hover {
  background-color: var(--hover-color) !important;
}

.bubble-3we2di:before {
  border-top-color: var(--hover-color) !important;
}

.input-cIJ7To:focus,
.input-cIJ7To.focused-1mmYsC {
  border-color: var(--main-color) !important;
}

.connectedAccountVerifiedIcon-3aZz_K g path:nth-child(2),
.verified-3uJH7V g path:nth-child(2),
.verified-2-ja4L g path:nth-child(2),
.verifiedIcon-2TCIsJ g path:nth-child(2),
.verifiedIcon-1vpk3S path:nth-of-type(2),
#app-mount .iconTierNone-3xOaeG,
.verified-1eC5dy path[fill="#4f545c"],
.verifiedIcon-3oz8wo path[fill="#7289da"]
.gameVerifiedIcon-2dGGa5 path[fill="#7289da"] {
  fill: var(--main-color) !important;
}

.verifiedIcon-3oz8wo,
.verified-1eC5dy,
.lookInverted-2D7oAl.colorBrand-3pXr91 {
color: var(--main-color) !important;
}

.lookInverted-2D7oAl.colorGreen-29iAKY {
  color: var(--online) !important;
}

#app-mount .iconBackgroundTierOne-2LhaMB,
#app-mount .iconBackgroundTierThree-3qw3JX, 
#app-mount .iconBackgroundTierTwo-3bCmdc, 
#app-mount .iconBackgroundTierNone-3MPhMJ {
  color: white;
}

#app-mount .header-2o-2hj .premiumGuildIconGem-C4yUDR {
  margin-top: 1px;
}

.input-autosize-input:focus,
.themeDefault-24hCdX {
  background-color: var(--quaternary-color) !important;
}

.number-3ceIrJ {
  background-color: var(--quaternary-color) !important;
  border-color: var(--tertiary-color) !important;
}

.foreground-2aE44H {
  stroke: var(--main-color) !important;
}

.lookFilled-1Gx00P.colorGrey-2DXtkV:disabled {
  background: var(--primary-color);
}

.lookFilled-1Gx00P.colorGrey-2DXtkV {
  background: var(--secondary-color);
}

.lookGhost-2Fn_0-.colorGrey-2DXtkV .contents-18-Yxp {
  position: relative;
  background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), var(--main-color);
  background-clip: text;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  color: transparent;
}

.lookGhost-2Fn_0- .contents-18-Yxp {
  transition: color 500ms ease-in-out;
}

.lookGhost-2Fn_0-.colorGrey-2DXtkV {
  background: var(--main-color);
}

.lookGhost-2Fn_0-::before {
  position: absolute;
  content: "";
  height: 100%;
  width: 100%;
  top: 0;
  left: 0;
  background: linear-gradient(rgba(0,0,0,0.1), rgba(0,0,0,0.1)), var(--primary-color);
  opacity: .9;
  transition: all 500ms ease-in-out;
}

.lookGhost-2Fn_0-.colorBrand-3pXr91 .contents-18-Yxp {
  position: relative;
  color: var(--main-color);
  z-index: 1;
}

.lookGhost-2Fn_0-.colorBrand-3pXr91 {
  background: var(--main-color);
}

.lookGhost-2Fn_0-.colorBrand-3pXr91::before {
  opacity: .8;
}

.lookFilled-1Gx00P.colorGrey-2DXtkV:hover {
  background: var(--primary-color);
}

.path2-1q7bG_,
.path-92Hmty {
  stroke: var(--hover-color) !important;
}

.path3-2l9TIX {
  stroke: var(--main-color) !important;
}

.bda-slist .bda-footer a {
  color: var(--main-color);
}

.actionRed-gYn8D3 {
  background-color: var(--dnd);
  transition: all .2s ease-in-out;
}

.actionRed-gYn8D3:hover {
  background-color: var(--dnd);
  transform: scale(1.08);
}

.actionRed-gYn8D3:active {
    background-color: var(--dnd);
    filter: brightness(0.5);
    transform: scale(0.9);
}

.themeDark-3Ap_7i {
  background-color: var(--primary-color);
}

.ragingDemon-bDcoXE {
  background-color: var(--primary-color);
}

.symbol-3ffeCr {
  background-color: var(--main-color);
  -webkit-mask-image: url(https://monstrousdev.github.io/themes/assets/svgs/demon-fill.svg);
  -webkit-mask-position: center;
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-size: 80vw 60vh;
}

.symbol-3ffeCr img {
  display: none;
}

.symbol-3ffeCr::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #231F1F;
  -webkit-mask-image: url(https://monstrousdev.github.io/themes/assets/svgs/demon-outline.svg);
  -webkit-mask-position: center;
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-size: 80vw 60vh;
}

.wrapper-2ZbzR9 {
  background: transparent !important;
}

.theme-dark .theme-light .input-1mgnkM,
.theme-dark .theme-light .input-UJ9Tr3 {
    color: #eee;
}

  /* 20.a. Plugin Optimization */
    /* 20.a.1. BetterFormatting */
.bf-toolbar:before {
  background: var(--quaternary-color) !important;
}

  /* 20.a.2. Permission Viewer */
#permissions-modal-wrapper #permissions-modal {
  border-color: var(--primary-color);
}

#permissions-modal-wrapper .perm-side {
  background: transparent !important
}

#permissions-modal-wrapper .role-item {
  border: 1px solid transparent;
}

#permissions-modal-wrapper .role-item:hover {
  background-color: transparent !important;
  border-color: var(--hover-color);
}

  /* 20.a.3. Character Counter */
span#charcounter {
  color: rgba(255, 255, 255, .3);
  right: 10px;
  bottom: 0em;
}

.message-1PNnaP span#charcounter {
  bottom: -.5em;
}

  /* 20.a.4. Reply System */
div.reply-list {
  background: var(--primary-color)
}

div.reply-item {
  background: transparent;
  border: 1px solid var(--main-color)
}

  /* 20.a.5. Server Folders */

.wrapper-1Rf91z.foldercontentclosed {
  width: 0;
}

.wrapper-1Rf91z.foldercontent {
  transition: all .2s ease-in-out;
}

.wrapper-1Rf91z.foldercontent .scrollerWrap-1IAIlv .scroller-2TZvBN {
  border-top: 2px solid var(--main-color);
  box-sizing: border-box;
  margin-top: -2px;
}

  /* 20.a.6. Share Button Plugin */
.sb-button:hover {
  background-color: var(--main-color) !important;
}

.metalloriff-changelog-scroller::-webkit-scrollbar {
  display: none;
}

  /* 20.a.7. Theme & Plugon Repo */
.themerepo-modal .themeEntry.downloadable .btn-download,
.pluginrepo-modal .pluginEntry.downloadable .btn-download {
  background-color: var(--main-color) !important;
}

  /* 20.a.8. Personal Pins */
.popoutBottomRight-2JrySt.noArrow-3BYQ0Z.popout-personalpins-notes {
  margin-top: 12px;
}

  /* 20.a.9. Detailed Tooltip */
.layerContainer-yqaFcK .dst-tooltip.tooltip-2QfLtc.tooltipRight-2JM5PQ {
  background-color: var(--main-color) !important;
}

  /* 20.a.10. Ghost Ping */
  #ghostping-panel {
    top: 48px !important;
    height: calc(100% - 48px) !important;
    width: 100% !important;
    padding: 30px !important;
    box-sizing: border-box;
  }
  
  #ghostping-panel[style*="opacity: 0.9"] {
    opacity: 1 !important;
  }
  
  #ghostping-panel #ghostping-panel-close-button ~ div {
    background-color: var(--quaternary-color) !important;
    width: calc(100% - 80px) !important;
    padding: 20px !important;
    box-shadow: 0 2px 20px var(--shadow) !important;
  }

  /* 20.a.11. Display Servers to Channels */
  .DSAC-styled .wrapper-1Rf91z:not(.foldercontent) .scrollerWrap-1IAIlv .scroller-2TZvBN>.listItem-2P_4kh:first-child {
    margin-top: -42px !important;
  }

/* 20.b. Addon Optimization */
  /* 20.b.1. Custom Popouts */

.header-QKLPzZ .avatar-3EQepX::before {
  content:'';
  position:absolute;
  top:-34px; /*Distance from the avatar container to the edge of the modal (y)*/
  left:-20px; /*Distance from the avatar container to the edge of the modal (x)*/
  width:601px; /*Width of modal header*/
  height: 600px; /*Height of modal header*/
  opacity:.5;
  pointer-events:none;
  background: var(--user-background) center/cover no-repeat;
  -webkit-mask: linear-gradient(black, transparent 80%);
}

.header-QKLPzZ *:not(:first-child),
.tabBarItem-1b8RUP {
  z-index:1;
}

/* 21. Custom CSS */
.bd-detached-editor .chat-3bRxxu .title-3qD0b- > div:last-child,
.bd-detached-editor .headerBar-UHpsPw > div:last-child {
    margin-right: 0 !important;
}

#bd-customcss-detach-container #bd-customcss-attach-controls{
    display: flex;
    flex-flow: column;
    align-items: center;
}
#bd-customcss-attach-controls {
    display: flex;
    flex-flow: column;
    align-items: center;
}
#bd-customcss-detach-controls-button > span {
    font-size: 0 !important;
    display: flex;
    flex-flow: column;
    align-items: center;
}
#bd-customcss-attach-controls .checkbox-group {
    order: 1;
}

/* Main CSS Box */
.ace-monokai {
  background-color: #232327;
  color: white;
}

/* Gutter Line */
.ace-monokai .ace_gutter {
  background: #101011;
  color: var(--streaming);
}

/* Shorter Highlight Line */
.ace-monokai .ace_gutter-active-line {
  background-color: #1E1E21;
}

/* When Clicking and Dragging through the codes to highlight them */
.ace-monokai .ace_marker-layer .ace_selection {
  background: var(--main-color);
}

/* Long Highlight Line */
.ace-monokai .ace_marker-layer .ace_active-line {
  background: #121212;
}

/* Bracket Border */
.ace-monokai .ace_marker-layer .ace_bracket {
  margin: -1px 0 0 -1px;
  border: 1px solid var(--hover-color);
}

/* Comment Code */
.ace-monokai .ace_comment {
  color: var(--online);
}





/* 22. @Media Edits */
/* change screen size */

@media only screen and (max-width: 915px) {

  .membersWrap-2h-GB4 {
    pointer-events: none;
  }

  .members-1998pB{
    transform:translate(145px);
    z-index:2;
    transition:all 300ms ease;
    pointer-events: all;
  }

  .members-1998pB:hover{
    animation:member 300ms ease;
    transform:translate(0px);
    box-shadow:4px 0 10px 6px rgba(0, 0, 0, 0.8);
  }

  .members-1998pB .avatar-3uk_u9 {
    margin-left: 12px;
    transition: all 300ms ease;
  }
  
  .members-1998pB:hover .avatar-3uk_u9 {
    margin-left: 0px;
  }

  .members-1998pB:hover::after{ 
    display: none; 
  }
  
  .member-3W1lQa{
    margin-left:20px;
  }
  
  .members-1998pB:hover .member-3W1lQa{
    margin-left: 15px;
  }

  .members-1998pB .membersGroup-v9BXpm {
    transform-origin:left;
    font-size: 8px;
    padding:2px;
    transition:all 300ms ease;
    width:30% !important;
    height: 27px !important;
    margin-left: 10px !important;
  }
  
  .members-1998pB:hover .membersGroup-v9BXpm{
    font-size: 13px; 
    width: 100% !important;
    padding: 4px; 
    text-align: center;
    margin-left: 2px !important;
  }

  .members-1998pB .content-3QAtGj{
    opacity:0;
    transition:opacity 300ms ease, margin 100ms ease;
  }
  
  .members-1998pB .content-3QAtGj .nameTag-3p0yK- {
    margin-bottom:6px;
  }
  
  .members-1998pB:hover .content-3QAtGj { 
    opacity:1;
  }
  
  [class*="scroller-"] .members-1998pB{
    height: 100%;
    --add: 200px;
    height: calc(100% + var(--add));
    padding-bottom: calc(20px + var(--add));
    margin-bottom: var(--add);
    transform: translate(142px);
  }
  
  [class*="scroller-"] .members-1998pB:hover{
    animation: member 300ms ease;
    transform: translate(0px);
    box-shadow: 4px 0 10px 6px rgba(0, 0, 0, 0.8);
  }

  .header-toolbar button.active{display:none;}

  
  .chat-3bRxxu .chatContent-a9vAAp {
    margin-right:-145px !important;
    z-index:1
  }
  
  .chat-3bRxxu .content-yTz4x3>.spacer-1fA9zc.vertical-V37hAW:only-child {
    margin-right:0px !important;
    z-index:1
  }
      
  .chat-3bRxxu .content-yTz4x3.spacer-1fA9zc.vertical-V37hAW{
    margin-right:0px;
    z-index:1
  }
  
  .searchResultsWrap-2DKFzt {
    z-index: 2 !important;
  }
  
}
