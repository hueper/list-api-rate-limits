# list-api-rate-limits
List of HTTP API Rate Limiting

Posts

| Service         | endpoint               | window        | user limit  | app limit   | notes       | links  |
| --------------- |:----------------------:| -------------:| -----------:| -----------:| -----------:| ------:|
| twitter         | statuses/update        | 15min         | 15          | -           |             | [twitter](https://dev.twitter.com/rest/public/rate-limiting) |
| linkedin        | shares                 | 1day          | 25          | 125000      |             | [linkedin](https://developer.linkedin.com/docs/share-on-linkedin) |
| tumblr          | {blog-identifier}/post | n/a           | n/a         | n/a         |             | [tumblr](https://www.tumblr.com/docs/en/api/v2) |
| soundcloud      | tracks                 | n/a           | n/a         | n/a         | paid plans  | [soundcloud docs](https://developers.soundcloud.com/docs/api/rate-limits), [soundcloud portal](http://uploadandmanage.help.soundcloud.com/customer/portal/articles/2162441-uploading-requirements) |
| youtube         | videos                 | Quota usage   | Quota usage | Quota usage |             | [developers.google.com/youtube](https://developers.google.com/youtube/v3/getting-started#quota), [console.developers.google.com](https://console.developers.google.com) |
