# LANDE-RD

**種別 / Type**: フリーソフト / Freeware

## 概要
東芝製 HDD＆DVDレコーダー用の **ネットダビング仮想HDD** です（RD-Z1 で動作確認）。
LANDE-RD を起動し、東芝製HDD＆DVDレコーダー側から「ネットワーク」を選択してダビングします。

## 主な機能
- **RD → PC** のダビングに対応（PC→RD へは、RD→PC でダビングしたファイルのみ可能）
- RD-Z1 の場合、`REMOTE.INI` の `auto_cmd=0` を `auto_cmd=1` にすると、自動でネットワーク機器選択画面を開く（他機種も `cmd_00〜` を編集すれば動作する可能性あり）
- **送信完了後の自動電源オフ**（PC / RD 両方）に対応。RD→PC 送信中に RD 側で電源オフを有効にすると PC もシャットダウン

## 対応OS
- Windows 2000 / XP / Vista

## ダウンロード
[Releases](https://github.com/HDBENCH/software/releases) からZIPをダウンロードしてください。

---

## Overview (English)
A **virtual HDD for network dubbing** with Toshiba HDD&DVD recorders (verified on RD-Z1).
Launch LANDE-RD, then choose "Network" on the Toshiba recorder to dub.

**Features**
- Supports **RD → PC** dubbing (PC → RD is possible only for files previously dubbed RD → PC)
- On RD-Z1, changing `auto_cmd=0` to `auto_cmd=1` in `REMOTE.INI` opens the network-device selection screen automatically (other models may work by editing `cmd_00...`)
- **Auto power-off after transfer** (both PC and RD). Enabling power-off on the RD during an RD→PC transfer also shuts down the PC

**Supported OS:** Windows 2000 / XP / Vista
**Download:** Get the ZIP from [Releases](https://github.com/HDBENCH/software/releases).

---
本ソフトウェアは無保証です。自己責任でご利用ください。 / Provided without warranty. Use at your own risk.
(C) 2001-2026 HDBENCH.NET
