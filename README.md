Composite panel loader
======================

See CompositePanelLoader:

1. Creates CompositePanel component that is ancestor of CssLayout
2. Creates inner TabSheet
3. Reads `page` elements inside of `demo:compositePanel` tag and its `caption` attribute and creates appropriate tabs
4. Populates each tab with GroupBoxLayout