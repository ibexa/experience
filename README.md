# Ibexa DXP Experience Symfony Flex metapackage

This is a metapackage for Symfony Flex-based Ibexa DXP Experience installation. 
It requires a subscription.

Learn more about [Ibexa DXP](https://www.ibexa.co/products).

## Installation

1. Create a new project from [ibexa/website-skeleton](https://github.com/ibexa/website-skeleton):
    ```
    composer create-project ibexa/website-skeleton ibexa_website
    ```
1. Require `ibexa-experience` package:
    ```
    composer config repositories.ibexa composer https://updates.ibexa.co
    composer require ibexa/experience
    ```

## COPYRIGHT
Copyright (C) 1999-2020 Ibexa AS (formerly eZ Systems AS). All rights reserved.

## LICENSE
This source code is available separately under the following licenses:

A - Ibexa Business Use License Agreement (Ibexa BUL),
version 2.3 or later versions (as license terms may be updated from time to time)
Ibexa BUL is granted by having a valid Ibexa DXP (formerly eZ Platform Enterprise) subscription,
as described at: https://www.ibexa.co/product
For the full Ibexa BUL license text, please see:
- LICENSE-bul file placed in the root of this source code, or
- https://www.ibexa.co/software-information/licenses-and-agreements (latest version applies)

AND

B - Ibexa Trial and Test License Agreement (Ibexa TTL),
version 2.2 or later versions (as license terms may be updated from time to time)
Trial can be granted by Ibexa, reach out to Ibexa AS for evaluation access: https://www.ibexa.co/about-ibexa/contact-us
For the full Ibexa TTL license text, please see:
- LICENSE file placed in the root of this source code, or
- https://www.ibexa.co/software-information/licenses-and-agreements (latest version applies)
