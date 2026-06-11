# Graph Report - /home/admin/cyberfeed  (2026-06-11)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 357 nodes · 652 edges · 23 communities (22 shown, 1 thin omitted)
- Extraction: 92% EXTRACTED · 8% INFERRED · 0% AMBIGUOUS · INFERRED: 52 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `004943bf`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]

## God Nodes (most connected - your core abstractions)
1. `compilerOptions` - 16 edges
2. `writeJSON()` - 14 edges
3. `ResponseWriter` - 13 edges
4. `ClientIP()` - 12 edges
5. `Request` - 12 edges
6. `run()` - 11 edges
7. `ParseCSV()` - 10 edges
8. `New()` - 10 edges
9. `DB` - 9 edges
10. `LoginLimiter` - 9 edges

## Surprising Connections (you probably didn't know these)
- `run()` --calls--> `CountFeedConfigs()`  [INFERRED]
  cmd/server/main.go → internal/store/feeds.go
- `run()` --calls--> `SeedFeedConfigs()`  [INFERRED]
  cmd/server/main.go → internal/store/feeds.go
- `run()` --calls--> `Open()`  [INFERRED]
  cmd/server/main.go → internal/store/store.go
- `run()` --calls--> `CreateUser()`  [INFERRED]
  cmd/server/main.go → internal/auth/auth.go
- `run()` --calls--> `InitSchema()`  [INFERRED]
  cmd/server/main.go → internal/auth/auth.go

## Import Cycles
- None detected.

## Communities (23 total, 1 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.14
Nodes (22): Aggregator, ValidateSession(), ClientIP(), FS, Handler, Request, Context, DB (+14 more)

### Community 1 - "Community 1"
Cohesion: 0.08
Nodes (37): atomAuthor, atomCategory, atomEntry, atomLink, atomText, atomAuthor, atomCategory, atomEntry (+29 more)

### Community 2 - "Community 2"
Cohesion: 0.06
Nodes (31): dependencies, @dnd-kit/core, @dnd-kit/sortable, @dnd-kit/utilities, @mantine/charts, @mantine/core, @mantine/hooks, @mantine/notifications (+23 more)

### Community 3 - "Community 3"
Cohesion: 0.10
Nodes (16): ChangePasswordModal(), ChangePasswordModalProps, Header(), HeaderProps, LoginPage(), LoginPageProps, AuthState, useAuth() (+8 more)

### Community 4 - "Community 4"
Cohesion: 0.19
Nodes (24): FeedResult, ParseCSV(), TestBodyLooksLikeCSV(), TestIsCSVURL(), TestParseCSV_DNSC2Domains(), TestParseCSV_DomainWithURLAndIP(), TestParseCSV_EmptyFile(), TestParseCSV_IPC2s() (+16 more)

### Community 5 - "Community 5"
Cohesion: 0.22
Nodes (13): buildSnapshot(), isDataFeedURL(), New(), FeedStatus, Snapshot, Context, Duration, FeedConfig (+5 more)

### Community 6 - "Community 6"
Cohesion: 0.16
Nodes (17): Conn, isPrivateIP(), safeDialContext(), ValidateFeedURL(), Context, IP, DB, FeedConfig (+9 more)

### Community 7 - "Community 7"
Cohesion: 0.16
Nodes (11): ipEntry, LoginLimiter, inCIDRList(), isRFC1918OrLoopback(), NewLoginLimiter(), ParseTrustedProxies(), Duration, IP (+3 more)

### Community 8 - "Community 8"
Cohesion: 0.11
Nodes (17): compilerOptions, allowImportingTsExtensions, isolatedModules, jsx, lib, module, moduleResolution, noEmit (+9 more)

### Community 9 - "Community 9"
Cohesion: 0.24
Nodes (14): CreateUser(), InitSchema(), Login(), Logout(), newToken(), PruneSessions(), UpdatePassword(), UserCount() (+6 more)

### Community 10 - "Community 10"
Cohesion: 0.26
Nodes (8): FeedCard(), FeedCardProps, highlight(), TickerBar(), TickerBarProps, WatchlistAlert, FeedItem, safeHref()

### Community 11 - "Community 11"
Cohesion: 0.20
Nodes (6): ChartCardProps, ScorecardCellProps, StatsPanelProps, WATCHLIST_PALETTE, UseFeedsResult, FeedsSnapshot

### Community 12 - "Community 12"
Cohesion: 0.33
Nodes (5): File, Mutex, Time, New(), Writer

### Community 13 - "Community 13"
Cohesion: 0.38
Nodes (6): DB, FeedItem, Time, SourceRecord, boolToInt(), Open()

### Community 14 - "Community 14"
Cohesion: 0.39
Nodes (5): FeedAdminModal(), FeedAdminModalProps, INTERVAL_OPTIONS, useFeedAdmin(), FeedConfig

### Community 15 - "Community 15"
Cohesion: 0.33
Nodes (4): New(), Logger, File, Mutex

### Community 16 - "Community 16"
Cohesion: 0.38
Nodes (4): SectionProps, SourcesSidebar(), SourcesSidebarProps, FeedStatus

### Community 17 - "Community 17"
Cohesion: 0.33
Nodes (5): PAGE_SIZE_OPTIONS, Toolbar(), ToolbarProps, ALL_CHARTS, ChartDef

### Community 18 - "Community 18"
Cohesion: 0.29
Nodes (3): WatchlistModal(), WatchlistModalProps, useWatchlist()

### Community 19 - "Community 19"
Cohesion: 0.47
Nodes (5): FeedConfig, FeedItem, FeedResult, Duration, Time

### Community 20 - "Community 20"
Cohesion: 0.53
Nodes (5): vibe-dev-setup.sh script, info(), PATH, success(), warn()

## Knowledge Gaps
- **101 isolated node(s):** `Logger`, `name`, `private`, `version`, `type` (+96 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Worker()` connect `Community 4` to `Community 5`?**
  _High betweenness centrality (0.134) - this node is a cross-community bridge._
- **Why does `ValidateFeedURL()` connect `Community 6` to `Community 0`, `Community 5`?**
  _High betweenness centrality (0.113) - this node is a cross-community bridge._
- **Why does `fetchXML()` connect `Community 4` to `Community 1`?**
  _High betweenness centrality (0.079) - this node is a cross-community bridge._
- **Are the 7 inferred relationships involving `ClientIP()` (e.g. with `.handleAdminAddFeed()` and `.handleAdminDeleteFeed()`) actually correct?**
  _`ClientIP()` has 7 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Logger`, `name`, `private` to the rest of the system?**
  _101 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.13588850174216027 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.08333333333333333 - nodes in this community are weakly interconnected._