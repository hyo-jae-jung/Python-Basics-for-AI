<h1>BoostCamp AI Tech 3rd Pre-Course</h1>

<h3>python</h3>

파이썬 더블 언더스코어: Magic Method
https://corikachu.github.io/articles/python/python-magic-method

New Module : 
tqdm
time

<h5>file</h5>
binary/text


<h3>math</h3>

<h5>vector</h5>

norm
L1 : 벡터들의 절대값 합
L2 : 피타고라스 공식을 이용한 벡터들의 유클리드 합

L1, L2 머신러닝에서 용도에 맞게 사용됨

L2만 벡터들의 각도를 구할 수 있음

cos(theta) = x,y의 내적 / ||x|| * ||y||

정사영은 한 벡터를 다른 벡터로 수직으로 빛을 쐈을 때 나오는 그림자의 길이인데 여기에 다른 벡터의 절대값을 곱해주면 내적의 값이 된다.
내적은 두 벡터의 유사도를 측정 할 때 사용되기도 한다.

<h5>matrix</h5>

np.inner(X,Y) : X,Y^t의 내적
np.linalg.inv(X) : X의 역행렬
np.linalg.pinv(X) : X의 유사역행렬 or 무어 펜로즈 역행렬

<h5>Gradient descent</h5>

sympy.diff로 미분 가능

그레디언트 벡터(gradient vector)