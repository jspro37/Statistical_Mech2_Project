# Statistical_Mech2_Project

본 프로젝트는 2024학년도 2학기 통계물리학(Statistical Mechanics II) 기말 과제로 수행되었습니다. 통계물리에 적용되는 여러 이론과 모델을 심도 있게 학습한 후, 관련 연구 논문을 리뷰(review)하고 주요 결과를 재현(reproduce)하여 발표하는 형식으로 구성되었습니다.

이번 연구에서는 공개된 축구 경기 데이터를 활용해 **패스 네트워크 맵(pass map)**을 구현하였으며, 네트워크 이론과 축구 경기 분석을 결합한 Ming-Xia Li 등(2025)의 논문  
“Motive Analysis and Passing Behavior in Football Passing Networks”  
를 재현해 보았습니다. 이를 통해 실제 경기 데이터를 기반으로 모티프 분석(motif analysis)과 패스 행동(passing behavior)에 대한 통계적 유의성을 검증하고, 네트워크 지표의 실용적 가치를 탐구하였습니다.

자세한 코드와 내용 요약은 Statistical Mech2 project.ipynb&통계물리 Final Project 최종본.pptx 를 참고하면 됩니다.
 Statistical Mech2 project.ipynb 코드의 In:[18] 까지가 아래 참고한 Github 링크의 코드이고, 그 이후에는 직접 작성한 코드 입니다.

- **참고문헌**  
  Li, M.-X., Xu, L.-G., & Zhou, W.-X. (2025). Motif analysis and passing behavior in football passing networks. *Chaos, Solitons & Fractals.*  
- **논문 요약**  
  3199경기의 축구 패스 데이터를 분석하여 3-노드 모티프의 빈도와 구조를 비교한 결과, 홈팀의 패스 효율이 원정팀보다 높고 양방향 패스 모티프가 공격 성과와 강한 상관관계를 보였으며, 직진성 패스 구조는 득점 차를 긍정적으로 확대하는 반면 패스백이 잦을수록 공격 성공 확률이 낮아짐을 밝혔다.
- **데이터 및 코드**  
  [GitHub 저장소](https://github.com/hadjdeh/football-data-analysis)
-> 23-24 프리미어 리그의 첼시와 맨체스터 시티의 경기 데이터 + 해당 데이터를 패스맵으로 시각화 하는 예시 코드
