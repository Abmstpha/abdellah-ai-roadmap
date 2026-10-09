# Abdellah AI Roadmap

An eight-day journey by Abdellahi El Moustapha to refresh my memory and revisit AI concepts through practical experiments. The notebooks follow a technical progression: prompting, representations, classification, retrieval, live search, database tools, agent orchestration, and model training.

Follow the daily posts and experiment write-ups on [my LinkedIn](https://www.linkedin.com/in/Abmstpha/).

| Notebook | Experiment |
| --- | --- |
| [abdellah-day-1-prompting.ipynb](abdellah-day-1-prompting.ipynb) | Conversation memory, sampling, classification, structured extraction, numerical verification, and code tools |
| [abdellah-day-2-embeddings-and-similarity.ipynb](abdellah-day-2-embeddings-and-similarity.ipynb) | Paraphrases, typos, French translation, normalization, cosine similarity, heatmap, and ranking |
| [abdellah-day-3-classifying-embeddings-with-keras.ipynb](abdellah-day-3-classifying-embeddings-with-keras.ipynb) | Supervised support routing using frozen embeddings, a Keras classifier, and a centroid baseline |
| [abdellah-day-4-document-q-a-with-rag.ipynb](abdellah-day-4-document-q-a-with-rag.ipynb) | Local document retrieval, grounded answers, citations, and an unsupported-question check |
| [abdellah-day-5-mistral-web-search-grounding.ipynb](abdellah-day-5-mistral-web-search-grounding.ipynb) | Live search grounding, source metadata, answer support, and a timestamped result |
| [abdellah-day-6-database-function-calling.ipynb](abdellah-day-6-database-function-calling.ipynb) | Synthetic SQLite data, read-only tools, conversation history, SQL traces, and independent answer checks |
| [abdellah-day-7-building-an-agent-with-langgraph.ipynb](abdellah-day-7-building-an-agent-with-langgraph.ipynb) | Explicit model/tool nodes, state, bounded routing, live web search, a local MCP server, and verified traces |
| [abdellah-day-8-fine-tuning-a-custom-model.ipynb](abdellah-day-8-fine-tuning-a-custom-model.ipynb) | DistilBERT weight updates, held-out sentiment predictions, and checkpoint reload verification |

In Kaggle, enable Internet and attach a secret named `MISTRAL_API_KEY` for the hosted API notebooks. CPU is sufficient for those workflows. Select a GPU for fine-tuning; that notebook uses a public pretrained checkpoint and requires no API key.

To run a notebook on Colab, upload its `.ipynb` file, run the setup cells, and provide `MISTRAL_API_KEY` through the environment for hosted inference. Select a GPU for Day 8.

For another Jupyter environment, install the notebook-specific dependencies and provide `MISTRAL_API_KEY` through the environment. `requirements.txt` lists the combined dependencies. `MISTRAL_MODEL` and `MISTRAL_EMBED_MODEL` can override model names.

The examples are small and synthetic. Their checks verify the demonstrated tasks, not general model reliability. Search results are time-sensitive.
