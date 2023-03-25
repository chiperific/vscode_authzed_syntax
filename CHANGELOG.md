# Change Log

All notable changes to the "authzed" extension will be documented in this file.

## [1.0.0]
- Finish mapping grammar names to tokens
- Deviate from [Authzed's displayed color patterns](https://authzed.com/docs/reference/schema-lang) in favor of more standard VS Code language grammars
- CHOICE: Operators (=,==,&,&&,+,-,:,|,->) should use names based on `keyword.operator`, but this seems to be either white/black (depending on dark vs. light color theme). Given the embedded nature of these symbols, I wanted high-contrast and high visibility in editors, so they're set to `string.regexp` and `markup.bold`

## [0.1.0]
- In development
