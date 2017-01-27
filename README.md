This repo demonstrates a bug with single quotes and sass in a particular webpack build chain.

To reproduce, clone this repo, then run:
`npm install`
`npm build:prod`

You will see an error message unrelated to the quotes, but changing the single quotes to double qoutes in `_test.scss` will fix the issue.
