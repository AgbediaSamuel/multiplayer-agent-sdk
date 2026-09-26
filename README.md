# Multiplayer Agent SDK

A capstone project exploring a reusable collaboration layer for existing AI agent interfaces.

## Goal

The first version will let several humans share one authoritative agent run. Participants should see the same ordered session history and live output, contribute attributed messages, see presence, and catch up after a dropped connection.

The SDK will provide session, participant, message, and event interfaces. The host application will decide which human messages reach its agent and will retain control of its agent loop, tools, approvals, and UI.

## Planned evaluation

- Demonstrate two clients collaborating around one agent run in a small reference interface.
- Test ordering, participant attribution, reconnection, and retried submissions.
- Integrate the SDK into a second host interface to test whether the contract is reusable. OpenCode is a candidate, subject to scope.

## Status

The project is at the brief and design stage. No SDK implementation or evaluation results are claimed yet. The API and guarantees will be documented as they are developed.
