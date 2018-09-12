+++
# Projects widget.
widget = "projects"
active = true
date = 2016-04-20T00:00:00

title = "研究内容"
subtitle = "宇佐美研で取り組んでいる主な研究テーマを紹介します。"

# Order that this section will appear in.
weight = 20

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# To show all items, set `tag` to "*".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"

[[filter]]
  name = "低消費電力"
  tag = "low-energy"

[[filter]]
  name = "処理速度向上"
  tag = "speed-up"

[[filter]]
  name = "実チップ設計"
  tag = "design"

[[filter]]
  name = "FPGA"
  tag = "FPGA"

[[filter]]
  name = "共同研究"
  tag = "coop"
+++

