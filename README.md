# authzed README

The Schema of SpiceDB or a Permissions System in Authzed defines the types of objects found, how those objects relate to one another, and the permissions that can be computed off of those relations.

The Schema Language's extension for use on a file system is `.zed`

This extension models syntax highlighting based off [Authzed's own docs](https://authzed.com/docs/reference/schema-lang)

## Features

`schema.zed` can be broken down into the following components:

* comment, either line or block
* objectDefinition: ^(definition|caveat) (prefix|)@variable {$
* objectRelation: ^\s{1,4}relation @variable: @variable (or) @variable(#reference)
* objectPermission:

* declaration: ^\s{1,4}type + variable + operator(equal|assign) + variable + operator(or|arrow)

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release
