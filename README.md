# HKUST_Advisor_Chatbot

# 🤖 HKUST Course Advisor: Your Smart Guide to All Things HKUST!

Welcome to the HKUST Course Advisor project! Ever felt lost navigating the vast landscape of university information? This project is here to help! It is a smart assistant that can answer your questions about HKUST – from academic programs and admissions to campus services and important milestones.

Think of it as having a friendly, knowledgeable guide right at your fingertips, powered by the magic of artificial intelligence!

## ✨ What does it do?

This project takes a bunch of documents containing information about HKUST (like program descriptions, admission details, etc.) and transforms them into a searchable knowledge base. When you ask a question, the advisor quickly finds the most relevant pieces of information and uses a language model to generate a helpful and easy-to-understand answer.

No more sifting through countless web pages! Just ask your question and get a concise response.

## 🛠 How does it work? (The Techie Bit, simplified!)

Here's a peek under the hood:

1.  **Loading the Brain:** It starts by reading through all the .md files in a specific folder (that's your knowledge base!).
2.  **Breaking it Down:** The information is then broken into smaller, manageable chunks. This makes it easier for the computer to process.
3.  **Understanding the Meaning:** Each chunk of text is converted into a numerical representation called an "embedding." This captures the meaning of the text.
4.  **Building a Super Search Index:** These embeddings are stored in a special structure called a FAISS index. This allows for incredibly fast searching.
5.  **Asking the Question:** When you type a question, it's also converted into an embedding.
6.  **Finding the Best Matches:** The system searches the FAISS index to find the chunks of information that are most similar in meaning to your question.
7.  **Generating the Answer:** Finally, a language model (like a mini-GPT) takes the relevant information it found and your question, and crafts a human-like answer!


## 🙏 Contributing

Want to make this advisor even better? Contributions are welcome! Feel free to fork the project, add more information to the knowledge base, improve the code, or suggest new features.

Let's build the best HKUST Course Advisor together!
