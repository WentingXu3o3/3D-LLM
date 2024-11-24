# 3D-LLM
related work for LLMs in 3D scene understanding

### 1. TransRefer3D: Entity-and-Relation Aware Transformer for Fine-Grained 3D Visual Grounding 
_MM2021 Beihang Uni, Chinese Academy of Sciences_
- the first group to exploit Transformer to achieve a better cross-modal feature representation for the 3D visual grounding task
- proposes a TransRefer3D network to extract entity-and-relation-aware multimodal context among objects
- devises an Entity-aware Attention (EA) module matching between object features and linguistic entity features via con-attention
- and a Relaiton-aware Attention (RA) module to first extract visual relation features of object-object pairs via an asymmetric operator
- performs cross-modal attention between visual relation features and linguistic relation features
