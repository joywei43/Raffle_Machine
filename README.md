# Everest Raffle Machine

A browser-based weighted raffle wheel for Everest Poker Room.

## Deploy to Vercel

1. Upload this folder to a GitHub repository.
2. Import the repository in Vercel.
3. Keep **Framework Preset** as `Other`.
4. Vercel will publish the `dist` folder automatically.

## Data storage

Daily and Weekly pools are stored independently in the browser. Data remains after the page or computer is restarted, but it is tied to that browser and device. Use **Backup Data** regularly and **Restore Data** when moving to another device.

No server, database, account, or external service is required.

## Replace the logo

Replace `dist/everest-logo.png` with another PNG using the same filename. The header, raffle wheel, empty state, and browser icon all use this single file.

## Prize queue

- Newly added prizes appear at the top and become the next draw.
- Use `+` and `−` to adjust each prize quantity.
- Use `↑` and `↓` to change the drawing order.
- Each confirmed winner consumes one prize. A prize with multiple quantities stays active until every unit is drawn.
