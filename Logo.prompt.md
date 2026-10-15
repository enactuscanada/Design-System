One-line: renders an official Enactus logo file at a given height — use it anywhere a mark is needed instead of drawing one.

```jsx
<Logo variant="primary" height={56} basePath="../.." clearSpace />
```

Variants — all five are **horizontal lockups or the standalone mark**; the supplied asset package contains no text-only wordmark file:

| Variant | File | Use on |
|---|---|---|
| `primary` | `enactus-primary.svg` | Light and Off-White grounds — the preferred treatment |
| `full-color-white` | `enactus-full-color-white.png` | Almost Black, dark and photographic grounds |
| `black` | `enactus-primary-black.svg` | Enactus Gold and light colour grounds, and any one-colour reproduction |
| `lockup-black` | `enactus-lockup-black.png` | Raster fallback for `primary` where SVG is not supported (640×360, includes ™) |
| `mark-gold` | `enactus-mark-gold.png` | The origami mark alone — top-right corner marker on slides that don't carry the full logo, avatars, favicons. Never directly under or beside the full logo |

When horizontal space is tight, use `mark-gold` — not a cropped lockup. A true wordmark-only lockup exists in the brand guide but was not supplied here; request the file from social@enactus.ca rather than cropping one yourself.

Rules: never stretch, rotate, recolour, outline or add effects. Keep clear space equal to the height of the "n" in "enactus" — `clearSpace` does this for you. Minimum reproduction size is 3/4in (≈72px). For non-standard and team lockups, contact social@enactus.ca.
