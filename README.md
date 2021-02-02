# 'Neural Machine Translation for Indian Languages [english Hindi]'

```
class NeuralNetwork:
    def __init__(self, x, y):
        self.input      = x
        self.weights1   = np.random.rand(self.input.shape[1],4)
        self.weights2   = np.random.rand(4,1)
        self.y          = y
        self.output     = np.zeros(y.shape)
```
` https://gist.github.com/jamesloyys/796ad704748174da94e313097042e04c#file-neural_network_init-py `
