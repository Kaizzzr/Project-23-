# Project-23-
FIrst Public Repository 

    def main():
        Project_23 = []

        while True:
             Kumails_next_move  = input("Kumails_next_move: ")

                 if  Kumails_next_move  == "undo":
                     undone = Project_23.pop()
                     print(f"undone {undone}")
                elif  Kumails_next_move  == "restart":
                     Project_23.clear()
                     print("Project_23 cleared")
                else:
                     Project_23.append(Kumails_next_move )
                     print(Project_23)

    main()
