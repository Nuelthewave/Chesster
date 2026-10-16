# 1.0.0 (2026-10-16)


### Bug Fixes

* **auth:** bound challenge store with expiry sweep and capacity policy ([#391](https://github.com/Nuelthewave/Chesster/issues/391)) ([81fa366](https://github.com/Nuelthewave/Chesster/commit/81fa3661aa5b697b49bbfcd4c0ebba04b6808806))
* **backend:** keep deletion sessions revoked ([f9af09e](https://github.com/Nuelthewave/Chesster/commit/f9af09e24f847519564d28726f17afd0e0e7f352))
* **backend:** prune archived game partitions ([f70c91d](https://github.com/Nuelthewave/Chesster/commit/f70c91d345c6ce34d4b8dc51c392b601c2b1415f))
* **backend:** validate coordinator secret key gracefully and support env alias fallback keys ([cfa57d3](https://github.com/Nuelthewave/Chesster/commit/cfa57d3d3da3dc160d08b71ef989cfafb87b5214))
* **build:** configure visualizer plugin for bundle stats generation ([5c701f9](https://github.com/Nuelthewave/Chesster/commit/5c701f992a78391cbab32f07b600d012bebd8df6))
* **ci:** refresh backend lockfile ([41de40b](https://github.com/Nuelthewave/Chesster/commit/41de40bb0e96bb7426663aa5d2aa6e18687bc1f5))
* **ci:** restore Node 24 in .nvmrc for native Jest ESM require support ([1c21402](https://github.com/Nuelthewave/Chesster/commit/1c21402107a3ec1cea22a34815ad72f336b84461))
* **contracts:** fix clippy len_zero warning in test.rs ([90c2354](https://github.com/Nuelthewave/Chesster/commit/90c235493bb3786a5957d9e7f5ca273331bf93cd))
* **contracts:** reconcile EscrowError limits and format after upstream merge ([be8785a](https://github.com/Nuelthewave/Chesster/commit/be8785a4b9d07e54dbd518df43c7dfd33c00f699))
* **contracts:** reconcile EscrowError limits and format after upstream merge ([40dc134](https://github.com/Nuelthewave/Chesster/commit/40dc134fcd3e60d1ce1276475d7cf9ca80afc4b6))
* **contracts:** repair escrow test boundaries ([e6119ab](https://github.com/Nuelthewave/Chesster/commit/e6119ab1d5f10ed13c8ecd979f83716197d6feba))
* correct workspace CI dependency paths ([99c6f5f](https://github.com/Nuelthewave/Chesster/commit/99c6f5f627b10b4a747c098feb0526025926fb88))
* **database:** add existence checks for optional tables in RLS migration ([#137](https://github.com/Nuelthewave/Chesster/issues/137)) ([8ee29b5](https://github.com/Nuelthewave/Chesster/commit/8ee29b51e552152efa0f2a668cef684e1091a85a))
* **database:** add indexes for game and move queries ([6b76cea](https://github.com/Nuelthewave/Chesster/commit/6b76ceaeb46b1e0fa9e8ec62a7fe9cc0e5656898))
* **database:** drop end_reason from seed (column not in canonical schema) ([c39d4c2](https://github.com/Nuelthewave/Chesster/commit/c39d4c2bcabfd6aa74b8454080991fea1c73c625))
* **database:** sync package-lock with pg dependency ([7abc974](https://github.com/Nuelthewave/Chesster/commit/7abc974180e5e938fff854711cb92886a0c0c4fa))
* **escrow:** resolve clippy bool_assert_comparison warning in test.rs ([e3e5227](https://github.com/Nuelthewave/Chesster/commit/e3e5227855f2554072a0ae96737a198dde03de9e))
* **escrow:** resolve clippy warnings and update wasm size budget limit ([8b66ec1](https://github.com/Nuelthewave/Chesster/commit/8b66ec1363eb62eecb8a7a4d3e41d181b5329468))
* fix payout model ([b553e28](https://github.com/Nuelthewave/Chesster/commit/b553e28575e8b6c44d542525b25faa7b8365fa57))
* **frontend:** remove leave game button while waiting for opponent ([601e34a](https://github.com/Nuelthewave/Chesster/commit/601e34a75ec967b66afd4991c0951736647d0c3e))
* **frontend:** repair SpectatorPage and ChessBoard broken by merge conflicts ([b1566c2](https://github.com/Nuelthewave/Chesster/commit/b1566c22ae2d8bd6cd83aff727c175b12fba4916))
* **frontend:** resolve ESLint errors and Vitest config type overload ([ca643d9](https://github.com/Nuelthewave/Chesster/commit/ca643d91414696c57dfe69c20fa72fade005ff18))
* **health:** update database provider name to Neon PostgreSQL and simplify status page design ([c86a588](https://github.com/Nuelthewave/Chesster/commit/c86a5883999ed7070753a6b21caed75b061d7ce2))
* repair corrupted ChessBoard and GameResultModal components ([e20b18d](https://github.com/Nuelthewave/Chesster/commit/e20b18debb1f3c3d929ced4a78454d7a6769e798))
* resolve build and test failures across frontend, backend, and contracts ([aff2196](https://github.com/Nuelthewave/Chesster/commit/aff219652ea062df677cef2b42f580e7e1dff089))
* resolve cross-origin CSRF validation in production and refine game layout ([69bec13](https://github.com/Nuelthewave/Chesster/commit/69bec138161cf66797a4463de73792507ab0866f))
* resolve frontend/backend env validation and DB schema fallback for time control columns ([ff43083](https://github.com/Nuelthewave/Chesster/commit/ff430839de28b409626af12cfb93029a906683c7))
* resolve issue [#225](https://github.com/Nuelthewave/Chesster/issues/225) ([#270](https://github.com/Nuelthewave/Chesster/issues/270)) ([6f36f74](https://github.com/Nuelthewave/Chesster/commit/6f36f74e0e26ace0dd167325cf41dd9c7952cf63))
* resolve issues [#386](https://github.com/Nuelthewave/Chesster/issues/386), [#387](https://github.com/Nuelthewave/Chesster/issues/387), [#388](https://github.com/Nuelthewave/Chesster/issues/388), [#447](https://github.com/Nuelthewave/Chesster/issues/447) (closes [#386](https://github.com/Nuelthewave/Chesster/issues/386), closes [#387](https://github.com/Nuelthewave/Chesster/issues/387), closes [#388](https://github.com/Nuelthewave/Chesster/issues/388), closes [#447](https://github.com/Nuelthewave/Chesster/issues/447)) ([#451](https://github.com/Nuelthewave/Chesster/issues/451)) ([bd754a8](https://github.com/Nuelthewave/Chesster/commit/bd754a8ad581b78b707fe9f254c85750aeca08df))
* resolve smart contract compilation errors, frontend TS build, and test suite configs ([6e83092](https://github.com/Nuelthewave/Chesster/commit/6e83092faa04528fb9bce38f4e65b0364eb3bb23))
* **seo:** add meta description and robots.txt for Lighthouse SEO compliance ([55047cb](https://github.com/Nuelthewave/Chesster/commit/55047cbfdf358e10d46fa19f4bf6fa000628da20))
* stabilize backend CI test environment ([5f306c8](https://github.com/Nuelthewave/Chesster/commit/5f306c8d1a6fda90dca44151feeb664b7c44e3da))
* stabilize backend CI test environment ([42d5860](https://github.com/Nuelthewave/Chesster/commit/42d58602f7bd9842b105bab003568f55867f8909))
* **test:** resolve Node 22 ESM require error, test env variables, and redis handles ([6a6b6a4](https://github.com/Nuelthewave/Chesster/commit/6a6b6a425c59fcdbdc98c9c5aea8590a7b9b35d2))
* **tests:** resolve escrow test duplication and db health service cache reset ([2ab39aa](https://github.com/Nuelthewave/Chesster/commit/2ab39aa7869fb5d270282de8f1e3402ff8f6e18f))
* **ui:** improve mobile responsiveness and remove overlapping banners and floating controls ([c113498](https://github.com/Nuelthewave/Chesster/commit/c11349829ceed5c08838418488be351a4e1a35e1))


### Features

* **#304:** Implement spectator chat slow-mode and room isolation ([11b0a18](https://github.com/Nuelthewave/Chesster/commit/11b0a187f2648405a4f56c29acace2e19c4ec584)), closes [#304](https://github.com/Nuelthewave/Chesster/issues/304)
* **#306:** Interactive Tactical Puzzle Solver with Hint System ([f2b0ddd](https://github.com/Nuelthewave/Chesster/commit/f2b0ddd1e0aba1aafe5f218145f314e3629b5f2a)), closes [#306](https://github.com/Nuelthewave/Chesster/issues/306)
* add configurable regional wager blocking ([eadb5c0](https://github.com/Nuelthewave/Chesster/commit/eadb5c0c7cf97db4ac8d16a9041e3892390f3373))
* add custom sound theme packs (wood, plastic, arcade, retro 8-bit) ([f468bc1](https://github.com/Nuelthewave/Chesster/commit/f468bc18399aee75a2875aac0f8b11d80bf9b2e0)), closes [#307](https://github.com/Nuelthewave/Chesster/issues/307)
* add escrow retries whitelist and events ([c3edf69](https://github.com/Nuelthewave/Chesster/commit/c3edf691b5629ebea7d0020c6767903e2d226260))
* add escrow unresolved-match fallback ([883b464](https://github.com/Nuelthewave/Chesster/commit/883b4648fafd8b4e6551cf680487f9388e8139a2))
* add low-time warning alert with pulsing border and tick sound ([fbd8e76](https://github.com/Nuelthewave/Chesster/commit/fbd8e762945fc70478b6a56550ebe9cc0099e5bc)), closes [#309](https://github.com/Nuelthewave/Chesster/issues/309)
* add share match link QR code to game lobby ([44de0ef](https://github.com/Nuelthewave/Chesster/commit/44de0ef1e1d3bc0e6182e631b4f6185556a31a99))
* add spectator reactions, themes, controls, and csrf ([7dd4527](https://github.com/Nuelthewave/Chesster/commit/7dd4527b58147e74d21a8c680e287bdcc588af22))
* anti-cheat telemetry, helmet CORS/CSP, touch gestures, animation improvements ([f73de28](https://github.com/Nuelthewave/Chesster/commit/f73de28185075b66218c954419a2ac5b0955aca8)), closes [#105](https://github.com/Nuelthewave/Chesster/issues/105) [#106](https://github.com/Nuelthewave/Chesster/issues/106) [#116](https://github.com/Nuelthewave/Chesster/issues/116) [#120](https://github.com/Nuelthewave/Chesster/issues/120)
* **backend,contracts:** match creation rate limiting, api docs, tournament rake, and disqualification slashing (closes [#151](https://github.com/Nuelthewave/Chesster/issues/151), closes [#152](https://github.com/Nuelthewave/Chesster/issues/152), closes [#221](https://github.com/Nuelthewave/Chesster/issues/221), closes [#222](https://github.com/Nuelthewave/Chesster/issues/222)) ([5ee7463](https://github.com/Nuelthewave/Chesster/commit/5ee7463241d94d809d92824276a8c0e3cdaa4e6d))
* **backend:** add account privacy redaction ([31e417f](https://github.com/Nuelthewave/Chesster/commit/31e417f75e98146c90e15896ccfcbd58957aa66a))
* **backend:** add asynchronous event broadcasting ([7bfb067](https://github.com/Nuelthewave/Chesster/commit/7bfb0672a4cbd944d01603eef7a3bd1f965e87f3))
* **backend:** add automated game archival ([360cb3d](https://github.com/Nuelthewave/Chesster/commit/360cb3decb61b49b866e32609ba0f1de0b4ea421))
* **backend:** add daily active player and match volume aggregation service ([#69](https://github.com/Nuelthewave/Chesster/issues/69)) ([8a7de90](https://github.com/Nuelthewave/Chesster/commit/8a7de9056a3d5f7b393ddef6f89afedc8ee81fc8))
* **backend:** add daily chess puzzles ([5bcaf11](https://github.com/Nuelthewave/Chesster/commit/5bcaf1168916b7722c5f9f7061f81b33215dc1fb))
* **backend:** add dynamic elo bucket expansion to matchmaking ([b0267d8](https://github.com/Nuelthewave/Chesster/commit/b0267d89f8c9228bf723cdbf38400b0b9f41519e)), closes [#248](https://github.com/Nuelthewave/Chesster/issues/248)
* **backend:** add global exception handling & Sentry error reporting middleware ([#61](https://github.com/Nuelthewave/Chesster/issues/61)) ([01ac707](https://github.com/Nuelthewave/Chesster/commit/01ac707ebeadc574dfb1d800bbba887aa1f9ddfa))
* **backend:** add IP rate limiting for WebSocket handshakes ([25cd6c8](https://github.com/Nuelthewave/Chesster/commit/25cd6c83383f2fc300031c6ba54722f7fdd7d240)), closes [#244](https://github.com/Nuelthewave/Chesster/issues/244)
* **backend:** add JWT authentication middleware for profile customization ([0029b98](https://github.com/Nuelthewave/Chesster/commit/0029b981153d48bc06f36b8df4f8f4f4a6143687))
* **backend:** add match audit log export API for dispute resolution ([94f62c8](https://github.com/Nuelthewave/Chesster/commit/94f62c81a1ad2aeda84dd0bc36f6018f66b58fed)), closes [#243](https://github.com/Nuelthewave/Chesster/issues/243)
* **backend:** add referral commission tracking ([43347bf](https://github.com/Nuelthewave/Chesster/commit/43347bfbb937561cc603bc80ded2a78fb1813c40))
* **backend:** add Stockfish AI bot opponent endpoint for single player ([7b2fc89](https://github.com/Nuelthewave/Chesster/commit/7b2fc897b3fb5ba1dc09a0b6b4727029f8f72e6e))
* **backend:** Add structured logging, health checks, PGN/FEN support, and Stellar indexer ([c5cfa80](https://github.com/Nuelthewave/Chesster/commit/c5cfa80778f36852e50dc0f9cb5fc4e1948cc0a1))
* **backend:** add webhook exponential backoff and dead-letter queue ([f527e8f](https://github.com/Nuelthewave/Chesster/commit/f527e8f2ebf1dce6ac1acbfd4ad22358d72b12e5)), closes [#246](https://github.com/Nuelthewave/Chesster/issues/246)
* **backend:** cache user profile stats and match history in redis ([8a76331](https://github.com/Nuelthewave/Chesster/commit/8a763312e68ce144d45776589d1ed48deea93dbd)), closes [#247](https://github.com/Nuelthewave/Chesster/issues/247)
* **backend:** configure Prisma ORM with Supabase connection pooling and schema sync ([154e3ee](https://github.com/Nuelthewave/Chesster/commit/154e3eee0f8502b73ab8fc31b2dbdeaeb267dd7b))
* **backend:** dispatch tournament notifications ([61e4e23](https://github.com/Nuelthewave/Chesster/commit/61e4e23d4b2a1c1fea4bab20a3dfc55c27bc7092))
* **backend:** enable websocket per-message deflate ([b6e68db](https://github.com/Nuelthewave/Chesster/commit/b6e68db91eafb251114e6c2300ab256b831cb628))
* **backend:** enforce wager geo compliance ([e6a8567](https://github.com/Nuelthewave/Chesster/commit/e6a8567ee63fb7ec9c5159a740471f35fc2779e7))
* **backend:** export rich PGN game records ([#393](https://github.com/Nuelthewave/Chesster/issues/393)) ([5a6cdb5](https://github.com/Nuelthewave/Chesster/commit/5a6cdb5953cf1bb562f388bda7030785987cf400))
* **backend:** Implement Distributed Lock for Move Submission using Redis Redlock - Closes [#239](https://github.com/Nuelthewave/Chesster/issues/239) ([75d8595](https://github.com/Nuelthewave/Chesster/commit/75d859539ce4da4cb959593a81f0e6ba6269d4cb))
* **backend:** implement Elo rating update calculation service ([#66](https://github.com/Nuelthewave/Chesster/issues/66)) ([01c966f](https://github.com/Nuelthewave/Chesster/commit/01c966fc6553eaf72dbb25705cb0a9fa6ffe28fb))
* **backend:** implement GET /api/leaderboard endpoint and player stats synchronization ([ab62776](https://github.com/Nuelthewave/Chesster/commit/ab62776d63787cc9492be5347b56b8ed85438dda))
* **backend:** Implement Matchmaking Queue with Elo-Based Rating Pairings ([4e784a8](https://github.com/Nuelthewave/Chesster/commit/4e784a8cb0d42c895eb202367e5886780a1b81fd))
* **backend:** Implement move validation cache, cron cleanup, paginated history, and undo protocol ([18c7696](https://github.com/Nuelthewave/Chesster/commit/18c7696965358a3b01e4faf3aa2331b3d19fec7c)), closes [#60](https://github.com/Nuelthewave/Chesster/issues/60) [#59](https://github.com/Nuelthewave/Chesster/issues/59) [#58](https://github.com/Nuelthewave/Chesster/issues/58) [#54](https://github.com/Nuelthewave/Chesster/issues/54) [#60](https://github.com/Nuelthewave/Chesster/issues/60) [#59](https://github.com/Nuelthewave/Chesster/issues/59) [#58](https://github.com/Nuelthewave/Chesster/issues/58) [#54](https://github.com/Nuelthewave/Chesster/issues/54)
* **backend:** Implement Real-Time Socket.io Tournament Lifecycle Events ([8d40f80](https://github.com/Nuelthewave/Chesster/commit/8d40f80de44653664e82450e121732fd548adb73))
* **backend:** Implement Redis Adapter for Socket.io Clustering & Horizontal Scaling - Closes [#238](https://github.com/Nuelthewave/Chesster/issues/238) ([99707a0](https://github.com/Nuelthewave/Chesster/commit/99707a0af4b63ea07e07b6ac9d3246004d464240))
* **backend:** implement threefold repetition and 50-move draw detection ([8f87590](https://github.com/Nuelthewave/Chesster/commit/8f87590b2c8c67956b62949eaf3396ab6d0dbb32)), closes [#242](https://github.com/Nuelthewave/Chesster/issues/242)
* **backend:** implement webhook notification service for match payout confirmations ([918336a](https://github.com/Nuelthewave/Chesster/commit/918336a25ec4a04dd31d937d0fc4469a0b92de61)), closes [#48](https://github.com/Nuelthewave/Chesster/issues/48) [#49](https://github.com/Nuelthewave/Chesster/issues/49) [#50](https://github.com/Nuelthewave/Chesster/issues/50) [#51](https://github.com/Nuelthewave/Chesster/issues/51)
* **backend:** Implement WebSocket Latency Telemetry and Automatic Disconnect Grace Period - Closes [#240](https://github.com/Nuelthewave/Chesster/issues/240) ([9013e8f](https://github.com/Nuelthewave/Chesster/commit/9013e8f7131a3ad29a4d716f80a532998d5d1fcb))
* **backend:** migrate from Supabase to Neon PostgreSQL and Prisma ([dae00f8](https://github.com/Nuelthewave/Chesster/commit/dae00f86f67a29a83cfc89bc19c93f5f393fadd0))
* **backend:** persist anti-cheat analysis ([07b7f25](https://github.com/Nuelthewave/Chesster/commit/07b7f25e0224d8037c4fee10a91a44a1daf3fcf9))
* **backend:** run stockfish bot moves in a worker thread pool ([c8519d4](https://github.com/Nuelthewave/Chesster/commit/c8519d49b09fc0c06d8820a958a4346c33fcec58)), closes [#241](https://github.com/Nuelthewave/Chesster/issues/241)
* **backend:** Socket.io reconnect grace period + per-player clock increments ([6de060d](https://github.com/Nuelthewave/Chesster/commit/6de060d2a516f26b51796569e3c0f9a7239a13ff)), closes [#43](https://github.com/Nuelthewave/Chesster/issues/43) [#45](https://github.com/Nuelthewave/Chesster/issues/45)
* **backend:** stream game replays over server-sent events ([077b6ba](https://github.com/Nuelthewave/Chesster/commit/077b6ba4a199022f5deca22cc59ade19828c2e44)), closes [#245](https://github.com/Nuelthewave/Chesster/issues/245)
* **batch:** resolve assigned issues 397, 398, 399, 400 (closes [#397](https://github.com/Nuelthewave/Chesster/issues/397), [#398](https://github.com/Nuelthewave/Chesster/issues/398), [#399](https://github.com/Nuelthewave/Chesster/issues/399), [#400](https://github.com/Nuelthewave/Chesster/issues/400)) ([#453](https://github.com/Nuelthewave/Chesster/issues/453)) ([4c0c6f8](https://github.com/Nuelthewave/Chesster/commit/4c0c6f8d359295484b3b8f877c8e6f185aff7706))
* board social card image generator (closes [#310](https://github.com/Nuelthewave/Chesster/issues/310)) ([670fc78](https://github.com/Nuelthewave/Chesster/commit/670fc78f7554b60188a5e8c38fb728e8ca20f90e))
* **chess:** add blindfold and fog-of-war variants ([#395](https://github.com/Nuelthewave/Chesster/issues/395)) ([626a824](https://github.com/Nuelthewave/Chesster/commit/626a8241dcacf8758e61981ef754dca555cf5ee5))
* **contracts,backend:** implement escrow features for issues [#287](https://github.com/Nuelthewave/Chesster/issues/287), [#288](https://github.com/Nuelthewave/Chesster/issues/288), [#289](https://github.com/Nuelthewave/Chesster/issues/289), and [#290](https://github.com/Nuelthewave/Chesster/issues/290) ([4e35ce1](https://github.com/Nuelthewave/Chesster/commit/4e35ce17a5416b47c3be1f8233a0bd080a8a05ff))
* **contracts,ci:** bound stale match GC batches and pin GitHub Actions to commit SHAs (closes [#379](https://github.com/Nuelthewave/Chesster/issues/379), closes [#380](https://github.com/Nuelthewave/Chesster/issues/380)) ([2293056](https://github.com/Nuelthewave/Chesster/commit/229305637594b42dd4ef394ef5abca1b0bf4aead))
* **contracts:** Add comprehensive escrow enhancements ([6f6c89f](https://github.com/Nuelthewave/Chesster/commit/6f6c89f0830d81d4240fd52ff70fabc72923a48d)), closes [#33](https://github.com/Nuelthewave/Chesster/issues/33) [#32](https://github.com/Nuelthewave/Chesster/issues/32) [#31](https://github.com/Nuelthewave/Chesster/issues/31) [#30](https://github.com/Nuelthewave/Chesster/issues/30)
* **contracts:** Add Comprehensive Rustdoc Comments, Stale Match GC, and Native XLM Utilities ([2f2fd6c](https://github.com/Nuelthewave/Chesster/commit/2f2fd6c5a38008459eebadf428d650e6f112dc51))
* **contracts:** Add Cryptographic Ed25519 Result Signature Verification in Escrow Settlement ([98a7a03](https://github.com/Nuelthewave/Chesster/commit/98a7a030e50701788eae50c82b12cd8cfbbe5b02)), closes [#233](https://github.com/Nuelthewave/Chesster/issues/233)
* **contracts:** add emergency pause circuit breaker (issue [#22](https://github.com/Nuelthewave/Chesster/issues/22)) ([910a11f](https://github.com/Nuelthewave/Chesster/commit/910a11ff5ce0c9423ab607eb6bcc321ec5e1bbb4))
* **contracts:** add escrow emergency drain safe-harbor with timelock delay ([f700309](https://github.com/Nuelthewave/Chesster/commit/f700309c5adb0f98b98fa66cd403db440aefabd4))
* **contracts:** Add match cancellation and cooperative mutual draw resolution ([#20](https://github.com/Nuelthewave/Chesster/issues/20)) ([b9118cb](https://github.com/Nuelthewave/Chesster/commit/b9118cba9c68ecf89ee48f5b9ab8c00d278ea1fe))
* **contracts:** add multi-sig emergency admin recovery scheme ([e9264aa](https://github.com/Nuelthewave/Chesster/commit/e9264aa48e9859da9125ad2921a37249cd73c908))
* **contracts:** Add On-Chain Event Emitting for Player Win Streak & Trophy Milestones - Closes [#237](https://github.com/Nuelthewave/Chesster/issues/237) ([fbdb3ea](https://github.com/Nuelthewave/Chesster/commit/fbdb3ea99636c8465445af07ee9c7af85b202185))
* **contracts:** add storage TTL auto-extension, allowance checks, dispute time-lock, and batch resolution ([807a876](https://github.com/Nuelthewave/Chesster/commit/807a8769a1bca8a5e4b6d642afe41eb2843d13b9))
* **contracts:** Escrow security hardening — coordinator rotation, reentrancy guard, balance invariants, upgradeability ([03f1eab](https://github.com/Nuelthewave/Chesster/commit/03f1eab8985b7f68dc0761fe447cef05377e4e3b)), closes [#100](https://github.com/Nuelthewave/Chesster/issues/100) [#103](https://github.com/Nuelthewave/Chesster/issues/103) [#104](https://github.com/Nuelthewave/Chesster/issues/104) [#102](https://github.com/Nuelthewave/Chesster/issues/102) [#100](https://github.com/Nuelthewave/Chesster/issues/100) [#102](https://github.com/Nuelthewave/Chesster/issues/102) [#103](https://github.com/Nuelthewave/Chesster/issues/103) [#104](https://github.com/Nuelthewave/Chesster/issues/104)
* **contracts:** Implement Batch Settlement Function for Concurrent Escrows ([516f067](https://github.com/Nuelthewave/Chesster/commit/516f067e61e0ea003772db1a20078e319a528429)), closes [#236](https://github.com/Nuelthewave/Chesster/issues/236)
* **contracts:** Implement Compact Binary Serialization for Match Storage to Reduce Soroban Gas ([3738574](https://github.com/Nuelthewave/Chesster/commit/3738574ca31c0fa8199728ee205dcb82d41b0f01)), closes [#234](https://github.com/Nuelthewave/Chesster/issues/234)
* **contracts:** implement dynamic platform fee discount for staked token holders ([efda452](https://github.com/Nuelthewave/Chesster/commit/efda452d67933e78d6058b61b36a90b529d4ef22))
* **contracts:** Implement Dynamic Wager Scaling with Configurable Minimum & Maximum Limits ([c5d44b6](https://github.com/Nuelthewave/Chesster/commit/c5d44b6e7275a0d97a7b295ad10d96d95ac334af)), closes [#23](https://github.com/Nuelthewave/Chesster/issues/23)
* **contracts:** implement match expiration & auto-claim refund timeout logic ([e391bc5](https://github.com/Nuelthewave/Chesster/commit/e391bc55195d745db3da1c5521eb60bb6f0fcaba)), closes [#19](https://github.com/Nuelthewave/Chesster/issues/19) [#21](https://github.com/Nuelthewave/Chesster/issues/21)
* **contracts:** implement match nonce, side betting pool, fee discount, and mutual cancellation ([d1b1e5a](https://github.com/Nuelthewave/Chesster/commit/d1b1e5a2d4aa2a513a4774aa6456c0312e28337b)), closes [#34](https://github.com/Nuelthewave/Chesster/issues/34) [#35](https://github.com/Nuelthewave/Chesster/issues/35) [#36](https://github.com/Nuelthewave/Chesster/issues/36) [#37](https://github.com/Nuelthewave/Chesster/issues/37)
* **contracts:** implement nonce-based replay protection for player deposit signatures ([90c3515](https://github.com/Nuelthewave/Chesster/commit/90c35156945a72108c3da08a139315ff95d79624))
* **contracts:** Implement On-Chain Player Elo Rating Ledger Proof ([93d6acb](https://github.com/Nuelthewave/Chesster/commit/93d6acba0b0e3224d05afa6f3c5c053553b1e383))
* **contracts:** Implement platform fee tiering and treasury vault configuration ([#19](https://github.com/Nuelthewave/Chesster/issues/19)) ([b9db53c](https://github.com/Nuelthewave/Chesster/commit/b9db53c606d4dc53d0f9e360c5b0179397b66ad7))
* **contracts:** implement player elo rating commitment and proof-of-skill on stellar ([2491c28](https://github.com/Nuelthewave/Chesster/commit/2491c28a8bcf9824be5300e74096389f877e4e71))
* **contracts:** Implement Time-Based Escrow Forfeit Protocol for Inactive Players ([5b1d670](https://github.com/Nuelthewave/Chesster/commit/5b1d67027dbd7a1960cdc81ceea6029a2fea5dd5)), closes [#231](https://github.com/Nuelthewave/Chesster/issues/231)
* **contracts:** Support Multi-Token Wagers in Soroban Escrow ([0b46b92](https://github.com/Nuelthewave/Chesster/commit/0b46b924fb273783ffa2265b5e348800e7526ec7))
* **contracts:** Support Soroban SAC Token Allowances for Multi-Asset Wagers (USDC / EURC) ([4b75a87](https://github.com/Nuelthewave/Chesster/commit/4b75a878298ffa381f3e9e5aa18e3818bcbb067f)), closes [#232](https://github.com/Nuelthewave/Chesster/issues/232)
* coordinate lobby expiry with Soroban escrow refund ([#396](https://github.com/Nuelthewave/Chesster/issues/396)) ([5a7a6c1](https://github.com/Nuelthewave/Chesster/commit/5a7a6c1eca39348cbd70803cf4f94e3891afa93c)), closes [#lobby-escrow-expiry](https://github.com/Nuelthewave/Chesster/issues/lobby-escrow-expiry)
* **database:** add automated encrypted PostgreSQL backup & snapshot script ([3d93bf3](https://github.com/Nuelthewave/Chesster/commit/3d93bf317bfbd291fb72ac7035f1256b0b3445f9)), closes [#119](https://github.com/Nuelthewave/Chesster/issues/119)
* **database:** add idempotent seed data script for local dev & E2E ([8d7dab4](https://github.com/Nuelthewave/Chesster/commit/8d7dab463dd2cc8c3a0b13d0e8f42dd4559b5973)), closes [#117](https://github.com/Nuelthewave/Chesster/issues/117)
* **database:** add migration runner script with rollback support ([69dc8fa](https://github.com/Nuelthewave/Chesster/commit/69dc8fa81716ab9db9174afab3fcf3458be6f719)), closes [#80](https://github.com/Nuelthewave/Chesster/issues/80)
* **database:** add move history JSONB schema validation constraint ([#77](https://github.com/Nuelthewave/Chesster/issues/77)) ([bb252f6](https://github.com/Nuelthewave/Chesster/commit/bb252f6d1a46b1b2b5e9bfe8c786f4e26dcbfc73))
* **database:** add player match statistics aggregation trigger ([#76](https://github.com/Nuelthewave/Chesster/issues/76)) ([6a745d8](https://github.com/Nuelthewave/Chesster/commit/6a745d854caa09be8f5d9529ce26193645d4b222))
* **database:** add soft delete and archival partitioning migration ([#74](https://github.com/Nuelthewave/Chesster/issues/74)) ([2737e83](https://github.com/Nuelthewave/Chesster/commit/2737e8351c43851bca1b2a1e47cb4d955c3d96d7))
* **database:** add token wager transaction ledger table migration ([#79](https://github.com/Nuelthewave/Chesster/issues/79)) ([d2e0c74](https://github.com/Nuelthewave/Chesster/commit/d2e0c74972c0c1a45fde3947ac412f42aff503a5))
* **database:** add tournament bracket and participant tables migration ([c902d26](https://github.com/Nuelthewave/Chesster/commit/c902d2646daed783abd8d19d3efc736f11f20e78))
* **database:** implement match_audit_logs table for dispute resolution ([96cfa54](https://github.com/Nuelthewave/Chesster/commit/96cfa54816795c760fd665d0f71ef660cd9684ea)), closes [#73](https://github.com/Nuelthewave/Chesster/issues/73)
* **database:** implement puzzles schema, seed script, and atomic escrow settle procedure (closes [#321](https://github.com/Nuelthewave/Chesster/issues/321), closes [#322](https://github.com/Nuelthewave/Chesster/issues/322)) ([c758713](https://github.com/Nuelthewave/Chesster/commit/c758713dec9cea5824382c23b30e12553e7a5c7a))
* **database:** implement Row-Level Security (RLS) policies for all Supabase tables ([#137](https://github.com/Nuelthewave/Chesster/issues/137)) ([e860208](https://github.com/Nuelthewave/Chesster/commit/e86020865e2ed8f493d03d71f67903745946b475))
* **database:** partition games table by month on created_at (012) ([cc63e5a](https://github.com/Nuelthewave/Chesster/commit/cc63e5ae83135d5a41b35b2098ba4033af287903)), closes [#118](https://github.com/Nuelthewave/Chesster/issues/118)
* **db:** [#319](https://github.com/Nuelthewave/Chesster/issues/319) player_rating_history table, [#320](https://github.com/Nuelthewave/Chesster/issues/320) referral_program and claimable_commission_ledger tables ([db5d00c](https://github.com/Nuelthewave/Chesster/commit/db5d00c41ccb4f0ccded0b0e372d0fc37112c344))
* **frontend:** add client-side stockfish evaluation bar ([5eaaca7](https://github.com/Nuelthewave/Chesster/commit/5eaaca7b167d9682b87005d562fa9f06241009fc)), closes [#250](https://github.com/Nuelthewave/Chesster/issues/250)
* **frontend:** add customizable board themes (Wood, Neon, Classic, Marble) ([bca8b13](https://github.com/Nuelthewave/Chesster/commit/bca8b1303e1a7ada5152d3016f159fdfaa7fc28b)), closes [#82](https://github.com/Nuelthewave/Chesster/issues/82)
* **frontend:** add customizable piece sets and board flip toggle ([#125](https://github.com/Nuelthewave/Chesster/issues/125), [#128](https://github.com/Nuelthewave/Chesster/issues/128)) ([7eb1c0f](https://github.com/Nuelthewave/Chesster/commit/7eb1c0f597dc163e2a79a90a50fc5e98bc4b2c4a))
* **frontend:** add in-app notification toast system for game invitations ([#126](https://github.com/Nuelthewave/Chesster/issues/126)) ([bb9b515](https://github.com/Nuelthewave/Chesster/commit/bb9b515ddc72cdf1b916b619e3de39ede5d3a765))
* **frontend:** add keyboard move input, leaderboard filters, disconnect banner, and PGN drag-and-drop ([197b889](https://github.com/Nuelthewave/Chesster/commit/197b8891bbf3e7293d31526c8b0e60786278337b)), closes [#315](https://github.com/Nuelthewave/Chesster/issues/315) [#316](https://github.com/Nuelthewave/Chesster/issues/316) [#317](https://github.com/Nuelthewave/Chesster/issues/317) [#318](https://github.com/Nuelthewave/Chesster/issues/318)
* **frontend:** add live game spectator mode with evaluation bar ([#127](https://github.com/Nuelthewave/Chesster/issues/127)) ([3016823](https://github.com/Nuelthewave/Chesster/commit/30168231d922694287def19f624fc660a554ed79))
* **frontend:** add live system status and endpoint telemetry page at /status ([5c6be4e](https://github.com/Nuelthewave/Chesster/commit/5c6be4e28e6910cb68307127deb19f8f1ef60788))
* **frontend:** add low-time cue, autoplay unlock, and sound service tests ([7bfeda1](https://github.com/Nuelthewave/Chesster/commit/7bfeda1f0fbd0c56183e6323d62972f793fe4996))
* **frontend:** add network/offline connection alert banner ([86ea021](https://github.com/Nuelthewave/Chesster/commit/86ea021c0077610379ee5a1666be91bffc59f52c)), closes [#256](https://github.com/Nuelthewave/Chesster/issues/256)
* **frontend:** add PGN import and visual move replay analyzer ([9335a83](https://github.com/Nuelthewave/Chesster/commit/9335a8358869e051ee92d8416de0e0323ddf1788))
* **frontend:** add player profile page with rating history chart ([629285c](https://github.com/Nuelthewave/Chesster/commit/629285c90b70c992386ab306872d91566ef3cfab)), closes [#255](https://github.com/Nuelthewave/Chesster/issues/255)
* **frontend:** add post-game result modal with PGN copy, rematch and share ([47dfa08](https://github.com/Nuelthewave/Chesster/commit/47dfa0862f640d1e747de2e4835d49e3918a38ae)), closes [#254](https://github.com/Nuelthewave/Chesster/issues/254)
* **frontend:** add right-click arrows and square highlights to the board ([23482a5](https://github.com/Nuelthewave/Chesster/commit/23482a524797106a324bb80caca97d7ba830b6bc))
* **frontend:** add streamer mode with hidden balances ([26215f0](https://github.com/Nuelthewave/Chesster/commit/26215f0621178fb723988c9637997f057751fbbb))
* **frontend:** add touch drag-and-drop piece movement with haptic feedback ([fb8db99](https://github.com/Nuelthewave/Chesster/commit/fb8db997b82c67bb21562aa4627a487ac7d64896))
* **frontend:** build live streamer mode with hidden wager balances, address masking, enlarged board coordinates, and stream overlay route ([8d7ef6c](https://github.com/Nuelthewave/Chesster/commit/8d7ef6cfbc834c4fa66919386ed071f479d87543))
* **frontend:** build Tournament Hub screen with category filters and search ([#228](https://github.com/Nuelthewave/Chesster/issues/228)) ([b83b330](https://github.com/Nuelthewave/Chesster/commit/b83b330e8f32ce483b490864c0b16ab67154c1f0))
* **frontend:** Build Tournament Match Ready Queue Modal and Auto-Redirect Flow ([#273](https://github.com/Nuelthewave/Chesster/issues/273)) ([3ee2cc1](https://github.com/Nuelthewave/Chesster/commit/3ee2cc10fc9db17db960924df60574094d838bfa)), closes [#230](https://github.com/Nuelthewave/Chesster/issues/230)
* **frontend:** Create Interactive Tree Tournament Bracket Component with Live Match Links ([cf9308b](https://github.com/Nuelthewave/Chesster/commit/cf9308bb893cb5cfaf28f5eb67fa33f2777d7f9a)), closes [#229](https://github.com/Nuelthewave/Chesster/issues/229)
* **frontend:** game playback rewind, material display, move indicators, fullscreen ([37f1312](https://github.com/Nuelthewave/Chesster/commit/37f13121e26348fabc120b1ec54a14e6cfb817e8)), closes [#124](https://github.com/Nuelthewave/Chesster/issues/124) [#123](https://github.com/Nuelthewave/Chesster/issues/123) [#112](https://github.com/Nuelthewave/Chesster/issues/112) [#109](https://github.com/Nuelthewave/Chesster/issues/109)
* **frontend:** high-contrast accessibility board theme for low-vision players ([fde1e8f](https://github.com/Nuelthewave/Chesster/commit/fde1e8f2ecb237328725c0fdf37521489cb9578b)), closes [hi#contrast](https://github.com/hi/issues/contrast) [#314](https://github.com/Nuelthewave/Chesster/issues/314) [Hi#Contrast](https://github.com/Hi/issues/Contrast) [hi#contrast](https://github.com/hi/issues/contrast)
* **frontend:** Implement Multi-Language Internationalization (i18n) Framework (EN, ES, FR, ZH) ([cddc5c0](https://github.com/Nuelthewave/Chesster/commit/cddc5c0daa9b42c669016560587bc8f45cfe4549))
* **frontend:** keyboard shortcuts, board accessibility, wager pills, and leaderboard ([d1a3e17](https://github.com/Nuelthewave/Chesster/commit/d1a3e174fa3bd09cc40fa466f1a1a8dbfce96707))
* **frontend:** move accuracy & blunder classification in post-game analysis ([2202e89](https://github.com/Nuelthewave/Chesster/commit/2202e8973a4473962e577fec4bb62072d01b3eb8)), closes [#313](https://github.com/Nuelthewave/Chesster/issues/313)
* **frontend:** resolve analysis depth gauge, touch haptics, i18n, and bracket pan-zoom (closes [#438](https://github.com/Nuelthewave/Chesster/issues/438), closes [#439](https://github.com/Nuelthewave/Chesster/issues/439), closes [#440](https://github.com/Nuelthewave/Chesster/issues/440), closes [#441](https://github.com/Nuelthewave/Chesster/issues/441)) ([#452](https://github.com/Nuelthewave/Chesster/issues/452)) ([8513b01](https://github.com/Nuelthewave/Chesster/commit/8513b01c1e36a693ecda99378ad924c24474de30))
* **frontend:** volume control, PGN/FEN export, multi-wallet, ESLint fixes ([bf7d586](https://github.com/Nuelthewave/Chesster/commit/bf7d5869cd08e672b2b759892f63027cc39ec005)), closes [#107](https://github.com/Nuelthewave/Chesster/issues/107) [#108](https://github.com/Nuelthewave/Chesster/issues/108) [#110](https://github.com/Nuelthewave/Chesster/issues/110) [#111](https://github.com/Nuelthewave/Chesster/issues/111)
* harden chat and add tournament health coverage ([86b8634](https://github.com/Nuelthewave/Chesster/commit/86b86341165a8f15b1bf09767ee1544daadf0abb))
* implement Blindfold Mode & Peek feature (Issue [#305](https://github.com/Nuelthewave/Chesster/issues/305)) ([ca248ad](https://github.com/Nuelthewave/Chesster/commit/ca248ad440ffe045ff2aa33416bc1d909a44b24a))
* implement contract storage TTL, allowance check, batch resolution, and theme mode ([79afb68](https://github.com/Nuelthewave/Chesster/commit/79afb68966be423461f4ddf5848001784cc2c2d5)), closes [#29](https://github.com/Nuelthewave/Chesster/issues/29) [#27](https://github.com/Nuelthewave/Chesster/issues/27) [#25](https://github.com/Nuelthewave/Chesster/issues/25) [#129](https://github.com/Nuelthewave/Chesster/issues/129)
* implement player referral dashboard (closes [#308](https://github.com/Nuelthewave/Chesster/issues/308)) ([cd0eaec](https://github.com/Nuelthewave/Chesster/commit/cd0eaecafed002d9891eab799e9079d6f34a3fc3))
* implement Socket.io reconnect handshake recovery with game state rehydration (issue [#303](https://github.com/Nuelthewave/Chesster/issues/303)) ([b47e1ca](https://github.com/Nuelthewave/Chesster/commit/b47e1cadb2caf75bb3b6c1d174930dc045807409))
* **metrics:** expose websocket telemetry for issue 294 ([#392](https://github.com/Nuelthewave/Chesster/issues/392)) ([4cc634e](https://github.com/Nuelthewave/Chesster/commit/4cc634e6098f1712626c04e7d5aec3dedd796fcd))
* moderate player chat messages ([02bc34a](https://github.com/Nuelthewave/Chesster/commit/02bc34a2b9d15a52a338af62204f47f1acd575bc))
* **platform:** implement openapi specs, release automation, disconnect grace tests, and e2e lobby flow ([#455](https://github.com/Nuelthewave/Chesster/issues/455)) ([5c5d40e](https://github.com/Nuelthewave/Chesster/commit/5c5d40e486d65dfa29cd80f33c9da495378e2503)), closes [#450](https://github.com/Nuelthewave/Chesster/issues/450) [#449](https://github.com/Nuelthewave/Chesster/issues/449) [#448](https://github.com/Nuelthewave/Chesster/issues/448) [#446](https://github.com/Nuelthewave/Chesster/issues/446)
* **rating:** add Glicko-2 player updates ([#394](https://github.com/Nuelthewave/Chesster/issues/394)) ([9d48da0](https://github.com/Nuelthewave/Chesster/commit/9d48da0d50e13a1517b6642ccb73affd0e3f62ba))
* **security,db:** resolve issues [#442](https://github.com/Nuelthewave/Chesster/issues/442), [#443](https://github.com/Nuelthewave/Chesster/issues/443), [#444](https://github.com/Nuelthewave/Chesster/issues/444), [#445](https://github.com/Nuelthewave/Chesster/issues/445) (closes [#442](https://github.com/Nuelthewave/Chesster/issues/442), closes [#443](https://github.com/Nuelthewave/Chesster/issues/443), closes [#444](https://github.com/Nuelthewave/Chesster/issues/444), closes [#445](https://github.com/Nuelthewave/Chesster/issues/445)) ([#454](https://github.com/Nuelthewave/Chesster/issues/454)) ([167f37f](https://github.com/Nuelthewave/Chesster/commit/167f37fd344cab9fbfd94a947ee1a7e8e458e16c))
* **security,testing:** sanitize chat XSS, rate-limit and sanitize API inputs, add frontend unit tests ([3557f66](https://github.com/Nuelthewave/Chesster/commit/3557f66d096cec22f2bc14fffd31a532d56e0698))
* **security:** resolve multiple assigned security tasks (closes [#323](https://github.com/Nuelthewave/Chesster/issues/323), closes [#324](https://github.com/Nuelthewave/Chesster/issues/324), closes [#325](https://github.com/Nuelthewave/Chesster/issues/325), closes [#326](https://github.com/Nuelthewave/Chesster/issues/326)) ([d05e842](https://github.com/Nuelthewave/Chesster/commit/d05e842c69213d89f331af4530f885186fa304ce))
* show wallet XLM/SAC balances in the navbar ([67e389a](https://github.com/Nuelthewave/Chesster/commit/67e389a2af87078b94e544016b8e5ce27b65df9f))
* **tournament:** implement on-chain prize escrow, refund window, bracket seeding, and round advancement ([709f2fc](https://github.com/Nuelthewave/Chesster/commit/709f2fcdf4a15c7f7a845e3b5e6b2dc8a8b9339d)), closes [#219](https://github.com/Nuelthewave/Chesster/issues/219) [#220](https://github.com/Nuelthewave/Chesster/issues/220) [#223](https://github.com/Nuelthewave/Chesster/issues/223) [#224](https://github.com/Nuelthewave/Chesster/issues/224)


### Performance Improvements

* **contracts:** optimize contract WASM size within 64 KB budget limit ([8e14730](https://github.com/Nuelthewave/Chesster/commit/8e1473031ecd98a292ee3558fb3ab2ba12daa4d2))

# [1.39.0](https://github.com/Kaycee276/Chesster/compare/v1.38.4...v1.39.0) (2026-10-15)


### Bug Fixes

* resolve issues [#386](https://github.com/Kaycee276/Chesster/issues/386), [#387](https://github.com/Kaycee276/Chesster/issues/387), [#388](https://github.com/Kaycee276/Chesster/issues/388), [#447](https://github.com/Kaycee276/Chesster/issues/447) (closes [#386](https://github.com/Kaycee276/Chesster/issues/386), closes [#387](https://github.com/Kaycee276/Chesster/issues/387), closes [#388](https://github.com/Kaycee276/Chesster/issues/388), closes [#447](https://github.com/Kaycee276/Chesster/issues/447)) ([#451](https://github.com/Kaycee276/Chesster/issues/451)) ([bd754a8](https://github.com/Kaycee276/Chesster/commit/bd754a8ad581b78b707fe9f254c85750aeca08df))
* **tests:** resolve escrow test duplication and db health service cache reset ([2ab39aa](https://github.com/Kaycee276/Chesster/commit/2ab39aa7869fb5d270282de8f1e3402ff8f6e18f))


### Features

* **batch:** resolve assigned issues 397, 398, 399, 400 (closes [#397](https://github.com/Kaycee276/Chesster/issues/397), [#398](https://github.com/Kaycee276/Chesster/issues/398), [#399](https://github.com/Kaycee276/Chesster/issues/399), [#400](https://github.com/Kaycee276/Chesster/issues/400)) ([#453](https://github.com/Kaycee276/Chesster/issues/453)) ([4c0c6f8](https://github.com/Kaycee276/Chesster/commit/4c0c6f8d359295484b3b8f877c8e6f185aff7706))
* **frontend:** resolve analysis depth gauge, touch haptics, i18n, and bracket pan-zoom (closes [#438](https://github.com/Kaycee276/Chesster/issues/438), closes [#439](https://github.com/Kaycee276/Chesster/issues/439), closes [#440](https://github.com/Kaycee276/Chesster/issues/440), closes [#441](https://github.com/Kaycee276/Chesster/issues/441)) ([#452](https://github.com/Kaycee276/Chesster/issues/452)) ([8513b01](https://github.com/Kaycee276/Chesster/commit/8513b01c1e36a693ecda99378ad924c24474de30))
* **platform:** implement openapi specs, release automation, disconnect grace tests, and e2e lobby flow ([#455](https://github.com/Kaycee276/Chesster/issues/455)) ([5c5d40e](https://github.com/Kaycee276/Chesster/commit/5c5d40e486d65dfa29cd80f33c9da495378e2503)), closes [#450](https://github.com/Kaycee276/Chesster/issues/450) [#449](https://github.com/Kaycee276/Chesster/issues/449) [#448](https://github.com/Kaycee276/Chesster/issues/448) [#446](https://github.com/Kaycee276/Chesster/issues/446)
* **security,db:** resolve issues [#442](https://github.com/Kaycee276/Chesster/issues/442), [#443](https://github.com/Kaycee276/Chesster/issues/443), [#444](https://github.com/Kaycee276/Chesster/issues/444), [#445](https://github.com/Kaycee276/Chesster/issues/445) (closes [#442](https://github.com/Kaycee276/Chesster/issues/442), closes [#443](https://github.com/Kaycee276/Chesster/issues/443), closes [#444](https://github.com/Kaycee276/Chesster/issues/444), closes [#445](https://github.com/Kaycee276/Chesster/issues/445)) ([#454](https://github.com/Kaycee276/Chesster/issues/454)) ([167f37f](https://github.com/Kaycee276/Chesster/commit/167f37fd344cab9fbfd94a947ee1a7e8e458e16c))

## [1.39.0](https://github.com/Nuelthewave/Chesster/compare/v1.38.4...v1.39.0) (2026-10-16)


### Features

* **#304:** Implement spectator chat slow-mode and room isolation ([11b0a18](https://github.com/Nuelthewave/Chesster/commit/11b0a187f2648405a4f56c29acace2e19c4ec584))
* **#306:** Interactive Tactical Puzzle Solver with Hint System ([f2b0ddd](https://github.com/Nuelthewave/Chesster/commit/f2b0ddd1e0aba1aafe5f218145f314e3629b5f2a))
* add configurable regional wager blocking ([eadb5c0](https://github.com/Nuelthewave/Chesster/commit/eadb5c0c7cf97db4ac8d16a9041e3892390f3373))
* add custom sound theme packs (wood, plastic, arcade, retro 8-bit) ([f468bc1](https://github.com/Nuelthewave/Chesster/commit/f468bc18399aee75a2875aac0f8b11d80bf9b2e0)), closes [#307](https://github.com/Nuelthewave/Chesster/issues/307)
* add escrow retries whitelist and events ([c3edf69](https://github.com/Nuelthewave/Chesster/commit/c3edf691b5629ebea7d0020c6767903e2d226260))
* add escrow retry, whitelist, forfeit, and event support ([623c78f](https://github.com/Nuelthewave/Chesster/commit/623c78f9c3d3b42ccb3fe1d0df79a54eca76ef20))
* add escrow unresolved-match fallback ([883b464](https://github.com/Nuelthewave/Chesster/commit/883b4648fafd8b4e6551cf680487f9388e8139a2))
* add low-time warning alert with pulsing border and tick sound ([fbd8e76](https://github.com/Nuelthewave/Chesster/commit/fbd8e762945fc70478b6a56550ebe9cc0099e5bc)), closes [#309](https://github.com/Nuelthewave/Chesster/issues/309)
* add share match link QR code to game lobby ([44de0ef](https://github.com/Nuelthewave/Chesster/commit/44de0ef1e1d3bc0e6182e631b4f6185556a31a99))
* add spectator reactions, themes, controls, and csrf ([7dd4527](https://github.com/Nuelthewave/Chesster/commit/7dd4527b58147e74d21a8c680e287bdcc588af22))
* add spectator reactions, themes, controls, and CSRF ([e509379](https://github.com/Nuelthewave/Chesster/commit/e509379cd4d445e353c43418fa58ad5c659c6eb7))
* anti-cheat telemetry, Helmet CORS/CSP, mobile touch gestures, smooth animation ([297ef00](https://github.com/Nuelthewave/Chesster/commit/297ef00eb8bea3c34fce8528a3a2adcbbf5e08e4))
* anti-cheat telemetry, helmet CORS/CSP, touch gestures, animation improvements ([f73de28](https://github.com/Nuelthewave/Chesster/commit/f73de28185075b66218c954419a2ac5b0955aca8)), closes [#105](https://github.com/Nuelthewave/Chesster/issues/105) [#106](https://github.com/Nuelthewave/Chesster/issues/106) [#116](https://github.com/Nuelthewave/Chesster/issues/116) [#120](https://github.com/Nuelthewave/Chesster/issues/120)
* **backend,contracts:** match creation rate limiting, api docs, tournament rake, and disqualification slashing (closes [#151](https://github.com/Nuelthewave/Chesster/issues/151), closes [#152](https://github.com/Nuelthewave/Chesster/issues/152), closes [#221](https://github.com/Nuelthewave/Chesster/issues/221), closes [#222](https://github.com/Nuelthewave/Chesster/issues/222)) ([5ee7463](https://github.com/Nuelthewave/Chesster/commit/5ee7463241d94d809d92824276a8c0e3cdaa4e6d))
* **backend,contracts:** rate limiting, swagger docs, tournament rake, and disqualification slashing ([858fc81](https://github.com/Nuelthewave/Chesster/commit/858fc810581e8f3f62e27596898710cf1297acb9))
* **backend:** add account privacy redaction ([31e417f](https://github.com/Nuelthewave/Chesster/commit/31e417f75e98146c90e15896ccfcbd58957aa66a))
* **backend:** add asynchronous event broadcasting ([7bfb067](https://github.com/Nuelthewave/Chesster/commit/7bfb0672a4cbd944d01603eef7a3bd1f965e87f3))
* **backend:** add automated game archival ([360cb3d](https://github.com/Nuelthewave/Chesster/commit/360cb3decb61b49b866e32609ba0f1de0b4ea421))
* **backend:** add daily active player and match volume aggregation service ([#69](https://github.com/Nuelthewave/Chesster/issues/69)) ([ca7a615](https://github.com/Nuelthewave/Chesster/commit/ca7a615a974e29e83a777208559b4ee0b947e821))
* **backend:** add daily active player and match volume aggregation service ([#69](https://github.com/Nuelthewave/Chesster/issues/69)) ([8a7de90](https://github.com/Nuelthewave/Chesster/commit/8a7de9056a3d5f7b393ddef6f89afedc8ee81fc8))
* **backend:** add daily chess puzzles ([5bcaf11](https://github.com/Nuelthewave/Chesster/commit/5bcaf1168916b7722c5f9f7061f81b33215dc1fb))
* **backend:** add dynamic elo bucket expansion to matchmaking ([daa11c7](https://github.com/Nuelthewave/Chesster/commit/daa11c7e546af04e8df410da09ad0d4adae3aaf7))
* **backend:** add dynamic elo bucket expansion to matchmaking ([b0267d8](https://github.com/Nuelthewave/Chesster/commit/b0267d89f8c9228bf723cdbf38400b0b9f41519e)), closes [#248](https://github.com/Nuelthewave/Chesster/issues/248)
* **backend:** add global exception handling & Sentry error reporting middleware ([#61](https://github.com/Nuelthewave/Chesster/issues/61)) ([7920d91](https://github.com/Nuelthewave/Chesster/commit/7920d91b19ab60e9db5287bcac09829950ab1693))
* **backend:** add global exception handling & Sentry error reporting middleware ([#61](https://github.com/Nuelthewave/Chesster/issues/61)) ([01ac707](https://github.com/Nuelthewave/Chesster/commit/01ac707ebeadc574dfb1d800bbba887aa1f9ddfa))
* **backend:** add growth, events, notifications, and anti-cheat services ([a0624f2](https://github.com/Nuelthewave/Chesster/commit/a0624f28a7d31e1692fec024207afe345239b84a))
* **backend:** add IP rate limiting for WebSocket handshakes ([9d19de5](https://github.com/Nuelthewave/Chesster/commit/9d19de59f50db2febadd4fb903d5144d4529fe1d))
* **backend:** add IP rate limiting for WebSocket handshakes ([25cd6c8](https://github.com/Nuelthewave/Chesster/commit/25cd6c83383f2fc300031c6ba54722f7fdd7d240)), closes [#244](https://github.com/Nuelthewave/Chesster/issues/244)
* **backend:** add JWT authentication middleware for profile customization ([0029b98](https://github.com/Nuelthewave/Chesster/commit/0029b981153d48bc06f36b8df4f8f4f4a6143687))
* **backend:** add match audit log export API for dispute resolution ([33e147b](https://github.com/Nuelthewave/Chesster/commit/33e147b2d9126fae82b7bb3d84951340cf03e92a))
* **backend:** add match audit log export API for dispute resolution ([94f62c8](https://github.com/Nuelthewave/Chesster/commit/94f62c81a1ad2aeda84dd0bc36f6018f66b58fed)), closes [#243](https://github.com/Nuelthewave/Chesster/issues/243)
* **backend:** add privacy, archival, compliance, and puzzles ([bb31307](https://github.com/Nuelthewave/Chesster/commit/bb313072a6422a3f60291b116dc8e6cbe08cfe17))
* **backend:** add referral commission tracking ([43347bf](https://github.com/Nuelthewave/Chesster/commit/43347bfbb937561cc603bc80ded2a78fb1813c40))
* **backend:** add regional wager blocking ([4451df3](https://github.com/Nuelthewave/Chesster/commit/4451df31bbd2807fdfc8fdabb7e8fad3b1d5222f))
* **backend:** add Stockfish AI bot opponent endpoint for single player ([7b2fc89](https://github.com/Nuelthewave/Chesster/commit/7b2fc897b3fb5ba1dc09a0b6b4727029f8f72e6e))
* **backend:** Add structured logging, health checks, PGN/FEN support, and Stellar indexer ([ce1f9a2](https://github.com/Nuelthewave/Chesster/commit/ce1f9a26ba4323142a3c0e0767d7550567f15f08))
* **backend:** Add structured logging, health checks, PGN/FEN support, and Stellar indexer ([c5cfa80](https://github.com/Nuelthewave/Chesster/commit/c5cfa80778f36852e50dc0f9cb5fc4e1948cc0a1))
* **backend:** add webhook exponential backoff and dead-letter queue ([c575d80](https://github.com/Nuelthewave/Chesster/commit/c575d8020721dfdac5e89c1398ea25d147159ef3))
* **backend:** add webhook exponential backoff and dead-letter queue ([f527e8f](https://github.com/Nuelthewave/Chesster/commit/f527e8f2ebf1dce6ac1acbfd4ad22358d72b12e5)), closes [#246](https://github.com/Nuelthewave/Chesster/issues/246)
* **backend:** Backend enhancements - cache, cleanup, history, and undo ([3092d82](https://github.com/Nuelthewave/Chesster/commit/3092d82d6610fd09b09b2b9a8a00d73f718f96fa))
* **backend:** cache user profile stats and match history in redis ([ecda241](https://github.com/Nuelthewave/Chesster/commit/ecda241c850f1ede9465d9c6e8b3780176bae6ae))
* **backend:** cache user profile stats and match history in redis ([8a76331](https://github.com/Nuelthewave/Chesster/commit/8a763312e68ce144d45776589d1ed48deea93dbd)), closes [#247](https://github.com/Nuelthewave/Chesster/issues/247)
* **backend:** configure Prisma ORM with Supabase connection pooling and schema sync ([154e3ee](https://github.com/Nuelthewave/Chesster/commit/154e3eee0f8502b73ab8fc31b2dbdeaeb267dd7b))
* **backend:** dispatch tournament notifications ([61e4e23](https://github.com/Nuelthewave/Chesster/commit/61e4e23d4b2a1c1fea4bab20a3dfc55c27bc7092))
* **backend:** enable websocket per-message deflate ([b5deaa3](https://github.com/Nuelthewave/Chesster/commit/b5deaa353f89f9d587c85dc7fbd53cbdf11f2042))
* **backend:** enable websocket per-message deflate ([b6e68db](https://github.com/Nuelthewave/Chesster/commit/b6e68db91eafb251114e6c2300ab256b831cb628))
* **backend:** enforce wager geo compliance ([e6a8567](https://github.com/Nuelthewave/Chesster/commit/e6a8567ee63fb7ec9c5159a740471f35fc2779e7))
* **backend:** export rich PGN game records ([#393](https://github.com/Nuelthewave/Chesster/issues/393)) ([5a6cdb5](https://github.com/Nuelthewave/Chesster/commit/5a6cdb5953cf1bb562f388bda7030785987cf400))
* **backend:** Implement Distributed Lock for Move Submission using Redis Redlock - Closes [#239](https://github.com/Nuelthewave/Chesster/issues/239) ([75d8595](https://github.com/Nuelthewave/Chesster/commit/75d859539ce4da4cb959593a81f0e6ba6269d4cb))
* **backend:** implement Elo rating update calculation service ([#66](https://github.com/Nuelthewave/Chesster/issues/66)) ([8cd1a68](https://github.com/Nuelthewave/Chesster/commit/8cd1a6883d88690d3023a9ac362b306785e7f12d))
* **backend:** implement Elo rating update calculation service ([#66](https://github.com/Nuelthewave/Chesster/issues/66)) ([01c966f](https://github.com/Nuelthewave/Chesster/commit/01c966fc6553eaf72dbb25705cb0a9fa6ffe28fb))
* **backend:** implement GET /api/leaderboard endpoint and player stats synchronization ([ab62776](https://github.com/Nuelthewave/Chesster/commit/ab62776d63787cc9492be5347b56b8ed85438dda))
* **backend:** Implement Matchmaking Queue with Elo-Based Rating Pairings ([4e784a8](https://github.com/Nuelthewave/Chesster/commit/4e784a8cb0d42c895eb202367e5886780a1b81fd))
* **backend:** Implement move validation cache, cron cleanup, paginated history, and undo protocol ([18c7696](https://github.com/Nuelthewave/Chesster/commit/18c7696965358a3b01e4faf3aa2331b3d19fec7c))
* **backend:** Implement Real-Time Socket.io Tournament Lifecycle Events ([70fa8e1](https://github.com/Nuelthewave/Chesster/commit/70fa8e1c4a2a8e696c01eb9ae183c5611b31674a))
* **backend:** Implement Real-Time Socket.io Tournament Lifecycle Events ([8d40f80](https://github.com/Nuelthewave/Chesster/commit/8d40f80de44653664e82450e121732fd548adb73))
* **backend:** Implement Redis Adapter for Socket.io Clustering & Horizontal Scaling - Closes [#238](https://github.com/Nuelthewave/Chesster/issues/238) ([99707a0](https://github.com/Nuelthewave/Chesster/commit/99707a0af4b63ea07e07b6ac9d3246004d464240))
* **backend:** implement threefold repetition and 50-move draw detection ([cf68061](https://github.com/Nuelthewave/Chesster/commit/cf680613889bb6d5cb2042a4a797ab896a124a08))
* **backend:** implement threefold repetition and 50-move draw detection ([8f87590](https://github.com/Nuelthewave/Chesster/commit/8f87590b2c8c67956b62949eaf3396ab6d0dbb32)), closes [#242](https://github.com/Nuelthewave/Chesster/issues/242)
* **backend:** implement webhook notification service for match payou… ([36b9c91](https://github.com/Nuelthewave/Chesster/commit/36b9c9126f696b29c5f0e8a22ae458eb9b09ce39))
* **backend:** implement webhook notification service for match payout confirmations ([918336a](https://github.com/Nuelthewave/Chesster/commit/918336a25ec4a04dd31d937d0fc4469a0b92de61))
* **backend:** Implement WebSocket Latency Telemetry and Automatic Disconnect Grace Period - Closes [#240](https://github.com/Nuelthewave/Chesster/issues/240) ([9013e8f](https://github.com/Nuelthewave/Chesster/commit/9013e8f7131a3ad29a4d716f80a532998d5d1fcb))
* **backend:** migrate from Supabase to Neon PostgreSQL and Prisma ([dae00f8](https://github.com/Nuelthewave/Chesster/commit/dae00f86f67a29a83cfc89bc19c93f5f393fadd0))
* **backend:** moderate player chat ([4311b41](https://github.com/Nuelthewave/Chesster/commit/4311b41885ae92e45deb0614b08dcb92f36b2ee0))
* **backend:** persist anti-cheat analysis ([07b7f25](https://github.com/Nuelthewave/Chesster/commit/07b7f25e0224d8037c4fee10a91a44a1daf3fcf9))
* **backend:** reconnect strategy, clock increments, Stockfish bot, JWT auth ([a1a7090](https://github.com/Nuelthewave/Chesster/commit/a1a709032be738c92a2afec9008ee5afb97df260))
* **backend:** refund unresolved escrow matches ([06c8dd4](https://github.com/Nuelthewave/Chesster/commit/06c8dd42ab82156c1af063ace26a5f046b646824))
* **backend:** run stockfish bot moves in a worker thread pool ([a2b39b3](https://github.com/Nuelthewave/Chesster/commit/a2b39b3aaac3960b6d3934353bbc3d9b31ffb3e5))
* **backend:** run stockfish bot moves in a worker thread pool ([c8519d4](https://github.com/Nuelthewave/Chesster/commit/c8519d49b09fc0c06d8820a958a4346c33fcec58)), closes [#241](https://github.com/Nuelthewave/Chesster/issues/241)
* **backend:** Socket.io reconnect grace period + per-player clock increments ([6de060d](https://github.com/Nuelthewave/Chesster/commit/6de060d2a516f26b51796569e3c0f9a7239a13ff))
* **backend:** stream game replays over server-sent events ([a1d14b1](https://github.com/Nuelthewave/Chesster/commit/a1d14b1fc5835b4eca4a061a73b25852578660a1))
* **backend:** stream game replays over server-sent events ([077b6ba](https://github.com/Nuelthewave/Chesster/commit/077b6ba4a199022f5deca22cc59ade19828c2e44)), closes [#245](https://github.com/Nuelthewave/Chesster/issues/245)
* **batch:** resolve assigned issues 397, 398, 399, 400 (closes [#397](https://github.com/Nuelthewave/Chesster/issues/397), [#398](https://github.com/Nuelthewave/Chesster/issues/398), [#399](https://github.com/Nuelthewave/Chesster/issues/399), [#400](https://github.com/Nuelthewave/Chesster/issues/400)) ([#453](https://github.com/Nuelthewave/Chesster/issues/453)) ([4c0c6f8](https://github.com/Nuelthewave/Chesster/commit/4c0c6f8d359295484b3b8f877c8e6f185aff7706))
* board social card image generator (closes [#310](https://github.com/Nuelthewave/Chesster/issues/310)) ([670fc78](https://github.com/Nuelthewave/Chesster/commit/670fc78f7554b60188a5e8c38fb728e8ca20f90e))
* **chess:** add blindfold and fog-of-war variants ([#395](https://github.com/Nuelthewave/Chesster/issues/395)) ([626a824](https://github.com/Nuelthewave/Chesster/commit/626a8241dcacf8758e61981ef754dca555cf5ee5))
* **contracts,backend:** implement escrow features for issues [#287](https://github.com/Nuelthewave/Chesster/issues/287), [#288](https://github.com/Nuelthewave/Chesster/issues/288), [#289](https://github.com/Nuelthewave/Chesster/issues/289), and [#290](https://github.com/Nuelthewave/Chesster/issues/290) ([4e35ce1](https://github.com/Nuelthewave/Chesster/commit/4e35ce17a5416b47c3be1f8233a0bd080a8a05ff))
* **contracts,ci:** bound stale match GC batches and pin GitHub Actions to commit SHAs ([#379](https://github.com/Nuelthewave/Chesster/issues/379), [#380](https://github.com/Nuelthewave/Chesster/issues/380)) ([174b0bd](https://github.com/Nuelthewave/Chesster/commit/174b0bd8a1e07cee7449473fa7bcd7f13cf21071))
* **contracts,ci:** bound stale match GC batches and pin GitHub Actions to commit SHAs (closes [#379](https://github.com/Nuelthewave/Chesster/issues/379), closes [#380](https://github.com/Nuelthewave/Chesster/issues/380)) ([2293056](https://github.com/Nuelthewave/Chesster/commit/229305637594b42dd4ef394ef5abca1b0bf4aead))
* **contracts:** Add comprehensive escrow enhancements ([e155ae7](https://github.com/Nuelthewave/Chesster/commit/e155ae74b132e05b68285c4e2a23079d7fef96f4))
* **contracts:** Add comprehensive escrow enhancements ([6f6c89f](https://github.com/Nuelthewave/Chesster/commit/6f6c89f0830d81d4240fd52ff70fabc72923a48d)), closes [#33](https://github.com/Nuelthewave/Chesster/issues/33) [#32](https://github.com/Nuelthewave/Chesster/issues/32) [#31](https://github.com/Nuelthewave/Chesster/issues/31) [#30](https://github.com/Nuelthewave/Chesster/issues/30)
* **contracts:** Add Comprehensive Rustdoc Comments, Stale Match GC, and Native XLM Utilities ([2f2fd6c](https://github.com/Nuelthewave/Chesster/commit/2f2fd6c5a38008459eebadf428d650e6f112dc51))
* **contracts:** Add Contract Pause Emergency State Switch by Admin Coordinator ([bc32c4c](https://github.com/Nuelthewave/Chesster/commit/bc32c4caf3f108d0ecc81e20cd6af64f585d097a))
* **contracts:** add coordinator rotation, reentrancy guard, balance invariants and upgradeability ([87fbad8](https://github.com/Nuelthewave/Chesster/commit/87fbad82e4e1e8b91b90b8563eab03b8c37eca1f))
* **contracts:** Add Cryptographic Ed25519 Result Signature Verificat… ([f90c201](https://github.com/Nuelthewave/Chesster/commit/f90c201587ec1ac2c6ce6732ff0952a6a80ca394))
* **contracts:** Add Cryptographic Ed25519 Result Signature Verification in Escrow Settlement ([98a7a03](https://github.com/Nuelthewave/Chesster/commit/98a7a030e50701788eae50c82b12cd8cfbbe5b02)), closes [#233](https://github.com/Nuelthewave/Chesster/issues/233)
* **contracts:** add emergency pause circuit breaker (issue [#22](https://github.com/Nuelthewave/Chesster/issues/22)) ([910a11f](https://github.com/Nuelthewave/Chesster/commit/910a11ff5ce0c9423ab607eb6bcc321ec5e1bbb4))
* **contracts:** add escrow emergency drain safe-harbor with timelock delay ([2b50360](https://github.com/Nuelthewave/Chesster/commit/2b50360c6cb8bd8a55cb12246387c9b461b9215a))
* **contracts:** add escrow emergency drain safe-harbor with timelock delay ([f700309](https://github.com/Nuelthewave/Chesster/commit/f700309c5adb0f98b98fa66cd403db440aefabd4))
* **contracts:** Add match cancellation and cooperative mutual draw r… ([32d18c4](https://github.com/Nuelthewave/Chesster/commit/32d18c44e7f0d64e6d68cd62b935513f5a354483))
* **contracts:** Add match cancellation and cooperative mutual draw resolution ([#20](https://github.com/Nuelthewave/Chesster/issues/20)) ([b9118cb](https://github.com/Nuelthewave/Chesster/commit/b9118cba9c68ecf89ee48f5b9ab8c00d278ea1fe))
* **contracts:** add multi-sig emergency admin recovery ([c1b4871](https://github.com/Nuelthewave/Chesster/commit/c1b4871c37001da70bcd741f1c98ffe294e2c0b6))
* **contracts:** add multi-sig emergency admin recovery scheme ([e9264aa](https://github.com/Nuelthewave/Chesster/commit/e9264aa48e9859da9125ad2921a37249cd73c908))
* **contracts:** Add On-Chain Event Emitting for Player Win Streak & Trophy Milestones - Closes [#237](https://github.com/Nuelthewave/Chesster/issues/237) ([fbdb3ea](https://github.com/Nuelthewave/Chesster/commit/fbdb3ea99636c8465445af07ee9c7af85b202185))
* **contracts:** add storage TTL auto-extension, allowance checks, di… ([3c89a40](https://github.com/Nuelthewave/Chesster/commit/3c89a40defc5ae0263f1d71d48b96d13f8812ce1))
* **contracts:** add storage TTL auto-extension, allowance checks, dispute time-lock, and batch resolution ([807a876](https://github.com/Nuelthewave/Chesster/commit/807a8769a1bca8a5e4b6d642afe41eb2843d13b9))
* **contracts:** Escrow security hardening — coordinator rotation, reentrancy guard, balance invariants, upgradeability ([03f1eab](https://github.com/Nuelthewave/Chesster/commit/03f1eab8985b7f68dc0761fe447cef05377e4e3b)), closes [#100](https://github.com/Nuelthewave/Chesster/issues/100) [#102](https://github.com/Nuelthewave/Chesster/issues/102) [#103](https://github.com/Nuelthewave/Chesster/issues/103) [#104](https://github.com/Nuelthewave/Chesster/issues/104)
* **contracts:** Implement Batch Settlement Function for Concurrent E… ([7e351c4](https://github.com/Nuelthewave/Chesster/commit/7e351c4aa602a84a7feb46ad85be2a7d8cfac288))
* **contracts:** Implement Batch Settlement Function for Concurrent Escrows ([516f067](https://github.com/Nuelthewave/Chesster/commit/516f067e61e0ea003772db1a20078e319a528429)), closes [#236](https://github.com/Nuelthewave/Chesster/issues/236)
* **contracts:** Implement Compact Binary Serialization for Match Sto… ([6e81804](https://github.com/Nuelthewave/Chesster/commit/6e81804c79351b81c3133dd293a4314e3afbbb0b))
* **contracts:** Implement Compact Binary Serialization for Match Storage to Reduce Soroban Gas ([3738574](https://github.com/Nuelthewave/Chesster/commit/3738574ca31c0fa8199728ee205dcb82d41b0f01)), closes [#234](https://github.com/Nuelthewave/Chesster/issues/234)
* **contracts:** implement dynamic platform fee discount for staked token holders ([a91cd4f](https://github.com/Nuelthewave/Chesster/commit/a91cd4f7cefab4238636c75ff8884716baef08b9))
* **contracts:** implement dynamic platform fee discount for staked token holders ([efda452](https://github.com/Nuelthewave/Chesster/commit/efda452d67933e78d6058b61b36a90b529d4ef22))
* **contracts:** Implement Dynamic Wager Scaling with Configurable Mi… ([db6c704](https://github.com/Nuelthewave/Chesster/commit/db6c704ffc048532d5233fe1b75533249e70c091))
* **contracts:** Implement Dynamic Wager Scaling with Configurable Minimum & Maximum Limits ([c5d44b6](https://github.com/Nuelthewave/Chesster/commit/c5d44b6e7275a0d97a7b295ad10d96d95ac334af)), closes [#23](https://github.com/Nuelthewave/Chesster/issues/23)
* **contracts:** implement match expiration & auto-claim refund timeo… ([0959a51](https://github.com/Nuelthewave/Chesster/commit/0959a51cd7ea15db2bea1522a8019bc06841d7f0))
* **contracts:** implement match expiration & auto-claim refund timeout logic ([e391bc5](https://github.com/Nuelthewave/Chesster/commit/e391bc55195d745db3da1c5521eb60bb6f0fcaba))
* **contracts:** implement match nonce, side betting pool, fee discount, and mutual cancellation ([e517469](https://github.com/Nuelthewave/Chesster/commit/e51746926015fd5ec31c96498e78c51090435909))
* **contracts:** implement match nonce, side betting pool, fee discount, and mutual cancellation ([d1b1e5a](https://github.com/Nuelthewave/Chesster/commit/d1b1e5a2d4aa2a513a4774aa6456c0312e28337b)), closes [#34](https://github.com/Nuelthewave/Chesster/issues/34) [#35](https://github.com/Nuelthewave/Chesster/issues/35) [#36](https://github.com/Nuelthewave/Chesster/issues/36) [#37](https://github.com/Nuelthewave/Chesster/issues/37)
* **contracts:** implement nonce-based replay protection for player deposit signatures ([a5298f5](https://github.com/Nuelthewave/Chesster/commit/a5298f59bc62565f85654d88aa310d893d3d5032))
* **contracts:** implement nonce-based replay protection for player deposit signatures ([90c3515](https://github.com/Nuelthewave/Chesster/commit/90c35156945a72108c3da08a139315ff95d79624))
* **contracts:** Implement On-Chain Player Elo Rating Ledger Proof ([99dcc08](https://github.com/Nuelthewave/Chesster/commit/99dcc08261bcd3b954e248c5752d1295f9618618))
* **contracts:** Implement On-Chain Player Elo Rating Ledger Proof ([93d6acb](https://github.com/Nuelthewave/Chesster/commit/93d6acba0b0e3224d05afa6f3c5c053553b1e383))
* **contracts:** Implement platform fee tiering and treasury vault co… ([bfc170c](https://github.com/Nuelthewave/Chesster/commit/bfc170c75d6c93469fc43e49e2565a8770fdfc0f))
* **contracts:** Implement platform fee tiering and treasury vault configuration ([#19](https://github.com/Nuelthewave/Chesster/issues/19)) ([b9db53c](https://github.com/Nuelthewave/Chesster/commit/b9db53c606d4dc53d0f9e360c5b0179397b66ad7))
* **contracts:** implement player elo rating commitment and proof-of-skill on stellar ([c2a54ab](https://github.com/Nuelthewave/Chesster/commit/c2a54abce32270cf6c9c28489eeed3b5aa76f160))
* **contracts:** implement player elo rating commitment and proof-of-skill on stellar ([2491c28](https://github.com/Nuelthewave/Chesster/commit/2491c28a8bcf9824be5300e74096389f877e4e71))
* **contracts:** Implement Time-Based Escrow Forfeit Protocol for Ina… ([0e0dddd](https://github.com/Nuelthewave/Chesster/commit/0e0dddd2f2fc13e423d2aa58a7a0abf6ebf70391))
* **contracts:** Implement Time-Based Escrow Forfeit Protocol for Inactive Players ([5b1d670](https://github.com/Nuelthewave/Chesster/commit/5b1d67027dbd7a1960cdc81ceea6029a2fea5dd5)), closes [#231](https://github.com/Nuelthewave/Chesster/issues/231)
* **contracts:** Support Multi-Token Wagers in Soroban Escrow ([6516d3e](https://github.com/Nuelthewave/Chesster/commit/6516d3ed85f1c6457ffea3b42be3a03f42fbbe0d))
* **contracts:** Support Multi-Token Wagers in Soroban Escrow ([0b46b92](https://github.com/Nuelthewave/Chesster/commit/0b46b924fb273783ffa2265b5e348800e7526ec7))
* **contracts:** Support Soroban SAC Token Allowances for Multi-Asset Wagers (USDC / EURC) ([4b75a87](https://github.com/Nuelthewave/Chesster/commit/4b75a878298ffa381f3e9e5aa18e3818bcbb067f)), closes [#232](https://github.com/Nuelthewave/Chesster/issues/232)
* **contracts:** Support Soroban SAC Token Allowances for Multi-Asset… ([9eab64e](https://github.com/Nuelthewave/Chesster/commit/9eab64eadab655ada2cc538fb53b006de62b4a84))
* coordinate lobby expiry with Soroban escrow refund ([#396](https://github.com/Nuelthewave/Chesster/issues/396)) ([5a7a6c1](https://github.com/Nuelthewave/Chesster/commit/5a7a6c1eca39348cbd70803cf4f94e3891afa93c))
* **database:** add automated encrypted PostgreSQL backup & snapshot … ([2492bb6](https://github.com/Nuelthewave/Chesster/commit/2492bb6c285bac85ac4c2c64ac25adc9332200b3))
* **database:** add automated encrypted PostgreSQL backup & snapshot script ([3d93bf3](https://github.com/Nuelthewave/Chesster/commit/3d93bf317bfbd291fb72ac7035f1256b0b3445f9)), closes [#119](https://github.com/Nuelthewave/Chesster/issues/119)
* **database:** add idempotent seed data script for local dev & E2E ([8d7dab4](https://github.com/Nuelthewave/Chesster/commit/8d7dab463dd2cc8c3a0b13d0e8f42dd4559b5973)), closes [#117](https://github.com/Nuelthewave/Chesster/issues/117)
* **database:** add migration runner script with rollback support ([69dc8fa](https://github.com/Nuelthewave/Chesster/commit/69dc8fa81716ab9db9174afab3fcf3458be6f719))
* **database:** add move history JSONB schema validation constraint ([#77](https://github.com/Nuelthewave/Chesster/issues/77)) ([313e421](https://github.com/Nuelthewave/Chesster/commit/313e421b59e2253debc371df9e70365536cb6a72))
* **database:** add move history JSONB schema validation constraint ([#77](https://github.com/Nuelthewave/Chesster/issues/77)) ([bb252f6](https://github.com/Nuelthewave/Chesster/commit/bb252f6d1a46b1b2b5e9bfe8c786f4e26dcbfc73))
* **database:** add player match statistics aggregation trigger ([#76](https://github.com/Nuelthewave/Chesster/issues/76)) ([3c17bb4](https://github.com/Nuelthewave/Chesster/commit/3c17bb41f646eae8589558301c108deb2215e24d))
* **database:** add player match statistics aggregation trigger ([#76](https://github.com/Nuelthewave/Chesster/issues/76)) ([6a745d8](https://github.com/Nuelthewave/Chesster/commit/6a745d854caa09be8f5d9529ce26193645d4b222))
* **database:** add player profiles and Elo tracking ([2acfd36](https://github.com/Nuelthewave/Chesster/commit/2acfd36cbee1a99aa238250d1047b0d634df5f02))
* **database:** add soft delete and archival partitioning migration ([#74](https://github.com/Nuelthewave/Chesster/issues/74)) ([2737e83](https://github.com/Nuelthewave/Chesster/commit/2737e8351c43851bca1b2a1e47cb4d955c3d96d7))
* **database:** add soft delete and game archival partitioning migration ([6b2fee2](https://github.com/Nuelthewave/Chesster/commit/6b2fee23bf4bdeb43935251c01a100aa9a1c6881))
* **database:** add token wager transaction ledger table migration ([#79](https://github.com/Nuelthewave/Chesster/issues/79)) ([4b2332f](https://github.com/Nuelthewave/Chesster/commit/4b2332f871a8df098213bc0bc6a764aa852acb60))
* **database:** add token wager transaction ledger table migration ([#79](https://github.com/Nuelthewave/Chesster/issues/79)) ([d2e0c74](https://github.com/Nuelthewave/Chesster/commit/d2e0c74972c0c1a45fde3947ac412f42aff503a5))
* **database:** add tournament bracket and participant tables migration ([96e8d29](https://github.com/Nuelthewave/Chesster/commit/96e8d29871b805fecf7b441a5c24e9a570904fad))
* **database:** add tournament bracket and participant tables migration ([c902d26](https://github.com/Nuelthewave/Chesster/commit/c902d2646daed783abd8d19d3efc736f11f20e78))
* **database:** add tournament bracket schema ([17038b6](https://github.com/Nuelthewave/Chesster/commit/17038b65ac5eebead33e22fc216a9283df31ec65))
* **database:** Implement chess puzzles schema & atomic escrow settle procedure ([#321](https://github.com/Nuelthewave/Chesster/issues/321), [#322](https://github.com/Nuelthewave/Chesster/issues/322)) ([aad1101](https://github.com/Nuelthewave/Chesster/commit/aad1101d1f1f1c23c74b8ef38a77eb6fedc5950e))
* **database:** implement database migration runner script with rollback support ([3be748a](https://github.com/Nuelthewave/Chesster/commit/3be748adf178af8ae783b330dd5de973d367cc9a))
* **database:** implement match_audit_logs table for dispute resolution ([c092639](https://github.com/Nuelthewave/Chesster/commit/c0926397c938cbe7eda9067f30b2b46b65a3ea21))
* **database:** implement match_audit_logs table for dispute resolution ([96cfa54](https://github.com/Nuelthewave/Chesster/commit/96cfa54816795c760fd665d0f71ef660cd9684ea)), closes [#73](https://github.com/Nuelthewave/Chesster/issues/73)
* **database:** implement puzzles schema, seed script, and atomic escrow settle procedure (closes [#321](https://github.com/Nuelthewave/Chesster/issues/321), closes [#322](https://github.com/Nuelthewave/Chesster/issues/322)) ([c758713](https://github.com/Nuelthewave/Chesster/commit/c758713dec9cea5824382c23b30e12553e7a5c7a))
* **database:** implement Row-Level Security (RLS) policies for all Supabase tables ([#137](https://github.com/Nuelthewave/Chesster/issues/137)) ([e860208](https://github.com/Nuelthewave/Chesster/commit/e86020865e2ed8f493d03d71f67903745946b475))
* **database:** partition games table by month on created_at (012) ([18cbf81](https://github.com/Nuelthewave/Chesster/commit/18cbf811aec5d555f37d9c71cde2061cf52735ac))
* **database:** partition games table by month on created_at (012) ([cc63e5a](https://github.com/Nuelthewave/Chesster/commit/cc63e5ae83135d5a41b35b2098ba4033af287903)), closes [#118](https://github.com/Nuelthewave/Chesster/issues/118)
* **db:** [#319](https://github.com/Nuelthewave/Chesster/issues/319) player_rating_history table, [#320](https://github.com/Nuelthewave/Chesster/issues/320) referral_program and claimable_commission_ledger tables ([db5d00c](https://github.com/Nuelthewave/Chesster/commit/db5d00c41ccb4f0ccded0b0e372d0fc37112c344))
* **db:** player rating history and referral program tables ([ee25be2](https://github.com/Nuelthewave/Chesster/commit/ee25be22d25cb350a73d9adb5897a641cf78634a))
* **escrow:** implement time-lock escrows, platform metrics, fee sponsorship, and mutual cancellation ([1edfeb6](https://github.com/Nuelthewave/Chesster/commit/1edfeb66f709c467df78dcbe87353f81fc7d479b))
* **frontend:** add client-side stockfish evaluation bar ([e83f72e](https://github.com/Nuelthewave/Chesster/commit/e83f72ea2c9604e03a9b5a119f17c729bed033e7))
* **frontend:** add client-side stockfish evaluation bar ([5eaaca7](https://github.com/Nuelthewave/Chesster/commit/5eaaca7b167d9682b87005d562fa9f06241009fc)), closes [#250](https://github.com/Nuelthewave/Chesster/issues/250)
* **frontend:** add customizable board themes (Wood, Neon, Classic, Marble) ([bca8b13](https://github.com/Nuelthewave/Chesster/commit/bca8b1303e1a7ada5152d3016f159fdfaa7fc28b)), closes [#82](https://github.com/Nuelthewave/Chesster/issues/82)
* **frontend:** add customizable piece sets and board flip toggle ([#125](https://github.com/Nuelthewave/Chesster/issues/125), [#128](https://github.com/Nuelthewave/Chesster/issues/128)) ([7eb1c0f](https://github.com/Nuelthewave/Chesster/commit/7eb1c0f597dc163e2a79a90a50fc5e98bc4b2c4a))
* **frontend:** add in-app notification toast system for game invitations ([#126](https://github.com/Nuelthewave/Chesster/issues/126)) ([bb9b515](https://github.com/Nuelthewave/Chesster/commit/bb9b515ddc72cdf1b916b619e3de39ede5d3a765))
* **frontend:** add keyboard move input, leaderboard filters, disconnect banner, and PGN drag-and-drop ([974c37c](https://github.com/Nuelthewave/Chesster/commit/974c37c2077b593375f99b7750c170ce4b37f98c))
* **frontend:** add keyboard move input, leaderboard filters, disconnect banner, and PGN drag-and-drop ([197b889](https://github.com/Nuelthewave/Chesster/commit/197b8891bbf3e7293d31526c8b0e60786278337b))
* **frontend:** add live game spectator mode with evaluation bar ([#127](https://github.com/Nuelthewave/Chesster/issues/127)) ([3016823](https://github.com/Nuelthewave/Chesster/commit/30168231d922694287def19f624fc660a554ed79))
* **frontend:** add live system status and endpoint telemetry page at /status ([5c6be4e](https://github.com/Nuelthewave/Chesster/commit/5c6be4e28e6910cb68307127deb19f8f1ef60788))
* **frontend:** add low-time cue, autoplay unlock, and sound service tests ([7bfeda1](https://github.com/Nuelthewave/Chesster/commit/7bfeda1f0fbd0c56183e6323d62972f793fe4996))
* **frontend:** add network/offline connection alert banner ([fbfd819](https://github.com/Nuelthewave/Chesster/commit/fbfd8195630b78631a40a1f05096598feec224b2))
* **frontend:** add network/offline connection alert banner ([86ea021](https://github.com/Nuelthewave/Chesster/commit/86ea021c0077610379ee5a1666be91bffc59f52c)), closes [#256](https://github.com/Nuelthewave/Chesster/issues/256)
* **frontend:** add PGN import and visual move replay analyzer ([9335a83](https://github.com/Nuelthewave/Chesster/commit/9335a8358869e051ee92d8416de0e0323ddf1788))
* **frontend:** add player profile page with rating history chart ([c224dfc](https://github.com/Nuelthewave/Chesster/commit/c224dfcaad1295bb900abee17df2148907ac6df5))
* **frontend:** add player profile page with rating history chart ([629285c](https://github.com/Nuelthewave/Chesster/commit/629285c90b70c992386ab306872d91566ef3cfab)), closes [#255](https://github.com/Nuelthewave/Chesster/issues/255)
* **frontend:** add post-game result modal with PGN copy, rematch and share ([db04c74](https://github.com/Nuelthewave/Chesster/commit/db04c748dcd305725515af378001d0ff2b5f5049))
* **frontend:** add post-game result modal with PGN copy, rematch and share ([47dfa08](https://github.com/Nuelthewave/Chesster/commit/47dfa0862f640d1e747de2e4835d49e3918a38ae)), closes [#254](https://github.com/Nuelthewave/Chesster/issues/254)
* **frontend:** add right-click arrows and square highlights to the board ([23482a5](https://github.com/Nuelthewave/Chesster/commit/23482a524797106a324bb80caca97d7ba830b6bc))
* **frontend:** add streamer mode with hidden balances ([26215f0](https://github.com/Nuelthewave/Chesster/commit/26215f0621178fb723988c9637997f057751fbbb))
* **frontend:** add touch drag-and-drop piece movement with haptic feedback ([fb8db99](https://github.com/Nuelthewave/Chesster/commit/fb8db997b82c67bb21562aa4627a487ac7d64896))
* **frontend:** build live streamer mode with hidden wager balances, address masking, enlarged board coordinates, and stream overlay route ([8d7ef6c](https://github.com/Nuelthewave/Chesster/commit/8d7ef6cfbc834c4fa66919386ed071f479d87543))
* **frontend:** build Tournament Hub screen with category filters and search ([#228](https://github.com/Nuelthewave/Chesster/issues/228)) ([b83b330](https://github.com/Nuelthewave/Chesster/commit/b83b330e8f32ce483b490864c0b16ab67154c1f0))
* **frontend:** build Tournament Hub screen with category filters and… ([09402cf](https://github.com/Nuelthewave/Chesster/commit/09402cf089ffbd8e1aec8b7912c0e77a31cf47e5))
* **frontend:** Build Tournament Match Ready Queue Modal and Auto-Redirect Flow ([#273](https://github.com/Nuelthewave/Chesster/issues/273)) ([3ee2cc1](https://github.com/Nuelthewave/Chesster/commit/3ee2cc10fc9db17db960924df60574094d838bfa)), closes [#230](https://github.com/Nuelthewave/Chesster/issues/230)
* **frontend:** complete synthesized audio engine for game SFX ([6a9175a](https://github.com/Nuelthewave/Chesster/commit/6a9175a6ed82cce5855347e2acffde125c64c27b))
* **frontend:** Create Interactive Tree Tournament Bracket Component … ([b3f128d](https://github.com/Nuelthewave/Chesster/commit/b3f128d5017130e6bde28941b273bbab88599d2a))
* **frontend:** Create Interactive Tree Tournament Bracket Component with Live Match Links ([cf9308b](https://github.com/Nuelthewave/Chesster/commit/cf9308bb893cb5cfaf28f5eb67fa33f2777d7f9a)), closes [#229](https://github.com/Nuelthewave/Chesster/issues/229)
* **frontend:** custom move arrows and square highlights via right-click ([cd67a38](https://github.com/Nuelthewave/Chesster/commit/cd67a3827563b872c636c0c706fac5435389e34c))
* **frontend:** fullscreen toggle, move indicators, material advantage & move-history rewind ([798e3b5](https://github.com/Nuelthewave/Chesster/commit/798e3b5bb299bca43d3b9eaf54f51d142aae49ef))
* **frontend:** game playback rewind, material display, move indicators, fullscreen ([37f1312](https://github.com/Nuelthewave/Chesster/commit/37f13121e26348fabc120b1ec54a14e6cfb817e8)), closes [#124](https://github.com/Nuelthewave/Chesster/issues/124) [#123](https://github.com/Nuelthewave/Chesster/issues/123) [#112](https://github.com/Nuelthewave/Chesster/issues/112) [#109](https://github.com/Nuelthewave/Chesster/issues/109)
* **frontend:** high-contrast accessibility board theme for low-vision players ([fde1e8f](https://github.com/Nuelthewave/Chesster/commit/fde1e8f2ecb237328725c0fdf37521489cb9578b))
* **frontend:** Implement Multi-Language Internationalization (i18n) … ([7eb0a61](https://github.com/Nuelthewave/Chesster/commit/7eb0a61bb1b0f26e9d14810501ed2ed982f330d9))
* **frontend:** Implement Multi-Language Internationalization (i18n) Framework (EN, ES, FR, ZH) ([cddc5c0](https://github.com/Nuelthewave/Chesster/commit/cddc5c0daa9b42c669016560587bc8f45cfe4549))
* **frontend:** keyboard shortcuts, board accessibility, wager pills, and leaderboard ([d1a3e17](https://github.com/Nuelthewave/Chesster/commit/d1a3e174fa3bd09cc40fa466f1a1a8dbfce96707))
* **frontend:** mobile touch drag-and-drop piece movement with haptics ([e37ff2b](https://github.com/Nuelthewave/Chesster/commit/e37ff2b604e21ddf589495f7f3744bd3a9e42fc7))
* **frontend:** move accuracy & blunder classification in post-game analysis ([2202e89](https://github.com/Nuelthewave/Chesster/commit/2202e8973a4473962e577fec4bb62072d01b3eb8))
* **frontend:** move accuracy badges + high-contrast accessibility theme ([66046af](https://github.com/Nuelthewave/Chesster/commit/66046afbe3c0e71d8af9ff55c3f43045e20b7403))
* **frontend:** PGN import and visual move replay analyzer screen ([940b93f](https://github.com/Nuelthewave/Chesster/commit/940b93f4e97db0bf4bcb9d0228185762e46b36fc))
* **frontend:** resolve analysis depth gauge, touch haptics, i18n, and bracket pan-zoom (closes [#438](https://github.com/Nuelthewave/Chesster/issues/438), closes [#439](https://github.com/Nuelthewave/Chesster/issues/439), closes [#440](https://github.com/Nuelthewave/Chesster/issues/440), closes [#441](https://github.com/Nuelthewave/Chesster/issues/441)) ([#452](https://github.com/Nuelthewave/Chesster/issues/452)) ([8513b01](https://github.com/Nuelthewave/Chesster/commit/8513b01c1e36a693ecda99378ad924c24474de30))
* **frontend:** volume control, PGN/FEN export, multi-wallet support, ESLint fixes ([0426cb9](https://github.com/Nuelthewave/Chesster/commit/0426cb9b8dbff92aab6aae34a22e958ca65594af))
* **frontend:** volume control, PGN/FEN export, multi-wallet, ESLint fixes ([bf7d586](https://github.com/Nuelthewave/Chesster/commit/bf7d5869cd08e672b2b759892f63027cc39ec005)), closes [#107](https://github.com/Nuelthewave/Chesster/issues/107) [#108](https://github.com/Nuelthewave/Chesster/issues/108) [#110](https://github.com/Nuelthewave/Chesster/issues/110) [#111](https://github.com/Nuelthewave/Chesster/issues/111)
* harden chat and add tournament health coverage ([86b8634](https://github.com/Nuelthewave/Chesster/commit/86b86341165a8f15b1bf09767ee1544daadf0abb))
* harden chat, add DB health telemetry, and tournament E2E coverage ([04db4ff](https://github.com/Nuelthewave/Chesster/commit/04db4ff79374638e951028cc716e96c40f80c217))
* implement Blindfold Mode & Peek feature (Issue [#305](https://github.com/Nuelthewave/Chesster/issues/305)) ([ca248ad](https://github.com/Nuelthewave/Chesster/commit/ca248ad440ffe045ff2aa33416bc1d909a44b24a))
* implement contract enhancements and frontend theme mode ([32eac2c](https://github.com/Nuelthewave/Chesster/commit/32eac2ca3d6d5c92f6eedaf481e7831f0563d866))
* implement contract storage TTL, allowance check, batch resolution, and theme mode ([79afb68](https://github.com/Nuelthewave/Chesster/commit/79afb68966be423461f4ddf5848001784cc2c2d5))
* implement player referral dashboard (closes [#308](https://github.com/Nuelthewave/Chesster/issues/308)) ([cd0eaec](https://github.com/Nuelthewave/Chesster/commit/cd0eaecafed002d9891eab799e9079d6f34a3fc3))
* implement Socket.io reconnect handshake recovery with game state rehydration (issue [#303](https://github.com/Nuelthewave/Chesster/issues/303)) ([b47e1ca](https://github.com/Nuelthewave/Chesster/commit/b47e1cadb2caf75bb3b6c1d174930dc045807409))
* **metrics:** expose websocket telemetry for issue 294 ([#392](https://github.com/Nuelthewave/Chesster/issues/392)) ([4cc634e](https://github.com/Nuelthewave/Chesster/commit/4cc634e6098f1712626c04e7d5aec3dedd796fcd))
* moderate player chat messages ([02bc34a](https://github.com/Nuelthewave/Chesster/commit/02bc34a2b9d15a52a338af62204f47f1acd575bc))
* **platform:** implement openapi specs, release automation, disconnect grace tests, and e2e lobby flow ([#455](https://github.com/Nuelthewave/Chesster/issues/455)) ([5c5d40e](https://github.com/Nuelthewave/Chesster/commit/5c5d40e486d65dfa29cd80f33c9da495378e2503))
* **rating:** add Glicko-2 player updates ([#394](https://github.com/Nuelthewave/Chesster/issues/394)) ([9d48da0](https://github.com/Nuelthewave/Chesster/commit/9d48da0d50e13a1517b6642ccb73affd0e3f62ba))
* **security,db:** resolve issues [#442](https://github.com/Nuelthewave/Chesster/issues/442), [#443](https://github.com/Nuelthewave/Chesster/issues/443), [#444](https://github.com/Nuelthewave/Chesster/issues/444), [#445](https://github.com/Nuelthewave/Chesster/issues/445) (closes [#442](https://github.com/Nuelthewave/Chesster/issues/442), closes [#443](https://github.com/Nuelthewave/Chesster/issues/443), closes [#444](https://github.com/Nuelthewave/Chesster/issues/444), closes [#445](https://github.com/Nuelthewave/Chesster/issues/445)) ([#454](https://github.com/Nuelthewave/Chesster/issues/454)) ([167f37f](https://github.com/Nuelthewave/Chesster/commit/167f37fd344cab9fbfd94a947ee1a7e8e458e16c))
* **security,testing:** chat XSS sanitization, API rate limiting and input sanitization, and frontend unit tests ([edc43a8](https://github.com/Nuelthewave/Chesster/commit/edc43a879b61b14f37fcbf5b39b3d37c4a1f98d8))
* **security,testing:** sanitize chat XSS, rate-limit and sanitize API inputs, add frontend unit tests ([3557f66](https://github.com/Nuelthewave/Chesster/commit/3557f66d096cec22f2bc14fffd31a532d56e0698))
* **security:** resolve multiple assigned security tasks ([a1504a4](https://github.com/Nuelthewave/Chesster/commit/a1504a40c525cecdba204ce703d45bf134ac6b07))
* **security:** resolve multiple assigned security tasks (closes [#323](https://github.com/Nuelthewave/Chesster/issues/323), closes [#324](https://github.com/Nuelthewave/Chesster/issues/324), closes [#325](https://github.com/Nuelthewave/Chesster/issues/325), closes [#326](https://github.com/Nuelthewave/Chesster/issues/326)) ([d05e842](https://github.com/Nuelthewave/Chesster/commit/d05e842c69213d89f331af4530f885186fa304ce))
* Seed data script + customizable board themes ([f69cecf](https://github.com/Nuelthewave/Chesster/commit/f69cecfbe4f25805128d42fcc8ff9bbb41c6ecdb))
* show wallet XLM/SAC balances in the navbar ([67e389a](https://github.com/Nuelthewave/Chesster/commit/67e389a2af87078b94e544016b8e5ce27b65df9f))
* **tournament:** implement on-chain prize escrow, refund window, bracket seeding, and round advancement ([8036877](https://github.com/Nuelthewave/Chesster/commit/8036877ea785649049b36b340a400481ce2bff79))
* **tournament:** implement on-chain prize escrow, refund window, bracket seeding, and round advancement ([709f2fc](https://github.com/Nuelthewave/Chesster/commit/709f2fcdf4a15c7f7a845e3b5e6b2dc8a8b9339d))


### Bug Fixes

* **auth:** bound challenge store with expiry sweep and capacity policy ([#391](https://github.com/Nuelthewave/Chesster/issues/391)) ([81fa366](https://github.com/Nuelthewave/Chesster/commit/81fa3661aa5b697b49bbfcd4c0ebba04b6808806))
* **backend:** keep deletion sessions revoked ([f9af09e](https://github.com/Nuelthewave/Chesster/commit/f9af09e24f847519564d28726f17afd0e0e7f352))
* **backend:** prune archived game partitions ([f70c91d](https://github.com/Nuelthewave/Chesster/commit/f70c91d345c6ce34d4b8dc51c392b601c2b1415f))
* **backend:** validate coordinator secret key gracefully and support env alias fallback keys ([cfa57d3](https://github.com/Nuelthewave/Chesster/commit/cfa57d3d3da3dc160d08b71ef989cfafb87b5214))
* **build:** configure visualizer plugin for bundle stats generation ([5c701f9](https://github.com/Nuelthewave/Chesster/commit/5c701f992a78391cbab32f07b600d012bebd8df6))
* **ci:** refresh backend lockfile ([41de40b](https://github.com/Nuelthewave/Chesster/commit/41de40bb0e96bb7426663aa5d2aa6e18687bc1f5))
* **ci:** restore Node 24 in .nvmrc for native Jest ESM require support ([1c21402](https://github.com/Nuelthewave/Chesster/commit/1c21402107a3ec1cea22a34815ad72f336b84461))
* **contracts:** fix clippy len_zero warning in test.rs ([90c2354](https://github.com/Nuelthewave/Chesster/commit/90c235493bb3786a5957d9e7f5ca273331bf93cd))
* **contracts:** reconcile EscrowError limits and format after upstream merge ([be8785a](https://github.com/Nuelthewave/Chesster/commit/be8785a4b9d07e54dbd518df43c7dfd33c00f699))
* **contracts:** reconcile EscrowError limits and format after upstream merge ([40dc134](https://github.com/Nuelthewave/Chesster/commit/40dc134fcd3e60d1ce1276475d7cf9ca80afc4b6))
* **contracts:** repair escrow test boundaries ([e6119ab](https://github.com/Nuelthewave/Chesster/commit/e6119ab1d5f10ed13c8ecd979f83716197d6feba))
* correct workspace CI dependency paths ([99c6f5f](https://github.com/Nuelthewave/Chesster/commit/99c6f5f627b10b4a747c098feb0526025926fb88))
* **database:** add existence checks for optional tables in RLS migration ([#137](https://github.com/Nuelthewave/Chesster/issues/137)) ([8ee29b5](https://github.com/Nuelthewave/Chesster/commit/8ee29b51e552152efa0f2a668cef684e1091a85a))
* **database:** add indexes for game and move queries ([518fbd5](https://github.com/Nuelthewave/Chesster/commit/518fbd514e0ff2c4e3e13af700087dceb2378987))
* **database:** add indexes for game and move queries ([6b76cea](https://github.com/Nuelthewave/Chesster/commit/6b76ceaeb46b1e0fa9e8ec62a7fe9cc0e5656898))
* **database:** drop end_reason from seed (column not in canonical schema) ([c39d4c2](https://github.com/Nuelthewave/Chesster/commit/c39d4c2bcabfd6aa74b8454080991fea1c73c625))
* **database:** sync package-lock with pg dependency ([7abc974](https://github.com/Nuelthewave/Chesster/commit/7abc974180e5e938fff854711cb92886a0c0c4fa))
* **escrow:** resolve clippy bool_assert_comparison warning in test.rs ([e3e5227](https://github.com/Nuelthewave/Chesster/commit/e3e5227855f2554072a0ae96737a198dde03de9e))
* **escrow:** resolve clippy warnings and update wasm size budget limit ([8b66ec1](https://github.com/Nuelthewave/Chesster/commit/8b66ec1363eb62eecb8a7a4d3e41d181b5329468))
* fix payout model ([b553e28](https://github.com/Nuelthewave/Chesster/commit/b553e28575e8b6c44d542525b25faa7b8365fa57))
* **frontend:** remove leave game button while waiting for opponent ([601e34a](https://github.com/Nuelthewave/Chesster/commit/601e34a75ec967b66afd4991c0951736647d0c3e))
* **frontend:** repair SpectatorPage and ChessBoard broken by merge conflicts ([b1566c2](https://github.com/Nuelthewave/Chesster/commit/b1566c22ae2d8bd6cd83aff727c175b12fba4916))
* **frontend:** resolve ESLint errors and Vitest config type overload ([ca643d9](https://github.com/Nuelthewave/Chesster/commit/ca643d91414696c57dfe69c20fa72fade005ff18))
* **health:** update database provider name to Neon PostgreSQL and simplify status page design ([c86a588](https://github.com/Nuelthewave/Chesster/commit/c86a5883999ed7070753a6b21caed75b061d7ce2))
* repair corrupted ChessBoard and GameResultModal components ([e20b18d](https://github.com/Nuelthewave/Chesster/commit/e20b18debb1f3c3d929ced4a78454d7a6769e798))
* resolve batch issues 237, 238, 239, 240 ([1626231](https://github.com/Nuelthewave/Chesster/commit/16262312a208313c478a903e32a6e7c5a9866637))
* resolve build and test failures across frontend, backend, and contracts ([aff2196](https://github.com/Nuelthewave/Chesster/commit/aff219652ea062df677cef2b42f580e7e1dff089))
* resolve cross-origin CSRF validation in production and refine game layout ([69bec13](https://github.com/Nuelthewave/Chesster/commit/69bec138161cf66797a4463de73792507ab0866f))
* resolve frontend/backend env validation and DB schema fallback for time control columns ([ff43083](https://github.com/Nuelthewave/Chesster/commit/ff430839de28b409626af12cfb93029a906683c7))
* resolve issue [#225](https://github.com/Nuelthewave/Chesster/issues/225) ([#270](https://github.com/Nuelthewave/Chesster/issues/270)) ([6f36f74](https://github.com/Nuelthewave/Chesster/commit/6f36f74e0e26ace0dd167325cf41dd9c7952cf63))
* resolve issues [#386](https://github.com/Nuelthewave/Chesster/issues/386), [#387](https://github.com/Nuelthewave/Chesster/issues/387), [#388](https://github.com/Nuelthewave/Chesster/issues/388), [#447](https://github.com/Nuelthewave/Chesster/issues/447) (closes [#386](https://github.com/Nuelthewave/Chesster/issues/386), closes [#387](https://github.com/Nuelthewave/Chesster/issues/387), closes [#388](https://github.com/Nuelthewave/Chesster/issues/388), closes [#447](https://github.com/Nuelthewave/Chesster/issues/447)) ([#451](https://github.com/Nuelthewave/Chesster/issues/451)) ([bd754a8](https://github.com/Nuelthewave/Chesster/commit/bd754a8ad581b78b707fe9f254c85750aeca08df))
* resolve smart contract compilation errors, frontend TS build, and test suite configs ([6e83092](https://github.com/Nuelthewave/Chesster/commit/6e83092faa04528fb9bce38f4e65b0364eb3bb23))
* **seo:** add meta description and robots.txt for Lighthouse SEO compliance ([55047cb](https://github.com/Nuelthewave/Chesster/commit/55047cbfdf358e10d46fa19f4bf6fa000628da20))
* stabilize backend CI test environment ([5f306c8](https://github.com/Nuelthewave/Chesster/commit/5f306c8d1a6fda90dca44151feeb664b7c44e3da))
* stabilize backend CI test environment ([42d5860](https://github.com/Nuelthewave/Chesster/commit/42d58602f7bd9842b105bab003568f55867f8909))
* **test:** resolve Node 22 ESM require error, test env variables, and redis handles ([6a6b6a4](https://github.com/Nuelthewave/Chesster/commit/6a6b6a425c59fcdbdc98c9c5aea8590a7b9b35d2))
* **tests:** resolve escrow test duplication and db health service cache reset ([2ab39aa](https://github.com/Nuelthewave/Chesster/commit/2ab39aa7869fb5d270282de8f1e3402ff8f6e18f))
* **ui:** improve mobile responsiveness and remove overlapping banners and floating controls ([c113498](https://github.com/Nuelthewave/Chesster/commit/c11349829ceed5c08838418488be351a4e1a35e1))


### Performance Improvements

* **contracts:** optimize contract WASM size within 64 KB budget limit ([8e14730](https://github.com/Nuelthewave/Chesster/commit/8e1473031ecd98a292ee3558fb3ab2ba12daa4d2))


### Code Refactoring

* **lobby:** remove status page button from header navigation ([e01a880](https://github.com/Nuelthewave/Chesster/commit/e01a88016fb02ef3bad21ab8301d9788aa785ac4))


### Documentation

* add CONTRIBUTING.md and GitHub issue templates ([d39cfa1](https://github.com/Nuelthewave/Chesster/commit/d39cfa1bf73c59af2eb6f98288a65b0a61953218))
* add contributor and integration guides ([69f3faf](https://github.com/Nuelthewave/Chesster/commit/69f3faf2d51ca965e6bf49d50ac52946d5f99e27))
* add contributor and integration guides ([348f12e](https://github.com/Nuelthewave/Chesster/commit/348f12e09a132058c7e28df519aa8b3292d2fa8a)), closes [#98](https://github.com/Nuelthewave/Chesster/issues/98) [#96](https://github.com/Nuelthewave/Chesster/issues/96) [#97](https://github.com/Nuelthewave/Chesster/issues/97) [#99](https://github.com/Nuelthewave/Chesster/issues/99)
* add FLOSSAfrica funding badge and support section ([d864a44](https://github.com/Nuelthewave/Chesster/commit/d864a44cae68bc20a74d0a381d11aa9d574a4cb4))
* add tournament system plan and osswc-issues-gen roadmap reference ([55ceaf4](https://github.com/Nuelthewave/Chesster/commit/55ceaf4fe24fbf88e6167a402fe87f1002884a4d))
* **governance:** establish dev-branch contribution workflow and updated CI guides ([21f9c68](https://github.com/Nuelthewave/Chesster/commit/21f9c68fa006845a7ff6e97ce28528500f02ebbf))


### Tests

* accept degraded health status response ([65bf7d5](https://github.com/Nuelthewave/Chesster/commit/65bf7d5da7700c4bed7e183dd5666c819c36f301))
* add backend load and frontend chess coverage ([98b918d](https://github.com/Nuelthewave/Chesster/commit/98b918daabee2f8ea1d677762ee53b839cdae35b))
* add chess load and engine coverage ([c2593ef](https://github.com/Nuelthewave/Chesster/commit/c2593ef02e835545dad5360dd9f2382801156edf))
* add comprehensive Chesster coverage ([7d705f8](https://github.com/Nuelthewave/Chesster/commit/7d705f8f3fc08de2ee510a6fbe8f59a95a8b3b6e))
* add comprehensive Chesster coverage ([9efcb6a](https://github.com/Nuelthewave/Chesster/commit/9efcb6adbe51f71eb934c841ce2bbf6db3c0b4e6))
* add Playwright visual regression suite for theming and modals ([1031cdf](https://github.com/Nuelthewave/Chesster/commit/1031cdffabca670229b37324f8c7b492bdc58709))
* add state transition tests for the game Zustand store ([f0ed64c](https://github.com/Nuelthewave/Chesster/commit/f0ed64c4675df4fe2f3903829a9335470e6058b5))
* **backend:** add rate limiter and input sanitization middleware unit tests ([8e2098e](https://github.com/Nuelthewave/Chesster/commit/8e2098e68a959d2e0c16bf6bc6e88b29130d81f0))
* **backend:** cover retry/backoff, fee estimation, and forfeit in escrowService ([9013eb8](https://github.com/Nuelthewave/Chesster/commit/9013eb8dfd5cc538a595ae44d3c28a83cc938694))
* **backend:** Rate Limiter and Input Sanitization Middleware Unit Tests ([b76606f](https://github.com/Nuelthewave/Chesster/commit/b76606f777db307b612e6531dab676f74633817a))
* **contracts:** fuzz escrow balance conservation ([b463640](https://github.com/Nuelthewave/Chesster/commit/b463640a6a84cd0cc866a80e5a91254f70d0061f))
* **contracts:** fuzz escrow balance conservation ([abb3c0b](https://github.com/Nuelthewave/Chesster/commit/abb3c0b89e810bd59c3e067aa10c1a2f0872bd1d))
* cover tournament flows and enforce CI quality gates ([c38e033](https://github.com/Nuelthewave/Chesster/commit/c38e03389547c24aa94eac7c42819e623ec16595))
* cover tournaments and enforce CI budgets ([f7729c1](https://github.com/Nuelthewave/Chesster/commit/f7729c11361c4a23531763718a187862b20e46f7))
* isolate health route configuration ([7d2dbc5](https://github.com/Nuelthewave/Chesster/commit/7d2dbc50e2237d0dce793bd1110f20e7277aa354))
* isolate health route configuration ([71a46b4](https://github.com/Nuelthewave/Chesster/commit/71a46b4a6ac3d779817cfc4ccb5bbbfd5d18e4c7))
* isolate health route SDK dependency ([4dc5b47](https://github.com/Nuelthewave/Chesster/commit/4dc5b474bc2831d4afbbec2f234f3798d73d4065))
* isolate health route SDK dependency ([5bf0b10](https://github.com/Nuelthewave/Chesster/commit/5bf0b10c7562e1aae05a20b056dc3f3bc3fccf5e))


### Continuous Integration

* add Lighthouse CI accessibility and SEO audits ([adb0b10](https://github.com/Nuelthewave/Chesster/commit/adb0b10a86358b5a0936659d1a5f01be0cd7aed8))
* add Lighthouse CI accessibility and SEO audits ([3e3f220](https://github.com/Nuelthewave/Chesster/commit/3e3f22065306daa0668625b279df4d43f3b3f900))
* **devops:** consolidate CI pipeline, add PR lint, security audit, and Docker dev setup ([108582e](https://github.com/Nuelthewave/Chesster/commit/108582eb469abbb861c1b6490f4b09067146b041))
* **devops:** consolidate CI pipeline, add PR lint, security audit, and Docker dev setup ([9b9864a](https://github.com/Nuelthewave/Chesster/commit/9b9864a10d1493f3d60502974d3af6ba8cfe5662))
* **pr-lint:** add contents: read and statuses: read permissions for pr-lint workflow ([4577ff9](https://github.com/Nuelthewave/Chesster/commit/4577ff95f3ad42dfd798a986ba362290e6c35502))
* **pr-lint:** grant statuses: write permission to allow setting PR status checks ([14c95b3](https://github.com/Nuelthewave/Chesster/commit/14c95b34ccb722f6595822c7110019cb43d83e89))
* **release:** release only from master so GitHub releases are marked latest ([0aa3748](https://github.com/Nuelthewave/Chesster/commit/0aa37482ebafd04412de4a6047ce3d8209d614d9))
* **release:** upgrade release-please action and fix workflow permissions ([b09166f](https://github.com/Nuelthewave/Chesster/commit/b09166f6760c74987f66426da8409a636d2c59f3))
* remove redundant pnpm version in action-setup to resolve packageManager conflict ([b5685c6](https://github.com/Nuelthewave/Chesster/commit/b5685c6b1cf4191407f229e4a65b4534ffeab73f))
* repair malformed npm lockfiles ([0c6f6a2](https://github.com/Nuelthewave/Chesster/commit/0c6f6a287dd627f1f6cb1a9311bd98acec91d6d7))
* repair npm lockfiles ([08b2c7b](https://github.com/Nuelthewave/Chesster/commit/08b2c7be4bc850cec66d62d7a6ef2ee078c1261c))
* replace unavailable Rust audit action ([641d7f8](https://github.com/Nuelthewave/Chesster/commit/641d7f848e53c6ab4daec36ba9fb9e5d7b921150))
* replace unavailable Rust audit action ([9543de6](https://github.com/Nuelthewave/Chesster/commit/9543de6c80a4c6568a0759d3ea8053e5412181a6))

## [1.38.4](https://github.com/Kaycee276/Chesster/compare/v1.38.3...v1.38.4) (2026-10-05)


### Bug Fixes

* **build:** configure visualizer plugin for bundle stats generation ([5c701f9](https://github.com/Kaycee276/Chesster/commit/5c701f992a78391cbab32f07b600d012bebd8df6))

## [1.38.3](https://github.com/Kaycee276/Chesster/compare/v1.38.2...v1.38.3) (2026-10-05)


### Bug Fixes

* **seo:** add meta description and robots.txt for Lighthouse SEO compliance ([55047cb](https://github.com/Kaycee276/Chesster/commit/55047cbfdf358e10d46fa19f4bf6fa000628da20))

## [1.38.2](https://github.com/Kaycee276/Chesster/compare/v1.38.1...v1.38.2) (2026-10-05)


### Bug Fixes

* **ci:** restore Node 24 in .nvmrc for native Jest ESM require support ([1c21402](https://github.com/Kaycee276/Chesster/commit/1c21402107a3ec1cea22a34815ad72f336b84461))

## [1.38.1](https://github.com/Kaycee276/Chesster/compare/v1.38.0...v1.38.1) (2026-10-05)


### Bug Fixes

* **test:** resolve Node 22 ESM require error, test env variables, and redis handles ([6a6b6a4](https://github.com/Kaycee276/Chesster/commit/6a6b6a425c59fcdbdc98c9c5aea8590a7b9b35d2))

# [1.38.0](https://github.com/Kaycee276/Chesster/compare/v1.37.0...v1.38.0) (2026-10-05)


### Bug Fixes

* **health:** update database provider name to Neon PostgreSQL and simplify status page design ([c86a588](https://github.com/Kaycee276/Chesster/commit/c86a5883999ed7070753a6b21caed75b061d7ce2))
* **ui:** improve mobile responsiveness and remove overlapping banners and floating controls ([c113498](https://github.com/Kaycee276/Chesster/commit/c11349829ceed5c08838418488be351a4e1a35e1))


### Features

* **frontend:** add live system status and endpoint telemetry page at /status ([5c6be4e](https://github.com/Kaycee276/Chesster/commit/5c6be4e28e6910cb68307127deb19f8f1ef60788))

# [1.37.0](https://github.com/Kaycee276/Chesster/compare/v1.36.1...v1.37.0) (2026-10-04)


### Features

* **backend:** implement GET /api/leaderboard endpoint and player stats synchronization ([ab62776](https://github.com/Kaycee276/Chesster/commit/ab62776d63787cc9492be5347b56b8ed85438dda))

## [1.36.1](https://github.com/Kaycee276/Chesster/compare/v1.36.0...v1.36.1) (2026-10-04)


### Bug Fixes

* resolve cross-origin CSRF validation in production and refine game layout ([69bec13](https://github.com/Kaycee276/Chesster/commit/69bec138161cf66797a4463de73792507ab0866f))

# [1.36.0](https://github.com/Kaycee276/Chesster/compare/v1.35.0...v1.36.0) (2026-10-04)


### Features

* **backend:** migrate from Supabase to Neon PostgreSQL and Prisma ([dae00f8](https://github.com/Kaycee276/Chesster/commit/dae00f86f67a29a83cfc89bc19c93f5f393fadd0))

# [1.35.0](https://github.com/Kaycee276/Chesster/compare/v1.34.0...v1.35.0) (2026-10-04)


### Features

* **backend:** configure Prisma ORM with Supabase connection pooling and schema sync ([154e3ee](https://github.com/Kaycee276/Chesster/commit/154e3eee0f8502b73ab8fc31b2dbdeaeb267dd7b))

# [1.34.0](https://github.com/Kaycee276/Chesster/compare/v1.33.0...v1.34.0) (2026-10-04)


### Bug Fixes

* **auth:** bound challenge store with expiry sweep and capacity policy ([#391](https://github.com/Kaycee276/Chesster/issues/391)) ([81fa366](https://github.com/Kaycee276/Chesster/commit/81fa3661aa5b697b49bbfcd4c0ebba04b6808806))
* resolve build and test failures across frontend, backend, and contracts ([aff2196](https://github.com/Kaycee276/Chesster/commit/aff219652ea062df677cef2b42f580e7e1dff089))
* resolve issue [#225](https://github.com/Kaycee276/Chesster/issues/225) ([#270](https://github.com/Kaycee276/Chesster/issues/270)) ([6f36f74](https://github.com/Kaycee276/Chesster/commit/6f36f74e0e26ace0dd167325cf41dd9c7952cf63))


### Features

* **backend:** export rich PGN game records ([#393](https://github.com/Kaycee276/Chesster/issues/393)) ([5a6cdb5](https://github.com/Kaycee276/Chesster/commit/5a6cdb5953cf1bb562f388bda7030785987cf400))
* **chess:** add blindfold and fog-of-war variants ([#395](https://github.com/Kaycee276/Chesster/issues/395)) ([626a824](https://github.com/Kaycee276/Chesster/commit/626a8241dcacf8758e61981ef754dca555cf5ee5))
* **contracts:** Implement Time-Based Escrow Forfeit Protocol for Inactive Players ([5b1d670](https://github.com/Kaycee276/Chesster/commit/5b1d67027dbd7a1960cdc81ceea6029a2fea5dd5)), closes [#231](https://github.com/Kaycee276/Chesster/issues/231)
* **contracts:** Support Soroban SAC Token Allowances for Multi-Asset Wagers (USDC / EURC) ([4b75a87](https://github.com/Kaycee276/Chesster/commit/4b75a878298ffa381f3e9e5aa18e3818bcbb067f)), closes [#232](https://github.com/Kaycee276/Chesster/issues/232)
* coordinate lobby expiry with Soroban escrow refund ([#396](https://github.com/Kaycee276/Chesster/issues/396)) ([5a7a6c1](https://github.com/Kaycee276/Chesster/commit/5a7a6c1eca39348cbd70803cf4f94e3891afa93c)), closes [#lobby-escrow-expiry](https://github.com/Kaycee276/Chesster/issues/lobby-escrow-expiry)
* **frontend:** Build Tournament Match Ready Queue Modal and Auto-Redirect Flow ([#273](https://github.com/Kaycee276/Chesster/issues/273)) ([3ee2cc1](https://github.com/Kaycee276/Chesster/commit/3ee2cc10fc9db17db960924df60574094d838bfa)), closes [#230](https://github.com/Kaycee276/Chesster/issues/230)
* **metrics:** expose websocket telemetry for issue 294 ([#392](https://github.com/Kaycee276/Chesster/issues/392)) ([4cc634e](https://github.com/Kaycee276/Chesster/commit/4cc634e6098f1712626c04e7d5aec3dedd796fcd))
* **rating:** add Glicko-2 player updates ([#394](https://github.com/Kaycee276/Chesster/issues/394)) ([9d48da0](https://github.com/Kaycee276/Chesster/commit/9d48da0d50e13a1517b6642ccb73affd0e3f62ba))

# [1.33.0](https://github.com/Kaycee276/Chesster/compare/v1.32.0...v1.33.0) (2026-09-28)


### Features

* **contracts,ci:** bound stale match GC batches and pin GitHub Actions to commit SHAs (closes [#379](https://github.com/Kaycee276/Chesster/issues/379), closes [#380](https://github.com/Kaycee276/Chesster/issues/380)) ([2293056](https://github.com/Kaycee276/Chesster/commit/229305637594b42dd4ef394ef5abca1b0bf4aead))

# [1.32.0](https://github.com/Kaycee276/Chesster/compare/v1.31.0...v1.32.0) (2026-09-28)


### Features

* **frontend:** Create Interactive Tree Tournament Bracket Component with Live Match Links ([cf9308b](https://github.com/Kaycee276/Chesster/commit/cf9308bb893cb5cfaf28f5eb67fa33f2777d7f9a)), closes [#229](https://github.com/Kaycee276/Chesster/issues/229)

# [1.31.0](https://github.com/Kaycee276/Chesster/compare/v1.30.0...v1.31.0) (2026-09-28)


### Features

* **frontend:** add keyboard move input, leaderboard filters, disconnect banner, and PGN drag-and-drop ([197b889](https://github.com/Kaycee276/Chesster/commit/197b8891bbf3e7293d31526c8b0e60786278337b)), closes [#315](https://github.com/Kaycee276/Chesster/issues/315) [#316](https://github.com/Kaycee276/Chesster/issues/316) [#317](https://github.com/Kaycee276/Chesster/issues/317) [#318](https://github.com/Kaycee276/Chesster/issues/318)

# [1.30.0](https://github.com/Kaycee276/Chesster/compare/v1.29.0...v1.30.0) (2026-09-28)


### Bug Fixes

* **contracts:** reconcile EscrowError limits and format after upstream merge ([be8785a](https://github.com/Kaycee276/Chesster/commit/be8785a4b9d07e54dbd518df43c7dfd33c00f699))


### Features

* **contracts:** add escrow emergency drain safe-harbor with timelock delay ([f700309](https://github.com/Kaycee276/Chesster/commit/f700309c5adb0f98b98fa66cd403db440aefabd4))
* **frontend:** add streamer mode with hidden balances ([26215f0](https://github.com/Kaycee276/Chesster/commit/26215f0621178fb723988c9637997f057751fbbb))
* **frontend:** build live streamer mode with hidden wager balances, address masking, enlarged board coordinates, and stream overlay route ([8d7ef6c](https://github.com/Kaycee276/Chesster/commit/8d7ef6cfbc834c4fa66919386ed071f479d87543))
* **frontend:** Implement Multi-Language Internationalization (i18n) Framework (EN, ES, FR, ZH) ([cddc5c0](https://github.com/Kaycee276/Chesster/commit/cddc5c0daa9b42c669016560587bc8f45cfe4549))

# [1.29.0](https://github.com/Kaycee276/Chesster/compare/v1.28.0...v1.29.0) (2026-09-27)


### Features

* **security,testing:** sanitize chat XSS, rate-limit and sanitize API inputs, add frontend unit tests ([3557f66](https://github.com/Kaycee276/Chesster/commit/3557f66d096cec22f2bc14fffd31a532d56e0698))

# [1.28.0](https://github.com/Kaycee276/Chesster/compare/v1.27.0...v1.28.0) (2026-09-27)


### Features

* **security:** resolve multiple assigned security tasks (closes [#323](https://github.com/Kaycee276/Chesster/issues/323), closes [#324](https://github.com/Kaycee276/Chesster/issues/324), closes [#325](https://github.com/Kaycee276/Chesster/issues/325), closes [#326](https://github.com/Kaycee276/Chesster/issues/326)) ([d05e842](https://github.com/Kaycee276/Chesster/commit/d05e842c69213d89f331af4530f885186fa304ce))

# [1.27.0](https://github.com/Kaycee276/Chesster/compare/v1.26.0...v1.27.0) (2026-09-27)


### Features

* **backend:** Implement Real-Time Socket.io Tournament Lifecycle Events ([8d40f80](https://github.com/Kaycee276/Chesster/commit/8d40f80de44653664e82450e121732fd548adb73))

# [1.26.0](https://github.com/Kaycee276/Chesster/compare/v1.25.0...v1.26.0) (2026-09-27)


### Features

* **db:** [#319](https://github.com/Kaycee276/Chesster/issues/319) player_rating_history table, [#320](https://github.com/Kaycee276/Chesster/issues/320) referral_program and claimable_commission_ledger tables ([db5d00c](https://github.com/Kaycee276/Chesster/commit/db5d00c41ccb4f0ccded0b0e372d0fc37112c344))

# [1.25.0](https://github.com/Kaycee276/Chesster/compare/v1.24.0...v1.25.0) (2026-09-27)


### Bug Fixes

* correct workspace CI dependency paths ([99c6f5f](https://github.com/Kaycee276/Chesster/commit/99c6f5f627b10b4a747c098feb0526025926fb88))


### Features

* **backend:** Implement Distributed Lock for Move Submission using Redis Redlock - Closes [#239](https://github.com/Kaycee276/Chesster/issues/239) ([75d8595](https://github.com/Kaycee276/Chesster/commit/75d859539ce4da4cb959593a81f0e6ba6269d4cb))
* **backend:** Implement Redis Adapter for Socket.io Clustering & Horizontal Scaling - Closes [#238](https://github.com/Kaycee276/Chesster/issues/238) ([99707a0](https://github.com/Kaycee276/Chesster/commit/99707a0af4b63ea07e07b6ac9d3246004d464240))
* **backend:** Implement WebSocket Latency Telemetry and Automatic Disconnect Grace Period - Closes [#240](https://github.com/Kaycee276/Chesster/issues/240) ([9013e8f](https://github.com/Kaycee276/Chesster/commit/9013e8f7131a3ad29a4d716f80a532998d5d1fcb))
* **contracts:** Add On-Chain Event Emitting for Player Win Streak & Trophy Milestones - Closes [#237](https://github.com/Kaycee276/Chesster/issues/237) ([fbdb3ea](https://github.com/Kaycee276/Chesster/commit/fbdb3ea99636c8465445af07ee9c7af85b202185))

# [1.24.0](https://github.com/Kaycee276/Chesster/compare/v1.23.0...v1.24.0) (2026-09-27)


### Bug Fixes

* **contracts:** reconcile EscrowError limits and format after upstream merge ([40dc134](https://github.com/Kaycee276/Chesster/commit/40dc134fcd3e60d1ce1276475d7cf9ca80afc4b6))
* **contracts:** repair escrow test boundaries ([e6119ab](https://github.com/Kaycee276/Chesster/commit/e6119ab1d5f10ed13c8ecd979f83716197d6feba))
* **escrow:** resolve clippy warnings and update wasm size budget limit ([8b66ec1](https://github.com/Kaycee276/Chesster/commit/8b66ec1363eb62eecb8a7a4d3e41d181b5329468))
* repair corrupted ChessBoard and GameResultModal components ([e20b18d](https://github.com/Kaycee276/Chesster/commit/e20b18debb1f3c3d929ced4a78454d7a6769e798))


### Features

* add share match link QR code to game lobby ([44de0ef](https://github.com/Kaycee276/Chesster/commit/44de0ef1e1d3bc0e6182e631b4f6185556a31a99))
* **contracts,backend:** implement escrow features for issues [#287](https://github.com/Kaycee276/Chesster/issues/287), [#288](https://github.com/Kaycee276/Chesster/issues/288), [#289](https://github.com/Kaycee276/Chesster/issues/289), and [#290](https://github.com/Kaycee276/Chesster/issues/290) ([4e35ce1](https://github.com/Kaycee276/Chesster/commit/4e35ce17a5416b47c3be1f8233a0bd080a8a05ff))
* **contracts:** add multi-sig emergency admin recovery scheme ([e9264aa](https://github.com/Kaycee276/Chesster/commit/e9264aa48e9859da9125ad2921a37249cd73c908))
* **contracts:** implement dynamic platform fee discount for staked token holders ([efda452](https://github.com/Kaycee276/Chesster/commit/efda452d67933e78d6058b61b36a90b529d4ef22))
* **database:** implement puzzles schema, seed script, and atomic escrow settle procedure (closes [#321](https://github.com/Kaycee276/Chesster/issues/321), closes [#322](https://github.com/Kaycee276/Chesster/issues/322)) ([c758713](https://github.com/Kaycee276/Chesster/commit/c758713dec9cea5824382c23b30e12553e7a5c7a))
* show wallet XLM/SAC balances in the navbar ([67e389a](https://github.com/Kaycee276/Chesster/commit/67e389a2af87078b94e544016b8e5ce27b65df9f))

# [1.23.0](https://github.com/Kaycee276/Chesster/compare/v1.22.0...v1.23.0) (2026-09-26)


### Features

* **contracts:** implement nonce-based replay protection for player deposit signatures ([90c3515](https://github.com/Kaycee276/Chesster/commit/90c35156945a72108c3da08a139315ff95d79624))

# [1.22.0](https://github.com/Kaycee276/Chesster/compare/v1.21.0...v1.22.0) (2026-09-26)


### Bug Fixes

* **backend:** keep deletion sessions revoked ([f9af09e](https://github.com/Kaycee276/Chesster/commit/f9af09e24f847519564d28726f17afd0e0e7f352))
* **backend:** prune archived game partitions ([f70c91d](https://github.com/Kaycee276/Chesster/commit/f70c91d345c6ce34d4b8dc51c392b601c2b1415f))
* **frontend:** repair SpectatorPage and ChessBoard broken by merge conflicts ([b1566c2](https://github.com/Kaycee276/Chesster/commit/b1566c22ae2d8bd6cd83aff727c175b12fba4916))


### Features

* **#304:** Implement spectator chat slow-mode and room isolation ([11b0a18](https://github.com/Kaycee276/Chesster/commit/11b0a187f2648405a4f56c29acace2e19c4ec584)), closes [#304](https://github.com/Kaycee276/Chesster/issues/304)
* **#306:** Interactive Tactical Puzzle Solver with Hint System ([f2b0ddd](https://github.com/Kaycee276/Chesster/commit/f2b0ddd1e0aba1aafe5f218145f314e3629b5f2a)), closes [#306](https://github.com/Kaycee276/Chesster/issues/306)
* add custom sound theme packs (wood, plastic, arcade, retro 8-bit) ([f468bc1](https://github.com/Kaycee276/Chesster/commit/f468bc18399aee75a2875aac0f8b11d80bf9b2e0)), closes [#307](https://github.com/Kaycee276/Chesster/issues/307)
* add low-time warning alert with pulsing border and tick sound ([fbd8e76](https://github.com/Kaycee276/Chesster/commit/fbd8e762945fc70478b6a56550ebe9cc0099e5bc)), closes [#309](https://github.com/Kaycee276/Chesster/issues/309)
* **backend:** add account privacy redaction ([31e417f](https://github.com/Kaycee276/Chesster/commit/31e417f75e98146c90e15896ccfcbd58957aa66a))
* **backend:** add asynchronous event broadcasting ([7bfb067](https://github.com/Kaycee276/Chesster/commit/7bfb0672a4cbd944d01603eef7a3bd1f965e87f3))
* **backend:** add automated game archival ([360cb3d](https://github.com/Kaycee276/Chesster/commit/360cb3decb61b49b866e32609ba0f1de0b4ea421))
* **backend:** add daily chess puzzles ([5bcaf11](https://github.com/Kaycee276/Chesster/commit/5bcaf1168916b7722c5f9f7061f81b33215dc1fb))
* **backend:** add dynamic elo bucket expansion to matchmaking ([b0267d8](https://github.com/Kaycee276/Chesster/commit/b0267d89f8c9228bf723cdbf38400b0b9f41519e)), closes [#248](https://github.com/Kaycee276/Chesster/issues/248)
* **backend:** add match audit log export API for dispute resolution ([94f62c8](https://github.com/Kaycee276/Chesster/commit/94f62c81a1ad2aeda84dd0bc36f6018f66b58fed)), closes [#243](https://github.com/Kaycee276/Chesster/issues/243)
* **backend:** add referral commission tracking ([43347bf](https://github.com/Kaycee276/Chesster/commit/43347bfbb937561cc603bc80ded2a78fb1813c40))
* **backend:** add webhook exponential backoff and dead-letter queue ([f527e8f](https://github.com/Kaycee276/Chesster/commit/f527e8f2ebf1dce6ac1acbfd4ad22358d72b12e5)), closes [#246](https://github.com/Kaycee276/Chesster/issues/246)
* **backend:** cache user profile stats and match history in redis ([8a76331](https://github.com/Kaycee276/Chesster/commit/8a763312e68ce144d45776589d1ed48deea93dbd)), closes [#247](https://github.com/Kaycee276/Chesster/issues/247)
* **backend:** dispatch tournament notifications ([61e4e23](https://github.com/Kaycee276/Chesster/commit/61e4e23d4b2a1c1fea4bab20a3dfc55c27bc7092))
* **backend:** enforce wager geo compliance ([e6a8567](https://github.com/Kaycee276/Chesster/commit/e6a8567ee63fb7ec9c5159a740471f35fc2779e7))
* **backend:** persist anti-cheat analysis ([07b7f25](https://github.com/Kaycee276/Chesster/commit/07b7f25e0224d8037c4fee10a91a44a1daf3fcf9))
* **backend:** run stockfish bot moves in a worker thread pool ([c8519d4](https://github.com/Kaycee276/Chesster/commit/c8519d49b09fc0c06d8820a958a4346c33fcec58)), closes [#241](https://github.com/Kaycee276/Chesster/issues/241)
* **backend:** stream game replays over server-sent events ([077b6ba](https://github.com/Kaycee276/Chesster/commit/077b6ba4a199022f5deca22cc59ade19828c2e44)), closes [#245](https://github.com/Kaycee276/Chesster/issues/245)
* board social card image generator (closes [#310](https://github.com/Kaycee276/Chesster/issues/310)) ([670fc78](https://github.com/Kaycee276/Chesster/commit/670fc78f7554b60188a5e8c38fb728e8ca20f90e))
* **contracts:** Add Cryptographic Ed25519 Result Signature Verification in Escrow Settlement ([98a7a03](https://github.com/Kaycee276/Chesster/commit/98a7a030e50701788eae50c82b12cd8cfbbe5b02)), closes [#233](https://github.com/Kaycee276/Chesster/issues/233)
* **contracts:** Implement Compact Binary Serialization for Match Storage to Reduce Soroban Gas ([3738574](https://github.com/Kaycee276/Chesster/commit/3738574ca31c0fa8199728ee205dcb82d41b0f01)), closes [#234](https://github.com/Kaycee276/Chesster/issues/234)
* **contracts:** implement player elo rating commitment and proof-of-skill on stellar ([2491c28](https://github.com/Kaycee276/Chesster/commit/2491c28a8bcf9824be5300e74096389f877e4e71))
* **frontend:** add client-side stockfish evaluation bar ([5eaaca7](https://github.com/Kaycee276/Chesster/commit/5eaaca7b167d9682b87005d562fa9f06241009fc)), closes [#250](https://github.com/Kaycee276/Chesster/issues/250)
* **frontend:** add player profile page with rating history chart ([629285c](https://github.com/Kaycee276/Chesster/commit/629285c90b70c992386ab306872d91566ef3cfab)), closes [#255](https://github.com/Kaycee276/Chesster/issues/255)
* **frontend:** high-contrast accessibility board theme for low-vision players ([fde1e8f](https://github.com/Kaycee276/Chesster/commit/fde1e8f2ecb237328725c0fdf37521489cb9578b)), closes [hi#contrast](https://github.com/hi/issues/contrast) [#314](https://github.com/Kaycee276/Chesster/issues/314) [Hi#Contrast](https://github.com/Hi/issues/Contrast) [hi#contrast](https://github.com/hi/issues/contrast)
* **frontend:** keyboard shortcuts, board accessibility, wager pills, and leaderboard ([d1a3e17](https://github.com/Kaycee276/Chesster/commit/d1a3e174fa3bd09cc40fa466f1a1a8dbfce96707))
* **frontend:** move accuracy & blunder classification in post-game analysis ([2202e89](https://github.com/Kaycee276/Chesster/commit/2202e8973a4473962e577fec4bb62072d01b3eb8)), closes [#313](https://github.com/Kaycee276/Chesster/issues/313)
* implement Blindfold Mode & Peek feature (Issue [#305](https://github.com/Kaycee276/Chesster/issues/305)) ([ca248ad](https://github.com/Kaycee276/Chesster/commit/ca248ad440ffe045ff2aa33416bc1d909a44b24a))
* implement player referral dashboard (closes [#308](https://github.com/Kaycee276/Chesster/issues/308)) ([cd0eaec](https://github.com/Kaycee276/Chesster/commit/cd0eaecafed002d9891eab799e9079d6f34a3fc3))
* implement Socket.io reconnect handshake recovery with game state rehydration (issue [#303](https://github.com/Kaycee276/Chesster/issues/303)) ([b47e1ca](https://github.com/Kaycee276/Chesster/commit/b47e1cadb2caf75bb3b6c1d174930dc045807409))

# [1.21.0](https://github.com/Kaycee276/Chesster/compare/v1.20.0...v1.21.0) (2026-09-25)


### Features

* **frontend:** add right-click arrows and square highlights to the board ([23482a5](https://github.com/Kaycee276/Chesster/commit/23482a524797106a324bb80caca97d7ba830b6bc))

# [1.20.0](https://github.com/Kaycee276/Chesster/compare/v1.19.0...v1.20.0) (2026-09-25)


### Features

* harden chat and add tournament health coverage ([86b8634](https://github.com/Kaycee276/Chesster/commit/86b86341165a8f15b1bf09767ee1544daadf0abb))

# [1.19.0](https://github.com/Kaycee276/Chesster/compare/v1.18.0...v1.19.0) (2026-09-25)


### Features

* **frontend:** add network/offline connection alert banner ([86ea021](https://github.com/Kaycee276/Chesster/commit/86ea021c0077610379ee5a1666be91bffc59f52c)), closes [#256](https://github.com/Kaycee276/Chesster/issues/256)

# [1.18.0](https://github.com/Kaycee276/Chesster/compare/v1.17.0...v1.18.0) (2026-09-25)


### Features

* **backend:** add IP rate limiting for WebSocket handshakes ([25cd6c8](https://github.com/Kaycee276/Chesster/commit/25cd6c83383f2fc300031c6ba54722f7fdd7d240)), closes [#244](https://github.com/Kaycee276/Chesster/issues/244)
* **backend:** implement threefold repetition and 50-move draw detection ([8f87590](https://github.com/Kaycee276/Chesster/commit/8f87590b2c8c67956b62949eaf3396ab6d0dbb32)), closes [#242](https://github.com/Kaycee276/Chesster/issues/242)
* **frontend:** add PGN import and visual move replay analyzer ([9335a83](https://github.com/Kaycee276/Chesster/commit/9335a8358869e051ee92d8416de0e0323ddf1788))
* **frontend:** add post-game result modal with PGN copy, rematch and share ([47dfa08](https://github.com/Kaycee276/Chesster/commit/47dfa0862f640d1e747de2e4835d49e3918a38ae)), closes [#254](https://github.com/Kaycee276/Chesster/issues/254)

# [1.17.0](https://github.com/Kaycee276/Chesster/compare/v1.16.0...v1.17.0) (2026-09-25)


### Features

* add spectator reactions, themes, controls, and csrf ([7dd4527](https://github.com/Kaycee276/Chesster/commit/7dd4527b58147e74d21a8c680e287bdcc588af22))
* **frontend:** add low-time cue, autoplay unlock, and sound service tests ([7bfeda1](https://github.com/Kaycee276/Chesster/commit/7bfeda1f0fbd0c56183e6323d62972f793fe4996))
* **frontend:** add touch drag-and-drop piece movement with haptic feedback ([fb8db99](https://github.com/Kaycee276/Chesster/commit/fb8db997b82c67bb21562aa4627a487ac7d64896))

# [1.16.0](https://github.com/Kaycee276/Chesster/compare/v1.15.0...v1.16.0) (2026-09-24)


### Features

* **frontend:** build Tournament Hub screen with category filters and search ([#228](https://github.com/Kaycee276/Chesster/issues/228)) ([b83b330](https://github.com/Kaycee276/Chesster/commit/b83b330e8f32ce483b490864c0b16ab67154c1f0))

# [1.15.0](https://github.com/Kaycee276/Chesster/compare/v1.14.0...v1.15.0) (2026-09-24)


### Features

* **contracts:** Implement Batch Settlement Function for Concurrent Escrows ([516f067](https://github.com/Kaycee276/Chesster/commit/516f067e61e0ea003772db1a20078e319a528429)), closes [#236](https://github.com/Kaycee276/Chesster/issues/236)

# [1.14.0](https://github.com/Kaycee276/Chesster/compare/v1.13.0...v1.14.0) (2026-09-24)


### Features

* **tournament:** implement on-chain prize escrow, refund window, bracket seeding, and round advancement ([709f2fc](https://github.com/Kaycee276/Chesster/commit/709f2fcdf4a15c7f7a845e3b5e6b2dc8a8b9339d)), closes [#219](https://github.com/Kaycee276/Chesster/issues/219) [#220](https://github.com/Kaycee276/Chesster/issues/220) [#223](https://github.com/Kaycee276/Chesster/issues/223) [#224](https://github.com/Kaycee276/Chesster/issues/224)


### Performance Improvements

* **contracts:** optimize contract WASM size within 64 KB budget limit ([8e14730](https://github.com/Kaycee276/Chesster/commit/8e1473031ecd98a292ee3558fb3ab2ba12daa4d2))

# [1.13.0](https://github.com/Kaycee276/Chesster/compare/v1.12.0...v1.13.0) (2026-09-24)


### Features

* **backend,contracts:** match creation rate limiting, api docs, tournament rake, and disqualification slashing (closes [#151](https://github.com/Kaycee276/Chesster/issues/151), closes [#152](https://github.com/Kaycee276/Chesster/issues/152), closes [#221](https://github.com/Kaycee276/Chesster/issues/221), closes [#222](https://github.com/Kaycee276/Chesster/issues/222)) ([5ee7463](https://github.com/Kaycee276/Chesster/commit/5ee7463241d94d809d92824276a8c0e3cdaa4e6d))

# [1.12.0](https://github.com/Kaycee276/Chesster/compare/v1.11.0...v1.12.0) (2026-09-24)


### Features

* **database:** add tournament bracket and participant tables migration ([c902d26](https://github.com/Kaycee276/Chesster/commit/c902d2646daed783abd8d19d3efc736f11f20e78))

# [1.11.0](https://github.com/Kaycee276/Chesster/compare/v1.10.1...v1.11.0) (2026-09-23)


### Features

* implement contract storage TTL, allowance check, batch resolution, and theme mode ([79afb68](https://github.com/Kaycee276/Chesster/commit/79afb68966be423461f4ddf5848001784cc2c2d5)), closes [#29](https://github.com/Kaycee276/Chesster/issues/29) [#27](https://github.com/Kaycee276/Chesster/issues/27) [#25](https://github.com/Kaycee276/Chesster/issues/25) [#129](https://github.com/Kaycee276/Chesster/issues/129)

## [1.10.1](https://github.com/Kaycee276/Chesster/compare/v1.10.0...v1.10.1) (2026-09-16)


### Bug Fixes

* **database:** add existence checks for optional tables in RLS migration ([#137](https://github.com/Kaycee276/Chesster/issues/137)) ([8ee29b5](https://github.com/Kaycee276/Chesster/commit/8ee29b51e552152efa0f2a668cef684e1091a85a))

# [1.10.0](https://github.com/Kaycee276/Chesster/compare/v1.9.4...v1.10.0) (2026-09-16)


### Features

* **database:** implement Row-Level Security (RLS) policies for all Supabase tables ([#137](https://github.com/Kaycee276/Chesster/issues/137)) ([e860208](https://github.com/Kaycee276/Chesster/commit/e86020865e2ed8f493d03d71f67903745946b475))

## [1.9.4](https://github.com/Kaycee276/Chesster/compare/v1.9.3...v1.9.4) (2026-09-07)


### Bug Fixes

* resolve frontend/backend env validation and DB schema fallback for time control columns ([ff43083](https://github.com/Kaycee276/Chesster/commit/ff430839de28b409626af12cfb93029a906683c7))

## [1.9.3](https://github.com/Kaycee276/Chesster/compare/v1.9.2...v1.9.3) (2026-09-07)


### Bug Fixes

* **frontend:** remove leave game button while waiting for opponent ([601e34a](https://github.com/Kaycee276/Chesster/commit/601e34a75ec967b66afd4991c0951736647d0c3e))

## [1.9.2](https://github.com/Kaycee276/Chesster/compare/v1.9.1...v1.9.2) (2026-09-06)


### Bug Fixes

* **backend:** validate coordinator secret key gracefully and support env alias fallback keys ([cfa57d3](https://github.com/Kaycee276/Chesster/commit/cfa57d3d3da3dc160d08b71ef989cfafb87b5214))

## [1.9.1](https://github.com/Kaycee276/Chesster/compare/v1.9.0...v1.9.1) (2026-09-06)


### Bug Fixes

* **contracts:** fix clippy len_zero warning in test.rs ([90c2354](https://github.com/Kaycee276/Chesster/commit/90c235493bb3786a5957d9e7f5ca273331bf93cd))

# [1.9.0](https://github.com/Kaycee276/Chesster/compare/v1.8.0...v1.9.0) (2026-09-06)


### Bug Fixes

* **ci:** refresh backend lockfile ([41de40b](https://github.com/Kaycee276/Chesster/commit/41de40bb0e96bb7426663aa5d2aa6e18687bc1f5))
* **database:** add indexes for game and move queries ([6b76cea](https://github.com/Kaycee276/Chesster/commit/6b76ceaeb46b1e0fa9e8ec62a7fe9cc0e5656898))
* resolve smart contract compilation errors, frontend TS build, and test suite configs ([6e83092](https://github.com/Kaycee276/Chesster/commit/6e83092faa04528fb9bce38f4e65b0364eb3bb23))
* stabilize backend CI test environment ([5f306c8](https://github.com/Kaycee276/Chesster/commit/5f306c8d1a6fda90dca44151feeb664b7c44e3da))
* stabilize backend CI test environment ([42d5860](https://github.com/Kaycee276/Chesster/commit/42d58602f7bd9842b105bab003568f55867f8909))


### Features

* add configurable regional wager blocking ([eadb5c0](https://github.com/Kaycee276/Chesster/commit/eadb5c0c7cf97db4ac8d16a9041e3892390f3373))
* add escrow unresolved-match fallback ([883b464](https://github.com/Kaycee276/Chesster/commit/883b4648fafd8b4e6551cf680487f9388e8139a2))
* anti-cheat telemetry, helmet CORS/CSP, touch gestures, animation improvements ([f73de28](https://github.com/Kaycee276/Chesster/commit/f73de28185075b66218c954419a2ac5b0955aca8)), closes [#105](https://github.com/Kaycee276/Chesster/issues/105) [#106](https://github.com/Kaycee276/Chesster/issues/106) [#116](https://github.com/Kaycee276/Chesster/issues/116) [#120](https://github.com/Kaycee276/Chesster/issues/120)
* **backend:** enable websocket per-message deflate ([b6e68db](https://github.com/Kaycee276/Chesster/commit/b6e68db91eafb251114e6c2300ab256b831cb628))
* **contracts:** add emergency pause circuit breaker (issue [#22](https://github.com/Kaycee276/Chesster/issues/22)) ([910a11f](https://github.com/Kaycee276/Chesster/commit/910a11ff5ce0c9423ab607eb6bcc321ec5e1bbb4))
* **contracts:** Add match cancellation and cooperative mutual draw resolution ([#20](https://github.com/Kaycee276/Chesster/issues/20)) ([b9118cb](https://github.com/Kaycee276/Chesster/commit/b9118cba9c68ecf89ee48f5b9ab8c00d278ea1fe))
* **contracts:** Escrow security hardening — coordinator rotation, reentrancy guard, balance invariants, upgradeability ([03f1eab](https://github.com/Kaycee276/Chesster/commit/03f1eab8985b7f68dc0761fe447cef05377e4e3b)), closes [#100](https://github.com/Kaycee276/Chesster/issues/100) [#103](https://github.com/Kaycee276/Chesster/issues/103) [#104](https://github.com/Kaycee276/Chesster/issues/104) [#102](https://github.com/Kaycee276/Chesster/issues/102) [#100](https://github.com/Kaycee276/Chesster/issues/100) [#102](https://github.com/Kaycee276/Chesster/issues/102) [#103](https://github.com/Kaycee276/Chesster/issues/103) [#104](https://github.com/Kaycee276/Chesster/issues/104)
* **contracts:** Implement Dynamic Wager Scaling with Configurable Minimum & Maximum Limits ([c5d44b6](https://github.com/Kaycee276/Chesster/commit/c5d44b6e7275a0d97a7b295ad10d96d95ac334af)), closes [#23](https://github.com/Kaycee276/Chesster/issues/23)
* **contracts:** implement match expiration & auto-claim refund timeout logic ([e391bc5](https://github.com/Kaycee276/Chesster/commit/e391bc55195d745db3da1c5521eb60bb6f0fcaba)), closes [#19](https://github.com/Kaycee276/Chesster/issues/19) [#21](https://github.com/Kaycee276/Chesster/issues/21)
* **contracts:** Implement platform fee tiering and treasury vault configuration ([#19](https://github.com/Kaycee276/Chesster/issues/19)) ([b9db53c](https://github.com/Kaycee276/Chesster/commit/b9db53c606d4dc53d0f9e360c5b0179397b66ad7))
* **frontend:** add customizable piece sets and board flip toggle ([#125](https://github.com/Kaycee276/Chesster/issues/125), [#128](https://github.com/Kaycee276/Chesster/issues/128)) ([7eb1c0f](https://github.com/Kaycee276/Chesster/commit/7eb1c0f597dc163e2a79a90a50fc5e98bc4b2c4a))
* **frontend:** add in-app notification toast system for game invitations ([#126](https://github.com/Kaycee276/Chesster/issues/126)) ([bb9b515](https://github.com/Kaycee276/Chesster/commit/bb9b515ddc72cdf1b916b619e3de39ede5d3a765))
* **frontend:** add live game spectator mode with evaluation bar ([#127](https://github.com/Kaycee276/Chesster/issues/127)) ([3016823](https://github.com/Kaycee276/Chesster/commit/30168231d922694287def19f624fc660a554ed79))
* **frontend:** game playback rewind, material display, move indicators, fullscreen ([37f1312](https://github.com/Kaycee276/Chesster/commit/37f13121e26348fabc120b1ec54a14e6cfb817e8)), closes [#124](https://github.com/Kaycee276/Chesster/issues/124) [#123](https://github.com/Kaycee276/Chesster/issues/123) [#112](https://github.com/Kaycee276/Chesster/issues/112) [#109](https://github.com/Kaycee276/Chesster/issues/109)
* **frontend:** volume control, PGN/FEN export, multi-wallet, ESLint fixes ([bf7d586](https://github.com/Kaycee276/Chesster/commit/bf7d5869cd08e672b2b759892f63027cc39ec005)), closes [#107](https://github.com/Kaycee276/Chesster/issues/107) [#108](https://github.com/Kaycee276/Chesster/issues/108) [#110](https://github.com/Kaycee276/Chesster/issues/110) [#111](https://github.com/Kaycee276/Chesster/issues/111)
* moderate player chat messages ([02bc34a](https://github.com/Kaycee276/Chesster/commit/02bc34a2b9d15a52a338af62204f47f1acd575bc))

# [1.8.0](https://github.com/Kaycee276/Chesster/compare/v1.7.0...v1.8.0) (2026-08-26)


### Bug Fixes

* **database:** drop end_reason from seed (column not in canonical schema) ([c39d4c2](https://github.com/Kaycee276/Chesster/commit/c39d4c2bcabfd6aa74b8454080991fea1c73c625))
* **database:** sync package-lock with pg dependency ([7abc974](https://github.com/Kaycee276/Chesster/commit/7abc974180e5e938fff854711cb92886a0c0c4fa))


### Features

* **contracts:** Implement On-Chain Player Elo Rating Ledger Proof ([93d6acb](https://github.com/Kaycee276/Chesster/commit/93d6acba0b0e3224d05afa6f3c5c053553b1e383))
* **database:** add automated encrypted PostgreSQL backup & snapshot script ([3d93bf3](https://github.com/Kaycee276/Chesster/commit/3d93bf317bfbd291fb72ac7035f1256b0b3445f9)), closes [#119](https://github.com/Kaycee276/Chesster/issues/119)
* **database:** add idempotent seed data script for local dev & E2E ([8d7dab4](https://github.com/Kaycee276/Chesster/commit/8d7dab463dd2cc8c3a0b13d0e8f42dd4559b5973)), closes [#117](https://github.com/Kaycee276/Chesster/issues/117)
* **database:** add migration runner script with rollback support ([69dc8fa](https://github.com/Kaycee276/Chesster/commit/69dc8fa81716ab9db9174afab3fcf3458be6f719)), closes [#80](https://github.com/Kaycee276/Chesster/issues/80)
* **database:** partition games table by month on created_at (012) ([cc63e5a](https://github.com/Kaycee276/Chesster/commit/cc63e5ae83135d5a41b35b2098ba4033af287903)), closes [#118](https://github.com/Kaycee276/Chesster/issues/118)
* **frontend:** add customizable board themes (Wood, Neon, Classic, Marble) ([bca8b13](https://github.com/Kaycee276/Chesster/commit/bca8b1303e1a7ada5152d3016f159fdfaa7fc28b)), closes [#82](https://github.com/Kaycee276/Chesster/issues/82)

# [1.7.0](https://github.com/Kaycee276/Chesster/compare/v1.6.0...v1.7.0) (2026-08-26)


### Features

* **database:** add token wager transaction ledger table migration ([#79](https://github.com/Kaycee276/Chesster/issues/79)) ([d2e0c74](https://github.com/Kaycee276/Chesster/commit/d2e0c74972c0c1a45fde3947ac412f42aff503a5))

# [1.6.0](https://github.com/Kaycee276/Chesster/compare/v1.5.0...v1.6.0) (2026-08-25)


### Features

* add escrow retries whitelist and events ([c3edf69](https://github.com/Kaycee276/Chesster/commit/c3edf691b5629ebea7d0020c6767903e2d226260))
* **backend:** add daily active player and match volume aggregation service ([#69](https://github.com/Kaycee276/Chesster/issues/69)) ([8a7de90](https://github.com/Kaycee276/Chesster/commit/8a7de9056a3d5f7b393ddef6f89afedc8ee81fc8))
* **backend:** add global exception handling & Sentry error reporting middleware ([#61](https://github.com/Kaycee276/Chesster/issues/61)) ([01ac707](https://github.com/Kaycee276/Chesster/commit/01ac707ebeadc574dfb1d800bbba887aa1f9ddfa))
* **backend:** implement Elo rating update calculation service ([#66](https://github.com/Kaycee276/Chesster/issues/66)) ([01c966f](https://github.com/Kaycee276/Chesster/commit/01c966fc6553eaf72dbb25705cb0a9fa6ffe28fb))
* **backend:** Implement Matchmaking Queue with Elo-Based Rating Pairings ([4e784a8](https://github.com/Kaycee276/Chesster/commit/4e784a8cb0d42c895eb202367e5886780a1b81fd))
* **contracts:** Add Comprehensive Rustdoc Comments, Stale Match GC, and Native XLM Utilities ([2f2fd6c](https://github.com/Kaycee276/Chesster/commit/2f2fd6c5a38008459eebadf428d650e6f112dc51))
* **database:** add move history JSONB schema validation constraint ([#77](https://github.com/Kaycee276/Chesster/issues/77)) ([bb252f6](https://github.com/Kaycee276/Chesster/commit/bb252f6d1a46b1b2b5e9bfe8c786f4e26dcbfc73))
* **database:** add player match statistics aggregation trigger ([#76](https://github.com/Kaycee276/Chesster/issues/76)) ([6a745d8](https://github.com/Kaycee276/Chesster/commit/6a745d854caa09be8f5d9529ce26193645d4b222))
* **database:** add soft delete and archival partitioning migration ([#74](https://github.com/Kaycee276/Chesster/issues/74)) ([2737e83](https://github.com/Kaycee276/Chesster/commit/2737e8351c43851bca1b2a1e47cb4d955c3d96d7))
* **database:** implement match_audit_logs table for dispute resolution ([96cfa54](https://github.com/Kaycee276/Chesster/commit/96cfa54816795c760fd665d0f71ef660cd9684ea)), closes [#73](https://github.com/Kaycee276/Chesster/issues/73)

# [1.5.0](https://github.com/Kaycee276/Chesster/compare/v1.4.0...v1.5.0) (2026-08-25)


### Features

* **backend:** Add structured logging, health checks, PGN/FEN support, and Stellar indexer ([c5cfa80](https://github.com/Kaycee276/Chesster/commit/c5cfa80778f36852e50dc0f9cb5fc4e1948cc0a1))
* **backend:** implement webhook notification service for match payout confirmations ([918336a](https://github.com/Kaycee276/Chesster/commit/918336a25ec4a04dd31d937d0fc4469a0b92de61)), closes [#48](https://github.com/Kaycee276/Chesster/issues/48) [#49](https://github.com/Kaycee276/Chesster/issues/49) [#50](https://github.com/Kaycee276/Chesster/issues/50) [#51](https://github.com/Kaycee276/Chesster/issues/51)
* **contracts:** Support Multi-Token Wagers in Soroban Escrow ([0b46b92](https://github.com/Kaycee276/Chesster/commit/0b46b924fb273783ffa2265b5e348800e7526ec7))

# [1.4.0](https://github.com/Kaycee276/Chesster/compare/v1.3.0...v1.4.0) (2026-08-25)


### Features

* **backend:** Implement move validation cache, cron cleanup, paginated history, and undo protocol ([18c7696](https://github.com/Kaycee276/Chesster/commit/18c7696965358a3b01e4faf3aa2331b3d19fec7c)), closes [#60](https://github.com/Kaycee276/Chesster/issues/60) [#59](https://github.com/Kaycee276/Chesster/issues/59) [#58](https://github.com/Kaycee276/Chesster/issues/58) [#54](https://github.com/Kaycee276/Chesster/issues/54) [#60](https://github.com/Kaycee276/Chesster/issues/60) [#59](https://github.com/Kaycee276/Chesster/issues/59) [#58](https://github.com/Kaycee276/Chesster/issues/58) [#54](https://github.com/Kaycee276/Chesster/issues/54)

# [1.3.0](https://github.com/Kaycee276/Chesster/compare/v1.2.0...v1.3.0) (2026-08-24)


### Features

* **contracts:** add storage TTL auto-extension, allowance checks, dispute time-lock, and batch resolution ([807a876](https://github.com/Kaycee276/Chesster/commit/807a8769a1bca8a5e4b6d642afe41eb2843d13b9))

# [1.2.0](https://github.com/Kaycee276/Chesster/compare/v1.1.0...v1.2.0) (2026-08-24)


### Features

* **backend:** add JWT authentication middleware for profile customization ([0029b98](https://github.com/Kaycee276/Chesster/commit/0029b981153d48bc06f36b8df4f8f4f4a6143687))
* **backend:** add Stockfish AI bot opponent endpoint for single player ([7b2fc89](https://github.com/Kaycee276/Chesster/commit/7b2fc897b3fb5ba1dc09a0b6b4727029f8f72e6e))
* **backend:** Socket.io reconnect grace period + per-player clock increments ([6de060d](https://github.com/Kaycee276/Chesster/commit/6de060d2a516f26b51796569e3c0f9a7239a13ff)), closes [#43](https://github.com/Kaycee276/Chesster/issues/43) [#45](https://github.com/Kaycee276/Chesster/issues/45)

# [1.1.0](https://github.com/Kaycee276/Chesster/compare/v1.0.1...v1.1.0) (2026-08-24)


### Bug Fixes

* **escrow:** resolve clippy bool_assert_comparison warning in test.rs ([e3e5227](https://github.com/Kaycee276/Chesster/commit/e3e5227855f2554072a0ae96737a198dde03de9e))


### Features

* **contracts:** Add comprehensive escrow enhancements ([6f6c89f](https://github.com/Kaycee276/Chesster/commit/6f6c89f0830d81d4240fd52ff70fabc72923a48d)), closes [#33](https://github.com/Kaycee276/Chesster/issues/33) [#32](https://github.com/Kaycee276/Chesster/issues/32) [#31](https://github.com/Kaycee276/Chesster/issues/31) [#30](https://github.com/Kaycee276/Chesster/issues/30)
* **contracts:** implement match nonce, side betting pool, fee discount, and mutual cancellation ([d1b1e5a](https://github.com/Kaycee276/Chesster/commit/d1b1e5a2d4aa2a513a4774aa6456c0312e28337b)), closes [#34](https://github.com/Kaycee276/Chesster/issues/34) [#35](https://github.com/Kaycee276/Chesster/issues/35) [#36](https://github.com/Kaycee276/Chesster/issues/36) [#37](https://github.com/Kaycee276/Chesster/issues/37)

## [1.0.1](https://github.com/Kaycee276/Chesster/compare/v1.0.0...v1.0.1) (2026-08-24)


### Bug Fixes

* **frontend:** resolve ESLint errors and Vitest config type overload ([ca643d9](https://github.com/Kaycee276/Chesster/commit/ca643d91414696c57dfe69c20fa72fade005ff18))

# 1.0.0 (2026-08-24)


### Bug Fixes

* fix payout model ([b553e28](https://github.com/Kaycee276/Chesster/commit/b553e28575e8b6c44d542525b25faa7b8365fa57))

# Changelog

All notable changes to **Chesster** will be automatically documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
