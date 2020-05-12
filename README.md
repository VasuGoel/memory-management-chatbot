# MemBot
Interactive ChatBot build using wxWidgets cross-platform GUI library and optimized with modern C++ memory management in mind. The ChatBot code creates a dialogue where users can ask questions about some aspects of memory management in C++. After the knowledge base of the chatbot has been loaded from a text file (which by the way you can add to), a knowledge graph representation is created in computer memory, where chatbot answers represent the graph nodes and user queries represent the graph edges. After a user query has been sent to the chatbot, the Levenshtein distance is used to identify the most probable answer.

Modern memory management techniques used are Dynamic Memory Allocation (The Heap), Resource Copying Policies with Copy and Move semantics using Lvalues and Rvalues for implementing the Rule of Five, Resource Acquisition Is Initialization (RAII), Smart Pointers and Transfering ownerships.

