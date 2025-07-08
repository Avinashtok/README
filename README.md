## 🔄 Fast Sync Snapshot

To sync your 0G Storage Node from block `3507655` quickly:

```bash
cd ~/0g-storage-node/run/db/
rm -rf flow_db
wget -O flow_db.tar.gz https://github.com/Avinashtok/0g-fast-sync/releases/download/backup-3507655/flow_db-3507655.tar.gz
sha256sum flow_db.tar.gz
# Should match:
# 9c5f8da7221239ce421a6d2fc0531e56c5a41c9a82b2971281cb3cab959c2334
tar -xzvf flow_db.tar.gz
