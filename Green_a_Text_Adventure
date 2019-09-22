player_energy = 10
rooms = [["sign"], [["light bulb"], "door"], ["strange slot", "block chain weapon", "door"], ["sign"]]

print("\nNarrator: You wake up in a jolt.\n")
print("Narrator: Your in an evil and dimly lit energy company's headquarters with 4 paths, a sign hangs above each "
      "one.\n")
print("Path 1: \"YE MUST BE OF GREAT GREEN WIT TO STAND THE TEST OF...\"")
print("Path 2: \"GREEN SHALL LIGHT THE WAY.\"")
print("Path 3: \"IF YE HAVE GREEN, YE ARE FREE.\"")
print("Path 4: \"GREEN WILL GUIDE YOU THROUGH...\"\n")
print("Narrator: Upon reading the signs you know what you must do, escape!\n")
print("Narrator: But be warned you only have a certain amount of energy to spend on moves.\n")
print("Narrator: Run out, and it's GAME OVER! Complete a puzzle and gain back energy!\n")
print("Narrator: You squeal (quite girlishly) in surprise as a sophisticated floating box shares in your situation.\n")
print("green: Whoa! Hey where are we!?\n")

name = input("green: More importantly who are you? ")

print("\ngreen: Oh Cool! sup " + name + " I'm green, a Proof of Power, blockchain-utilizing box of awesomeness!\n")
print("green: Huh, you haven't heard of me eh? I'll explain on the way, right now we gotta get outta here.\n")
print("green: I'll help you through this HQ and show you the freedom of green! (pay attention to my hints).\n")


def player_energy_deduct():
    global player_energy
    player_energy -= 1


def player_energy_addition():
    global player_energy
    player_energy += 2


player_action = input("Alright, where are we headed boss? (\"room 1\", \"room 2\", \"room 3\", \"room 4\") ")

# ----------------------------------------------------------------------------------------------------------------------

if player_action == "room 1":
    player_energy_deduct()
    print("\n" + str(player_energy))
    print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
    print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
    print("Narrator: green notices the only other object in the room, a plaque\n")
    print("green: Hey look " + name + ", a clue!\n")
    print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
    print("\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM I?\"\n")
    print("green: Hmm... ok, this is a good teaching moment...\n")
    # The first of it's kind. Green Box takes power directly from the grid and converts it to data.
    # This toaster sized device plugs directly into your home and can help to offset some of your energy expense.
    print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
    print("green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to data.\n")
    print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
    player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
    while player_action != "energy expenses":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
        player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
    print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
    player_energy_addition()
    player_action = input("Alright, where are we headed now? (\"room 2\", \"room 3\", \"room 4\") ")

    if player_action == "room 2":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb cutout.\n")
        player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
        if player_action == "open chest":
            print("Narrator: You found a bulb! And you...\"borrow it.\"")
            exit
        if player_action == "kick chest":
            print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
            print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
            print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
            exit
        print("green: " + name + " I think this is another teaching moment...\n")
        # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data, analytics,
        # and usage to power the Blockchain. It provides a provable process in which energy from the traditional power
        # grid or renewable sources can be inverted through the Proof of Power process, then stored, transferred,
        # and shared using Blockchain technology. In short, green™ is open source technology to power the
        # Blockchain.Through the Proof of Power process, the Green Blockchain provides a new way to effectively sell,
        # hold or share any energy production peer to peer.
        print("green: Let me tell you a little more about myself...\n")
        print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
        print("green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
              "to sell, hold or share ANY energy production peer to peer.\n")
        print("green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
              "here.\n")
        player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
        while player_action != "place bulb in cutout":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
        print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 3\", \"room 4\") ")

        if player_action == "room 3":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print("green: This is essentially the same as portable power which is delivered through the internet via "
                  "my blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")
            print("green: Sweet lets go!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 4\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                  "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")

        elif player_action == "room 4":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                  "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")
            print("green: YAY! Onwards!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 3\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print("green: This is essentially the same as portable power which is delivered through the internet via "
                  "my blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")

    elif player_action == "room 3":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
        print("green: Oh oh! I can help! I feel another lesson coming on!\n")
        # The most obvious use case for this technology is in providing power support to blockchains that use
        # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
        # portable power, delivered through the internet via the Green blockchain.
        print("green: Fun fact time: I am the first blockchain based battery tech!\n")
        print("green: This is essentially the same as portable power which is delivered through the internet via my "
              "blockchain!\n")
        player_action = input("green: May I help with this one? ")
        while player_action != "yes":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
            player_action = input("green: Please let me help you... (Just say yes) ")
        print("\nNarrator: green fuels the generator and opens the door!\n")
        print("green: Sweet lets go!")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 2\", \"room 4\") ")

        if player_action == "room 2":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 4\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")

        elif player_action == "room 4":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")
            print("green: YAY! Onwards!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 2\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")

    elif player_action == "room 4":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the wall.\n")
        print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
        print("green: You know, that's not a bad question... What are the benefits of green?\n")
        # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology will NOT
        # keep up with 21st century needs. It simply cannot.
        print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
        print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
              "and we need to implement that more.\n")
        # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to peer.
        print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
              "functionality. And with that said *Ahem* green is the best. \n")
        player_action = input("green: so " + name + " what's the answer to this riddle?")
        while player_action != "green is the best":
            player_energy_deduct()
            print("\n" + str(player_energy))
            player_action = input("\ngreen: Come on, try again. ")
        print("\nNarrator: The door bursts open!\n")
        print("green: YAY! Onwards!")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 2\", \"room 3\") ")

        if player_action == "room 2":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 3\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")

        elif player_action == "room 3":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")
            print("green: Sweet lets go!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 2\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")

