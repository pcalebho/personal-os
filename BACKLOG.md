# 📥 personalos unified backlog

| status | activity | task | due |
| :--- | :--- | :--- | :--- |
$(cat /tmp/notion_full_dump.txt | while IFS='|' read -r status activity name due; do
  # normalize for markdown table
  CLEAN_STATUS=$(echo "$status" | tr '[:upper:]' '[:lower:]')
  CLEAN_NAME=$(echo "$name" | sed 's/|/\\|/g')
  echo "| $CLEAN_STATUS | $activity | $CLEAN_NAME | $due |"
done)

---
*last full sync (backlog + active): $(date -u +"%Y-%m-%d %H:%M UTC")*
