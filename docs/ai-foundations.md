# AI foundations

## What is AI?

Artificial intelligence is the design of systems that perform tasks associated with human intelligence, such as recognizing patterns, understanding language, making predictions, or choosing actions. Most real systems are **narrow AI**: they are built for a limited task rather than general human-like intelligence.

## Machine learning

Machine learning uses examples or experience to find patterns instead of relying only on hand-written rules.

- **Supervised learning:** examples have labels, such as “healthy” and “diseased.”
- **Unsupervised learning:** the system looks for groups or structure without supplied labels.
- **Reinforcement learning:** an agent learns by trying actions and receiving rewards or penalties.

Important distinctions:

- Training data is used to learn patterns.
- Test data checks how well the learned pattern works on unseen examples.
- A model can be accurate on training data but poor on new data; this is overfitting.
- Biased or incomplete data can produce unfair or unreliable results.

## Computer vision and NLP

Computer vision works with images or video. A digital image can be represented as a grid of pixels; colour images commonly store red, green, and blue values for each pixel.

Natural language processing works with human language. Typical tasks include classification, translation, search, summarization, and question answering. Language systems can make mistakes because words depend on context and because the training data may contain errors or bias.

## Case-study questions

For any AI application, ask:

1. What is the input and what decision or prediction is produced?
2. What data was used to build or evaluate the system?
3. What could go wrong?
4. Who benefits and who might be harmed?
5. How could a human review, appeal, or correct the result?

Examples:

- A hiring system may repeat historical discrimination.
- A recommendation system may create narrow “bubbles” or favour popular content.
- A crop-diagnosis system may fail on plants, lighting, or diseases absent from its training data.
- A navigation or delivery system must handle safety, uncertainty, and changing conditions.

## Responsible AI vocabulary

- **Privacy:** protecting personal information.
- **Bias:** a systematic tendency that can produce unequal outcomes.
- **Transparency:** making the system's purpose and limits understandable.
- **Accountability:** identifying who is responsible for decisions and fixes.
- **Robustness:** continuing to work safely when inputs vary or contain errors.
