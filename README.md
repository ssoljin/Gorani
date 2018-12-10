# hohohoho
switch는 전원을 의미하는 input입니다. 이는 전부 d-ff의 clear부분에 연결되어 입력 값이 0이 입력되는 경우 다른 input들의 입력 값과 관계 없이 0으로 reset 됩니다. 
Arm,thigh,leg,foot은 각각 input으로 d-ff에 의해 입력 값이 출력 값으로 바로 전달됩니다.
Clock은 시간을 나타내는 input입니다. 각 d-ff에 하나의 clock이 연결되어 시간을 공유하기 때문에 delay에 따른 오류가 발생하지 않습니다. 
Arm1,thigh1,leg1,foot1은 각각 output으로 d-ff에 의해 저장된 값을 출력합니다.

