# Concurrent-traffic-simulation_L2(From Udacity)

![Image](https://github.com/wadeld123/Concurrent-traffic-simulation_L2/raw/master/Image.png) 


# Project Tasks

    Task L2.1 : In method Vehicle::drive(), start up a task using std::async which takes a reference to the method Intersection::addVehicleToQueue, the object _currDestination and a shared pointer to this using the get_shared_this() function. Then, wait for the data to be available before proceeding to slow down.

    Task L2.2 : In method Intersection::addVehicleToQueue(), add the new vehicle to the waiting line by creating a promise, a corresponding future and then adding both to _waitingVehicles. Then wait until the vehicle has been granted entry.

    Task L2.3 : In method WaitingVehicles::permitEntryToFirstInQueue(), get the entries from the front of _promises and _vehicles. Then, fulfill promise and send signal back that permission to enter has been granted. Finally, remove the front elements from both queues.

