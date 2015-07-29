# Cookie Consent
Lightweight javascript plugin to comply with the EU cookie law.

This plugin is designed to show a bar that informs the user of the use of cookies, and a button with which he can accept it. It is designed to be lightweight, and do nothing more than needed, basically because existing plugins can do much more that I did not need.

## Usage
Include cookie-consent.js in your website, and call below code to initialise the plugin.

´´´js
$(document).ready(function () {
	$(window).cookieConsent();
}
´´´

For performance reasons, do not forget to minify the JS and CSS files when using on production sites.

## Credits
Originally based on EU Cookie Law Banner 2.4 by Robert Kent, James Bavington & Tom Foyster, but adapted by become a jQuery plugin.

I have published this here to share my effort. Commits that can improve efficiency and layout, or reduce code are very welcome!