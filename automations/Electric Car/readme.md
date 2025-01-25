## Use Case

I have a Tesla Model 3 and use Octopus Energy as my energy supplier. 

When plugging the car in, sometimes I noticed it can take up to 15 minutes for the intelligent dispatching to be scheduled. This meant that up to 15 minutes per day I would pay full price at £0.26Kwh on 32A which adds up over 30 days. 

This automation triggers when the car begins to charge OR when octopus confirm that a bump charge has begun (conditionally checks that the car is in zone.home). 

The charge rate is then set to 6A by default, and this will wait up to 15 minutes for either the ```bump charge``` or ```intelligent dispatching``` to switch to on and then set the amperage to be 32A. 

If it's not triggered, then it will still check manually that the bump charge or intelligent dispatching is on and if they're not on it will set back to 6A. 


## Prerequisites 

- [HomeAssistant-OctopusEnergy](https://github.com/BottlecapDave/HomeAssistant-OctopusEnergy) - Direct link to energy supplier
- [Tessie](https://www.home-assistant.io/integrations/tessie) - To communicate with the car.



## Notes 

This will not affect any other charges not related to the ```zone.home```.

You do not have to use the above prerequisites, aslong as your integrations offer something of the equivalent then this can still work for you.
