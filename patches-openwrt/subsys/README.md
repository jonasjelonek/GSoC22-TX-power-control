## Patch overview
---

| Patch number	| Purpose |
|---------------|---------|
| 910			| Changes from kernel 5.19 (commit 44fa75f207d8a106bc75e6230db61e961fdbf8a8), introduce new structure for dynamic tx status report for rates and tx-power |
| 911			| Changes from kernel 5.19 (commit 569cf386ec5f4619388ae0c62169175dc2804f32), support previously added structure in minstrel_ht |
| 912			| Modify the tx-power level annotation introduced by patch 910 to define ranges instead of a whole list |
| 913			| Annotate tx-power per packet in ieee80211_tx_info, per mrr in ieee80211_sta_rates; modify ieee80211_rate_status |
| 914			| Add hw flags for drivers to propagate TPC support |
| 915			| Add an utility function in mac80211 to convert ieee80211_tx_rate to rate_info (needed for use in ath9k, ...) |
