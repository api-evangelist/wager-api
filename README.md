# Wager API

Wager API is a modern sports betting data platform that enables developers to build sports betting applications, bots, and predictive models with a single API. The platform provides real-time sports odds including spreads, moneylines, totals, player props, and futures markets across NFL, NCAA, NBA, MLB, NHL, soccer, tennis, and golf.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Sports Betting
- Sports Odds
- Fantasy Sports
- Sports Data
- NFL
- NBA
- MLB
- NHL
- NCAA

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-03

## APIs

| API | Description |
|---|---|
| [Wager API - Sports Odds](https://wagerapi.com/) | Real-time game odds, player props, and futures for NFL, NCAA, NBA, MLB, NHL, soccer, tennis, golf |
| [Wager API - Fantasy Sports Data](https://wagerapi.com/) | Player statistics, projections, injury reports, lineups, and depth charts |

## OpenAPI Specifications

- [wager-api-openapi.yml](openapi/wager-api-openapi.yml) — Complete Wager API including odds, props, futures, players, injuries, games, and depth charts

## JSON Schemas

- [wager-api-game-odds-schema.json](json-schema/wager-api-game-odds-schema.json) — Game odds data model with markets schema

## JSON Structure

- [wager-api-game-odds-structure.json](json-structure/wager-api-game-odds-structure.json) — Game odds structure documentation

## JSON-LD Context

- [wager-api-context.jsonld](json-ld/wager-api-context.jsonld) — Linked data context mapping sports betting vocabulary to schema.org

## Examples

- [wager-api-get-game-odds-example.json](examples/wager-api-get-game-odds-example.json) — Get NFL game odds with spread, moneyline, and totals
- [wager-api-get-player-props-example.json](examples/wager-api-get-player-props-example.json) — Get player prop odds for a game

## Spectral Rules

- [wager-api-rules.yml](rules/wager-api-rules.yml) — Spectral ruleset enforcing Wager API conventions

## Naftiko Capabilities

### Shared Definitions

- [capabilities/shared/wager-api.yaml](capabilities/shared/wager-api.yaml) — Wager API consumed definitions (9 operations)

### Workflow Capabilities

- [capabilities/sports-betting.yaml](capabilities/sports-betting.yaml) — Comprehensive sports betting workflow with odds, props, futures, injuries, stats, and schedules (9 REST endpoints, 8 MCP tools)

## Vocabulary

- [wager-api-vocabulary.yml](vocabulary/wager-api-vocabulary.yml) — Sports betting odds, fantasy sports, and sports data vocabulary

## Common Properties

- [Website](https://wagerapi.com/)
- [Contact](https://wagerapi.com/#contact)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
