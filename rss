#!/usr/bin/env bash
set -euo pipefail

read -rp "Paste YouTube channel_id (: " CHANNEL_ID

RSS_URL="https://www.youtube.com/feeds/videos.xml?channel_id=${CHANNEL_ID}"
OUT="youtube-channel-${CHANNEL_ID}.rss.xml"

curl -fsSL "$RSS_URL" -o "$OUT"

echo "RSS saved to: $OUT"
echo "RSS URL: $RSS_URL"
echo "isn't that easy?"
