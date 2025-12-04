# Privacy Policy
Last Updated: 2025-12-04

## 1. Overview
This Privacy Policy describes how the Comment Edit Integrity Tracker ("the App")
collects, stores, and shares data. The App is designed to protect the integrity
of Mafia, Werewolf, and similar Reddit games by monitoring edited comments.

The App follows a strict minimal-data approach.

## 2. Data Collected
The App collects and temporarily stores:
- Comment ID
- The original comment body
- The edited comment body
- Basic Reddit metadata (author, timestamps)

The App does **not** collect private Reddit data or any data not provided
through official APIs.

## 3. Data Usage
Data is used solely for:
- Detecting comment edits
- Alerting moderators
- Providing temporary review history

## 4. Discord Sharing
To support rapid moderation, each tracked edited comment is sent to a **private
Discord moderator channel**.

You acknowledge and agree that:
- Only moderators should have access to this channel.
- Messages are **automatically deleted** at the end of each game.
- No permanent edit log is maintained in Discord.

No data is shared with anyone outside the subreddit’s moderator team.

## 5. Data Storage & Retention
- The App stores only the **latest 1000 comments** using Redis.
- Older entries are automatically deleted.
- No long-term archival storage is performed.
- No external database is used.

## 6. Data Sharing
The App does **not** sell, share, or transfer any data to third parties.

The only sharing that occurs is:
- Temporary Discord messages to moderators
- Optional logging visible only to moderators via the Devvit dashboard

## 7. User Rights
Reddit users may request:
- Removal of mistakenly collected non-public data
- Information about currently stored data linked to their username

Moderators may delete all stored data at any time.

## 8. Security
Data is stored within Reddit Devvit’s infrastructure.  
Discord messages are temporary and controlled by the moderator team.

No external services receive data beyond Discord notifications explicitly
configured by moderators.

## 9. Children’s Data
This App is not intended for users under 13, in accordance with Reddit policy.
No special processing occurs for minors.

## 10. Changes to This Policy
This Privacy Policy may be updated from time to time. Continued use of the App
indicates acceptance of any revised terms.

## 11. Contact
Contact the developer via Reddit or through the project repository.
