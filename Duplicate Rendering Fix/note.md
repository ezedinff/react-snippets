```
to fix over rendering or unnecessary renders we can use React.memo for returning the cache 
version and only the change to render and **useCallback** memoizes our callback so it won't foces re-rendering
```