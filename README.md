# T20 Spin Wheel Online (Vite + PeerJS)

Local: `npm install` then `npm run dev`.

## Vercel par deploy
1. Project ko GitHub par push karein.
2. vercel.com -> Add New -> Project -> repo import karein. Framework "Vite" apne aap detect hoga
   (Build: `npm run build`, Output: `dist`). Deploy dabayein.
   Ya CLI se: `npm i -g vercel` phir project folder me `vercel --prod`.

## Kaise khelte hain
Host "Naya room banao" dabata hai aur milne wala link doosre ko bhejta hai. Doosra wo link kholte hi Player Y ban jata hai.
Koi database ya sign-in nahi chahiye: dono browsers seedhe WebRTC (PeerJS) se jude hote hain.
Stats har player ke apne browser me rehte hain aur game ke ant me reveal hote hain.
