---
title: Added New Page
---

# New page 

We can create new pages with markdown file or by creating React component.

:::info

Check the [Pages Plugin API Reference documentation](./../api/plugins/plugin-content-pages.md) for an exhaustive list of options.

:::


## Add a React page {#add-a-react-page}

Create a file `/src/pages/helloReact.js`:

```jsx title="/src/pages/helloReact.js"
import React from 'react';
import Layout from '@theme/Layout';

function Hello() {
  return (
    <Layout title="Hello">
      <div
        style={{
          display: 'flex',
          justifyContent: 'center',
          alignItems: 'center',
          height: '50vh',
          fontSize: '20px',
        }}>
        <p>
          Edit <code>pages/helloReact.js</code> and save to reload.
        </p>
      </div>
    </Layout>
  );
}

export default Hello;
```

    <!--DOCUSAURUS_CODE_TABS-->
    <!--JavaScript-->
    
    ```js
    console.log('Hello, world!');
    ```
    <!--Python-->
    
    ```py
    print('Hello, world!')
    ```

    <!--C-->
    
    ```C
    #include <stdio.h>

    int main() {
       printf("Hello World!");
       return 0;
    }
    ```

    <!--Pascal-->
    
    ```Pascal
    program HelloWorld;
    begin
      WriteLn('Hello, world!');
    end.
    ```

    <!--END_DOCUSAURUS_CODE_TABS-->