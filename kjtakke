#--Common functions--#




def replace_in_list(lst, fr, to):
    """Replaces characters within list"""
    n = 0 #Itterations
    lst = list(map(lambda x: str(x), lst))
    #Itterate through each list item
    for x in lst:
        #Empty variables
        temp = []
        string = ""

        #characters in list items converted into the its own list with each character as a list item
        for i in range(len(x)):
            temp.append(x[i:i+1])

        #Replace values
        for j in range(len(x)):

            if temp[j] == fr:
                temp[j] = to
            else:
                pass

        #Convert list back to string
        for k in temp:
            string = string + k

            #Replace list items
        lst[n] = string
        n += 1

    return lst


def str_to_list(string):
    """Converts a string in to a list of individual character"""
    lst = []

    for x in range(len(string)):
        lst.append(string[x:x+1])
    return lst


def list_to_string(lst):
    """Converts a list in to a one string"""
    lst = list(map(lambda x: str(x), lst))
    return ' '.join(map(str, lst))
