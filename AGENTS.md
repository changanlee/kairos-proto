# AGENTS.md — Kairos(Codex)

> 工程標準 → `~/.codex/AGENTS.md`;生態系層 → `~/Desktop/Anthea/AGENTS.md`。本檔只補 Kairos-specific。

Anthea sage(時間 / 決策時機）。3 sub-repo(github),BMAD-managed,**near-launch**(12 Epic 規劃完成、pre-launch-checklist 已備、DB migration 30）。

## Session 啟動

無本地 `CLAUDE.md` → 套全域 7 個非協商 audit(見 `~/.codex/AGENTS.md`),報缺項標 P0/P1,再進 task。

## BMAD 階段(接 new/compacted session 先確認,不順慣性執行)

- sprint / Epic 狀態看 BMAD planning artifacts(`_bmad-output/...`)。
- near-launch:動 launch-critical 路徑前先讀 pre-launch-checklist。
- DB:migration 已到 30——加 migration 接續編號,不跳號。

## 已知 dogfood 訊號(來自 owner 規劃)

- Goal-layer survival ring 已 BUILT+MERGED(2026-06-14),**尚未 deployed**。
- 13.8 conversational re-plan = top dogfood 需求(owner 想像聊天一樣對 app 重新規劃)。

## Anthea 紀律

- Phase 1:**禁止 sage-to-sage 直接呼叫**;跨 sage 整合延到 Phase 4。
- model pin 變更前查 `ops/model-registry.md`(runtime-audit pending)。

## 接力

repo 根有 `HANDOFF.md` → 先讀 + `git log` 還原脈絡(見 `docs/HANDOFF-template.md`)。3 sub-repo 注意:HANDOFF 寫清楚是哪個 repo。
