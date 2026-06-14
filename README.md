# Awesome-BERT
## BERT Model Variants Ecosystem

Since its release, BERT has evolved into a diverse ecosystem of models optimized for performance, efficiency, architectural upgrades, and domain specialization.

## 🚀 Performance & Training Enhancements
* **RoBERTa** (Robustly Optimized BERT Approach): Drops the Next Sentence Prediction (NSP) task, uses larger batch sizes, and trains on 10× more data to beat base BERT accuracy.
* **DeBERTa** (Disentangled Attention BERT): Represents words using separate content and position vectors, yielding higher accuracy on benchmark tasks.
* **SpanBERT**: Optimizes question answering and text extraction by masking continuous spans of words instead of random single tokens.

## ⚡ Efficiency & Speed
* **DistilBERT**: Uses knowledge distillation to create a model that is 40% smaller and 60% faster while retaining 97% of BERT's language understanding.
* **ALBERT** (A Lite BERT): Reduces memory footprint by sharing parameters across layers and factorizing embedding layers.
* **TinyBERT**: A heavily distilled, hyper-compact variant engineered specifically for deployment on mobile and edge devices.

## 🏗️ Architectural Advancements
* **ELECTRA**: Replaces masking with a "replaced token detection" objective, using a discriminator network to train faster and use less compute.
* **ModernBERT**: Integrates hardware-friendly architectural upgrades directly into the encoder layer for faster processing.
* **NeoBERT**: Overcomes the original 512-token bottleneck by using a two-stage training approach to native 4096 long-context windows.

## 🧪 Domain & Language Specialization
* **BioBERT**: Pre-trained on biomedical corpora (PubMed) for specialized healthcare text mining and entity extraction.
* **SciBERT**: Trained on millions of computer science and broad scientific papers to parse academic literature.
* **mBERT** (Multilingual BERT): Pre-trained on Wikipedia text across 104 languages to facilitate zero-shot cross-lingual transfer.

## 📈 Star History

<div align="center">
   <a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-BERT&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-BERT&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-BERT&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-BERT&type=date&legend=bottom-right" />
    </picture>
   </a>
</div>
