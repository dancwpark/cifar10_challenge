# Tasks

## Update train.py
- [ ] Update tf.contrib.layers.batch_normalization in `model.py`
  * ISSUE: alternative tf.keras.layers.BatchNormalization does not include
    some keywords, such as decay.
  * Possible Solution: Use tensorflow-addons
    * ISSUE: No conda support (only pip)
  * Possible Solution: Write custom BatchNormalization layer or wrapper 
    for decay and missing keywords.

## Update pgd_attack.py

## Update model.py
- [ ] xref to update needed in train.py -> issue 1

## Update run_attack.py

## Update eval.py