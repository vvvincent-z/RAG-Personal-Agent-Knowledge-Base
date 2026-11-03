# RAG-Personal-Agent-Knowledge-Base
适用于个人知识库构建
把“文档上传”和“用户提问”这两条链路串起来：上传时走 loader -> ingest -> split -> vector/BM25，提问时走 retrieve_chunks -> 混合召回 -> 给 chat/agent 用
技术栈：技术栈：Python、FastAPI、LangChain、LangGraph、Milvus、PostgreSQL、Redis、BM25、Vue 3、TypeScript、Docker。
