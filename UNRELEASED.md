# Unreleased changes

### Breaking changes

### New components

Added new components [`VideoCard`](https://polaris.shopify.com/components/structure/video-card) and [`VideoThumbnail`](https://polaris.shopify.com/components/images-and-icons/video-thumbnail) ([#2725](https://github.com/Shopify/polaris-react/pull/2725))

### Enhancements

- Added high contrast outline to `Popover`, `Card` and `Indicator` ([#2792](https://github.com/Shopify/polaris-react/pull/2792))
- Removed `overflow: hidden` from `Card` ([#2806](https://github.com/Shopify/polaris-react/pull/2806))
- Truncated long sort options in `ResourceList` ([#2809](https://github.com/Shopify/polaris-react/pull/2809)
- Added high contrast outline to `ActionList` ([#2713](https://github.com/Shopify/polaris-react/pull/2713))
- Added high contrast border to `Button` ([#2712](https://github.com/Shopify/polaris-react/pull/2712))
- Added styled placeholder image to `Avatar` when initials are blank ([#2693](https://github.com/Shopify/polaris-react/pull/2693))
- Added new components `VideoCard` and `VideoThumbnail` ([#2725](https://github.com/Shopify/polaris-react/pull/2725))
- Added a `preferInputActivator` prop to `Popover` to allow better positioning of the overlay ([#2754](https://github.com/Shopify/polaris-react/pull/2754))

### Bug fixes

- Fixed incorrect used while importing from `polaris-tokens` ([#2778](https://github.com/Shopify/polaris-react/pull/2778))
- Fixed `DropZone` not supporting new file selection when `allowMultiple` is `false` ([#2737](https://github.com/Shopify/polaris-react/pull/2737))
- Fixed `Pagination` sizing on small screens with tooltips ([2747](https://github.com/Shopify/polaris-react/pull/2747))
- Fixed `Popover` setting a `tabindex` and other accessibility attributes on the activator wrapper when the `activator` is disabled ([#2473](https://github.com/Shopify/polaris-react/pull/2473))
- Added a `verticalAlignment` prop to `ResourceItem` to support control of content alignment ([#2743](https://github.com/Shopify/polaris-react/pull/2743)

### Documentation

### Development workflow

- Added `check:custom-property` job in travis ([#2778](https://github.com/Shopify/polaris-react/pull/2778))
- Exported missing OptionListProps ([#2777](https://github.com/Shopify/polaris-react/pull/2777))
- Omitted the Storybook `AppProvider` decorator for examples which already contain an `AppProvider` ([#2807](https://github.com/Shopify/polaris-react/pull/2807))

### Dependency upgrades

### Code quality

- Removed various type assertions and bumped test coverage ([#2638](https://github.com/Shopify/polaris-react/pull/2638))

### Deprecations
