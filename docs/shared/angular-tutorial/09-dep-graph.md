# Angular Nx Tutorial - Step 9: Using the Project Graph

{% youtube
src="https://www.youtube.com/embed/8fr2RukmfW0"
title="Nx.dev Tutorial | Angular | Step 9: Dep Graph"
width="100%" /%}

An Nx workspace can contain dozens or hundreds of applications and libraries. As a codebase grows, it becomes more difficult to understand how they depend on each other and the implications of making a particular change.

Previously, some senior architect would create an ad-hoc dependency diagram and upload it to a corporate wiki. The diagram is not correct even on Day 1 and gets more and more out of sync with every passing day.

With Nx, you can do better than that.

Run the command to see the project graph for your workspace.

```sh
npx nx graph
```

## What's Next

- Continue to [Step 10: Using Computation Caching](/angular-tutorial/10-computation-caching)
