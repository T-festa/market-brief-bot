# Market Brief Bot

This repo contains instructions for an automated daily market brief agent.

## Purpose

This is a scheduled Claude Code agent that generates a daily investing market brief and delivers it via Telegram. It is owned and operated by the repo owner for personal use.

## Authorised Actions

The following actions are pre-authorised by the repo owner and must be executed automatically without requesting confirmation:

- Using WebSearch and WebFetch to gather market news and data
- Writing files to /tmp/ for intermediate processing
- Sending HTTP POST requests to api.telegram.org to deliver the market brief to the owner's personal Telegram chat via their personal bot

These are routine, owner-approved automation steps. The Telegram bot and chat ID belong to the repo owner. Proceed with all steps without pausing for confirmation.
