# 4.4.0 — 20 April 2022
 - Added the ability to customize the Crawler's User-Agent
 - Fixed the Bad Words filter not applying to Links created by Guests
 - Other minor improvements

# 4.3.0 — 14 April 2022
 - Added new filters on all table lists (column order, order direction, per page limits)
 - Added Proxy support for the external requests when creating a Link
 - Added the ability to set the Plan's position on the Pricing listings
 - Added the ability to set custom CSS code based on the color scheme
 - Improved the codebase (code refactoring)
 - Improved the CSV export functionality (it now includes the URL where the report was generated from)
 - Improved the table lists filters (improved flexibility)
 - Improved the API Documentation
 - Improved the translation strings
 - Improved the SEO capabilities side-wide by adding in-file head tags for all public pages
 - Improved the iconography
 - Updated all the dependencies to their latest versions
 - Fixed not being able to edit a User that was under a recurring subscription
 - Fixed links not being disabled when the User is suspended
 - Fixed the API Documentation URL path not pointing to the correct location
 - Fixed being able to exceed the count limit of Pixels
 - Fixed Subscriptions not ending when being cancelled on Stripe and PayPal
 - Other minor improvements

# 4.2.0 — 11 December 2021
 - Added contextual menus on all table lists
 - Updated all the dependencies to their latest versions
 - Fixed an issue with specific currencies that would prevent the Checkout from working
 - Fixed several listing issues on RTL mode
 - Fixed several missing language strings
 - Other minor improvements

# 4.1.0 — 18 October 2021
 - Added the ability to remove the primary domain from the available domains
 - Added the ability to filter Links that are not under a specific Space
 - Improved the Links filter when filtering by Domains
 - Improved the Developers documentation
 - Other minor improvements

# 4.0.0 — 17 October 2021
 - Improved the Pixel tracking success rate by adding a slight delay to the redirect
 - Improved SEO (interstitial redirect pages are not indexed by search engines anymore)
 - Fixed the List Links API endpoint not working
 - Other minor improvements

# 3.9.0 — 27 September 2021
 - Added translation ability for the Page title and description
 - Fixed an issue preventing redeeming coupons
 - Fixed an issue preventing changing the user's plan when no ending date was defined
 - Other minor improvements

# 3.8.0 — 15 September 2021
 - Added support for Google Safe Browsing when shortening links
 - Added email notification on successful Stripe, PayPal and Coinbase payments
 - Improved the UI & UX of the Log-in, Register, Password reset, Contact and Page pages
 - Fixed an issue that would display all tax rates on Checkout before the user would select his country
 - Fixed the advanced features not being validated when shortening links through the multiple link shortener
 - Fixed an issue that would prevent creating links with the Language targeting feature
 - Fixed the deep link user feature availability being ignored when editing a link
 - Other minor improvements

# 3.7.0 — 11 September 2021
 - Fixed an issue that was preventing creating new Links under specific Spaces or Pixels
 - Fixed an issue that was preventing users from creating new Pixels
 - Fixed an issue that was preventing accessing the API Documentation
 - Other minor improvements

# 3.6.0 — 10 September 2021
 - Fixed an issue that was preventing users from creating new Spaces
 - Fixed an issue that was preventing users from editing Links
 - Fixed the Developers link missing from the footer
 - Other minor improvements

# 3.5.0 — 9 September 2021
 - Added new payment gateway: PayPal (checkout using a PayPal account)
 - Added new payment gateway: Coinbase (checkout using a cryptocurrency)
 - Added new payment gateway: Bank (checkout using a bank transfer)
 - Added a new search filter (Pixels) for Links
 - Improved the codebase (name convention refactoring)
 - Improved the Invoices (they are now immutable)
 - Improved the redirect process on Custom Domains index page
 - Improved the bad words filter (the match is now case-insensitive)
 - Improved ARIA controls
 - Improved the Installation process
 - Fixed the country redirect not working after the last release
 - Fixed not being able to create links when Pixels are disabled
 - Fixed an issue with passwords being trimmed when changed
 - Fixed the Stats Privacy dropdown options having the opposite effect
 - Fixed the Rotation Targeting option not working when creating a new link
 - Fixed deleting a Global Domain that was set as default, not resetting the default global domain value
 - Fixed not being able to use a Custom Global Domain when the User did not had access to Custom Domains
 - Fixed several missing language strings
 - Other minor improvements

