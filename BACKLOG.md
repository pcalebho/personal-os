# 📥 backlog inbox

| status | activity | task | due |
| :--- | :--- | :--- | :--- |
$(cat BACKLOG.md | sed 's/^[ \t]*//;s/[ \t]*$//' | while IFS='|' read -r status name due; do
  # clean up the fields
  STATUS=$(echo "$status" | xargs | tr '[:upper:]' '[:lower:]')
  NAME=$(echo "$name" | xargs)
  DUE=$(echo "$due" | xargs)
  
  # simplify due date display
  if [[ "$DUE" == "No Date" ]]; then DUE="-"; fi
  
  # map activity type based on typical keywords if possible, else keep generic
  ACTIVITY="general"
  if [[ "$NAME" =~ "Sale"|"customer"|"order" ]]; then ACTIVITY="sales"; fi
  if [[ "$NAME" =~ "Marketing"|"Case Study"|"Testimonial" ]]; then ACTIVITY="marketing"; fi
  if [[ "$NAME" =~ "Recruiting"|"Hire"|"SWE" ]]; then ACTIVITY="recruiting"; fi
  if [[ "$NAME" =~ "Product"|"Engineering"|"Refactor"|"Data" ]]; then ACTIVITY="product"; fi
  
  echo "| $STATUS | $ACTIVITY | $NAME | $DUE |"
done)

---
*last synced from notion: $(date -u +"%Y-%m-%d %H:%M UTC")*
