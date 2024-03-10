# Student Layer Intialization

Submitted by: Sunil Prajapati (st124073)


## Documentation

### Model Comparison and Evaluation

Following are the loss and accuracy acheived for each model with followin student layer initialization during training for 3 epochhs

| Student Layer | Training Loss | Validation Loss | Validation Accuracy|
|-|-|-|-|
|Top-k Layer| 0.2813 |  0.8237 | 0.6550     |
|Bottom-k Layer| 0.2711 | 0.8237 | 0.6550     |
|Odd Layer| 0.6985 | 0.8237 | 0.6550     |
|Bottom Layer| 0.6985 | 0.8237 | 0.6550     |

From the above table, it is evident that the different intialization did ot produce any different results in a significant way. The validation loss and accuracy remained same for all models. The only remarkable difference was acheived in training loss where it was same for odd layer model and bottom layer model but achieved lower loss for top-k layer model and bottom-l layer model with Bottom-K layer model producing the lowest loss with 0.2711.


### Challenges and Recommendations

Due to limit of the CPU, the experiment was kept to minimal but the significant results might be obtainable with more effective experiments. 
