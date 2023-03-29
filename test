class Passport():
    counter = 0

    def __init__(self, name, surname, patronymic):
        Passport.counter  =  self.counter  +  1
        self.__name  =  name
        self.__surname = surname
        self.__patronymic = patronymic
    def getName(self):
        return  self.__name

    def setName(self, name):
        self.__name  =  name

    def getCounter(self):
        return  Passport.counter

    def out(self):
        print("Human = ", self.__name)

    def getSurname(self):
        return  self.__surname

    def setSurname(self, surname):
        self.__surname  =  surname

    def getCounter(self):
        return  Passport.counter

    def out(self):
        print("Human = ", self.__surname)

    def getPatronymic(self):
        return  self.__patronymic

    def setName(self, patronymic):
        self.__patronymic  =  patronymic

    def getCounter(self):
        return  Passport.counter

    def out(self):
        print("Human = ", self.__patronymic)

class Builder(Passport):
    counter = 0

    def __init__(self, name, patronymic, surname):
        super(). __init__(name)
        Builder. counter  =  self.counter  +  1
        self.__patronymic =  patronymic
        self.__surname = surname

    def getPatronymic(self):
        return  self.__patronymic

    def setPatronymic(self, patronymic, surname):
        self.__patronymic  =  patronymic
        self.__surname = surname
    def getCounter(self):
        return  Builder.counter

    def out(self):
        print("Builder = ", self.__atronymic, self.__surname)

class Sailor(Passport):
    counter = 0

    def __init__(self, name, atronymic, surname):
        super(). __init__(name)
        Sailor.counter  =  self.counter  +  1
        self.__atronymic  =  atronymic
        self.__surname = surname
    def getAtronymic(self):
        return  self.__atronymic

    def setAtronymic(self, atronymic, surname):
        self.__atronymic  =  atronymic
        self.__surname = surname
    def getCounter(self):
        return  Sailor. counter

    def out(self):
        print("Sailor = ", self.__atronymic, self.__surname)

class Pilot(Passport):
    counter = 0

    def __init__(self, name, atronymic, surname):
        super(). __init__(name)
        Pilot. counter  =  self. counter  +  1
        self.__atronymic = atronymic
        self.__surname = surname
    def getreis(self):
        return  self.__atronymic

    def setreis(self, atronymic, surname):
        self.__atronymic = atronymic
        self.__surname = surname
    def getCounter(self):
        return  Pilot. counter

    def out(self):
        print("Pilot = ", self.__atronymic)

list  = [Passport("User"), Builder("builder", "welder"), Sailor("Jack", "Cap"), Pilot("Ivan", 100), Pilot("Sergey", 1200)]

def out(list):
    for el in list:
        el. out()

out(list)
print('--------------------------------------------')
def getCounter(list):
    for el in list:
        print(el. getCounter())

getCounter(list)

