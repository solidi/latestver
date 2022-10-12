# Latest Versioning 0.1

## Summary

Given a version number LABEL, increment the:

```
1. LABEL version when making a change.
```

## Introduction

**LatestVer** treats all previous releases as deprecated. Why aren't your patrons on the latest version LABEL? They should be. Ask them to bump to the latest.

## Latest Versioning Specification (LatestVer)

**LatestVer** is the same [SemVer](https://semver.org/), with these modifications:  

Every version is a crucial change. Every change is meaningful; otherwise, why perform the keystrokes to author the delta to your consumers? From spelling corrections to breaking API changes, treat each shift as *essential* and *necessary* for your adopters.

> Encourage adopters to use the latest version. Always.

## Context

**LatestVer** works best in natural software environments. Rarely will engineers bump to some minor or patch version? It's always a question about the primary label. And when scanning for an update, separators like periods, dashes, or spaces invoke degrees of fear. Mature teams dislike auto-bumping libraries because that's dangerous even with a suite of fifty-thousand unit and integration tests. So, **latestVer** removes all of that fear.

Ultimately, a human must see through a lib bump, which cannot be automated well in today's software environment. And if a tool is performing this work, cross your fingers if it compiles and deploys okay. And if it doesn't compile and takes more than thirty minutes to untangle, rethinking their architecture is needed. Good luck to them.

If there are security issues for your adopters, patch the latest version and encourage its usage. Be sure to state that previous releases are not *really* supported. Say, "bump early and often. Use our latest version!" Don't blame a previous version. Ask them to bump to the latest.

If the latest version doesn't fix the issue, encourage a fix-forward mentality. That's how the latest version works. The latest version will invariably resolve an emerging issue. Time is a healer, and so is *latestVer*.

Finally, engineers love to shop for new libraries. Who would ever use an older version of your library? Being on the Latest Version is where we purchase future maintenance labor, so encourage them to implement the latest version.

## A Note About LastVer, the Mirrored Version of LatestVer

This specification defines **latestVer**. However, we have noted countless exchanges when using  **latestVer**  where authors asked adopters the following:

> "Okay, looks like  **latestVer** isn't working for you. Have you tried the *last version*?" 

Meaning did they use the  **latestVer** in reverse? Hence, we enjoyed it so much that we branded it **lastVer**, defined as:

Given a version number LABEL, *decrement* the:

```
1. LABEL version when the latestVer does not work.
```

And then, your adopters will try it but confirm the change does not work. And this is why **latestVer** encourages a fix-forward mentality. It's time to stop lurking in the [Hacker News](https://news.ycombinator.com/) threads and start coding. Get to work, the customers are waiting.

## FAQ

### As an author of an API, how can I make the most of **LatestVer**?

Encourage an "update early and often" mindset. Always bump to the latest. And if the adopter is way out of date, ask them to bump to the latest.

### What about fixing security issues?

Why aren't they on your latest LABEL yet? Bump to the latest. That's where you'll patch the stuff they care about.

### What about those adopters who hedge pinned versions of your library?

Please encourage them to unpin. The latest version is where the magic will happen. 

### Are you the author of reversed versioning scheme **lastVer?**

Yes. We called first dibs on it.

## About

The Latest Versioning and Last Versioning specifications are authored by Doug "Surreal" Arcuri.

If you'd like to leave feedback, please [tweet at me](https://twitter.com/dougarcuri) and subscribe below. Hit the bell icon for unnecessary notifications.

## License

[Creative Commons - CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
