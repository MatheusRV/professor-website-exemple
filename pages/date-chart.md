---
layout: default
---

[Date_Chart](https://github.com/GSI/jekyll_date_chart) is a [Jekyll](https://jekyllrb.com/) plugin
that can transform [Markdown](https://en.wikipedia.org/wiki/Markdown) into dynamic tables. 

Read the [documentation](https://github.com/GSI/jekyll_date_chart) to get started.

## Usage:
Inset '{% dchart %}' at begin, then your markdown table and in end '{% enddchart %}' of your Markdown file.

## Examples:
{% dchart %}
| title of first table  | Unit of given values | comments on the table as a whole |
| 09.09.2013            |                =1000 | comment on this specific element |
| 10.10.2013            |               =+1000 | comment on this specific element |
| 11.11.2013            |                +1000 | comment on this specific element |

| title of second table | Unit of given values | comments on the table as a whole |
| 09.09.2013            |               =-2000 | comment on this specific element |
| 10.10.2013            |                =2000 | comment on this specific element |
| 12.12.2013            |                -2000 | comment on this specific element |
{% enddchart %}