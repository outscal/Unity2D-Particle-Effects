# How to use Particle Systems in Unity

- In the hierarchy window, **Right Click > Effects > Particle System**.
- By using the Move tool, you can move it anywhere in the scene you want to place it. You can Scale it, Rotate it, you can use almost all the tools according to the game requirement.
- In the Inspector Window, you can see the Particle System component. Play around with all the values to get your hands dirty.
- If you want to make your own particle effects, you have to use some other third-party tools like photoshop, ms paint to make the sprite, and then import it in Unity.

To import, in the Particle System component in the Inspector, go to **Renderer > Material.**

Select the Sprite Default Material
        

![Sprite Default](./Image/sprite_Default.png)

        
    
Then, select **Texture Sheet Animation.** Change the **Mode** from **Grid to Sprites.**

After that, click “None (Object)” below the Mode. Select the sprite that you have created or imported in Unity and you’re good to go.
        


![Particle System Component](./Image/particle_system_component.png)
        


![Particles in Unity](./Image/particles.png)



This one's pretty short so let's move on quickly
