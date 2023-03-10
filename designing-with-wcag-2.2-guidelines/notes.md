## Designing with the WCAG 2.2 Guidelines

Emma Moore, UX/UI Lead, Producer

Released: 11/23/2022

### Introduction

#### Inside the WCAG 2.2 accessibility (a11y) guidelines

#### Course use case

- 3 levels of WCAG compliance: A, AA, AAA

  - WCAG A - Minimum level:
    - Beginning stage, users can navigate with some issues but still have some degree of understanding
    - Barriers exist that cannot be overcome by assistive technology
    - Affects the broadest group with the most benefits and is essential

  - WCAG AA - More accessible:
    - Standard for most, if not all commercial sites
    - Some barriers will still exist with the minimum level of support
    - Impacts certain groups of users
    - Should work with most assistive technology on desktop and mobile devices
    - May impact the look of a page or affect site logic to a greater extent

  - WCAG AAA - Even more accessible:
    - Standard for most/all government sites
    - Highest level of conformance
    - Some criteria cannot be applied everywhere, so is generally not required
    - Even meeting AAA does not make pages accessible to everyone

### 1. Exploring WCAG 2.2

#### The struggle with automating WCAG 2.2

- Can you automate WCAG 2.2 with external software? No.
  - However, can be helpful for beginning the process

- External modules can help with:
  - Minimum focus appearance
  - Maximum focus appearance
  - Minimum target size

#### Dragging movements

- Designing for users who cannot use trackpad or mouse (keyboard users only)
  - Add scroll bar with up/down buttons
  - Add dropdown with options to move cards to specific locations (Move left/right/down/up)
  - Solutions may be clumsy but makes site more accessible

#### Accessible interactions

- New WCAG rules for button design
  - Large enough (user may have hand tremors):
    - At least 24px width + height (with some exceptions)
    - May include space in between buttons
  - Properly spaced
    - 4px space in between
    - Size exception: can be 20px x 20px with 4px space in between (24px total)
  - Indicate when selected:
    - For example, 2px border when focused/selected 
