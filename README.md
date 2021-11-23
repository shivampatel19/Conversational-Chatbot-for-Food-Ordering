# ContextualSLU: Multi-Turn Spoken/Natural Language Understanding


*A Keras implementation of the models described in [Chen et al. (2016)] (https://www.csie.ntu.edu.tw/~yvchen/doc/IS16_ContextualSLU.pdf).*

This model implements a memory network architecture for multi-turn understanding, 
where the history utterances are encoded as vectors and stored into memory cells for the current utterance's attention to improve slot tagging.
