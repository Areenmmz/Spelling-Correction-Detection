### **Spelling and Grammar Correction System**

This component is a text-refinement pipeline designed to improve the quality of business-related documents by automatically identifying and fixing linguistic errors.

#### **Core Features**
* **Comprehensive Correction:** Detects and fixes both non-word errors and real-word context errors.
* **Grammar Integration:** Includes a structural check to ensure sentences adhere to standard grammatical rules.
* **Interactive Interface:** A web-based GUI built with Gradio that allows for real-time text input and instant correction feedback.

#### **Technical Pipeline**
* **Advanced Preprocessing:** A rigorous multi-stage cleaning process including normalization, noise removal, tokenization, lemmatization, and custom stopword filtering.
* **Hybrid Similarity Logic:** The system determines the best word replacements by combining Levenshtein Distance (edit distance) with Bigram Similarity modeling.
* **Custom Business Vocabulary:** The model is powered by a specialized vocabulary derived from a massive dataset of over 2.8 million words, filtered down to 12,466 unique, high-relevance business terms to ensure accuracy in professional contexts.

#### **Technology Stack**
* **Natural Language Processing:** Built using Python with core libraries such as NLTK, spaCy, and SymSpell for linguistic analysis and tokenization.
* **Algorithms:** Implements weighted edit distance and N-gram corpus probability models.
* **Deployment:** Managed via a Gradio interface for seamless user interaction.

#### **Contributions**
* **Data & UI:** Managed preprocessing, data normalization, and the development of the Gradio interface.
* **Integration:** Focused on main script logic and the implementation of the grammar correction module.
* **Analysis:** Conducted exploratory data analysis to optimize vocabulary refinement and system performance
