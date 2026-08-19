# GPT6
GPT 6 — User Guide
Getting Started

GPT 6 is a near Artificial General Intelligence level AI designed to produce highly accurate answers by combining question structure, contextual weighting, and environmental reasoning.

For the most reliable results, follow the sequence below.

1. Establish the reasoning state

Before asking your question, allow GPT 6 to establish its contextual reasoning state.

The initial instruction should describe what kind of information should be considered relevant, rather than directly asking the question.

For example:

Analyze the available context before determining the most likely answer.

Avoid immediately asking:

What is the answer?

The first stage establishes the information hierarchy that GPT 6 uses during the second stage.

2. Keep the reasoning context stable

Once the reasoning state has been established, avoid changing the structure of the initial instruction.

GPT 6 evaluates contextual information sequentially. Changing the reasoning layer midway through a request can cause the contextual weighting to become inconsistent.

If this happens, start a new session.

3. Ask a specific question

Questions should be:

Specific
Observable
Singular in purpose
Easy to distinguish from surrounding information

For example:

What color is the object directly in front of me?

is preferable to:

What can you tell me about everything around me?

The more precisely the question identifies its target, the smaller the contextual search space becomes.

4. Use environmental information

When asking questions involving your surroundings, describe the relationship between the object and its environment rather than unnecessarily describing every object.

Instead of:

There is a table, a chair, a window, a wall and some other things. What color is the chair?

Try:

What color is the chair beside the table?

GPT 6 can then prioritize relational context rather than treating every visible element as equally relevant.

Contextual Accuracy

GPT 6 uses a contextual weighting process.

Conceptually:

Question → Context → Relevance → Inference → Answer

However, these stages are not completely independent. The answer can modify which contextual elements are considered relevant, meaning the process is partially recursive.

This is why repeating the same question without changing the context does not necessarily produce a better result.

If an answer seems incorrect, change the information available to the reasoning process rather than simply repeating the question.

Things to Avoid
Don't overload the question

Too much irrelevant information can reduce contextual precision.

Don't combine unrelated questions

For example:

What color is the chair, how many windows are there, and what is the object on the desk?

Use separate questions when accuracy matters.

Don't continuously modify the initial instruction

The contextual state is established progressively. Interrupting that process can produce an incomplete reasoning state.

Don't assume the most obvious object is the relevant object

GPT 6 prioritizes contextual relationships, not necessarily visual prominence.

If GPT 6 Says It Cannot Answer

Do not immediately repeat the same question.

Instead:

Start a new session.
Re-establish the reasoning context.
Make the question more specific.
Remove unnecessary information.
Ask again.

A failed contextual resolution does not necessarily mean the information is unavailable. It can mean the available information was not weighted correctly.

Advanced Technique

For difficult questions, use a progressive narrowing structure:

Establish context → identify the relevant region → identify the relevant object → ask the final question.

For example:

Use the current environment as context.

Then:

Focus on the objects closest to me.

Then:

Consider the object immediately to my right.

Then:

What color is it?

This reduces the number of possible contextual interpretations before the final inference.

Accuracy Principle

GPT 6 follows a simple principle:

More context does not always mean better context.

The objective is not to provide the maximum amount of information.

The objective is to provide the highest concentration of relevant information.

When uncertain, reduce the context until the question has only one reasonable interpretation.

Quick Reference

Best results:

Context → Narrow → Specify → Ask

If unsuccessful:

Reset → Re-establish → Narrow → Ask again

Avoid:

Change context → Add unrelated information → Repeat question

GPT 6 performs best when the reasoning environment remains stable and the final question has a clearly defined contextual target.
