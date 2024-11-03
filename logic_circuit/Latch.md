# 래치에 대해 알아보자

### 1. def of Latch
1. Clk 신호를 받지 않는 기억소자
2. 출력 Q와 Q bar가 서로 다른 값을 가져야만 한다!

### 2. Setup Time & Hold time
1. Setup Time: 클록신호가 바뀌기 전까지 입력이 변화 없이 있어야 하는 시간
   -> 샘플링 전 올바르게 인식되었는지 확인이 필요한 시간
2. Hold Time: 클록신호가 바뀐 뒤에 입력이 변화 없이 있어야 하는 시간
   -> 샘플링 후 올바르게 인식되었는지 확인이 필요한 시간

### 3. 클록이 있는 latch
1. 이를 level sensitive latch라고도 한다
2. clk enable인 동안에는 연속적으로 입력 변화가 출력에 전달된다
3. 반대로 플립플랍은 clk에 따라서만 출력이 바뀐다 (posedge, negedge, master/slave)

### 4. 기억소자의 예
1. SR latch
2. Level sensitive SR latch
3. JK latch
4. Master/Slave FF
5. Edge-triggered FF
6. etc
