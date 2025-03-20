---
layout: post
title: "Let Claue Code control your NodeJS debugger"
date: 2025-03-19
categories: projects
---

<b>Problem<b>

We experienced debugging death loop while vibe coding. 

Debugging Death Loop:
- Copy the exception or error
- Paste it into Claude/Cursor
- Hope it will fix it. 

It will fail, and you will try again hoping it will get it this time. Pretty soon, it will become 20 times and frustrating. No more vibes!

<b>Current Options<b>

When researched online, the current options are:
- Understand code better: I think this is preaching old ways to new class of programmers - vibe coders.
- Add log lines: To be effective, you should understand code better.

We thought about how an experienced programmer approach programming - by using a debugger and stepping through code. What if we allow Claude Code to set breakpoints, step through code and inspect variables?

<b>Solution<b>

We built an MCP server for exactly that. You can try yourself:
1. Run your NodeJS server with `--inspect` flag that accepts remote debugger
2. Add our MCP using the following command `claude mcp add nodejs-debugger npx @hyperdrive-eng/mcp-nodejs-debugger`
3. Sit back and enjoy the magic with Claude debugging yoru code!


<b>Important Links<b>
- [Github Repo](https://github.com/hyperdrive-eng/mcp-nodejs-debugger)
- [NPM Package](https://www.npmjs.com/package/@hyperdrive-eng/mcp-nodejs-debugger)

### Demo 
<iframe width="800" height="605" src="/assets/videos/mcp-nodejs-debugger.mp4" frameborder="0" allowfullscreen></iframe>


<style>
    .site-footer {
        display: none;
    }

    .post-title {
        font-size: 36px;
    }
    iframe {
        margin-top: 0;
    }
</style>