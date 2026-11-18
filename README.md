# Seven & Bloom: run it in VS Code

## 1. Open the folder
1. Unzip this folder.
2. Open VS Code, then **File > Open Folder** and choose `seven-and-bloom-site`.

## 2. Run it (Live Server)
1. Install the **Live Server** extension (VS Code suggests it, or press Ctrl+Shift+X and search for it).
2. Right-click **index.html** and choose **Open with Live Server**.
3. Press **Ctrl+S** after any edit and the page refreshes by itself.

No Live Server? Double-click `index.html` in File Explorer. It also works.

## 3. The landing page is one file: `seven-and-bloom.html` (about 259 lines)
`index.html` only sends visitors to it.

| What | Line (about) |
|---|---|
| Colours (light and dark mode) | 14 |
| Menu bar styling | 32 |
| Hero text and the rotating photo cards (styling) | 45 |
| Names grid styling | 68 |
| Phone and tablet rules | 93 |
| Menu bar (HTML) | 122 |
| Introduction text + 3 hero photo cards (HTML) | 136 |
| The seven names + registration numbers (HTML) | 154 |
| Footer (HTML) | 196 |
| Script (dark mode + photo rotation) | 215 |

## 4. Common edits
- **Change the introduction:** search for `Seven lives.` or `class="lead"`.
- **Change a name, photo or registration number:** search for `class="member"`. Each person is one `<a>` block.
- **The three rotating hero photos:** they are filled in automatically from the seven members, so you only edit the member blocks.
- **Change colours:** the first block in the style section (`:root`).
- **Add or remove a person:** copy or delete one `<a class="member"> ... </a>` block.
- **Each person's own page:** open their folder (`gloria/`, `patricia/`, `divine/`, `brollin/`, `frank/`, `emmanuel/`, `luke/`) and edit `index.html`.

Keep all folders together. Pages find their photos and each other by folder path.

## 5. Needs internet
Fonts load from Google and a few stock photos from Unsplash. Emmanuel's page also loads Tailwind and Alpine from the internet.