# ----------------------------------------------------------------------------------------------------------------------

elif player_action == "room 2":
    player_energy_deduct()
    print("\n" + str(player_energy))
    print("\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb cutout.\n")
    player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
    if player_action == "open chest":
        print("Narrator: You found a bulb! And you...\"borrow it.\"")
        exit
    if player_action == "kick chest":
        print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
        print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
        print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
        exit
    print("green: " + name + " I think this is another teaching moment...\n")
    # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data, analytics,
    # and usage to power the Blockchain. It provides a provable process in which energy from the traditional power
    # grid or renewable sources can be inverted through the Proof of Power process, then stored, transferred,
    # and shared using Blockchain technology. In short, green™ is open source technology to power the
    # Blockchain.Through the Proof of Power process, the Green Blockchain provides a new way to effectively sell,
    # hold or share any energy production peer to peer.
    print("green: Let me tell you a little more about myself...\n")
    print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
    print("green: This means that through the Proof of Power protocol the green blockchain allows for a new way to "
          "sell, hold or share ANY energy production peer to peer.\n")
    print("green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta here.\n")
    player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
    while player_action != "place bulb in cutout":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
        player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
    print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
    player_energy_addition()
    player_action = input("Alright, where are we headed now? (\"room 1\", \"room 3\", \"room 4\") ")

    if player_action == "room 1":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
        print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
        print("Narrator: green notices the only other object in the room, a plaque\n")
        print("green: Hey look " + name + ", a clue!\n")
        print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
        print(
            "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM I?\"\n")
        print("green: Hmm... ok, this is a good teaching moment...\n")
        # The first of it's kind. Green Box takes power directly from the grid and converts it to data.
        # This toaster sized device plugs directly into your home and can help to offset some of your energy expense.
        print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
        print(
            "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to data.\n")
        print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
        player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
        while player_action != "energy expenses":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
        print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 3\", \"room 4\") ")

        if player_action == "room 3":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")
            print("green: Sweet lets go!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 4\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")

        elif player_action == "room 4":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")
            print("green: YAY! Onwards!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 3\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")

    elif player_action == "room 3":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
        print("green: Oh oh! I can help! I feel another lesson coming on!\n")
        # The most obvious use case for this technology is in providing power support to blockchains that use
        # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
        # portable power, delivered through the internet via the Green blockchain.
        print("green: Fun fact time: I am the first blockchain based battery tech!\n")
        print("green: This is essentially the same as portable power which is delivered through the internet via my "
              "blockchain!\n")
        player_action = input("green: May I help with this one? ")
        while player_action != "yes":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
            player_action = input("green: Please let me help you... (Just say yes) ")
        print("\nNarrator: green fuels the generator and opens the door!\n")
        print("green: Sweet lets go!")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 1\", \"room 4\") ")

        if player_action == "room 1":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
            print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 4\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")

        elif player_action == "room 4":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")
            print("green: YAY! Onwards!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 1\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")

    elif player_action == "room 4":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print(
            "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the wall.\n")
        print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
        print("green: You know, that's not a bad question... What are the benefits of green?\n")
        # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
        # will NOT keep up with 21st century needs. It simply cannot.
        print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
        print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
              "and we need to implement that more.\n")
        # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
        # peer.
        print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
              "functionality. And with that said *Ahem* green is the best. \n")
        player_action = input("green: so " + name + " what's the answer to this riddle?")
        while player_action != "green is the best":
            player_energy_deduct()
            print("\n" + str(player_energy))
            player_action = input("\ngreen: Come on, try again. ")
        print("\nNarrator: The door bursts open!\n")
        print("green: YAY! Onwards!")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 1\", \"room 3\") ")

        if player_action == "room 1":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
            print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 3\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")

        elif player_action == "room 3":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")
            print("green: Sweet lets go!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 1\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")

