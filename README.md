# Attention-mechanism-from-scratch
Input Embeddings: The program creates input embeddings representing three tokens.

Weight Matrices: Random weight matrices for Query (Q), Key (K), and Value (V) are generated.

Compute Q, K, and V: The input embeddings are transformed into Query, Key, and Value vectors.

Attention Scores: The similarity between Query and Key vectors is calculated to determine how much attention each token should pay to others.

Scale Scores: The attention scores are divided by the square root of the key dimension to improve stability.

Softmax: The scaled scores are converted into attention weights (probabilities) using the Softmax function.

Final Attention Output: The attention weights are multiplied with the Value vectors to produce the final context-aware output.
