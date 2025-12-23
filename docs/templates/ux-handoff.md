# UX Designer Handoff Template

This template guides UX Designers in preparing comprehensive handoff documentation for developers, ensuring design intent is clearly communicated and implemented correctly.

---

## Handoff Overview

**Feature/Project Name**: [Name of feature or component]  
**UX Designer**: [Your name]  
**Developers**: [Developer names or team]  
**Target Sprint/Release**: [Sprint number or release version]  
**Date**: [Handoff date]

### Design Goal
[Brief description of the user problem being solved and the design approach]

### User Impact
[Who benefits from this feature and how it improves their experience]

---

## User Flows

### Primary User Flow
[Describe the main user journey step by step, or link to flow diagram]

**Example:**
1. User clicks "Create New Project" button on dashboard
2. Modal opens with project creation form
3. User fills in project name, description, and selects template
4. User clicks "Create" button
5. System validates input and creates project
6. User is redirected to new project page with success message

### Alternative Flows
[Describe edge cases, error states, or alternative paths]

**Example:**
- If validation fails, show inline error messages on form fields
- If user cancels, close modal and return to dashboard without changes

---

## Design Deliverables

### Design Mockups / Prototypes
- **Location**: [Link to Figma, Sketch, Adobe XD, or other design tool]
- **Key Screens**:
  - [Screen 1 name]: [Brief description and link]
  - [Screen 2 name]: [Brief description and link]
  - [Screen 3 name]: [Brief description and link]

### Annotated Designs
[Link to annotated mockups showing interaction details, spacing, colors, and states]

**Key Annotations to Include:**
- Clickable elements and their actions
- Hover states, focus states, active states
- Loading states and skeleton screens
- Error states and validation messages
- Empty states (no data scenarios)
- Responsive breakpoints and behavior

---

## Acceptance Criteria

### Functional Requirements
- [ ] [Specific functional requirement, e.g., "User can create a new project by filling the form"]
- [ ] [Another requirement, e.g., "Form validates all required fields before submission"]
- [ ] [Error handling, e.g., "Inline error messages appear for invalid inputs"]

### Visual Requirements
- [ ] [Visual requirement, e.g., "Button uses primary brand color (#3B82F6)"]
- [ ] [Layout requirement, e.g., "Modal is centered on screen and has max-width of 600px"]
- [ ] [Typography requirement, e.g., "Headings use font-size 24px, weight 600"]

### Interaction Requirements
- [ ] [Interaction detail, e.g., "Modal opens with fade-in animation (200ms)"]
- [ ] [Feedback requirement, e.g., "Success message appears for 3 seconds after submission"]
- [ ] [Responsiveness, e.g., "Layout adapts to mobile screens below 768px breakpoint"]

---

## Accessibility Notes

### WCAG Compliance
- **Target Level**: [e.g., WCAG 2.1 AA]

### Accessibility Requirements
- [ ] **Keyboard Navigation**: All interactive elements accessible via Tab key
- [ ] **Focus Indicators**: Visible focus states on all interactive elements
- [ ] **Screen Reader Support**: Proper ARIA labels and semantic HTML
- [ ] **Color Contrast**: All text meets minimum contrast ratio (4.5:1 for normal text)
- [ ] **Alternative Text**: Images and icons have descriptive alt text
- [ ] **Form Labels**: All form inputs have associated labels
- [ ] **Error Announcements**: Error messages announced to screen readers

### Specific Accessibility Notes
[Any feature-specific accessibility considerations]

**Example:**
- Modal should trap focus when open and return focus to trigger button on close
- Use `aria-live` region for success/error messages
- Ensure close button has accessible label "Close dialog"

---

## Design Specs & Assets

### Typography
- **Primary Font**: [Font name, e.g., "Inter"]
- **Heading Sizes**: [e.g., H1: 32px, H2: 24px, H3: 20px]
- **Body Text**: [e.g., 16px, line-height 1.5]
- **Font Weights**: [e.g., Regular: 400, Medium: 500, Bold: 700]

