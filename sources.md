# Sources, links, papers on Context Engineering (CE)

## Phil Schmid - The New Skill in AI is Not Prompting, It's Context Engineering
[CE the new Skill in AI](https://www.philschmid.de/context-engineering)

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

## LangChain - How Agetns Use Context Engineering
[YouTube How Agents Use Context Engineering](https://www.youtube.com/watch?v=XFCkrYHHfpQ)
3 principles
- Offload
  - e.g. User Memory
  - File system storage 
- Reduce
  - Compaction, old tool results are placed on the file system with a reference
  - Summarization
  - Filtering tool results before being passed on
- Isolate
  - Sub-agents used to work with separate but smaller contexts

Mentions:
- Context rot
