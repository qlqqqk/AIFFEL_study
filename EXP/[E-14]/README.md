## 회고록
|model|loss_acc|piture|
|------|---|---|
|model_0|![](EX00_fashion_loss_accuracy.gif)|![](EX00_fashion_mnist_dcgan.gif)|
|model_1|![](EX01_fashion_loss_accuracy.gif)|![](EX01_fashion_mnist_dcgan.gif)|

(참고블로그: https://zzcojoa.tistory.com/88?category=1035878)
흥미로운 개념과 실제로 구현했을 때 나타나는 gif가 굉장히 신기했던 모델이었다. 
- vainilla model vs 개선된 모델
생성 이미지로 판단했을때 바닐라의 경우 단순 노이즈와 색조합으로만 보이고 실제 그래프에서는 fake acc와 real acc간의 차이가 발생하는 것으로 볼때 아직까지는 판별자가 구별이 가능한 것으로 보인다.  
개선 모델의 생성이미지는 상대적으로 깔끔했는데, loss,acc 그래프를 어떻게 해석해야할지 어려웠다. 
  1. loss에서 gen loss는 평균 4~5정도를 유지하는데 disc loss에서는 0에 거의 수렴하는 것으로 볼때 어느정도까지 gen loss가 낮아질 수 있는지 궁금했다.(어느정도가 적정선인지?)
  2. fake/real acc의 경우 바닐라와 다르게 그래프가 겹치는 모습을 많이 보여주었다. 판별자가 허구 이미지와 실제이미지를 분간하지 못하기 때문에 잘나오고있는 그래프인 것으로 판단했다.(해창님의 어시스트...)

