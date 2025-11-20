# AI/LLM Chatbot Google Dorks

A curated list of Dorks to find publicly indexed, privately shared conversations from various AI/LLM chatbots. This repository is intended for security researchers, bug bounty hunters, and privacy enthusiasts to conduct research and raise awareness about potential data exposure.

> ⚠️ **Important Disclaimer**: This information is provided for **educational and authorized security research purposes only**. Accessing data without explicit permission is illegal and unethical. The authors are not responsible for any misuse of this information. Always act responsibly and in compliance with applicable laws and platform terms of service.

## 📋 Table of Contents

-   [What are Dorks?](#what-are-google-dorks)
-   [The Dorks List](#the-dorks-list)
-   [How to Use](#how-to-use)
-   [Ethical Considerations](#ethical-considerations)
-   [Contributing](#contributing)
-   [License](#license)
-   [Acknowledgments](#acknowledgments)

## What are Google Dorks?

Dorks, also known as Google hacking, involves using advanced search operators to refine search results and find information that is not easily accessible through a standard search query. In this context, we use them to locate specific URL patterns used by AI platforms to share chat conversations, which may have been inadvertently indexed by search engines.

## The Dorks List

The complete list of dorks for various AI platforms is maintained in the following file:

➡️ **[`DORKS.md`](./DORKS.md)** ⬅️

This file contains a table of dorks for platforms like ChatGPT, Mistral AI, Perplexity, and more.

## How to Use

1.  **Choose a Dork**: Go to the [`DORKS.md`](./DORKS.md) file and copy the dork for the platform you are interested in.
2.  **Use a Search Engine**: Paste the dork into the search bar of a search engine (e.g., Google, Bing, DuckDuckGo).
3.  **Refine Your Search (Optional)**: Add specific keywords to the end of the dork to narrow down the results.
    *   **Example**: To find indexed chats about "API keys" from Mistral AI, you would search for:
        ```
        site:chat.mistral.ai/chat/ "API keys"
        ```
4.  **Analyze Results**: Review the search results. **Do not attempt to access or exploit any sensitive or private data you may find.** The goal is to identify the existence of exposed data, not to view its contents.

## Ethical Considerations

-   **Authorized Research Only**: Use these dorks only on systems where you have explicit permission to test.
-   **Do Not Access Private Data**: If you find a link to a private conversation, do not click it with the intent to view its contents. The discovery of the link itself is often sufficient to demonstrate the vulnerability.
-   **Report Responsibly**: If you discover a significant data exposure vulnerability, report it through the platform's official bug bounty program or vulnerability disclosure channel. Provide clear, actionable information to help them fix the issue.
