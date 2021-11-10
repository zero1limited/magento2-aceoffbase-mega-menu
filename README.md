# Magento 2 - Ace Off Base Mega Menu

## Description

The Zero1 Ace Off Base Mega Menu module is a simple module which renders the main navigation as a mega menu style navigation on desktop. It goes hand in hand with the Zero1 Ace Off Base theme; using core Magento and keeping changes to a minimum, allowing us to make the most out of Magento whilst keeping the site as performant as possible.

## Features

- Renders desktop navigation as a mega menu
- Ability to add static blocks inside each navigational dropdown

## Static Blocks

The mega menu module injects cms blocks into each dropdown relating to the position of that element within the navigation. Each block must have the identifier prefixed with ```z1-mega-menu-```, followed by the position of that particular nav element. For example, ```z1-mega-menu-1``` will display in the first dropdown in the navigation; ```z1-mega-menu-2``` will display in the second dropdown in the navigation and so on.
 
## Installation

```
composer require zero1/aceoffbase-mega-menu
```

© Zero-1 Ltd | [www.zero1.co.uk](https://www.zero1.co.uk/)
