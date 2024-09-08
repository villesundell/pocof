# PoCoF - Portable Context Format for Neural Networks

Neural networks, in their various forms, are likely to remain integral to our work, with their influence growing year by year. However, a significant challenge persists: the lack of an efficient method to share or preserve our work—a fundamental human need, as this document itself indirectly illustrates.

Currently, sharing and collaborating on AI workflows is limited to "exporting" work for others to build upon, which strips away all the crucial context in the process. This loss of context poses a significant challenge, as it hinders effective collaboration and the preservation of valuable insights.

Despite the diverse nature of large language models and neural networks in general, one possible solution is outlined here. By abstractly defining a context through key parameters, such as the weighted ordering of tokens, we can create a portable context that can be transferred from model to model while maintaining considerable accuracy, even in the long term.

PoCoF leverages XML, a technology that offers extensibility, interoperability, and compatibility with version control systems like Git. XML’s structure also makes it ideal for long-term preservation, ensuring that the context remains accessible and useful well into the future.