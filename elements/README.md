# Marketplace Elements

## Structure

File name: name of package on npm, without special characters like `@`

File content:

```js
{
    "name": "FileDB", // Name of the element, required
    "id": "jovo-db-filedb", // Name of the npm package, including special characters, required 
    "description": "Store user data in a local JSON file for fast prototyping and debugging", // Up to 100 characters, required
    "type": "integration", // See types.json, required
    "tags": "database", // See tags.json, required
    "stack": "local", // Add stack like "local", "aws", optional
    "githubUrl": "https://github.com/jovotech/jovo-framework/tree/master/jovo-integrations/jovo-db-filedb" // Link to GitHub repo/subrepo, required
}
```
