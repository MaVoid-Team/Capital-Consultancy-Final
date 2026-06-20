# PDF Generation Rules

These instructions apply only to the Capital Consultancy proposal PDF generation process in this folder.

## Brand Source

- Use MaVoid's current rebrand file as the source of truth:
  `/Users/ziadnasreldin/Library/Mobile Documents/com~apple~CloudDocs/MaVoid/06_Marketing_Brand_Content/Company_Branding/MaVoid/new-design.md`
- Do not use the older `design.md` or old brand direction for this proposal.
- Use Josefin Sans consistently when generating the PDF.
- MaVoid should read as an enterprise operating-systems company: operational systems, workflow control, dashboards, reporting, custom enterprise software, role-based access, approvals, routing, visibility.

## Client-Facing Content Rules

- The PDF is sent directly to Capital Consultancy, so all content must be client-facing.
- Do not include internal planning notes, private scope debates, caveats, or reasoning that the client does not need.
- Never reflect internal production instructions, user-side constraints, or decisions between MaVoid and the agent in the final client-facing output.
- Treat instructions like "make it one page", "use this file", "leave prices blank", "check this internally", or similar process notes as build constraints only, not client-facing copy.
- Do not use internal constraints as titles, section names, explanatory text, or visible metadata unless the user explicitly says the client should see that exact wording.
- Do not mention BIM, Revit, or any excluded modules that were discussed internally.
- Do not include an exclusions section.
- Do not include a "recommended next steps" section.
- Do not use "recommend", "recommended", or "recommendation" language. MaVoid proposes what it will do; it does not frame the work as suggestions.
- Avoid generic filler, marketing slogans, fake metrics, invented proof, invented clients, or compliance claims.
- Keep the proposal focused on the ERP scope: sites, zones, GIS, assets, inspections, work orders, mini HR, attendance, employee location events, files, reports, and administration.

## Visual Direction

- The PDF background should be very light and clean, close to white. Avoid lemony green, beige, cream, washed-out mint, or muddy pale backgrounds.
- Use stronger MaVoid contrast: deep ink, electric blue, emerald, teal, sky blue, and clean near-white surfaces.
- Avoid purple gradients, beige themes, random neon colors, heavy glow, and generic AI-looking visuals.
- Avoid black top bars across the running pages. Page headers should be light, restrained, and use a thin divider.
- Do not use the green/cyan vertical pill element beside the logo.
- Do not use a black right-side cover panel.
- Do not put an empty decorative card or empty visual element on the cover.
- Do not put visible grid lines on the cover page.
- Do not use tables unless there is true row/column data that cannot be represented better. Prefer MaVoid-style panels, process maps, rails, chips, and grouped modules.
- Do not use cards inside cards.

## Cover Rules

- The cover must be clean, branded, and complete.
- The first viewport signal should be the proposal title and Capital Consultancy context.
- No black side panel, no visible grid, no empty decorative block, no bugged cover image.
- Headline lines need generous spacing and must never look stuck together.
- Metadata cards can be used for client, prepared by, and scope, but they must not feel empty or oversized.

## Typography And Spacing

- Use generous title leading. Large headlines should use approximately 1.3x line height or more.
- Keep clear vertical spacing between the green section label and the main heading.
- Body text should use comfortable leading. Do not allow lines to touch or visually merge.
- Text must never clip, overlap, or sit too close to borders.
- Check every page for text crowding, not only the pages the user comments on.
- If a heading or paragraph feels tight, reduce copy length, increase the container height, increase leading, or move content, instead of squeezing the text.

## PDF Build Workflow

- Generate the final artifact as a PDF unless the user explicitly asks for another format.
- Temporary build scripts are allowed, but remove them before final handoff unless the user asks to keep them.
- Do not leave stray render folders or intermediate exports in the deliverable folder.
- The deliverable folder should contain the final PDF and this scoped `AGENTS.md`.

## Required Quality Gate

Before sending the PDF back:

- Render all pages to image previews.
- Visually inspect all pages, including the cover, page headers, dense panels, and final page.
- Specifically check for:
  - text sticking together
  - clipped text
  - overlapping text
  - table-like layouts that should be panels
  - cover artifacts
  - black top bars
  - green/cyan vertical logo pills
  - washed-out or lemony backgrounds
- Run a text audit and confirm zero hits for:
  - `recommend`
  - `recommended`
  - `recommendation`
  - `BIM`
  - `Revit`
  - `excluded`
  - `exclusion`
  - `confidential discussion document`
  - `internal`
  - `hard fm`
  - `soft fm`
  - `property management`
  - `lease management`
  - `tenant management`
  - `rent collection`
  - `full payroll`
  - `accounting`
  - `finance`
