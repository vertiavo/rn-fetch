# rn-fetch

## Prerequisites

To use application you need to generate API key for TMDb.
You can do it by creating account and logging into it at:
[The Move Database](https://www.themoviedb.org).

Then, create a new file in project root called: _api_keys.js_.

In newly created file paste below snippet:

```javascript
const TMDB_API_KEY = "your_api_key";

export default TMDB_API_KEY;
```

Now, you should be able to perform requests to API.
