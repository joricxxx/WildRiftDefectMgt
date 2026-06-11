# WildRift v1.0 FirstPass Functional [Account Creation]: Unable to create an account

## [Summary]
    When clicking the "Request an account" button in the login page, it will direct to the homepage not the signup page

## [Precondition]
  * You have an internet connection
  * You must be a guest user
  * You must be in the login page

## [Steps to reproduce]
  1. Go to the website [https://tuon-six.vercel.app/]
  2. Click "Get Started"
  3. Click "Request an Account"

## [Actual results]
  - It directs to the homepage

## [Expected results]
  -  It will direct you to the signup page or something similar

## [Severity: How does this problem impact the customer/user?]
6. Major functionality issue — Account creation is blocked because the "Request an Account" button redirects users to the homepage instead of the signup/account request page. This prevents guest users from creating or requesting an account through the expected login flow.

## [Likelihood: How often will a customer/user use this feature/function?]
8. High — New users or guest users are likely to use the "Request an Account" button when they need access to the system.

## [Repeatability: Is this problem easily reproducible?]
10. 100% Reproducible — The issue occurs every time the user clicks "Request an Account" from the login page.

## [Impact Sizing (in days)]
Less than a day — This is likely a routing/link redirection issue and can be fixed by updating the button destination to the correct signup or account request page.