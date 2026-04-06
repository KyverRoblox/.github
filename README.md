# Kyver

Kyver is a web-based management platform for Roblox groups. It connects a Roblox group, a Discord server, and a web dashboard into one system where owners and staff can manage the parts of a community that usually get split across different tools.

Instead of handling ranks in one place, sessions somewhere else, moderation in another channel, and staff records in spreadsheets, Kyver brings everything together into one connected platform. The goal is simple: keep Roblox, Discord, and your dashboard in sync so management feels structured, consistent, and easier to run.

Kyver is built for Roblox communities that rely on organised staff teams, including cafes, hotels, military groups, studios, fan groups, and similar communities where activity, promotions, moderation, and internal systems actually matter.

## What Kyver does

Kyver gives each server its own connected management space. Owners can create servers linked to Roblox groups, invite staff, manage roles and permissions, configure settings, and handle billing on a per-server basis. Members have profiles, staff directories, role assignments, status tracking, and synced records that make it easier to keep track of who is active and what they are responsible for.

One of the main parts of Kyver is the ranking system. Staff with permission can promote or demote members from the web dashboard or through Discord slash commands. Rank changes are logged with reasons, classifications, history, revert support, cooldowns, and analytics. Ranking access is protected through connected Roblox account verification and group-access checks, so staff can only perform ranking actions when the linked setup is valid.

Kyver also includes a full session system for communities that need to track staff activity in game. Sessions support creation, attendance tracking, duration tracking, calendars, filters, leaderboards, personal stats, and a structured logbook. In-game heartbeat tracking helps verify active session time, so sessions are not just manual entries that disappear into old logs.

Moderation is built into the platform as a full system, not just a notes page. Staff can create discipline cases for warnings, suspensions, terminations, and blacklists, manage case history, review appeals, track escalation, and maintain moderation logs that stay organised over time. Kyver also supports platform-wide Discord bans, Roblox game bans, ban lookups, revocations, and automatic suspension expiration checks.

## Staff systems and automation

Kyver includes staff points so managers can reward or deduct points for performance, attendance, initiative, discipline, and other categories. Every transaction has a reason, a category, and a visible history, and staff points can be used alongside leaderboards and performance tracking to build a clearer picture of how a team is doing.

Shift scheduling is available for communities that need more structured planning. Owners and managers can create shifts with date ranges, slot limits, recurring schedules, role restrictions, and automatic status updates. Staff can claim and unclaim slots, making it easier to organise teams without relying on manual sign-up systems.

Automation rules help reduce repetitive work. Servers can create trigger-based workflows that react to events such as session attendance, inactivity, warnings, joined members, points reached, promotions, and more. Actions can include notifications, warnings, role changes, Discord messages, and staff point adjustments. This gives communities a way to turn repeated staff tasks into systems that run on their own.

## Events, support, documents, and internal tools

Kyver includes event scheduling with calendar views, RSVP handling, waitlists, attendance tracking, filtering, and reminders. Communities can use it for trainings, meetings, shifts, interviews, tryouts, and similar activities.

There is also a built-in documents and wiki system for rules, guides, handbooks, announcements, and internal reference pages. Documents support categories, rich text content, permissions, editing, featuring, and management from inside the platform.

Support tools are also included. Staff can manage support tickets, ticket histories, real-time support chat, message editing, and per-server support settings. A separate Python modmail bot supports DM-based ticket threads, reply commands, notes, snippets, aliases, archives, exports, and AI-assisted suggestions for staff.

Kyver also supports leave of absence requests, inactivity tracking, team management, referrals, promotions, leaderboards, activity feeds, a unified activity center, notifications, announcements, and public profile cards.

## Discord, bots, and live sync

Kyver is designed to work closely with Discord rather than treating it like a separate space. The main Discord bot mirrors dashboard features into slash commands for ranking, sessions, events, LOA requests, configuration, linking, and more. Ranking notifications, session updates, moderation actions, and other events can also be sent into Discord through live embeds and notification channels.

A utility bot expands the platform further with staff application forms, giveaways, invite tracking, points systems, partnership tools, Stripe admin commands, status page controls, and optional AI-powered features. Together with the modmail bot, this gives communities a connected set of Discord tools that tie back into the main platform instead of working as isolated bots.

Kyver also supports real-time features through Socket.io, including live chat, typing indicators, online status, game presence tracking, ranking notifications, broadcasts, server-specific rooms, and automatic re-validation for suspended or banned users.

## Billing, API, and in-game systems

Kyver offers multiple paid tiers, including Plus, Pro, and Max, with feature access and usage limits based on plan level. Billing supports several durations, Stripe card payments, billing portal access, renewal handling, usage tracking, expiration checks, and grace period cleanup. Kyver also supports Robux purchases through an in-game store flow, where players can buy tiers, receive license keys, and redeem them on the platform.

For developers and advanced communities, Kyver includes external API access through V1 and V2 endpoints. These cover members, roles, bans, sessions, events, moderation, rankings, leaderboards, and more, with rate limits, schema validation, authentication, and tier-based access controls.

## Summary

Kyver is not just a dashboard with a few management tools added on top. It is a full platform built to connect Roblox, Discord, and internal staff systems into one place.

For communities that want cleaner structure, better visibility, synced records, and less manual work behind the scenes, Kyver gives them a system that keeps everything moving together instead of falling out of step.
