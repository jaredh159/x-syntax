# x-syntax

Simple passthrough tagged template literal function for getting vscode syntax
highlighting. Import the function using a variable name like `css` or `graphql` to get
highlighting:

```ts
import css from 'x-syntax';

const myCss = css`
  body {
    display: none;
  }
`;
```

```ts
import graphql from 'x-syntax';

const query = graphql`
  mutation CreateDownload($data: DownloadInput!) {
    result: createDownload(data: $data) {
      _id
    }
  }
`;
```
