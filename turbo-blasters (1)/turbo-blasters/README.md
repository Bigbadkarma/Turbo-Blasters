# Turbo Blasters
Mobile-friendly real-time multiplayer browser racing shooter.

## Run
1. Install Node.js 18 or newer.
2. In this folder run `npm install` then `npm start`.
3. Open http://localhost:3000 on your computer.
4. For mobile on the same Wi-Fi, open `http://YOUR_COMPUTER_LAN_IP:3000` on the phone. Allow port 3000 through your firewall if needed.
5. For internet multiplayer, deploy this Node.js server to a hosting service supporting persistent WebSockets (for example Render or Railway), then share its HTTPS URL.
6. Friends enter the same room code to play together.

## Controls
Mobile: left, right, FIRE touch buttons. Desktop: A/D or arrow keys, Space to shoot.

## Rules
Score increases while driving. Each hit takes 20 HP; eliminating a rival gives 250 points. Restart after destruction. Rooms support up to 12 players. Server stores game state in memory; rooms reset when server restarts.
