# Manual

## Getting Started

Administrators can configure the module in `Administration -> Modules -> 2fa -> Configure`:

#### Enabled drivers
Users of the selected groups are enforced to E-mail driver by default.
- [x] E-mail
- [x] Google Authenticator
  - Note: to start using of this driver please run `composer install` from root folder of this module, otherwise this driver is disabled.

#### Enforced groups to use 2FA
- [x] Administrator
- [ ] Users

(_Default driver is "E-mail" for users from the selected enforced groups_)

#### Length of verifying code
- 6 by default

(_Currently is used only for driver "E-mail". The driver "Google Authenticator" cannot be configured because codes are generated by external app._)

## Account settings

User can select what driver to use for 2FA in `Account settings -> Settings -> Two-Factor Authentication`