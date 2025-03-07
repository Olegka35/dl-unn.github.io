# Results of Task 2

| Name                                                               | Test accuracy, %  | NN architecture|
|--------------------------------------------------------------------|-------------------|----------------|
| Alexey Sidnev (example)                                            |       59.2        | 1. Conv2D(3x3, ReLU, stride=2, out=20)<br>2. Conv2D(3x3, ReLU, stride=2, out=40)<br>3. Conv2D(3x3, ReLU, stride=2, out=80)<br>4. Fully connected (out=10)<br>5. Softmax 
| Batanina Liubov                                                    |       66.75       | 1. Conv2D(3x3, ReLU, padding="same", stride=1, out=32)<br>2. MaxPooling(2x2, stride=2)<br>3. BatchNormalization()<br>4. Conv2D(3x3, ReLU, padding="same", stride=1, out=64)<br>5. MaxPooling(2x2, stride=2)<br>6. BatchNormalization()<br>7. Conv2D(3x3, ReLU, padding="same", stride=1, out=128)<br>8. MaxPooling(2x2, stride=2)<br>9. BatchNormalization()<br>10. Flatten()<br>11. Fully connected(ReLU, out=128)<br>12. Dropout(0.1)<br>13. Fully connected (out=10)<br>14. Softmax
| Krasikova Ekaterina                                                |       62.92       | 1. Conv2D(3x3, ReLU, stride=1, out=8)<br>2. Conv2D(3x3, ReLU, stride=1, out=16)<br>3. MaxPool(2x2)<br>4. Conv2D(3x3, ReLU, stride=1, out=32)<br>5. Conv2D(3x3, ReLU, stride=1, out=32)<br>6. MaxPool(2x2)<br>7. Fully connected (out=400)<br>8. Fully connected (out=10)<br>9. Softmax              |
| Okunev Boris                                                       |                   |                |
| Zinoviev Vladimir                                                  |                   |                |
| Panova Elena                                                       |                   |                |
| Kuznetsov Vladislav                                                |       59.66       | 1. Fully connected (out=700), ReLU<br>2. Fully connected (out=300), ReLU<br>3. Fully connected (out=10)<br>4. Softmax           |
| Degtyarev Anton                                                    |       53.44       | 1. Flatten()<br>2. FullyConnected(units=1024), Elu<br>3. FullyConnected(units=512), Elu<br>4. FullyConnected(units=10)<br>5. Softmax               |
| Rodionov Fedor                                                     |       49.5        | 1. Fully connected (out=256), ReLU <br>2. Fully connected (out=64), ReLU <br>3. Fully connected (out=10), ReLU <br>4. Softmax        |
| Panov Aleksandr                                                    |                   |                |
| Senyaev Andrey                                                     |                   |                |
| Kamelina Julia                                                     |       61.24       | 1. Conv2D(5x5, ReLU, stride=1, out=8)<br>2. MaxPooling(2x2, stride=2)<br>3. Conv2D(3x3, ReLU, stride=1, out=16)<br>4. MaxPooling(2x2, stride=2)<br>5. Fully connected(ReLU, out=288)<br>6. Fully connected(ReLU, out=10)<br>7. Softmax |
| Protas Maria                                                       |       49.58       | 1. Fully Connected (ReLU, out=100) <br>2. Fully Connected (ReLU, out=30) <br>3. Fully Connected (out=10) <br>4. Softmax                |
| Romanov Alexander                                                  |       52.18       | 1. Fully connected (ReLU, out=250)<br>2. Fully connected (ReLU, out=100)<br>3. Fully connected (ReLU, out=10)<br> 4. Softmax |
| Kuznetsov Konstantin                                               |       53.37       | 1. Conv2D(3x3, ReLU, stride=1, out=16)<br>2. MaxPool(2x2)<br>3. Conv2D(3x3, ReLU, stride=1, out=16)<br>4. MaxPool(2x2)<br>5. Flatten()<br>6. Dense(ReLU, out=100)<br>7. Dense(ReLU, out=10)<br>8. Softmax |
| Tarasov Oleg                                                       |       46.99       | 1. Fully connected (input=1024, output=512)<br>2. ReLU<br>3. Fully connected (input=512, output=256)<br>4. ReLU<br>5. Fully connected (input=256, output=10)<br>6. Softmax|
| Mayachkin Arseny                                                   |                   |                |
| Usova Marina                                                       |                   |                |
| Shkenev Petr                                                       |                   |                |
| Daniil Roman                                                       |                   |                |
| Gribov Pavel                                                       |                   |                |
| Tarakanov Kirill                                                   |                   |                |
| Tarakanov Kirill                                                   |       54.79       | 1. Fully connected(out=256, activation=sigmoid)<br>2. Fully connected(out=128, activation=sigmoid)<br>3. Fully connected (out=10)<br>4. Softmax
| Gladyshev Alexey                                                   |       67.53       | 1. Conv2D(3x3, ReLU, stride=1, out=64)<br>2. MaxPool(2x2, stride=1)<br>3. BatchNormalization()<br>4.Conv2D(3x3, ReLU, stride=1, out=128)<br>5. MaxPool(2x2, stride=1)<br>6. BatchNormalization()<br>7. Conv2D(3x3, ReLU, stride=1, out=256)<br>8. MaxPool(2x2, stride=1)<br>9. BatchNormalization()<br>10. Flatten()<br>11. Dense(ReLU, out=128)<br>12. Dropout(0.7)<br>13. BatchNormalization()<br>14. Dense(ReLU, out=512)<br>15. Dropout(0.7)<br>16. BatchNormalization()<br>17. Dense(ReLU, out=1024)<br>18. Dropout(0.7)<br>19. BatchNormalization()<br>20. Softmax() |
| Nechesanov Vladimir                                                |       45.70       | DenseLayer (3072, 100) -> Sigmoid() -> DenseLayer (100, 200) -> Sigmoid() -> DenseLayer (200, 100) -> Sigmoid() -> DenseLayer(100, 10)                |
| Ananiev Semyon                                                     |                   |                |
| Generalov Alexander                                                |                   |                |
| Trifonov Alexander                                                 |                   |                |
| Shutina Svetlana                                                   |                   |                |
| Kuznetsov Victor                                                   |       45.18       | 1. Fully connected (out=1100), ReLU <br>2. Fully connected (out=1100), ReLU <br>3. Fully connected (out=10), ReLU <br>4. Softmax
| Israfilov Marat                                                    |       51.02       | 1. Fully connected (ReLU, out=1024)<br>2. Fully connected (ReLU, out=512)<br>3. Fully connected (ReLU, out=256)<br>4. Fully connected (out=10)<br>5. Softmax
| Kulikova Svetlana                                                  |       63.33       | 1. Conv2D(5x5, ReLU, stride=1, out=32)<br>2. BatchNormalization()<br>3. MaxPooling(2x2, stride=2)<br>4. Conv2D(5x5, ReLU, stride=1, out=64)<br>5. BatchNormalization()<br>6. MaxPooling(2x2, stride=2)<br>7. Conv2D(5x5, ReLU, stride=1, out=128)<br>8. Flatten()<br>9. Dense(ReLU, out=92)<br>10. Dense(out=10)<br>11. Softmax
