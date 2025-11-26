# Software System

## Backend (MVP)
- Python or Node.js API
- Payment → Camera Trigger logic
- Secure webhook verification
- Timestamped recording start/stop

## Cloud
- AWS S3 for video storage
- CloudFront for secure access
- DynamoDB (optional) for logging

## Flow
1. QR scan → landing page
2. Backend pings camera health
3. If OK → payment enabled
4. Payment success → camera triggered
5. Video uploaded to S3
6. Admin dashboard shows clip for review

## Future AI (Phase 2)
- Ball detection  
- Green-surface verification  
- Proximity scoring system  
