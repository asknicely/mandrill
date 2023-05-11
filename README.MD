# AskNicely Mandrill API

This is a direct clone of the last known version of the `mandrill/mandrill` package before it was abandoned. See https://bitbucket.org/mailchimp/mandrill-api-php/src/master/

We were pulling `mandrill/mandrill` in via our composer, so the first commit to this repo is exactly what we have been using.

Subsequent commits are minor tweaks to get around PHP 8 issues found in the library.

In future, we should be replacing this library with `mailchimp/transactional`. https://github.com/mailchimp/mailchimp-transactional-php