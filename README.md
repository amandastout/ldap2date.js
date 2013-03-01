[![Build Status](https://travis-ci.org/rsolomo/ldap2date.js.png?branch=master)](https://travis-ci.org/rsolomo/ldap2date.js)

# ldap2date.js

Do you have a string in [RFC 4517](http://www.ietf.org/rfc/rfc4517.txt) Generalized Time syntax, when you really just want a Date?

Or perhaps you need some Generalized Time, but have a Date instead.

If so, the methods below may help you. Currently, only 'Z', style strings are supported.

## Usage

### ldap2date.parse(time)

Returns a new Date() object
- `time` - String - A LDAP Generalized-Time string

---
### ldap2date.toGeneralizedTime(date)

Returns a string in GeneralizedTime syntax
- `date` - Date - A date object
