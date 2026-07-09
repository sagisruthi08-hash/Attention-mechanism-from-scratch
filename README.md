# Attention-mechanism-from-scratch
This program demonstrates the Scaled Dot-Product Attention mechanism, which is the main component of the Transformer architecture used in many AI models.
Step 1: Import the NumPy Library
The program first imports the NumPy library, which is used for performing mathematical calculations and matrix operations.
Step 2: Create Input Embeddings
An input matrix is created to represent the embeddings of three tokens (or words). Each token is represented by a vector of three numerical values. These embeddings are the input to the attention mechanism.
Step 3: Initialize Random Values
A random seed is set so that the randomly generated values remain the same every time the program is executed. This makes the output reproducible.
Step 4: Define Dimensions
The program determines the embedding size (model dimension) and the dimension of the Query, Key, and Value vectors. These dimensions are used to generate the required matrices.
Step 5: Generate Weight Matrices
Three random weight matrices are created:
Query (WQ) weight matrix
Key (WK) weight matrix
Value (WV) weight matrix
These matrices are used to transform the input embeddings into Query, Key, and Value vectors.
Step 6: Compute Query, Key, and Value
The input embeddings are multiplied by their corresponding weight matrices to generate:
Query (Q): Represents what information each token is searching for.
Key (K): Represents the characteristics of each token.
Value (V): Represents the actual information carried by each token.
Step 7: Calculate Attention Scores
The program calculates the similarity between every Query vector and every Key vector. The resulting attention score indicates how much one token should pay attention to another token. Higher scores indicate stronger relationships.
Step 8: Scale the Attention Scores
The attention scores are divided by the square root of the Key dimension. This scaling prevents the values from becoming too large, making the attention mechanism more stable and improving model performance.
Step 9: Apply the Softmax Function
The scaled scores are passed through the Softmax function. Softmax converts the scores into probability values between 0 and 1, where the sum of each row equals 1. These probabilities are called attention weights.
Step 10: Compute the Final Attention Output
The attention weights are multiplied by the Value vectors. This produces the final attention output, where each token's representation is updated by giving more importance to the most relevant tokens in the input.
Step 11: Display the Results
Finally, the program displays:
Input embeddings
Query vectors
Key vectors
Value vectors
Attention scores
Scaled attention scores
Attention weights
Final attention output
