# VS Code Progress Bar

The `vscode-progress-bar` component is used to indicate the length of time a process will take.

This may either be a determinate state in which the progress is a percentage of the total time needed to complete the task or as an indeterminate state where the wait time is unspecified.

The `vscode-progress-bar` renders a linear visual appearance for progress state. If a circular visual appearance is needed, use the `vscode-progress-ring`.

## Attributes

| Attribute | Type    | Description                            |
| --------- | ------- | -------------------------------------- |
| `value`   | string  | The current value of the progress bar. |
| `min`     | boolean | The minimum progress bar value.        |
| `max`     | boolean | The maximum progress bar value.        |

## Usage

### Basic Usage

The basic usage will display a looping animation to indicate an indeterminate state where the wait time is unspecified.

[Interactive Storybook Example](https://microsoft.github.io/vscode-webview-toolkit/?path=/story/library-progress-bar--default)

```html
<vscode-progress-bar></vscode-progress-bar>
```

### Value Attribute

[Interactive Storybook Example](https://microsoft.github.io/vscode-webview-toolkit/?path=/story/library-progress-bar--with-value)

```html
<vscode-progress-bar value="75"></vscode-progress-bar>
```

### Min Attribute

[Interactive Storybook Example](https://microsoft.github.io/vscode-webview-toolkit/?path=/story/library-progress-bar--with-value)

```html
<vscode-progress-bar min="0"></vscode-progress-bar>
```

### Max Attribute

[Interactive Storybook Example](https://microsoft.github.io/vscode-webview-toolkit/?path=/story/library-progress-bar--with-value)

```html
<vscode-progress-bar max="100"></vscode-progress-bar>
```