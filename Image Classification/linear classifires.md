## Lecture Notes

### Deep Neural Networks and Linear Classifiers

Deep neural networks are often compared to **Legos**, where each component builds upon the other. A **linear classifier** serves as one of the most fundamental building blocks for these networks.

> "These deep neural networks are kind of like Legos, and this linear classifier is kind of like the most basic building blocks of these giant networks." *(47:4)*

However, before diving deeper into neural networks, we first revisit **CIFAR-10** for further understanding.

### Parametric Approach and Efficient Models

In a **parametric approach**, we summarize training data into a set of parameters **W**, making the model more efficient at test time.

> "At test time, we no longer need the actual training data; we can throw it away. We only need these parameters, W, at test time. This allows our models to now be more efficient and actually run on small devices like phones." *(49:31)*

### Understanding the Function of a Linear Classifier

A linear classifier processes images by flattening them into vectors and applying weights.

> "We take this two by two image, stretch it into a column vector with four elements, and then apply weights for classification." *(51:24)*

For example, when classifying planes, the classifier might learn to recognize blue backgrounds and blobby structures.

> "The classifier for planes looks for blue stuff and blobby stuff, making it favor planes more." *(53:58)*

### Decision Boundaries and Limitations

Linear classifiers attempt to separate categories using linear boundaries.

> "The classifier will try to draw a single blue line to separate airplanes from all other classes." *(55:33)*

However, linear classifiers struggle with **multimodal data** where categories exist in non-continuous clusters.

> "For example, in the right figure, our blue category exists in three different islands, making classification harder." *(57:28)*

### Conclusion

Linear classification provides a foundational approach to categorization, but struggles in complex, multimodal scenarios.

> "This is a preview of next week's discussion on overcoming the limitations of linear classification." *(57:51)*

---

End of Lecture.
