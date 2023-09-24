# Notes
### Batch Size
모델 학습 중 parameter를 업데이트할 때, 사용할 데이터 개수를 의미한다. 예를 들어, 총 100개의 문제가 있을 때, 20개씩 풀고 채점한다면 Batch Size는 20이다.

### Iteration
전체 데이터에 대해 총 Batch의 수를 의미한다. Step이라고 부르기도 한다. 예를 들어, Batch Size가 300이고 전체 Dataset의 개수가 3,000이라면, 전체 데이터셋을 학습시키기 위해서는 총 10개의 Batch가 필요하다. 즉, Iteration의 수는 10이다.

### Epoch
전체 데이터셋을 학습한 횟수를 의미한다. 예를 들어, 문제집 한 권 전체를 1번 푼 사람, 3번, 5번 푼 사람이 있다. Epoch는 이처럼 문제집 한 권을 몇 회 풀었는지를 의미한다.

### Overfitting (과대적합)
모델이 훈련 데이터의 특수한 성질을 과하게 학습해 일반화를 못해 결국 테스트 데이터에서 오차가 커지는 현상

### Underfitting (과소적합)
훈련 데이터에 과적합도 못하고 일반화 성질도 학습하지 못해 훈련/테스트 데이터 모두 오차가 크게 나오는 경우