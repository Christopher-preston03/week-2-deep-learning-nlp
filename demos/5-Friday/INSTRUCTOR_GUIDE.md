# Friday: Transformers & Regularization - Instructor Guide

## Session Overview

**Topic**: Transformers & Regularization  
**Duration**: 2 hours  
**Style**: Quick, practical demos with minimal theory

---

## Session Timeline

| Time | Duration | Activity |
|------|----------|----------|
| 0:00 | 5 min | Quick intro |
| 0:05 | 20 min | Demo 1: Attention |
| 0:25 | 30 min | Demo 2: Build a Transformer |
| 0:55 | 5 min | Break |
| 1:00 | 20 min | Demo 3: Regularization |
| 1:20 | 30 min | Demo 4: Complete Example |
| 1:50 | 10 min | Week wrap-up |

---

## Demo 1: Attention (20 min)

**Key message**: Attention lets the model focus on relevant parts.

1. Run the script, show the bar chart
2. Point out: "sat" pays most attention to "cat" (the subject)
3. Show the 2-line Keras example
4. Emphasize: attention is interpretable!

**One-liner**: "Attention = learning which words matter for each word"

---

## Demo 2: Transformers (30 min)

**Key message**: Transformer = Embedding + Attention + Output

1. Show the simple 20-line model
2. Run training on IMDB
3. Point out: no RNNs, just attention!

**One-liner**: "This same pattern powers ChatGPT"

---

## Demo 3: Regularization (20 min)

**Key message**: Three techniques to prevent overfitting

1. Dropout: layers.Dropout(0.3)
2. L2: kernel_regularizer=l2(0.01)
3. Early Stopping: callbacks.EarlyStopping()

**One-liner**: "Use all three for production models"

---

## Demo 4: Complete Example (30 min)

**Key message**: Everything together

1. Walk through the complete model
2. Point out all the regularization
3. Show checkpointing and early stopping
4. Run training

**Final takeaway**: "You now have a production-ready template!"

---

## Files

- demo_01_attention_mechanism.py (110 lines)
- demo_02_transformer_architecture.py (120 lines)
- demo_03_regularization_techniques.py (130 lines)
- demo_04_putting_it_together.py (140 lines)
