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
<details>
  <summary>Toggle me!</summary>
  <div>
    <div>This is the detailed content</div>
    <br/>
    <details>
      <summary>
        Nested toggle! Some surprise inside...
      </summary>
      <div>
        😲😲😲😲😲
      </div>
    </details>
  </div>
</details>