# ----------------------------------------------------------------------------------------------------------------------

elif player_action == "room 3":
    player_energy_deduct()
    print("\n" + str(player_energy))
    print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
    print("green: Oh oh! I can help! I feel another lesson coming on!\n")
    # The most obvious use case for this technology is in providing power support to blockchains that use
    # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
    # portable power, delivered through the internet via the Green blockchain.
    print("green: Fun fact time: I am the first blockchain based battery tech!\n")
    print("green: This is essentially the same as portable power which is delivered through the internet via my "
          "blockchain!\n")
    player_action = input("green: May I help with this one? ")
    while player_action != "yes":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
        player_action = input("green: Please let me help you... (Just say yes) ")
    print("\nNarrator: green fuels the generator and opens the door!\n")
    print("green: Sweet lets go!")
    player_energy_addition()
    player_action = input("Alright, where are we headed now? (\"room 1\", \"room 2\", \"room 4\") ")

    if player_action == "room 1":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
        print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
        print("Narrator: green notices the only other object in the room, a plaque\n")
        print("green: Hey look " + name + ", a clue!\n")
        print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
        print(
            "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
            "I?\"\n")
        print("green: Hmm... ok, this is a good teaching moment...\n")
        # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
        # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
        print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
        print(
            "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
            "data.\n")
        print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
        player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
        while player_action != "energy expenses":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
        print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 2\", \"room 4\" ) ")

        if player_action == "room 2":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 4\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")

        elif player_action == "room 4":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")
            print("green: YAY! Onwards!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 2\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            
    elif player_action == "room 2":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print(
            "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
            "cutout.\n")
        player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
        if player_action == "open chest":
            print("Narrator: You found a bulb! And you...\"borrow it.\"")
            exit
        if player_action == "kick chest":
            print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
            print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
            print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
            exit
        print("green: " + name + " I think this is another teaching moment...\n")
        # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
        # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
        # traditional power grid or renewable sources can be inverted through the Proof of Power process,
        # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
        # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
        # new way to effectively sell, hold or share any energy production peer to peer.
        print("green: Let me tell you a little more about myself...\n")
        print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
        print(
            "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
            "to sell, hold or share ANY energy production peer to peer.\n")
        print(
            "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
            "here.\n")
        player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
        while player_action != "place bulb in cutout":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
        print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 1\", \"room 4\") ")

        if player_action == "room 1":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
            print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 4\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")

        elif player_action == "room 4":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the "
                "wall.\n")
            print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
            print("green: You know, that's not a bad question... What are the benefits of green?\n")
            # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
            # will NOT keep up with 21st century needs. It simply cannot.
            print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
            print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
                  "and we need to implement that more.\n")
            # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
            # peer.
            print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
                  "functionality. And with that said *Ahem* green is the best. \n")
            player_action = input("green: so " + name + " what's the answer to this riddle?")
            while player_action != "green is the best":
                player_energy_deduct()
                print("\n" + str(player_energy))
                player_action = input("\ngreen: Come on, try again. ")
            print("\nNarrator: The door bursts open!\n")
            print("green: YAY! Onwards!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 1\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")

    elif player_action == "room 4":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print(
            "\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the wall.\n")
        print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
        print("green: You know, that's not a bad question... What are the benefits of green?\n")
        # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology
        # will NOT keep up with 21st century needs. It simply cannot.
        print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
        print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
              "and we need to implement that more.\n")
        # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to
        # peer.
        print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
              "functionality. And with that said *Ahem* green is the best. \n")
        player_action = input("green: so " + name + " what's the answer to this riddle?")
        while player_action != "green is the best":
            player_energy_deduct()
            print("\n" + str(player_energy))
            player_action = input("\ngreen: Come on, try again. ")
        print("\nNarrator: The door bursts open!\n")
        print("green: YAY! Onwards!")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 1\", \"room 2\") ")

        if player_action == "room 1":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
            print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 2\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            
        elif player_action == "room 2":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 1\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
            
