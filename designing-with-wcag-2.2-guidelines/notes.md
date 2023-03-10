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
  - Properly spaced:
    - 4px space in between
    - Size exception: can be 20px x 20px with 4px space in between (24px total)
  - Indicate when selected:
    - For example, 2px border when focused/selected

- Help button so user can ask for assistance

#### Visual contrast and accessibility

- Level AA Ratios
  - 4.5 to 1 (visual presentation of text & images of text)
  - 3 to 1 (large scale text and images of large-scale text)

- [Accessibility Checker](accessibilitychecker.org)
  - Great tool for initial review, not for quick updates on design changes

- Figma plugins
  - Adee comprehensive accessibility tool
  - Can be used for analyzing text and graphics

#### Media accessibility

- Videos on websites
  - Tab overlay indicating "Video Only" and links out to "Alternative Media Assistance"
  - Video Only: indicates video has no audio
  - Users with limited vision will need alternative assistance, e.g. audible description of what's happening in the video
  - Providing captions on alternative media is NOT required - however, may help with SEO
  - Level AAA: offering option for sign language + captions
  - Transcription is ALWAYS required if there's audio

#### Providing context for developers

- Handing designs over to devs
  - Focus state layer indicates tabbing order of elements
  - Include context for elements on the page, e.g. images
    - Alt text:
      - Used primarily by screen readers
      - Shorter than description
    - Description:
      - Verbal paintbrush of image itself
      - Longer than alt text
      - Make sure content is not redundant. Is not helpful to users
  - Include a structured note
    - Outline layers so devs know where documentation is

#### Chapter Quiz 1

### 2. Designing with WCAG 2.2

#### Updating an inaccessible page in Figma

- User Testing
  - First step to understanding accessibility is having users with disabilities test your site
  - Range of disabilities, incl. hearing loss, visual impairment, motor disabilities

- Figma plugin: Anima
  - Imports HTML version of Figma file with public link
  - Paste link into Color Contrast Accessibility Validator
  - Then use Adee plugin for extra feedback

- Accessibility is a workflow & mindset, rather than one-step automated process

#### Visible controls

- Hidden content
  - Content not accessible w/ keyboard or only visible on hover
    - Replace hover actions with click actions
    - On click, all selections must be visible on the screen
  - Layered hidden buttons: consolidate a clear view of all options

#### Fixing inaccessible text

- What makes text inaccessible:
  - Font selection: Choose from open source or Google fonts so it's easily styled
  - Decorative fonts: Only use for logo or decoration (not large bodies of text)

- Formatting rules:
  - Line height & spacing: At least 1.5x font size
  - Paragraph spacing: At least 2x font size
  - Letter spacing (tracking): At least 0.12x font size
  - Word spacing: At least 0.16x font size

- Golden Ratio Typography (GRT) Calculator (for line height)

#### Accessible video

- All levels require:
  - Captions
  - Transcript
  - Controls: Stop/Play

- Level AAA:
  - Alternative time based media
  - Sign language
  - Extended audio description

#### Redundant content

- Redundant content is cumbersome for users with disabilities

- Forms:   
  - Consolidate info
  - Add checkbox for duplicate info ("billing address is the same")

#### Page-break navigation

- Adding page markers vs. endless scrolling
- Not a WCAG requirement - but helpful to include pagination

#### Context and accessibility

- Use language that all users can understand
  - Avoid abbreviations
  - Avoid "insider" terminology

- Arrow buttons for tabbing
  - Loop image slideshows so users don't need to tab back

- Dialogue boxes/popups
  - Make close button first in tab order
  - Make sure that form errors are easy to understand

#### Chapter Quiz 2

### Conclusion

#### Lay a foundation

- Share your work and questions in the course Q&A
- Download and review exercise files
- Follow instructor on LinkedIn
