# FCNN-MNIST

Fully Connected Neural Network

Fully Connected란 하나의 layer의 모든 뉴런들이 다음 layer의 모든 뉴런들과 연결되어 있는 상태이다.

# 구현

1. 필요한 모듈들을 설치해준다.
2. train_data와 test_data를 다운받는다.(train_data는 data폴더에 test_data는 test 폴더에 저장된다.)
3. batch size를 정해서 train_loader와 test_loader 생성한다.
4. model을 구현한다.
5. model 구현시 고려사항들을 정한 후 매 epoch, 매 iteration마다 back-propagation을 통해서 모델의 파라미터를 업데이트한다.
6. model을 학습시킨다.
7. model을 test 한다. 



# model 구현시 고려사항

1. 어떤 loss를 사용할지
2. 어떤 optimizer를 사용할지
3. 학습 횟수는 몇번으로 할 지
4. learning rate는 몇으로 할 지
