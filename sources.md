# Sources, links, papers on Context Engineering (CE)

## Yichao 'Peak' Ji
[Manus - Context Engineering Lessons](https://manus.im/blog/Context-Engineering-for-AI-Agents-Lessons-from-Building-Manus)

- Hints at the importance of KV Cache
  - TTFT reduced if... 
  - Context append only
  - Kepp prompt prefix stable in order to not invalidate caching (antipattern prefix with current date)
- Attention issues
  - Manus uses TODO.md which is placed into the context several times as progressing thereby re-iterating 

## Phil Schmid - Context Engineering For AI Agents: Part 2
[Phil Schmid - CE for AI Agents 2](https://www.philschmid.de/context-engineering-part-2)
