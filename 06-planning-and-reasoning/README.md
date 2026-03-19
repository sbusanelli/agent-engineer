# Lesson 6: planning and reasoning - how agents tackle complex tasks

## What you will learn

- Why planning is essential for agents handling complex tasks
- The agentic problem-solving loop: Get Mission, Scan Scene, Think, Act, Observe
- Plan-then-execute vs. reactive approaches and the trade-offs of each
- Hierarchical planning for breaking big tasks into manageable pieces
- Re-planning: how agents adapt when things go wrong
- Reasoning techniques: Chain-of-Thought, Tree-of-Thoughts, and self-consistency
- The orchestration layer's role in managing plans
- Common failure modes and how to avoid them

## Prerequisites

- [Lesson 2: How Agents Think](../02-how-agents-think/README.md)
- [Lesson 4: Agentic Design Patterns](../04-agentic-design-patterns/README.md)
- [Lesson 5: Memory and Context](../05-memory-and-context/README.md)

---

## ELI5: Planning is like packing for a trip

Imagine you are packing for a two-week trip. You could just start grabbing stuff and shoving it in a suitcase. Maybe you will get lucky and have everything you need. More likely, you will forget your toothbrush and pack three jackets you never wear.

A better approach: think about where you are going, what the weather will be like, what activities you have planned, and *then* make a packing list. Check items off as you pack them. If you find out halfway through that you do not have enough room, you re-prioritize - drop the "just in case" items and keep the essentials.

That is what planning does for an AI agent. Instead of reacting to each step blindly, the agent thinks ahead, makes a plan, and works through it systematically. And when the plan hits a snag, a good agent adjusts rather than plowing forward with a broken approach.

---
