# Case1

def stop_light(color):
    match color:

        case "red":
            return "STOP"
        case "green":
            return "GO"
        case "yellow":
            return "Slow Down"
        case _:
            return "NOT VALID"
        
input1 = input("Please pick a color:")
print(stop_light(input1))
