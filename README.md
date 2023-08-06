# Cogni: Multi-Functional Chatbot with NeuralDB and OpenAI

**Connecting Intelligence, Context, and Content**

Welcome to **Cogni**, an innovative application that leverages the power of the ThirdAI NeuralDB library and the OpenAI GPT-3.5-Turbo language model to provide users with diverse conversational experiences. Cogni is designed to offer a range of functionalities:

## About Cogni

Cogni introduces an innovative approach to interact with information of various kinds. Whether it's a PDF document, a blog post, or a YouTube video, Cogni makes it easier to engage meaningfully with content.

### PDF Interaction

Engage with PDF documents like never before! Cogni's PDF chatbot lets you upload PDF files and initiate conversations based on the content within them. By creating a NeuralDB with ThirdAI's library, we group semantically meaningful words together, enabling streamlined interactions. The chatbot analyzes and retrieves information from uploaded PDFs, and the OpenAI GPT-3.5-Turbo model generates interactive and informative responses.

### Website Interaction

Experience interactive browsing and chatting in one place. Cogni's website chatbot enables you to input a website link. The chatbot then uses the `ndb.parsing_utils.recursive_url_scrape` function to extract relevant content. Engage in a lively conversation with the extracted information, powered by both NeuralDB and OpenAI models.

### YouTube Video Chatbot

Have conversations with the content of your favorite YouTube videos. Provide a YouTube video ID, and Cogni's chatbot will leverage NeuralDB to retrieve pertinent content. The video's transcript is processed and transformed into a dynamic chat format using the OpenAI GPT-3.5-Turbo model. Enjoy an engaging dialogue with the video's content, driven by the power of AI.

## How It Works

Here's how Cogni seamlessly integrates these features:

1. **PDF Interaction**: Upload the PDFs, and Cogni's NeuralDB processes and stores the content using ThirdAI's library. You can then query the documents, and Cogni's GPT-3.5-Turbo model generates informative responses.

2. **Website Interaction**: Paste the URL of a blog post, and Cogni extracts relevant content. The NeuralDB processes the information, allowing you to engage in interactive conversations. GPT-3.5-Turbo enhances the experience by providing insightful discussions.

3. **YouTube Video Interaction**: Provide a YouTube video ID, and Cogni's chatbot retrieves and processes the video's content using NeuralDB. Engage in dynamic conversations about the video's subject matter, powered by GPT-3.5-Turbo.

## References

The development of Cogni is inspired by the following resources:

- [ThirdAI NeuralDB library](https://thirdai.com/neural-db/)
- [OpenAI GPT-3.5-Turbo language model](https://openai.com/blog/openai-api/)
- [PaperQA](https://paperqa.readthedocs.io/en/latest/)
