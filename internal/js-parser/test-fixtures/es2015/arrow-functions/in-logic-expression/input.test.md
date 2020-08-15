# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > arrow-functions > in-logic-expression`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/arrow-functions/in-logic-expression/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/arrow-functions/in-logic-expression/input.js"
		end: Object {
			column: 19
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/arrow-functions/in-logic-expression/input.js"
				end: Object {
					column: 19
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSLogicalExpression {
				operator: "||"
				loc: Object {
					filename: "es2015/arrow-functions/in-logic-expression/input.js"
					end: Object {
						column: 18
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				right: JSBooleanLiteral {
					value: true
					loc: Object {
						filename: "es2015/arrow-functions/in-logic-expression/input.js"
						end: Object {
							column: 18
							line: 1
						}
						start: Object {
							column: 14
							line: 1
						}
					}
				}
				left: JSArrowFunctionExpression {
					loc: Object {
						filename: "es2015/arrow-functions/in-logic-expression/input.js"
						end: Object {
							column: 9
							line: 1
						}
						start: Object {
							column: 1
							line: 1
						}
					}
					body: JSBlockStatement {
						body: Array []
						directives: Array []
						loc: Object {
							filename: "es2015/arrow-functions/in-logic-expression/input.js"
							end: Object {
								column: 9
								line: 1
							}
							start: Object {
								column: 7
								line: 1
							}
						}
					}
					head: JSFunctionHead {
						async: false
						hasHoistedVars: false
						params: Array []
						rest: undefined
						returnType: undefined
						thisType: undefined
						loc: Object {
							filename: "es2015/arrow-functions/in-logic-expression/input.js"
							end: Object {
								column: 6
								line: 1
							}
							start: Object {
								column: 1
								line: 1
							}
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/arrow-functions/in-logic-expression/input.js"
				end: Object {
					column: 19
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			expression: JSConditionalExpression {
				loc: Object {
					filename: "es2015/arrow-functions/in-logic-expression/input.js"
					end: Object {
						column: 18
						line: 2
					}
					start: Object {
						column: 0
						line: 2
					}
				}
				alternate: JSReferenceIdentifier {
					name: "b"
					loc: Object {
						filename: "es2015/arrow-functions/in-logic-expression/input.js"
						identifierName: "b"
						end: Object {
							column: 18
							line: 2
						}
						start: Object {
							column: 17
							line: 2
						}
					}
				}
				consequent: JSReferenceIdentifier {
					name: "a"
					loc: Object {
						filename: "es2015/arrow-functions/in-logic-expression/input.js"
						identifierName: "a"
						end: Object {
							column: 14
							line: 2
						}
						start: Object {
							column: 13
							line: 2
						}
					}
				}
				test: JSArrowFunctionExpression {
					loc: Object {
						filename: "es2015/arrow-functions/in-logic-expression/input.js"
						end: Object {
							column: 9
							line: 2
						}
						start: Object {
							column: 1
							line: 2
						}
					}
					body: JSBlockStatement {
						body: Array []
						directives: Array []
						loc: Object {
							filename: "es2015/arrow-functions/in-logic-expression/input.js"
							end: Object {
								column: 9
								line: 2
							}
							start: Object {
								column: 7
								line: 2
							}
						}
					}
					head: JSFunctionHead {
						async: false
						hasHoistedVars: false
						params: Array []
						rest: undefined
						returnType: undefined
						thisType: undefined
						loc: Object {
							filename: "es2015/arrow-functions/in-logic-expression/input.js"
							end: Object {
								column: 6
								line: 2
							}
							start: Object {
								column: 1
								line: 2
							}
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```