This page will show my personal understanding about Google's Nerual Machine Translation model ["Transformer"](https://arxiv.org/abs/1706.03762) 

Most Machine Translation models use the sequence-to-sequence (or Encoder-Decoder) structure, where the encoder maps an input sequence of $(x_1, x_2, ..., x_n)$ to a representation z = (z_1, z_2,..., z_n). The decoder then will generate the output sequence (y_1,..., y_m) based on the representation z.
