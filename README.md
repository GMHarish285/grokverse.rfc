# grokverse.rfc
Submissions repository for `ASOC16` - [https://github.com/acm-avv/grokverse.rfc](https://github.com/acm-avv/grokverse.rfc)

> [!NOTE]
All discussions regarding `ASOC13: Gamified 2D Metaverse Working Spaces` shall take place at [https://github.com/orgs/acm-avv/discussions/21](https://github.com/orgs/acm-avv/discussions/21)

## Overview
In-order to be eligible to work on this project as **Request for Code** under the banner of **Amrita Summer of Code, 2025**, you are required to form a team of size 1-4 and have all the members register at [amsoc.vercel.app](https://amsoc.vercel.app)

## Project Manager Details
```json
"Name": "HarishGM, Tharun Kumarr A",
"Year": "3rd and 4th",
"Roll": "CB.SC.U4CSE23027, CB.EN.U4CSE22253",
"GitHub": "@GMHarish285, @TharunKumarrA",
```

## How to Apply
Type out a message with the following details at [https://github.com/orgs/acm-avv/discussions/21](https://github.com/orgs/acm-avv/discussions/21):
1. Team Name
2. Team Members' Names, Roll-Numbers and respective GitHub usernames
3. Tag the project manager as **@username**

## Guidelines
1. Keep all discussions limited to this discussion channel by tagging the project manager via **@username**
2. Do not try to contact the project manager personally unless they are open to it.
4. Maintain decorum and avoid any misbehavior with the project manager. This can be subjected to disqualification.
5. Send us an update every week with regards to your progress for your respective project. If we do not receive an update for more than 10 days then your team will be disqualified automatically.

## Project Details
-   A platform similar to [https://gather.town](https://gather.town)
-   Use `PhasorJS` to build out the 2D animated components
-   `WebSockets` and `WebRTC` for chats and video servers
-   REST API servers for auth, creating new spaces, inviting people to a space
-   Would be interesting to see editable / extendable workspaces with an inventory of decoratives
-   Use `React.js` and rely on React Server Components via `Tanstack` if SSR is required due to the heavy rendering nature of this application. Avoid `Next.js` bloat at all costs and use `Tanstack Router`, `Query`, `Store` and `Forms`
-   Keep the backend in `Golang` as there is great support for `Websockets` (`Gorilla/websockets`) and `WebRTC` (`pion/webrtc`) and API (`gin-gonic`)
-   A combination of SQL and NoSQL databases would make sense here. Would love to see people building with `MongoDB` or `Cassandra` along with `PostgreSQL`.
