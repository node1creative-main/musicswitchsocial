🎵 MUSIC SWITCH SOCIAL

MusicSwitch is a social music-sharing web application that allows users to share music links across platforms while giving recipients the freedom to listen on their preferred music service. Built for modern music consumption, MusicSwitch removes platform lock-in and adds a social layer to music discovery.

Company: Node①Creative
Status: MVP / Active Development
Platforms: Web (Mobile apps planned)

🚨 The Problem

Music sharing today is fragmented by platform ecosystems:

Spotify users can’t easily share music with Apple Music users

Apple Music links don’t open cleanly for Spotify users

Group chats are cluttered with unusable links

There’s no social context, history, or personalization tied to shared music

Music is universal — music links shouldn’t be locked to platforms.

💡 The Solution

MusicSwitch acts as a platform-agnostic music link hub with built-in social messaging.

Instead of sending a single-platform link, users send a MusicSwitch link.
When the recipient clicks it, they can:

Choose Spotify, Apple Music, or YouTube Music

Automatically open the song on their default platform

See rich metadata (artist, album art, track info)

Keep conversations and music discovery in one place

🧠 App Description

MusicSwitch is a user-based social web app where users can:

Create a profile and choose a default music platform

Add and manage friends

Send messages with embedded music links

Receive music links and play them on any supported platform

Upgrade to premium for enhanced features

The application is built with scalability, monetization, and mobile expansion in mind.

🧱 Tech Stack
Frontend

React

TypeScript

Tailwind CSS

Shadcn UI

React Router

React Query

Backend

Node.js

Express

TypeScript

Sequelize ORM

MySQL / PostgreSQL

Authentication & Payments

JWT Authentication

Stripe Subscriptions

🧭 How to Use MusicSwitch
1. Register & Login

Create an account

Secure authentication via JWT

2. Create Your Profile

Set username and avatar

Choose your default music platform (Spotify, Apple Music, YouTube Music)

3. Add Friends

Send friend requests

Accept incoming requests

Build your music network

4. Send Music

Paste a music link from any supported platform

Select one or more friends

Add an optional message

Choose a platform override (Premium feature)

5. Receive & Play

View messages in your Inbox

See music previews and metadata

Play instantly on your preferred platform

🗂️ Application Structure
Frontend Pages

Home

Login / Register

Profile

Friends

Music Link Sender

Inbox

Subscription

Backend APIs

/auth – Authentication

/friends – Friend requests & management

/music-links – Music link creation & metadata

/messages – Messaging system

/subscription – Stripe subscription handling

💬 Messaging System

One-to-one messaging between friends

Messages can include:

Text

Music links

Messages are stored and retrievable

Designed for future real-time WebSocket support

🆓 Free vs 💎 Premium Features
Free Tier

Register & login

Create profile

Add friends (limited)

Send music links (daily limit)

Receive messages

Play music on default platform

Basic metadata previews

Premium Tier

Unlimited music link sends

Unlimited friends

Platform selection per message

Rich metadata (album art, enhanced previews)

Real-time inbox updates

Ad-free experience

Full message & link history

Future analytics & insights

💳 Subscription Model

MusicSwitch uses Stripe for subscription management:

Monthly recurring subscription

Secure checkout via Stripe Checkout

Automatic plan upgrades

Backend-verified access control

🔐 Security & Privacy

Passwords are hashed and never stored in plain text

JWT-based authentication

Protected API routes

User data scoped to authenticated sessions

No third-party tracking beyond required services

🚀 Roadmap
Short-Term

Finalize metadata resolution (Spotify / Apple APIs)

Real-time messaging

Improved inbox UI

Friend search by username/email

Mid-Term

iOS & Android apps (React Native)

Notifications

Playlist sharing

Premium analytics

Long-Term

Public sharing links

Creator profiles

Group chats

Music discovery feeds

📱 Mobile Expansion

MusicSwitch is architected as API-first, making it ideal for:

iOS app

Android app

Shared backend & authentication

Seamless feature parity across platforms

🏢 About Node①Creative

Node①Creative is a product-focused development studio dedicated to building scalable, user-centric applications with modern technologies and clean architecture.

📄 License

This project is currently proprietary and under active development.
Licensing terms will be finalized prior to public release.

✨ Final Note

MusicSwitch is built around a simple idea:

Music is universal — sharing it should be effortless.

This README represents the foundation of a product designed to grow, scale, and evolve across platforms.
