# model-evaluation-toolbox
CheatSheet for Simple, Pretty and Interactive Model Evaluation.

## Design Rule of CheatSheet
- 모든 기능은 하나의 함수로 만든다. input은 sklearn 스타일로 만든다.
    - [input] y_true, y_pred
    - [output] dict
- plotly 또는 bokeh를 활용하여 interactive한 시각화를 한다.
- 함수 내부의 연산은 최대한 numpy를 활용하여 최적화를 하고, return value는 pandas로 변환하기 쉽게 만들어준다.
- hard-coding을 주저하지 말자.