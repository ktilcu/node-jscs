Version 1.0.12:
 * Fixes for jsdoc params.

Version 1.0.11:
 * Prefix unary rules: `disallowSpaceAfterPrefixUnaryOperators`, `requireSpaceAfterPrefixUnaryOperators`.
 * Postfix unary rules: `disallowSpaceBeforePostfixUnaryOperators`, `requireSpaceBeforePostfixUnaryOperators`.

Version 1.0.10:
 * Reporter support — `console`, `text`, `checkstyle`.

Version 1.0.9:
 * Browser-compatible version.
 * Fix for `disallowMultipleLineBreaks` option to report only once per each sequence of line breaks.
 * Fix for `disallowMultipleLineBreaks` option to work properly when CRLF line break is used.

Version 1.0.8:
 * Fixes for `safeContextKeyword`.

Version 1.0.7:
 * Disallow spaces inside parentheses (@ignovak).

Version 1.0.6:
 * Convert tabs into spaces (@markelog).
 * Report illegal space between nested closing curly braces (@twoRoger).
 * Use absolute path to config when specified (@vtambourine).
 * safeContextKeyword option to check "var that = this" expressions (@doochik).

Version 1.0.4-1.0.5:
 * Fixed mistype `disallowMulipleVarDecl` -> `disallowMultipleVarDecl`.
 * Fixed error for invalid symlink checking.

Version 1.0.3:
 * Changed behaviour for `disallowMultipleVarDecl` options. Now accepts multiple var decl in `for` decl.

Version 1.0.2:
 * Option `requireSpacesInsideArrayBrackets` (@mishanga).

Version 1.0.1:
 * Not reporting about extra quotes for zero-starting numbers in `disallowQuotedKeysInObjects`.

Version 1.0.0:
 * Camel-case configuration options.
 * Option `requireAlignedObjectValues`.
 * Option `requireSpaceAfterObjectKeys`.
 * JSDoc for core functions and classes.
 * Fix error position for disallowSpacesInsideObjectBrackets and disallowSpacesInsideArrayBrackets.


Version 0.0.12:
 * Fix in `disallowSpaceAfterObjectKeys` location reporting.

Version 0.0.11:
 * Option `disallowSpaceAfterObjectKeys`.
 * Option `disallowSpacesInsideArrayBrackets`.
 * Do not automatically exclude hidden files. 

Version 0.0.10:
 * Fix in `disallowQuotedKeysInObjects`.

Version 0.0.9:
 * Fix in `disallowQuotedKeysInObjects`.

Version 0.0.8:
 * Fix in `requireSpacesInsideObjectBrackets`.
 * Option `disallowQuotedKeysInObjects`.

Version 0.0.7:
 * Option 'requireSpacesInsideObjectBrackets'.
 * Option 'disallowSpacesInsideObjectBrackets'.

Version 0.0.6:
 * Fixes incorrent checkPath behavior.

Version 0.0.5:
 * .jshintrc config.
 * Error message format fixes.

Version 0.0.4:
 * Option 'disallowYodaConditions'.
 * Option 'requireMultipleVarDecl'.

Version 0.0.3:
 * Option 'excludeFiles', which accepts patterns.

Version 0.0.2:
 * Link to parent nodes.

Version 0.0.1:
 * Initial implementation.
