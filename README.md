# Minimal reproducible example for "Unbound Breakpoints" bug in VSCode

Start with:

```
docker-compose up
```

Set a breakpoint in `index.ts` and start the debug config "Backend". The breakpoint will be gray and marked as "Unbound breakpoint".