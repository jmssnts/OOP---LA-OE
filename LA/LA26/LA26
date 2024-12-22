#LA 26

#turtles.py

from abc import ABC, abstractmethod



class NinjaTurtle(ABC):

    @property

    @abstractmethod

    def name(self):

        pass



class Leonardo(NinjaTurtle):

    def __init__(self, alias):

        self.__alias = alias



    @property

    def name(self):

        return self.__alias        



class Michealangelo(NinjaTurtle):

    def __init__(self, alias):

        self.__alias = "Micky"



    @property

    def name(self):

        return self.__alias        



class Donatello(NinjaTurtle):

    def __init__(self,alias):



        self.__alias = "Don"



    @property

    def name(self):

        return self.__alias        



class Raphael(NinjaTurtle):

    def __init__(self, alias):

        self.__alias = "Raph"



    @property

    def name(self):

        return self.__alias        



# main.py



import turtles as d 



leonardo = d.Leonardo("Leo")

michealangelo = d.Michealangelo("Micky")

donatello = d.Donatello("Don")

raphael = d.Raphael("Raph")



print(leonardo.name)

print(michealangelo.name)

print(donatello.name)

print(raphael.name)
