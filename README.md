# Attention-mechanism-from-scratch
Step 1: Input Embeddings: The program creates input embeddings representing three tokens.

Step 2: Weight Matrices: Random weight matrices for Query (Q), Key (K), and Value (V) are generated.

Step 3: Compute Q, K, and V: The input embeddings are transformed into Query, Key, and Value vectors.

Step 4: Attention Scores: The similarity between Query and Key vectors is calculated to determine how much attention each token should pay to others.

Step 5: Scale Scores: The attention scores are divided by the square root of the key dimension to improve stability.

Step 6: Softmax: The scaled scores are converted into attention weights (probabilities) using the Softmax function.

Step 7: Final Attention Output: The attention weights are multiplied with the Value vectors to produce the final context-aware output.
<img width="617" height="792" alt="Screenshot 2026-07-09 170812" src="https://github.com/user-attachments/assets/d37ee659-c72e-4ea2-b85a-5597693d01c8" />

