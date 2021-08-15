---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "zabbix_graph Resource - terraform-provider-zabbix"
subcategory: ""
description: |-
  
---

# zabbix_graph (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **height** (String) Height
- **item** (Block List, Min: 1) (see [below for nested schema](#nestedblock--item))
- **name** (String) Graph Name
- **width** (String) Width

### Optional

- **do3d** (Boolean) Show 3d graph
- **id** (String) The ID of this resource.
- **legend** (Boolean) Show legend
- **percent_left** (String) Left percentile
- **percent_right** (String) Right percentile
- **type** (String) Type, one of: pie, exploded, normal, stacked
- **work_period** (Boolean) Show work period
- **ymax** (String) Y Axis Max
- **ymax_itemid** (String) Y Axis Max ItemId
- **ymax_type** (String) Y Axis Max Type, one of: fixed, item, calculated
- **ymin** (String) Y Axis Min
- **ymin_itemid** (String) Y Axis Min ItemId
- **ymin_type** (String) Y Axis Min Type, one of: fixed, item, calculated

<a id="nestedblock--item"></a>
### Nested Schema for `item`

Required:

- **color** (String) color
- **itemid** (String) itemid

Optional:

- **drawtype** (String) Draw Type, one of: filled, bold, dot, dashed, gradient, line
- **function** (String) Function, one of: min, average, max, all, last
- **sortorder** (String) sort order
- **type** (String) Type, one of: simple, sum
- **yaxis_side** (String) Y Axis Side, one of: left, right

Read-Only:

- **id** (String) The ID of this resource.

