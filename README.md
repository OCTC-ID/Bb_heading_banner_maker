# Bb Tools

Small tools for building Blackboard Ultra courses at OCTC. Each one makes a PNG in KCTCS blue (or navy) and gold that you download and add to your course.

**Use the tools:** https://octc-id.github.io/Bb_tools/

| Tool | What it makes | Link |
|---|---|---|
| Course Banner Maker | The banner at the top of a course: a title, an optional subtitle such as the term, in navy or gold | https://octc-id.github.io/Bb_tools/course-banner/ |
| Heading Banner Maker | Level 1, 2, and 3 heading banners for pages inside a course | https://octc-id.github.io/Bb_tools/headings/ |

Both tools offer the Collegiate, Varsity, Minimal, and Playful styles. The heading banner maker adds Collegiate Gold (the Collegiate layout on a gold field, with no navy). The course banner maker adds Plate, Band, and Label.

## Sizes

### Course banners

Course banners are 5:1, Blackboard's banner shape: 1200 x 240, 2400 x 480 (default), or 4800 x 960.

### Heading banners

Heading banners are sized for use inside Blackboard documents, so they stay compact. Heights below are at the standard resolution (1200 px wide).

| Level | Shape | Height |
|---|---|---|
| 1 | A slim filled title strip in KCTCS blue | 120 px (a 10:1 strip) |
| 2 | Heading on white with its rule close underneath | About 40 to 60 px, depending on style and text |
| 3 | Smaller heading on white with a light rule or mark | About 25 to 50 px, depending on style and text |

Levels 2 and 3 always use the full image width and start at the left edge, so the heading lines up with the text under it. Each one is cropped to its artwork plus a 3 px margin above and below. When lowercase is on, the image keeps room for letters that drop below the line (g, j, p, q, y) even if the heading has none, so headings at one level stay consistent. A heading in ALL CAPS has no such letters, so its rule sits closer. Long headings shrink to fit the width.

**Download resolution** sets how sharp the image is: Standard (1200 px wide), High (2400 px, the default), or Extra high (4800 px). It does not change how big the heading looks. Blackboard decides how wide the image displays and may add its own space around image blocks.

Heading banners use the KCTCS brand colors: primary blue `#00467F`, primary gold `#E7A614`, secondary navy `#011D41`, and white, plus a light tint of the blue for hairline rules. (The course banner maker still uses the earlier navy and gold.)

## Accessibility

A banner is an image of text. When you add one in Blackboard, paste its text into the image's alt text. Each tool shows the alt text to copy.

A graphic heading does not add document structure. Keep a real Blackboard text heading (Heading 2, Heading 3) for each section so screen readers and the document outline can find it. If that text heading repeats the image's words, mark the image as decorative instead of adding alt text.

## Files

- `index.html`: the landing page that lists the tools
- `course-banner/index.html`: the course banner maker
- `headings/index.html`: the heading banner maker

Each page is self-contained. Fonts load from Google Fonts; there are no other dependencies.

## Contact

Stephanie Self, Instructional Designer and eLearning Coordinator, Owensboro Community & Technical College
stephanie.self@kctcs.edu
