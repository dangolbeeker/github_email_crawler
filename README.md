This is a GitHub mailbox crawler implemented using Node.js, RxJS, and TypeScript language. It can crawl the mailboxes of all Followers of a specified user. It uses RxJS to improve the stability of the program:

* Use Rx operator for fault tolerance processing;
* Frequency control is performed on the global request.

Usage: update the configuration in [config.ts](src/config.ts),

```
// your cookies on the GitHub website
const COOKIE: string[] = [
  '',
];

// To crawl the specified user of the Follower mailbox
const TARGET_USERS: string[] = [
  '',
]
```

Then execute `yarn start`.
