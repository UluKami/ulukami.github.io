---
layout: post
title:  "Locking Yourself In One Path"
date:   2026-07-06 14:58:07 -0400
categories: systems database
---
While I was sketching out the outline of how I plan for the system to operate, I had an epiphany of sorts. A majority of the work I was doing reminded me of the structured steps that one does when designing databases. 

The tools we are using to map out our designs is through the C4 model that was created by Simon Brown. You can check it out [here](https://c4model.com/). The levels between each diagram representing a more detailed scope in the design process evoked the memories of using the ER diagram and relational diagram to plan out my databases.

The ER diagram is very broad, allowing you to think of what entities are necessary and how each relates to each other. Due to this simplistic nature, you don’t get lost in thinking about the intricacies of the system, which allows you to focus on defining what is important.

Making a system’s context diagram functions the same way. By planning broad systems and defining their relationship to each other, you don’t get lost in developing the system and miss parts that you otherwise wouldn’t think about.

The same principles extend to using the relational diagram for database design and using the container diagram in the C4 model. Both expand on the finer details of what systems/variables must exist within the implementation and define more extensive relations between these said systems/variables.

Because I made this connection, I started to think that these universal patterns only extended to crafting my own systems context and container diagrams. However, I quickly learned that this wasn’t going to be the only connection I found between databases and other development spheres.

I watched episode 28 of the Signals&Threads podcast by Jane Street’s Ron Minsky, where Jacob Baskin discusses his experience working with the database infrastructure team at Jane Street. This episode is very interesting and I recommend checking it out for yourselves, but the reason I bring it up is due to one of Jacob’s perspectives on his current project with the company.

Near the end of the podcast, he describes his experiences with a computational graph API. He was able to apply his vast knowledge on SQL to the process of planning an optimization to the output of the API and then shortly discussed how reminiscent SQL queries are to the operations that are done to his system as a whole.

After sitting listening to this part of the episode and really stewing on that concept, it clicked on just how applicable these concepts are in other fields. Just how my experiences working on databases are transferable to systems design.

So, don’t box yourself into the one field that you specialize in. You are capable of doing much more by just expanding your scope.

But what do you think? Do you know of any other examples where learning one language or system helped you in improving another?

<script src="https://giscus.app/client.js"
        data-repo="UluKami/ulukami.github.io"
        data-repo-id="R_kgDOTO1r4A"
        data-category="Q&A"
        data-category-id="DIC_kwDOTO1r4M4DAoJk"
        data-mapping="og:title"
        data-strict="1"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="en"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>
