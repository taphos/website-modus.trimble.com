---
title: "Tooltips"
layout: "single"
description: "Tooltips provide a short description of a page element or control."
components: true
componentsWeb: true
images:
  - "/img/components/headers/tooltips.png"
bootstrapURL: "/components/tooltips/"
reactBootstrapURL: "/components/tooltips/"
webComponentsURL: "https://modus-web-components.trimble.com/?path=/story/components-tooltip--default"
tags: [styles]
---

## Specifications

- Icon tooltips and interactive tooltips may be positioned top, bottom, left, or right to the trigger item.
- The container of the tooltip text may be aligned to start, center or end.
- Do not make the tooltip larger than the element it appears from.

<img src="/img/components/tooltips-positions.svg" alt="Tooltip positions"/>
<style>
[data-theme="dark"] img[src="/img/components/tooltips-positions.svg"] {
 content: url(/img/components/tooltips-positions-dark.svg);
}
</style>

### Behaviors

- Icon tooltips appear on hover and focus.

### Editorial

- Keep it brief—aim for fewer than 10 words.
- End full sentences with a period. Using “&” is OK. No “!”.
- For brevity, don’t spell out numbers: Use 12, not twelve.
- Use tooltips to present small amounts of data. Tooltips are similar to toasts, or micro-conclusions, which give the user a short confirmation.
- Use the past tense rather than present perfect (was submitted vs. has been submitted). We avoid the past perfect tense because it lacks clarity for translators.
- Use sentence case for tooltips.
- Never add a link to text in a tooltip.

<script>
$(function () {
  $('[data-toggle="tooltip"]').tooltip();
});
</script>
