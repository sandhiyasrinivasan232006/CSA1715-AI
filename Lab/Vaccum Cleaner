def vacuum_cleaner(room_status, current_location):
    print("Initial Room Status:", room_status)
    print("Starting Location:", current_location)
    print()

    while "Dirty" in room_status.values():

        if room_status[current_location] == "Dirty":
            print("Room", current_location, "is Dirty. Cleaning...")
            room_status[current_location] = "Clean"
            print("Room", current_location, "is now Clean.")

        else:
            print("Room", current_location, "is already Clean.")

      
        if current_location == "A":
            current_location = "B"
        else:
            current_location = "A"

        print("Moving to Room", current_location)
        print("Current Status:", room_status)
        print()

    print("All rooms are clean!")
    print("Final Room Status:", room_status)


rooms = {
    "A": "Dirty",
    "B": "Dirty"
}

vacuum_cleaner(rooms, "A")