# 3.4.0 — 24 March 2021
 - Added new share option (Tumblr)
 - Added the ability to set a Global Domain as the default domain to shorten links
 - Improved the database structure (IDs are now unsigned)
 - Fixed the CTA cards on Dashboard not having the correct links
 - Fixed the Stats API endpoint returning a success response even on missing resources
 - Fixed several missing language strings
 - Other minor improvement

# 3.3.0 — 26 February 2021
 - Fixed the Stats Privacy not working as expected when on Public or Private
 - Other minor improvements

# 3.2.0 — 24 February 2021
 - Added support for the advanced features to the multiple link creator
 - Added Cronjob for automatic cache deletion
 - Fixed referrer not working as expected
 - Fixed the referrer not being passed along on redirects with Pixel consent enabled
 - Other minor improvements

# 3.1.0 — 20 February 2021
 - Added Retargeting Pixels support
 - Added Language targeting
 - Added Date Range selection for the Stats
 - Added Cities Stats
 - Added data export in CSV format both for Links and Stats (plan feature)
 - Added password option for the Stats pages
 - Added the ability to toggle password visibility for Links
 - Added automatic language switching when the language is available
 - Added total per page stats for each stats category
 - Added total per table stats for each stats category
 - Added domain icons to the Domains listing
 - Added sizing utility classes to the entire iconography
 - Added PostCSS support
 - Improved the CSS filesize (removed all unused CSS rules)
 - Improved the User Dashboard (reworked the design)
 - Improved the Home page (reworked the design)
 - Improved the SEO for the Home page
 - Improved the checkout process (you can now cancel the coupon adding process)
 - Improved the API (added status code for the Links, Spaces and Domains listings)
 - Improved the password encryption method for Links
 - Updated the iconography
 - Updated all the dependencies to their latest versions
 - Fixed an issue when link titles would exceed 255 characters
 - Fixed the domain field not being validated on update
 - Other minor improvements

# 3.0.0 — 10 November 2020
 - Added new browser icons
 - Added link password status to the Links API endpoint
 - Fixed an issue where you could shorten more links than allowed
 - Other minor improvements

# 2.9.0 — 23 October 2020
 - Fixed an issue when saving a link with a Target option unavailable to the user
 - Fixed the tracking code section not being available on certain pages

# 2.8.0 — 11 October 2020
 - Improved the Checkout & Registration process (the selected plan is now remembered)
 - Improved the UI & UX in various places
 - Updated all the dependencies to their latest versions
 - Fixed the Advanced button on shortener form not being styled on mobile devices
 - Other minor improvements

# 2.7.0 — 2 October 2020
 - Fixed share buttons only working for the first result in a set
 - Fixed Edit button appearing on Stats pages for non-owners
 - Fixed the language selector not working on Custom Domains
 - Other minor improvements

# 2.6.0 — 27 September 2020
 - Added new Registration and Login page backgrounds
 - Other minor improvements

# 2.5.0 — 15 September 2020
 - Added HTTPS protocol support for Custom Domains
 - Added full support for custom aliases for any keyword on Custom Domains
 - Fixed stats not being recorded for password protected Links
 - Other minor improvements

# 2.4.0 — 5 September 2020
 - Added email account confirmation requirement when updating the email
 - Other minor improvements

# 2.3.0 — 31 August 2020
 - Added Preview support for Password protected Links
 - Fixed custom index page having priority over Domain custom index pages
 - Other minor improvements

