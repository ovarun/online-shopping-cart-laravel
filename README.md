# online-shopping-cart-laravel
Welcome to the ultimate online shop cart package tailored for Laravel enthusiasts! This package is compatible with Laravel versions 7 through 11, ensuring seamless integration with your modern Laravel applications.

Inspired by the ingenious [mindscms/laravelshoppingcart](https://github.com/mindscms/laravelshoppingcart) package, we've borrowed some of their brilliant logics and extended them to create a more robust and feature-rich shopping cart experience.

Get ready to elevate your e-commerce projects with our meticulously crafted package, designed to provide unparalleled functionality and ease of use. Dive in and explore the endless possibilities for creating the perfect online shopping experience!

## Installation

Install the package through [Composer](http://getcomposer.org/).

Run the Composer require command from the Terminal:

    composer require ovarun/online-shopping-cart-laravel

### Laravel <= 7.0

Should you still be on version 7.0 of Laravel, the final steps for you are to add the service provider of the package and alias the package. To do this open your `config/app.php` file.

Add a new line to the `providers` array:

	Arunov\Shoppingcart\ShoppingcartServiceProvider::class

And optionally add a new line to the `aliases` array:

	'Cart' => Arunov\Shoppingcart\Facades\Cart::class,

Now you're ready to start using the shopping cart in your application.

**As of version 1 of this package it's possibly to use dependency injection to inject an instance of the Cart class into your controller or other class**

## Overview
Look at one of the following topics to learn more about project
