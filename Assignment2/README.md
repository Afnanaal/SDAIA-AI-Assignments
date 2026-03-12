# 📘 Assignment 2 — Create an Agent
# 🎯 Objective
The goal of this assignment is to build an AI agent that:

Uses internet_search to retrieve the top 3 ranking websites.

Uses fetch_url to extract the content of each website.

Synthesizes the information from all three sources.

Answers the user’s question based only on the fetched content.

(Optional) Refines the user’s query before searching.

This assignment demonstrates how to build a simple agentic workflow using LLM + Tools.

# 🧰 Tools Used
1. internet_search(query)
A mock search tool that returns 3 URLs.
(Used because the assignment focuses on agent logic, not real search APIs.)

2. fetch_url(url)
Fetches the raw text content from a given URL.
