# INSAN CRICKET — live online

GitHub Pages cannot host WebSockets. The game uses **PeerJS** (public broker at `0.peerjs.com`) so two browsers can create/join a room **today**.

## Play

1. Open https://sl8722569-ux.github.io/insan-cricket/web/
2. Multiplayer → Create casual or ranked room
3. Share the room code
4. Second player: Join
5. Host: Start match

Host is match authority. Guest plays the other side. Ranked rating is stored in `localStorage` (`insan-elo`) — not a global ladder.

## Optional self-hosted PeerServer

```
npx peer --port 9000
```

Then point the client at it (future hook: `localStorage.insan-peer-host`).

Friends = share the code. No fake “finding match…” spinner.
