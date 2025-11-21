# RAG

**Status:** 🟡 In Progress 
**Started:** 21 NOV 2025

## 📖 Overview

This covers whatever I learn about vLLMs

## 📚 Resources

### Courses
- Did not come across any course yet
### Articles & Videos

- [What is vLLM](https://www.geeksforgeeks.org/data-science/what-is-vllm/)
- [vLLM a quick start](https://towardsdev.com/vllm-a-quick-start-cf1c48aa5890) - This is good
- [Paged Attention](https://medium.com/my-musings-with-llms/understanding-kv-cache-and-paged-attention-in-llms-a-deep-dive-into-efficient-inference-62fa372432ce)



## 📓 Notebooks

- [Notebook Name](./notebooks/notebook_name.ipynb) - What this notebook covers

## 🎯 Key Concepts Learned

- ✅ FAISS

## 💡 Important Insights

The Tech: PagedAttention I'm really into vLLM right now. The core concept, PagedAttention, basically treats the KV cache like OS virtual memory.

Instead of pre-allocating contiguous blocks (which wastes GPU RAM), it breaks memory into pages.

These pages don't need to be next to each other, meaning zero fragmentation and way higher throughput.


The Experiment I tried running GPT-2 in a notebook and got bizarre results.

I set the temperature really high and I noticed it gave really bizzare results. That was interesting

Mistake: High temperature actually flattens the probability curve, making the model choose unlikely (random) words. On an old model like GPT-2, this just guarantees chaos.

Lesson: For stability, keep temp low (e.g., 0.1) or use a modern model like Llama-3.


## 📊 Projects

1. **Project Name** - Did not build anything yet

## 🔗 Additional Resources

Links to other helpful resources

---

[← Back to Main Roadmap](../README.md)