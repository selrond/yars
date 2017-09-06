# Y.A.R.S
Yet Another React Snippets.

Snippets for React-related development for Sublime Text.

## Installation

1. `CMD + Shift + P` → `Package Control: Add Repository`
2. paste in `https://github.com/selrond/yars`
3. `CMD + Shift + P` → `Package Control: Install Package`
4. search for `yars`

## Snippets
- `rcc` - Create React Class Component skeleton

 ```jsx
import React, { Component } from 'react';

class MyComponent extends Component {
   render() {
       return (
           <div>
           </div>
       );
   }
}

export default MyComponent;
```

- `rfc` - Create React Functional Component skeleton

```jsx
import React from 'react';

const MyComponent = (props) => {
    return (
        <div>
        </div>
    );
}

export default MyComponent;
```

- `ir` - Import React

```jsx
import React from 'react';
```

- `irc` - Import React Component

```jsx
import React, { Component } from 'react';
```

- `isc` - Import styled-components

```jsx
import styled from 'styled-components';
```

- `scs` - styled-components styled template

```jsx
const StyledComponent = styled.div`
    /* CSS */
`
```

- `sci` - styled-components interpolation

```jsx
${(props) => props.};
```

- `scscp` - styled-components [custom props workaround](https://github.com/styled-components/styled-components/issues/135#issuecomment-256018643)

```jsx
const StyledComponent = styled(({ customProp, ...rest }) => <ExistingComponent {...rest}></ExistingComponent>)`
    /* CSS */
`
``` 