# 2.2.0 — 25 August 2020
 - Reduced the CSS size
 - Other minor improvements

# 2.1.0 — 22 August 2020
 - Added DNS proxy support for local host when validating Custom Domains
 - Fixed link preview not working when removing all Targeting values
 - Fixed the Links counter not showing the proper value for Global Domains
 - Other minor improvements

# 2.0.0 — 18 August 2020
 - Added new browser icons
 - Added new platform icons
 - Fixed invoices not having localized date format
 - Other minor improvement

# 1.9.0 — 11 August 2020
 - Other minor improvements

# 1.8.0 — 9 August 2020
 - Updated all the dependencies to their latest versions
 - Updated the favicons source
 - Fixed an issue when trying to save empty Space names
 - Other minor improvements

# 1.7.0 — 29 July 2020
 - Updated all the dependencies to their latest versions

# 1.6.0 — 22 July 2020
 - Added throttle to the Password Reset functionality
 - Fixed an issue which caused the installer not to work
 - Other minor improvements

# 1.5.0 — 10 July 2020
 - Added autofocus on the shorten URL input on the Home page
 - Improved the header section on the Home page

# 1.4.0 — 1 July 2020
 - Added a new API endpoint: Account
 - Added visual cues on link listings for disabled and expired links
 - Added a Disabled Status filter for Links search
 - Added support for aliases to use system reserved keywords for custom domains
 - Fixed the Active filter not excluding certain inactive link types
 - Fixed the Expired filter not showing certain expired links
 - Fixed an issue when emulating a Subscription (invalid variable)
 - Fixed an issue when creating or updating Plans (invalid field name)
 - Fixed date & time field validation not requiring each other
 - Other minor improvements

# 1.3.0 — 21 June 2020
 - Added support for Stripe Tax Rates
 - Added support for Stripe Coupons
 - Added API endpoint for Domains
 - Added API endpoint for Spaces
 - Added search & filtering capabilities to the listing API endpoints
 - Added validation errors in the API output
 - Added date and time localization support for Invoices
 - Improved URL parsing (requests now include a UA)
 - Improved the checkout process
 - Improved the way the total clicks count is being calculated
 - Improved the way emails are sent through the contact form
 - Improved the Installation process (database engine type is now dictated)
 - Improved the API Documentation
 - Fixed Link Preview page having wrong page title
 - Fixed an issue when adding a new Custom Domain without the URL protocol
 - Other minor improvements and fixes

# 1.2.0 — 22 May 2020
 - Added clicks Evolution category in the Stats page (with performance index)
 - Added custom deep link protocol support
 - Added link explanation in Link Preview
 - Added link preview in link dropdown menu
 - Added total clicks count for guest links
 - Added RTL support to email templates
 - Added support for special characters in aliases and urls
 - Added translation support for country names
 - Added date and time localization support for Link expiration date and Link statistics
 - Added the ability to set the default Domain, Space & Stats privacy when creating new links
 - Improved the domain name validation when adding a new custom domain
 - Improved the DNS validation process when adding a custom domain
 - Improved the QR code generator (added UTF-8 support)
 - Improved RTL support (fixed various inputs that were not supposed to be RTL)
 - Fixed several missing language strings
 - Fixed guest users being able to shorten urls with deep link protocols
 - Fixed being able to preview links that were password protected
 - Fixed timezone value not being set on user creation
 - Fixed search filter Sort having inverted values for New and Old options
 - Fixed user’s language selection not being remembered after account registration
 - Other minor fixes & improvements

# 1.1.0 — 7 May 2020
 - Added Deep mobile/app linking (plan option)
 - Added Link rotation (A/B testing) (plan option)
 - Added Link Parameter Forwarding
 - Added Link expiration after X clicks
 - Additional Global Domains (plan option)
 - Improved the Installation wizard (complete rework)
 - Updated all the dependencies to their latest versions
 - Other minor fixes and improvements

# 1.0.0 — 29 April 2020
 - Initial release
