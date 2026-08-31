# Organogram Generator

A lightweight, browser-based tool for turning a structured organisational template into an editable organogram. It is designed for professional tender, donor, government, NGO, and procurement submissions.

## Start using it

1. Open `organogram-generator.html` in a web browser, or visit the deployed Cloudflare link: https://morning-forest-91d1.onyekachi24anyaegbu.workers.dev/
2. Paste or edit the structured template in the left-hand panel.
3. Select **Generate organogram**.
4. Edit the chart as needed.
5. Use **Download PNG** for documents or **Download SVG** for a scalable editable copy.

## Template format

Use headings for the hierarchy, followed by one position per line. Relationships use either `->` or `--DOTTED->`.

```text
ORGANOGRAM TITLE:
Contract Management and Supervisory Structure

LEVEL 1:
GardaWorld Operations Management

LEVEL 2:
Supervisor / Senior Security Officer

LEVEL 3:
Static Security Guard 1
Static Security Guard 2

RELIEF ROLE:
Relief Guard (1)
Role: Mobilised as required to maintain continuity of service

SUPPORT FUNCTIONS:
Programme Focal Point

LOCATIONS:
Palladium LAFIYA Programme Office, Borno

RELATIONSHIPS:
GardaWorld Operations Management -> Supervisor / Senior Security Officer
Supervisor / Senior Security Officer -> Static Security Guard 1
Supervisor / Senior Security Officer -> Static Security Guard 2
Supervisor / Senior Security Officer --DOTTED-> Relief Guard (1)
```

## Supported sections

- `ORGANOGRAM TITLE:` — chart title.
- `LEVEL 1:`, `LEVEL 2:`, `LEVEL 3:` and higher — hierarchy levels.
- `RELATIONSHIPS:` — reporting lines.
- `RELIEF ROLE:` — temporary or contingency position.
- `SUPPORT FUNCTIONS:` — support roles.
- `LOCATIONS:` — location-related positions or labels.

## Editing the chart

- **Move a box:** Drag it to a new position.
- **Rename or resize a box:** Double-click it, or select it and choose **Edit selected**.
- **Add a box:** Select **+ Add box**.
- **Remove a box:** Select it and choose **Remove selected**. Its connected lines are removed too; use Undo if needed.
- **Create a connector:** Hold Shift and select two boxes, then choose **Link selected** or **Dotted link**.
- **Edit a connector:** Click near a connector line, then choose **Edit connector**. You can change its start/end positions, solid/dotted style, and arrow direction.
- **Remove a connector:** Select it and choose **Remove selected**.
- **Arrange automatically:** Select **Auto-layout**. Use **Fit**, zoom controls, or drag to adjust the view.
- **Undo/Redo:** Use the arrow buttons in the toolbar.

## Arrow direction

When editing a connector, choose:

- **Down** for standard reporting from an upper box to a lower box.
- **Up** for reporting or workflow pointing from a lower box to an upper box.

## Downloads

- **Download PNG:** high-resolution image for Word documents, proposals, and reports.
- **Download SVG:** scalable vector version for further editing in compatible design software.
