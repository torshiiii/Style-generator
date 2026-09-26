# Closet Shuffle

An outfit generator that only uses clothes you actually own.

## How to use it (no coding needed)

1. Download `index.html` (on GitHub: click the file, then the **Download raw file** button).
2. Double-click it. It opens in your web browser. That's the whole app.

### Adding clothes from photos
In **My closet**, tap **Choose photos** and select as many photos as you like at once (or drag
them onto the box on a computer). Inside the Claude link, AI looks at each photo and fills in
what it is (top, pants, jacket, shoes…), its color and a name. Check each one, fix anything
that's off, then tap **Add all to closet**. When you open `index.html` directly, AI isn't
available, so you pick the type and color yourself.

### Getting started
1. Go to **My closet** and add your clothes. For each piece pick what it is
   (top, bottoms, shoes…), its main color, and what weather and occasions it's good for.
   A photo is optional.
2. Go to **Get dressed**, choose the weather and occasion, and tap **Shuffle outfit**.
3. Love one piece? Tap **Keep** on it and shuffle again: only the other pieces change.
   **Swap** changes just that one piece.
4. Tap **Save this outfit** to keep a combo in the **Saved** tab.

### Today's weather
On **Get dressed**, type your city (or tap **Use my location**). The app checks today's
forecast (free, from Open-Meteo) and picks clothes for hot, mild or cold weather, and adds a
jacket when rain is likely. Tap **°F / °C** to switch units.

Automatic weather works when you open `index.html` in a browser. Inside the Claude link it's
blocked, so you pick the weather yourself there.

### How outfits are picked
Outfits are laid out like a flat-lay photo: top, pants and shoes down the middle, belt and
watch on one side, sweater and jacket on the other. Each gets a name like
"Casual 1 — Cream and navy".

- Either a dress/jumpsuit, or a top + bottoms, plus shoes. A belt goes with pants and shorts.
- Light tops go with dark bottoms (and the other way around).
- The belt matches the shoes (brown with brown, black with black).
- A second color, like a navy collar on a gray polo, gets echoed by another piece.
- Neutrals (black, white, cream, beige, tan, brown, gray, navy, denim, light blue, olive) go
  with anything. Each outfit uses at most one bright color or pattern.
- A sweater is added sometimes when it's mild or cold; a coat always when it's cold.

### Where your closet is stored
When you open the file yourself, your clothes are saved in that browser on that device.
Clearing your browser data erases them, and they won't show up on another device.