# ----------------------------------------------------------------------------------------------------------------------

elif player_action == "room 4":
    player_energy_deduct()
    print("\n" + str(player_energy))
    print("\nNarrator: The 4th room is completely white and entirely empty except for a sign resting on the wall.\n")
    print("green: ok... The sign says \"WHY? WHY MUST YOU PERSIST IN YOUR ATTEMPT TO EXIT THIS PLACE?\n")
    print("green: You know, that's not a bad question... What are the benefits of green?\n")
    # In a wireless world, why is the power grid still like a “landline telephone” 19th century technology will NOT
    # keep up with 21st century needs. It simply cannot.
    print("green: There is massive innovation occurring everyday. So why do we still use power grids?\n")
    print("green: That's why ease of use and simplicity is a core consideration. We live in a wireless world, "
          "and we need to implement that more.\n")
    # Green and the Green Blockchain provide a new way to effectively capture, store and share energy peer to peer.
    print("green: In the end, I'm the future of energy, and my blockchain offers simplicity and innovative "
          "functionality. And with that said *Ahem* green is the best. \n")
    player_action = input("green: so " + name + " what's the answer to this riddle?")
    while player_action != "green is the best":
        player_energy_deduct()
        print("\n" + str(player_energy))
        player_action = input("\ngreen: Come on, try again. ")
    print("\nNarrator: The door bursts open!\n")
    print("green: YAY! Onwards!")
    player_energy_addition()
    player_action = input("Alright, where are we headed now? (\"room 1\", \"room 2\", \"room 3\") ")

    if player_action == "room 1":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
        print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
        print("Narrator: green notices the only other object in the room, a plaque\n")
        print("green: Hey look " + name + ", a clue!\n")
        print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
        print(
            "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
            "I?\"\n")
        print("green: Hmm... ok, this is a good teaching moment...\n")
        # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
        # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
        print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
        print(
            "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
            "data.\n")
        print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
        player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
        while player_action != "energy expenses":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
        print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 2\", \"room 3\") ")

        if player_action == "room 2":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 3\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")

    elif player_action == "room 3":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
        print("green: Oh oh! I can help! I feel another lesson coming on!\n")
        # The most obvious use case for this technology is in providing power support to blockchains that use
        # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
        # portable power, delivered through the internet via the Green blockchain.
        print("green: Fun fact time: I am the first blockchain based battery tech!\n")
        print("green: This is essentially the same as portable power which is delivered through the internet via my "
              "blockchain!\n")
        player_action = input("green: May I help with this one? ")
        while player_action != "yes":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
            player_action = input("green: Please let me help you... (Just say yes) ")
        print("\nNarrator: green fuels the generator and opens the door!\n")
        print("green: Sweet lets go!")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 2\") ")

        player_energy_deduct()
        print("\n" + str(player_energy))
        print(
            "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
            "cutout.\n")
        player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
        if player_action == "open chest":
            print("Narrator: You found a bulb! And you...\"borrow it.\"")
            exit
        if player_action == "kick chest":
            print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
            print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
            print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
            exit
        print("green: " + name + " I think this is another teaching moment...\n")
        # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
        # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
        # traditional power grid or renewable sources can be inverted through the Proof of Power process,
        # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
        # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
        # new way to effectively sell, hold or share any energy production peer to peer.
        print("green: Let me tell you a little more about myself...\n")
        print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
        print(
            "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
            "to sell, hold or share ANY energy production peer to peer.\n")
        print(
            "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
            "here.\n")
        player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
        while player_action != "place bulb in cutout":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
        print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
        
    elif player_action == "room 2":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print(
            "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
            "cutout.\n")
        player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
        if player_action == "open chest":
            print("Narrator: You found a bulb! And you...\"borrow it.\"")
            exit
        if player_action == "kick chest":
            print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
            print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
            print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
            exit
        print("green: " + name + " I think this is another teaching moment...\n")
        # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
        # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
        # traditional power grid or renewable sources can be inverted through the Proof of Power process,
        # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
        # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
        # new way to effectively sell, hold or share any energy production peer to peer.
        print("green: Let me tell you a little more about myself...\n")
        print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
        print(
            "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
            "to sell, hold or share ANY energy production peer to peer.\n")
        print(
            "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
            "here.\n")
        player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
        while player_action != "place bulb in cutout":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
        print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 1\", \"room 3\") ")

        if player_action == "room 1":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
            print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 3\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")


        elif player_action == "room 3":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
            print("green: Oh oh! I can help! I feel another lesson coming on!\n")
            # The most obvious use case for this technology is in providing power support to blockchains that use
            # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
            # portable power, delivered through the internet via the Green blockchain.
            print("green: Fun fact time: I am the first blockchain based battery tech!\n")
            print(
                "green: This is essentially the same as portable power which is delivered through the internet via my "
                "blockchain!\n")
            player_action = input("green: May I help with this one? ")
            while player_action != "yes":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
                player_action = input("green: Please let me help you... (Just say yes) ")
            print("\nNarrator: green fuels the generator and opens the door!\n")
            print("green: Sweet lets go!")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 1\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")

    elif player_action == "room 3":
        player_energy_deduct()
        print("\n" + str(player_energy))
        print("\nNarrator: You are now inside a security room. You see generator labeled \"blockchain\"\n")
        print("green: Oh oh! I can help! I feel another lesson coming on!\n")
        # The most obvious use case for this technology is in providing power support to blockchains that use
        # electricity, making green the first blockchain based battery technology. It’s basically the equivalent of
        # portable power, delivered through the internet via the Green blockchain.
        print("green: Fun fact time: I am the first blockchain based battery tech!\n")
        print("green: This is essentially the same as portable power which is delivered through the internet via my "
              "blockchain!\n")
        player_action = input("green: May I help with this one? ")
        while player_action != "yes":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\ngreen: Oh ok. I guess we'll just stay here for eternity then.\n")
            player_action = input("green: Please let me help you... (Just say yes) ")
        print("\nNarrator: green fuels the generator and opens the door!\n")
        print("green: Sweet lets go!")
        player_energy_addition()
        player_action = input("Alright, where are we headed now? (\"room 1\", \"room 2\") ")

        if player_action == "room 1":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
            print("\ngreen: Hey you're pretty smart " + name + "! On to the next room! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 2\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            
        elif player_action == "room 2":
            player_energy_deduct()
            print("\n" + str(player_energy))
            print(
                "\nNarrator: Upon entering this abandoned science lab you notice a chest and a door with a bulb "
                "cutout.\n")
            player_action = input("green: Ok... what should we do " + name + "? (\"open chest\", \"kick chest\") ")
            if player_action == "open chest":
                print("Narrator: You found a bulb! And you...\"borrow it.\"")
                exit
            if player_action == "kick chest":
                print("\nNarrator: Kicking the chest ultimately does nothing...Your foot is now in pain.\n")
                print("Narrator: But wait! The chest tips over and a bulb rolls out. You take the bulb.\n")
                print("Narrator: Your foot is still in pain though. Stupid solid state of matter.\n")
                exit
            print("green: " + name + " I think this is another teaching moment...\n")
            # green™ is the world's first "Proof of Power" Blockchain that directly connects power, energy data,
            # analytics, and usage to power the Blockchain. It provides a provable process in which energy from the
            # traditional power grid or renewable sources can be inverted through the Proof of Power process,
            # then stored, transferred, and shared using Blockchain technology. In short, green™ is open source
            # technology to power the Blockchain.Through the Proof of Power process, the Green Blockchain provides a
            # new way to effectively sell, hold or share any energy production peer to peer.
            print("green: Let me tell you a little more about myself...\n")
            print("green: I have the first ever \"Proof of Power\" Blockchain.\n")
            print(
                "green: This means that through the Proof of Power protocol the green blockchain allows for a new way "
                "to sell, hold or share ANY energy production peer to peer.\n")
            print(
                "green: ugh... It's getting kinda stuffy in here let's go. I'll tell you more as soon as we get outta "
                "here.\n")
            player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            while player_action != "place bulb in cutout":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: I didn't recognize that command. Maybe try \"place\" + \"thing\" + \"in thing\"\n")
                player_action = input("green: So " + name + ", what now? (Don't forget the bulb and the cutout) ")
            print("\ngreen: Whoa, nice going " + name + "! You opened the door! ")
            player_energy_addition()
            player_action = input("Alright, where are we headed now? (\"room 1\") ")

            player_energy_deduct()
            print("\n" + str(player_energy))
            print("\nNarrator: You enter a slightly brighter room with old computer stacks all along the walls.\n")
            print("Narrator: A peculiar jukebox playing terribly smooth jazz (utter torment) rests in the corner.\n")
            print("Narrator: green notices the only other object in the room, a plaque\n")
            print("green: Hey look " + name + ", a clue!\n")
            print("green: The plaque says \"IF YE BE RIGHTEOUS THEN ANSWER ME THIS...\"\n")
            print(
                "\"I AM OFTEN TIMES A MONETARY BURDEN BUT MAY BE MITIGATED BY THE USE OF SMART TECHNOLOGY. WHAT AM "
                "I?\"\n")
            print("green: Hmm... ok, this is a good teaching moment...\n")
            # The first of it's kind. Green Box takes power directly from the grid and converts it to data. This
            # toaster sized device plugs directly into your home and can help to offset some of your energy expense.
            print("green: So how do I work? Well, one of my jobs is to convert power to actual data.\n")
            print(
                "green: Just like a computer takes data and changes it to 1s and 0s, I take power and convert it to "
                "data.\n")
            print("green: This makes me pretty unique and allows me to help alleviate some *Ahem* energy expenses.\n")
            player_action = input("green: So " + name + ", what do you think the answer to the riddle is huh? ")
            while player_action != "energy expenses":
                player_energy_deduct()
                print("\n" + str(player_energy))
                print("\ngreen: Dang that wasn't right, don't worry you got this. Try again.\n")
                player_action = input("green: So " + name + ", what do you think the answer to the riddle is? ")
                
# ----------------------------------------------------------------------------------------------------------------------
