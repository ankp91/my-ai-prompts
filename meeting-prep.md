---
layout: default
title: Meeting Prep
nav_order: 1
---

# Meeting Preparation Prompt
Use this to summarize your notes before a call.

<div style="padding: 20px; border: 1px solid #005eb8; border-radius: 8px; background-color: #f0f4f8; margin: 20px 0;">
  <p id="p1" style="font-family: monospace; margin-bottom: 15px;">
    "Summarize the last 3 emails from [Name] and list the top 3 action items for our 1:1 meeting."
  </p>
  <button onclick="copyToClipboard('p1')" style="background: #005eb8; color: white; border: none; padding: 8px 15px; border-radius: 4px; cursor: pointer;">
    Copy Prompt
  </button>
</div>

<script>
function copyToClipboard(id) {
  const text = document.getElementById(id).innerText;
  navigator.clipboard.writeText(text);
  alert("Prompt copied!");
}
</script>
