# Random Video Chat — Developer Resources

A collection of tools libraries and platforms 
for building random video chat applications.

## Open Source Libraries
- simple-peer - WebRTC wrapper
- socket.io - Signaling server
- coturn - TURN server

## Architecture Considerations
- Peer to peer vs media server
- STUN vs TURN tradeoffs
- Moderation without accounts

## Real World Example
Chatzyo https://chatzyo.in built with vanilla 
JavaScript Node.js and Coturn. Serving users 
across 15 countries with zero accounts.

## Key Challenges Solved
- Carrier grade NAT on Indian mobile networks
- Safari iOS camera permission handling
- Language based room routing
