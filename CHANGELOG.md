# Changelog

## 1.9.0 (2022-01-28)

### Fixed

- Added pagination for favourites lists

### Added

- Buy Now button option for the product page
- Empty Cart button to clear multiple items at once
- One Click email login mode for homepage

### Added

- Option to show "Buy now" button on product page

## 1.8.4 (2021-12-15)

### Fixed

- Issue with invoice printing only first order on orders page in account

## 1.8.3 (2021-09-10)

### Updated

- Remove Promotional Pricing

## 1.8.2 (2021-08-27)

### Updated

- BC Theme Store Holiday Pricing
- Cache busting on Custom CSS

### Fixed

- Issue with custom fields not appearing if there is no product description

## 1.8.1 (2021-06-29)

### Fixed

- Z-index issue with compare checkbox on mobile devices
- Issues with quicksearch not passing settings correctly
- Search and add by SKU features now correctly hidden when lock down option is set to hide catalog for guests
- Missing mega menu styling

## 1.8.0 (2021-06-21)

### Changed

- New variation defaults
- Cookie Consent Manager now collapses to a link in the footer when accepted
- Wishlist buttons on cards are now separate from add to cart settings in control panel
- New header design
- Option to change header width to match global container width, relaxed or full width
- New quicksearch design
- Cleaned up mobile navigation

## Fixed

- Issue with wishlist not showing prices when restrict_to_login was set

## Added

- Three brand new navigation styles - Simple, Simple Enclosed and Mega Menu
- New navigation panel in theme editor
- Option to activate navigation dropdowns with hover instead of click
- SSL global region in footer
- Global container width control in theme editor > Theme Features panel

## 1.7.3 (2021-03-15)

### Updated
- Credit card vaulting update to align with platform changes
- Theme Store housekeeping
- Bumped Lodash

### Added
- Custom CSS support

## 1.7.2 (2021-01-25)

### Fixed
- Issue with add to cart button not showing on option change when initial selection is out of stock

## 1.7.1 (2020-11-02)

### Fixed

- Forgot password page access now allowed when storefront is locked down to only registered users
- Show More Facets popup now shows extra options

## 1.7.0 (2020-10-26)

### Changed

- Rebuilt logic on the category template to show side navigation components separately
- Tweaked shadow appearance on elements
- Adjusted width of shipping estimator fields in the cart
- Quick view modal closes when adding a product to the cart

### Fixed

- Availability field logic on product cards
- Stock levels show when changing options on product pages

### Added

- Global Page Builder regions
- Fields for custom Google fonts in theme editor

## 1.6.1 (2020-09-08)

### Updated
- Route "add to list" action to create a list page if no lists exist

### Fixed
- Hide Featured Categories in navigation control now hides them in the footer too

## 1.6.0 (2020-08-13)

### Added
- Use srcset for images with different loading options
- Added option for SVG logo

### Updated
- Updated lodash dependancy for improved security

### Fixed
- Header navigation with issue
- Add to wishlist menu on product listings since backend change

### Fixed
- Sanitize texts to stop HTML entities displaying
- Mobile Issue of last images in thumbnail slider unreachable if over 9 thumbnails
- Correct urls for account messages and order history on homepage
- Allow category header image to go full width
- Product card styles to use correct image size from theme settings

## 1.5.0 (2020-04-22)

### Added
- Control to stop newly created "ungrouped" accounts being able to see the catalogue and pricing

### Fixed
- Homepage hero content not showing when set to lockdown mode 2
- Display issue on account created screen
- Display issue with SVG icons focus state in header

## 1.4.0 (2020-04-16)

### Added
- Page Builder regions to homepage, content, category, product and article pages
- Page Builder regions to header and footer

### Fixed
- Issue with min-height being applied by sticky cart when page is short
- Cart bug where quantities would be changed after hitting enter key
- Wishlist bug where new wishlists could be created without a name and deleted without confirmation
- Positioning issue with new PayPal buttons
- Issue where an address could not be deleted in address list

## 1.3.0 (2019-08-06)

### Added
- Additional schema data for Google
- Controls for homepage login box colors in the theme editor

### Changed
- Handlebars scope for Options on returns page
- Switched off dynamic typing in the multi-add CSV import script
- Optimized SVG icons
- Align subcategories as a grid with padding
- Layout of compare page to accommodate more than 4 products
- Hide the description container on the product page if empty

### Fixed
- SKU fields now available on the product page even when master product has no SKU
- AMP iframe now loading correctly
- Stop add/remove buttons jumping around in Chrome and Safari on the multi-add page
- Add to cart script bug when quantity boxes are switched off
- Add to cart styling when quantity boxes are switched off
- Wishlist display switcher on account page
- Wishlist grid on account page
- Issue with hero slide 1 height on large screens
- Display issues in account/recent order details when order shipped to multiple locations

## 1.2.2 (2019-05-22)

### Changed
- Multi add form no longer removes form rows on success

### Fixed
- Bug with server responses when using quick add by SKU

## 1.2.1 (2019-04-23)

### Fixed
- Stock level only shows in search result when theme setting is enabled

## 1.2.0 (2019-04-17)

### Added
- Additional payment icons for the majority of Adyen services
- New save to list functionality, available in the B2B features panel in theme editor

### Fixed
- Sale tag now shows on the product page for sale items
- Issue with recent platform change to the faceted search system

### Removed
- Unnecessary font options in the optimized checkout settings in theme editor

## 1.1.0 (2019-04-09)

### Added
- New CSV upload feature on the add multiple SKUs page. Upload a 2 column CSV with a "sku" and "qty" heading to mass submit a cart
- Option to show product SKUs in the cart and mini cart
- Option to show the quantity already in cart on product cards and lists
- Google Pay, Alipay, WeChat Pay and UnionPay payment icons

### Changed
- Replaced Payment Font with SVG payment icons
- Optimized the mobile homepage

### Fixed
- Adjusted margins on the coupon and gift certificate boxes in the cart
- Restored borders to the header form inputs so they display correctly when the background is set to white
- Short description now appears on mobile product pages
- Adjusted some spacing issues with the product page image carousel
- View Full Description now links correctly in quick view modal

## 1.0.1 (2019-03-29)

### Added
- Option in theme editor to hide "ex. tax" label when only ex. tax prices are visible

### Changed
- Made the image panel on the product page sticky when products have a long options set

### Fixed
- Cleaned up the checkout page message when a minimum order value is set

## 1.0.0 (2019-03-19)
- Initial commit for the theme store
