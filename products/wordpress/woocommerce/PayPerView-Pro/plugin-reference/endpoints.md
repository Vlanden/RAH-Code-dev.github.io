# Plugin Reference

## `checkLastUsersOrder()`

The function checks if the last completed order for a logged-in user in WooCommerce was made within the last year.

**Returns:** A boolean value. It returns true if the user has placed a completed order within the last year, and false otherwise.

## `shortcodeLastUsersOrder($atts, $content = null)`

The function checks the state of the last user's order and returns the provided content if the state matches the attribute value, otherwise it returns an empty string.

**Parameters:**
- `atts`: An array of attributes passed to the shortcode function, specifying the desired state of the last user's order.
- `content`: The content that will be displayed if the condition is met.

**Returns:** The value of the `$content` variable if the `['state']` is equal to the order state. Otherwise, it returns an empty string.
