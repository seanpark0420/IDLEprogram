텐서플로우를 실행하기 위해 여러가지를 해보았다.
이때 가장 큰 문제점으로는 cmd에서 실행하는 것이었다
그래서 anaconda prompt에서 실행해야 정상적인 다운로드와 실행을 할 수 있다.
또한 실행할 때 관리자 권한으로 실행해야한다.
그래야 텐서플로우가 제대로 실행하는 것을 알았다.
텐서플로우 실행 방법은
conda create -n tensorflow python=3.8.3
activate tensorflow
