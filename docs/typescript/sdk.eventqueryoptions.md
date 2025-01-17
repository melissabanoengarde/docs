---
slug: /sdk.eventqueryoptions
title: EventQueryOptions interface
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# EventQueryOptions interface

Filters for querying past events

**Signature:**

```typescript
export interface EventQueryOptions<TFilter extends Record<string, any> = Record<string, any>>
```

## Properties

| Property                                           | Modifiers | Type                 | Description       |
| -------------------------------------------------- | --------- | -------------------- | ----------------- |
| [filters?](./sdk.eventqueryoptions.filters.md)     |           | TFilter              | <i>(Optional)</i> |
| [fromBlock?](./sdk.eventqueryoptions.fromblock.md) |           | string &#124; number | <i>(Optional)</i> |
| [order?](./sdk.eventqueryoptions.order.md)         |           | "asc" &#124; "desc"  | <i>(Optional)</i> |
| [toBlock?](./sdk.eventqueryoptions.toblock.md)     |           | string &#124; number | <i>(Optional)</i> |
