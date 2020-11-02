# styled-components-react-js-ts-snippets

## Features

This contains two snippets

scr:
will autocomplete to

```javascript
import React from "react";
import styled from "styled-components";

const Component = styled.div``;

export const NameOfComponent = () => {
  return <Component></Component>;
};
```

tscr:
will autocomplete to

```typescript
import React from "react";
import styled from "styled-components";

const Component = styled.div``;

type NameOfComponentProps = {};

export const NameOfComponent = ({}: NameOfComponentProps) => {
  return <Component></Component>;
};
```

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

- `myExtension.enable`: enable/disable this extension
- `myExtension.thing`: set to `blah` to do something
