# MG6
1.If you write a for loop inside an Update, I think that the loop will finish before the Update. I think that the way it's set up, it is made to prioritze the loop allowing it to complete. Once the loop finishes, it runs the rest of the code. If you write a for loop that takes a long time, there will be lag because it needs to process plenty of things that will pop up. Since the loop is being prioritized to finish, the game will lag if its a heavy for loop. 

2.The way the logic is set, I'm able to go through the platforms from underneath since if the cat moves up, the if statement with _rigidbody becomes true which disables the collider. The main issue then becomes that not only will the cat phase through the platform but through the walls as well. When I controlled the cat I would sometimes phase out of the game because the collider was false. The code allows this since Update() makes it run each time. Anytime the cat phases through something, it's because the collider is false. 

https://pearl-carp.itch.io/mg6

