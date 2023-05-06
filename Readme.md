# **This is my playlist**
#### This is my playlist
##### _This is my playlist_


---
- this is a bullet point
* this is a bullet point
---

This code import the `DL` Classifier

```python
# Loop over all the combinations of optimizers, learning rates, batch sizes, and number of output layers
for optimizer_name, optimizer in optimizer_dict.items():
    for num_layers in num_output_layers:
        # Add the output layers
        if num_layers == 1:
            output1 = Dense(train_generator.num_classes, activation='softmax')(x)
            outputs = [output1]
        elif num_layers == 2:
            x = Dense(1024, activation='relu')(x)
            output1 = Dense(train_generator.num_classes, activation='softmax')(x)

```


## [Banana Ripeness Classifier](https://github.com/ktchan33GBC/Banana-Ripeness-Classifier/tree/main/Backend)
---

![Image Link](https://github.com/ktchan33GBC/Banana-Ripeness-Classifier/blob/main/Image/UX_customer_journey.png)

---

![Demo](https://github.com/ktchan33GBC/Banana-Ripeness-Classifier/blob/main/Image/underriped_HD.gif)

