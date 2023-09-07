# DECO7381-Codenough

# Week 7 Snapshot

### Link for Trello board:

### https://trello.com/invite/b/kq2R14GD/ATTIb35c0f59cb16b88a35fa66e48371f49d647815FA/deco7381-weekly-journey

<img src="/images/trello.png" alt="Screenshot of the trello Board" title="Trello Board">

```
- Ruobing Wang
- Yushan Jiang
- Yiheng Wu
- Bosong Yu
- Zhiyuan Xiong
- Wang Zhang
```

In week 6, we assigned each member a task that goes through the whole project:

1. Use G29 to control the car (Physically mimics car movement, steering, acceleration, braking, etc.) - Wang
1. First-person perspective operation (Main responsibilities: first-person interface setting, steering wheel Angle as input, to ensure that the first person can successfully control the car and interface data interaction) - Yiheng
1. Vertigo operation (Main responsibilities: responsible for the vertigo effect of the screen, the change of operational attributes, as far as possible to imitate the real drunk driving human perspective). - Bosong
1. Scene construction (Main responsibilities: responsible for constructing roads, trees, and various scenes to ensure that objects can move successfully in the scene. - Eva (Yushan)
1. Obstacle setting and subsequent output (Main responsibility: make sure an object that hits an obstacle has an animation output and exits the game.) - Zhiyuan
1. User interface (Main responsibilities: UI interface, user interaction design. For example, users click different buttons to go to different interfaces, users click buttons to start any game and subsequent functions.) - Carrie (Ruobing)
1. Animation (Main responsibilities: Responsible for creating animations and scene designs that resonate with users.) - TBA

## In week 7 we have done so far:

## The primary <ins>UI menu </ins> has been completed below:

<img src="/images/UI.png" alt="The primary UI menu" title="UI basic">

## <ins>First-person perspective:</ins>

```
Simulate the G29 halfway through. The mirror effect on the car that right-hand driving got fixed
already. The future plan will be focused on car control and other relevant functions.

```

- Examined how to make the vehicle's kit change to right-hand drive.
  The Unity store sets are all left rudder, and there is no technique to recreate them. By taking the approach of mirroring the interior of the vehicle, the model is made to change to the right rudder.

- Bound the input actions to the animation of the steering wheel.
  Linking with the binding of G29 requires associating the input commands to the steering wheel animation as well as other operations.

### Future plan week 8:

If a new model was used, it would be beneficial to take the same approach to accomplish the same goal.

The script file needs to be modified to ensure proper functionality.

<img src="/image%20(1).png" alt="Screenshot of the trello Board" title="Trello Board">
<img src="/image.png" alt="Screenshot of the trello Board" title="Trello Board">

## <ins>Obstacles with collision have nearly been done </ins>

- We have completed the collision effect between objects
- Set the trigger when the object collision effect has feedback.

### Future Plan Week 8:
