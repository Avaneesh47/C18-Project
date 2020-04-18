# C18-Project

List of Bugs
Bug1 : Trex not colliding with ground
Code fix:trex.collide(invisibleGround);

Bug2:Reset function missing when mouse presses over restart icon
Code Fix:if(mousePressedOver(restart)) {
       reset();
    }
    
Bug 3:Obstacles and clouds kept on moving in end state as well
Code Fix:obstaclesGroup.setVelocityXEach(0);
         cloudsGroup.setVelocityXEach(0);
