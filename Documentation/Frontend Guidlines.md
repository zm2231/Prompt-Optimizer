### Frontend Guidelines

These guidelines ensure the user interface is elegant, functional, and consistent with macOS Human Interface Guidelines while supporting rapid development.

#### Fonts

• Primary font: Use `San Francisco` through `-apple-system`.  
• Font hierarchy: Titles (20–24px), subtitles (16–18px), body text (14–16px), captions (12px).

#### Color Palette

• Integrate macOS system colors with:  
  – Light Mode: Background `#F9F9F9`, text `#000000`.  
  – Dark Mode: Background `#1E1E1E`, text `#FFFFFF`.  
• Accent color: System default (`#007AFF`), applied to buttons and interactive elements.

#### Spacing & Layout Rules

• Use an 8px grid system to ensure uniformity.  
• Define margins (16px outer, 8px inner) and padding (12–16px).  
• Buttons: Minimum 32px height; input fields: at least 28px height.  
• Rely on Flexbox or CSS Grid for adaptive layouts and responsive design.

#### Preferred UI Libraries

• **Photon**: Offers macOS-like UI aesthetics tailored for Electron.  
• **Tailwind CSS**: For a highly configurable utility-first approach.  
• **React Desktop**: Supplies explicitly styled components that echo native macOS UI elements.