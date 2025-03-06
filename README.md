# rl-mujoco-tennis

## Humanoid-v5
![](/Images/sac_humanoid.gif)

## Ball Balance
![](/Images/sac_ball_balance.gif)

## Ball Bounce
![](/Images/sac_ball_bounce.gif)

## Wall Ball
![](/Images/sac_wall_ball.gif)

## Results
Hardware: Google Colab T4

| Simulation Type | Model Type | Average Reward | Training Time | Total Training Steps |
|-----------------|------------|----------------|---------------|----------------------|
| Humanoid-v5     | PPO        |                |               |                      |
| Humanoid-v5     | SAC        | 6579.66        | 4:41:52       | 3,800,000            |
| Ball Balance    | PPO        | 751            | 1:58:54       | 2,000,000            |
| Ball Balance    | SAC        | 751            | 1:52:23       | 2,000,000            |
| Ball Bounce     | PPO        |                |               |                      |
| Ball Bounce     | SAC        | 7.50           | 1:53:48       | 2,000,000            |
| WallBall-v1     | SAC        |                |               |                      |
| WallBall-v1     | PPO        |                |               |                      |
| TennisWall-v1   | PPO        |                |               |                      |
| TennisWall-v1   | PPO        |                |               |                      |
