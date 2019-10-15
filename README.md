# neural-network

# What is the Difference Between a Batch and an Epoch in a Neural Network?
https://machinelearningmastery.com/difference-between-a-batch-and-an-epoch/

```
for(i=1;i<=Epoch_Size;i++)
{
  for(j=1;j<=Number_Of_Samples_Of_Training_Dataset;j++)
    if(j%Batch_Size==0)
    {
      # Model Update.........
    }
}
```
