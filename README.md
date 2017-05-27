# Bug with flow and require with backticks

To reproduce:

1. `yarn`
2. `yarn run flow`

(I think that's all you need to do)

It is also possible to show that the error was introduced in v0.46:

1. `yarn add --dev flow@0.45`
2. `yarn run flow`
3. Notice no errors
4. `yarn add --dev flow@0.46`
5. `yarn run flow`
