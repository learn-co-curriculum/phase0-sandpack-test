# Sandpack test

## Learning Goals

- Example #1 - Sandpack code editor, console and preview components.
- Example #2 - Use code.assert to check function implementation.
- Example #3 - Sandpack test component (Jest) without console.
- Example #4 - Sandpack test component with console (failing).

## Introduction

Each example uses an iframe request to
[https://linda-seiter.github.io/code-test-app/](https://linda-seiter.github.io/code-test-app/).
The question id is passed as a query string parameter.

## Example #1 Editor + Console + Preview

<iframe width="800" height="600" src="https://linda-seiter.github.io/code-test-app"></iframe>

## Example #2 Editor + Console

<iframe width="800" height="600" src="https://linda-seiter.github.io/code-test-app/?id=2"></iframe>

## Example #3 Editor + Test

<iframe width="800" height="600" src="https://linda-seiter.github.io/code-test-app/?id=3"></iframe>

## Example #4 Editor + Test + Console (console.log tests fail)

<iframe width="800" height="600" src="https://linda-seiter.github.io/code-test-app/?id=4"></iframe>
