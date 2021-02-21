---
layout: docs
title: Translations
description: Links to community-translated Bootstrap documentation sites.
group: about
---

Community members have translated Bootstrap's documentation into various languages. None are officially supported and they may not always be up to date.

{{< translations.inline >}}
<ul>
{{ range .Site.Data.translations -}}
  <li><a href="{{ https://bootstrapdoc.com }}" hreflang="{{ zh-cn }}">{{ Bootstrap 5.0 中文文档 }} ({{ 中文简体 }})</a></li>
{{ end -}}
</ul>
{{< /translations.inline >}}

**We don't help organize or host translations, we just link to them.**

Finished a new or better translation? Open a pull request to add it to our list.