### Color Palette
- **Primary**: [Color name and hex code, e.g., "Blue #3B82F6"]
- **Secondary**: [Color and hex code]
- **Success**: [Color and hex code, e.g., "Green #10B981"]
- **Error**: [Color and hex code, e.g., "Red #EF4444"]
- **Background**: [Color and hex code]
- **Text**: [Color and hex code]

### Spacing & Layout
- **Grid System**: [e.g., "12-column grid with 16px gutters"]
- **Spacing Scale**: [e.g., "4px, 8px, 16px, 24px, 32px, 48px"]
- **Border Radius**: [e.g., "Small: 4px, Medium: 8px, Large: 12px"]

### Downloadable Assets
- **Icons**: [Link to icon set or SVG exports]
- **Images**: [Link to image assets with various resolutions]
- **Illustrations**: [Link to illustrations or graphics]
- **Design Tokens**: [Link to design token file if available]

### Component Library
[Link to component library or design system if applicable]

---

## Responsive Behavior

### Breakpoints
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

### Responsive Changes
[Describe how layout and components adapt at different screen sizes]

**Example:**
- **Mobile**: Modal becomes full-screen, form fields stack vertically
- **Tablet**: Modal maintains fixed width (600px), centered on screen
- **Desktop**: Same as tablet with larger spacing around modal

---

## States & Interactions

### Component States
- **Default**: [Description or link to mockup]
- **Hover**: [Description or link to mockup]
- **Focus**: [Description or link to mockup]
- **Active/Pressed**: [Description or link to mockup]
- **Disabled**: [Description or link to mockup]
- **Loading**: [Description or link to mockup]
- **Success**: [Description or link to mockup]
- **Error**: [Description or link to mockup]

### Animations & Transitions
[Describe any animations, timing, and easing]

**Example:**
- Modal fade-in: 200ms ease-out
- Button hover: color transition 150ms ease
- Success message: slide-in from top, 300ms ease-out

---

## Edge Cases & Error Handling

### Error Scenarios
1. **[Error type, e.g., "Network error"]**: [How to handle, e.g., "Show error toast with retry option"]
2. **[Error type, e.g., "Validation error"]**: [How to handle, e.g., "Inline error message below field"]
3. **[Error type, e.g., "Permission denied"]**: [How to handle, e.g., "Show alert with contact support link"]

### Empty States
[Describe what users see when there's no data]

**Example:**
- No projects yet: Show illustration with "Create your first project" call-to-action

### Loading States
[Describe loading indicators and skeleton screens]

**Example:**
- Show spinner on button during submission
- Use skeleton screen while fetching project list

---

## Developer Notes

### Implementation Guidance
[Any specific technical considerations or preferred approaches]

**Example:**
- Use existing Modal component from design system
- Reuse validation logic from user settings form
- Consider adding form auto-save for better UX

### Design System Components
[List design system components to use]
- Modal component
- Button (primary variant)
- Input field with validation
- Toast notification

### Questions or Clarifications
[List any open questions or areas needing developer input]

---

## Validation & Review

### Design QA Checklist
- [ ] Visual design matches mockups across breakpoints
- [ ] All interactive states implemented correctly
- [ ] Animations and transitions work as specified
- [ ] Accessibility requirements met (keyboard nav, focus states, ARIA)
- [ ] Color contrast meets WCAG standards
- [ ] Responsive behavior works on all target devices

### Collaboration
- **Design Review**: [Scheduled date or invite developers to review session]
- **Feedback Channel**: [Where to ask questions, e.g., Slack channel, GitHub discussions]
- **Availability**: [Designer availability for questions during implementation]

---

## Sign-off

**UX Designer Sign-off**: [Name and date]  
**Developer Acknowledgment**: [Name and date when accepted for implementation]
