---
title: "Shortcodes"
subtitle: "Easy life"
date: 2020-03-06
publishdate: 20-03-06
lastmod: 20-03-06
---

{{% structure/row %}}
## Bootstrap-related structure shortcodes

You can use the `structure/row` shortcode to structure your page based on Bootstrap rows. Something like this:
```
{{%/* structure/row */%}}
## Bootstrap-related structure shortcodes

You can use the `structure/row` shortcode to structure your page based on Bootstrap rows.

{{%/* /structure/row */%}}
```

{{% structure/row %}}

## Support for Bootstrap columns

By using `structure/column_start`, `structure/column_next` and `structure/column_end` you can start rows with columns and split text according to Bootstrap columns.

{{% structure/column_start "" %}}
Column 1
{{% structure/column_next "" %}}
Column 2
{{% structure/column_next "" %}}
Column 3
{{% structure/column_end "" %}}
