def find_distance():
    speed=float(input("Enter the speed of the vehicle: "))
    time=float(input("Enter the time of the vehicle: "))
    distance=speed*time
    return distance
result=find_distance()
print(f'Distance is: {result}')
