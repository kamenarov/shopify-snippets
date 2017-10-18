# Shopify Snippet - Menu with dropdown

This snippet allows to create dropdown menus in two ways at the same time:
1. Navigation created by handles. / `Shop > Dresses` -> `shop-dresses`
2. Shopify nested navigation. / `linklist.links.first.links `

### Usage

```liquid
{% include 'menu', handle: 'main-menu' %}
```

### Arguments

**handle**

The handle of the linklist menu.

**class**

Add class to first level `ul` menu.

```
default: none
```
