This repo demonstrates a bug with quotes? and sass in a particular webpack build chain.

To reproduce, clone this repo, then run:
`npm install`
`npm build:prod`

You will see an error message. removing the `content` line in on line 12 of styles.scss will prevent the error, but that should be valid scss.
