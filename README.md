This dockerfile is a temporary measure to stop some Docker image-caching
annoyances with our build server.

Don't rely on this for anything; I'm only publishing it publically because
that lets us pull it in instead of trying to cache the Docker layer locally on
our build server (afaict that local cache is being cleared for some reason,
so pulling in a public image instead of relying on the local cache should
solve our caching issues)
