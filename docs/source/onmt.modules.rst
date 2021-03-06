Doc: Modules
=============

Core Modules
------------

.. autoclass:: onmt.modules.Embeddings
    :members:



Encoders
---------

.. autoclass:: onmt.modules.EncoderBase
    :members:


.. autoclass:: onmt.modules.MeanEncoder
    :members:

.. autoclass:: onmt.modules.RNNEncoder
    :members:


Decoders
---------


.. autoclass:: onmt.modules.RNNDecoderBase
    :members:


.. autoclass:: onmt.modules.StdRNNDecoder
    :members:


.. autoclass:: onmt.modules.InputFeedRNNDecoder
    :members:

Attention
----------

.. autoclass:: onmt.modules.GlobalAttention
    :members:



Architecture: Transfomer
----------------------------


.. autoclass:: onmt.modules.TransformerEncoder
    :members:

.. autoclass:: onmt.modules.TransformerDecoder
    :members:


Architecture: Conv2Conv
----------------------------

.. autoclass:: onmt.modules.CNNEncoder
    :members:

.. autoclass:: onmt.modules.CNNDecoder
    :members:

Architecture: SRU
----------------------------

.. autoclass:: onmt.modules.SRU
    :members:


Alternative Encoders
--------------------

onmt\.modules\.AudioEncoder


.. autoclass:: onmt.modules.AudioEncoder
    :members:


onmt\.modules\.ImageEncoder


.. autoclass:: onmt.modules.ImageEncoder
    :members:


Extensions
----------

.. autoclass:: onmt.modules.CopyGenerator
    :members:
    :undoc-members:

.. autoclass:: onmt.modules.CopyGeneratorLossCompute
    :members:
    :undoc-members:


.. autoclass:: onmt.modules.ContextGate
    :members:
    :undoc-members:


Alternative Attention: Multi Headed
-----------------------------------

.. autoclass:: onmt.modules.MultiHeadedAttention
    :members:
    :undoc-members:


Alternative Attention: Structured Attention
-------------------------------------------

.. autoclass:: onmt.modules.MatrixTree
    :members:
    :undoc-members:




.. automodule:: onmt.modules.WeightNorm
    :members:
    :undoc-members:
    :show-inheritance:
