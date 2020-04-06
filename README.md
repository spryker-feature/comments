# Spryker Feature: Comments

With Comments, you can add multiple comments to any entity. The feature has been released as a global widget and can be integrated to any page or entity of your online store. By default, the Comments widget is integrated to the Cart page. This allows you to add multiple comments with tags, so these comments will be linked to order and appear not only in Zed Order Details page but in Yves Order Details page as well. Even better - conversation about the order can continue after the order had been placed, without losing any useful information.

## Installation

```
composer require spryker-feature/comments
```

## Recommended feature dependencies
- [spryker-feature/customer-account-management](https://github.com/spryker-feature/customer-account-management)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [CommentSalesConnector ^1.0.0](https://github.com/spryker/comment-sales-connector) (Connector)
- [Shop.CommentWidgetExtension ^1.0.0](https://github.com/spryker-shop/comment-widget-extension) (Extension)
