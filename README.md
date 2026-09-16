# great-southern-websites.github.io

The organisation Pages site for Great-Southern-Websites. It exists for two reasons. The
custom domain set on it (live.greatsouthern.website) is inherited by every project site in
the organisation, so each built site is reachable at live.greatsouthern.website/<repo>/
before the customer connects their own domain. The root redirects to the main site.

`404.html` is the second. GitHub Pages serves this repo's 404 page for
any address on the domain that does not match a site, so a link to a site that was never
built or has been removed gets ours instead of GitHub's grey screen (issue #102).
