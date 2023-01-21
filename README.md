<h1 align="center">LIVEIMG</h1>
<h2>example</h2>

```javascript
const uploadImg = require("liveimg");

var data = await uploadImg({
  username: YOUT_GITHUB_USERNAME,
  repo: YOUR_REPO_NAME,
  token: GITHUB_ACCESS_TOKEN,
  content: IMAGE_DATA_BASE64,
});
console.log(data);
```

<p>You have to create a public repo in your github acount to store all images</p>


